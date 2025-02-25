---
external help file:
Module Name: Microsoft.Graph.Search
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.search/new-mgexternalconnection
schema: 2.0.0
---

# New-MgExternalConnection

## SYNOPSIS
Create new navigation property to connections for external

## SYNTAX

### CreateExpanded1 (Default)
```
New-MgExternalConnection [-AdditionalProperties <Hashtable>]
 [-Configuration <IMicrosoftGraphExternalConnectorsConfiguration>] [-ConnectorId <String>]
 [-Description <String>] [-Groups <IMicrosoftGraphExternalConnectorsExternalGroup[]>] [-Id <String>]
 [-IngestedItemsCount <Int64>] [-Items <IMicrosoftGraphExternalConnectorsExternalItem1[]>] [-Name <String>]
 [-Operations <IMicrosoftGraphExternalConnectorsConnectionOperation[]>]
 [-Quota <IMicrosoftGraphExternalConnectorsConnectionQuota>]
 [-Schema <IMicrosoftGraphExternalConnectorsSchema1>]
 [-SearchSettings <IMicrosoftGraphExternalConnectorsSearchSettings>] [-State <String>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### Create1
```
New-MgExternalConnection -BodyParameter <IMicrosoftGraphExternalConnectorsExternalConnection1> [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to connections for external

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
externalConnection
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExternalConnectorsExternalConnection1
Parameter Sets: Create1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Configuration
configuration
To construct, please use Get-Help -Online and see NOTES section for CONFIGURATION properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExternalConnectorsConfiguration
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ConnectorId
The Teams App ID.
Optional.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
Description of the connection displayed in the Microsoft 365 admin center.
Optional.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Groups
Read-only.
Nullable.
To construct, please use Get-Help -Online and see NOTES section for GROUPS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExternalConnectorsExternalGroup[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Read-only.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IngestedItemsCount
.

```yaml
Type: System.Int64
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Items
Read-only.
Nullable.
To construct, please use Get-Help -Online and see NOTES section for ITEMS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExternalConnectorsExternalItem1[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
The display name of the connection to be displayed in the Microsoft 365 admin center.
Maximum length of 128 characters.
Required.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Operations
Read-only.
Nullable.
To construct, please use Get-Help -Online and see NOTES section for OPERATIONS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExternalConnectorsConnectionOperation[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Quota
connectionQuota
To construct, please use Get-Help -Online and see NOTES section for QUOTA properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExternalConnectorsConnectionQuota
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Schema
schema
To construct, please use Get-Help -Online and see NOTES section for SCHEMA properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExternalConnectorsSchema1
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SearchSettings
searchSettings
To construct, please use Get-Help -Online and see NOTES section for SEARCHSETTINGS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExternalConnectorsSearchSettings
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -State
connectionState

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExternalConnectorsExternalConnection1

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExternalConnectorsExternalConnection1

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphExternalConnectorsExternalConnection1>: externalConnection
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[Configuration <IMicrosoftGraphExternalConnectorsConfiguration>]`: configuration
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AuthorizedAppIds <String[]>]`: A collection of application IDs for registered Azure Active Directory apps that are allowed to manage the externalConnection and to index content in the externalConnection.
  - `[ConnectorId <String>]`: The Teams App ID. Optional.
  - `[Description <String>]`: Description of the connection displayed in the Microsoft 365 admin center. Optional.
  - `[Groups <IMicrosoftGraphExternalConnectorsExternalGroup[]>]`: Read-only. Nullable.
    - `[Id <String>]`: Read-only.
    - `[Description <String>]`: The description of the external group. Optional.
    - `[DisplayName <String>]`: The friendly name of the external group. Optional.
    - `[Members <IMicrosoftGraphExternalConnectorsIdentity[]>]`: A member added to an externalGroup. You can add Azure Active Directory users, Azure Active Directory groups, or other externalGroups as members.
      - `[Id <String>]`: Read-only.
      - `[Type <String>]`: identityType
  - `[IngestedItemsCount <Int64?>]`: 
  - `[Items <IMicrosoftGraphExternalConnectorsExternalItem1[]>]`: Read-only. Nullable.
    - `[Id <String>]`: Read-only.
    - `[Acl <IMicrosoftGraphExternalConnectorsAcl1[]>]`: An array of access control entries. Each entry specifies the access granted to a user or group. Required.
      - `[AccessType <String>]`: accessType
      - `[IdentitySource <String>]`: identitySourceType
      - `[Type <String>]`: aclType
      - `[Value <String>]`: The unique identifer of the identity. In case of Azure Active Directory identities, value is set to the object identifier of the user, group or tenant for types user, group and everyone (and everyoneExceptGuests) respectively. In case of external groups value is set to the ID of the externalGroup.
    - `[Content <IMicrosoftGraphExternalConnectorsExternalItemContent>]`: externalItemContent
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Type <String>]`: externalItemContentType
      - `[Value <String>]`: The content for the externalItem. Required.
    - `[Properties <IMicrosoftGraphExternalConnectorsProperties>]`: properties
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Name <String>]`: The display name of the connection to be displayed in the Microsoft 365 admin center. Maximum length of 128 characters. Required.
  - `[Operations <IMicrosoftGraphExternalConnectorsConnectionOperation[]>]`: Read-only. Nullable.
    - `[Id <String>]`: Read-only.
    - `[Error <IMicrosoftGraphPublicError>]`: publicError
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Code <String>]`: Represents the error code.
      - `[Details <IMicrosoftGraphPublicErrorDetail[]>]`: Details of the error.
        - `[Code <String>]`: The error code.
        - `[Message <String>]`: The error message.
        - `[Target <String>]`: The target of the error.
      - `[InnerError <IMicrosoftGraphPublicInnerError>]`: publicInnerError
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Code <String>]`: The error code.
        - `[Details <IMicrosoftGraphPublicErrorDetail[]>]`: A collection of error details.
        - `[Message <String>]`: The error message.
        - `[Target <String>]`: The target of the error.
      - `[Message <String>]`: A non-localized message for the developer.
      - `[Target <String>]`: The target of the error.
    - `[Status <String>]`: connectionOperationStatus
  - `[Quota <IMicrosoftGraphExternalConnectorsConnectionQuota>]`: connectionQuota
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[ItemsRemaining <Int64?>]`: 
  - `[Schema <IMicrosoftGraphExternalConnectorsSchema1>]`: schema
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[BaseType <String>]`: Must be set to microsoft.graph.externalItem. Required.
    - `[Properties <IMicrosoftGraphExternalConnectorsProperty1[]>]`: The properties defined for the items in the connection. The minimum number of properties is one, the maximum is 128.
      - `[Aliases <String[]>]`: A set of aliases or a friendly names for the property. Maximum 32 characters. Only alphanumeric characters allowed. For example, each string may not contain control characters, whitespace, or any of the following: :, ;, ,, (, ), [, ], {, }, %, $, +, !, *, =, &, ?, @, #, /, ~, ', ', <, >, `, ^. Optional.
      - `[IsQueryable <Boolean?>]`: Specifies if the property is queryable. Queryable properties can be used in Keyword Query Language (KQL) queries. Optional.
      - `[IsRefinable <Boolean?>]`: Specifies if the property is refinable.  Refinable properties can be used to filter search results in the Search API and add a refiner control in the Microsoft Search user experience. Optional.
      - `[IsRetrievable <Boolean?>]`: Specifies if the property is retrievable. Retrievable properties are returned in the result set when items are returned by the search API. Retrievable properties are also available to add to the display template used to render search results. Optional.
      - `[IsSearchable <Boolean?>]`: Specifies if the property is searchable. Only properties of type string or stringCollection can be searchable. Non-searchable properties are not added to the search index. Optional.
      - `[Labels <String[]>]`: Specifies one or more well-known tags added against a property. Labels help Microsoft Search understand the semantics of the data in the connection. Adding appropriate labels would result in an enhanced search experience (e.g. better relevance). Optional.The possible values are: title, url, createdBy, lastModifiedBy, authors, createdDateTime, lastModifiedDateTime, fileName, fileExtension, unknownFutureValue, iconUrl, containerName, containerUrl. Note that you must use the Prefer: include-unknown-enum-members request header to get the following values in this evolvable enum: iconUrl, containerName, containerUrl.
      - `[Name <String>]`: The name of the property. Maximum 32 characters. Only alphanumeric characters allowed. For example, each string may not contain control characters, whitespace, or any of the following: :, ;, ,, (, ), [, ], {, }, %, $, +, !, *, =, &, ?, @, #, /, ~, ', ', <, >, `, ^.  Required.
      - `[Type <String>]`: propertyType
  - `[SearchSettings <IMicrosoftGraphExternalConnectorsSearchSettings>]`: searchSettings
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[SearchResultTemplates <IMicrosoftGraphExternalConnectorsDisplayTemplate[]>]`: Enables the developer to define the appearance of the content and configure conditions that dictate when the template should be displayed.
      - `[Id <String>]`: The text identifier for the display template; for example, contosoTickets.
      - `[Layout <IMicrosoftGraphJson>]`: Json
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Priority <Int32?>]`: Defines the priority of a display template. A display template with priority 1 is evaluated before a template with priority 4. Gaps in priority values are supported.
      - `[Rules <IMicrosoftGraphExternalConnectorsPropertyRule[]>]`: Specifies additional rules for selecting this display template based on the item schema. Optional.
        - `[Operation <String>]`: ruleOperation
        - `[Property <String>]`: The property from the externalItem schema. Required.
        - `[Values <String[]>]`: A collection with one or many strings. The specified string(s) will be matched with the specified property using the specified operation. Required.
        - `[ValuesJoinedBy <String>]`: binaryOperator
  - `[State <String>]`: connectionState

CONFIGURATION <IMicrosoftGraphExternalConnectorsConfiguration>: configuration
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[AuthorizedAppIds <String[]>]`: A collection of application IDs for registered Azure Active Directory apps that are allowed to manage the externalConnection and to index content in the externalConnection.

GROUPS <IMicrosoftGraphExternalConnectorsExternalGroup[]>: Read-only. Nullable.
  - `[Id <String>]`: Read-only.
  - `[Description <String>]`: The description of the external group. Optional.
  - `[DisplayName <String>]`: The friendly name of the external group. Optional.
  - `[Members <IMicrosoftGraphExternalConnectorsIdentity[]>]`: A member added to an externalGroup. You can add Azure Active Directory users, Azure Active Directory groups, or other externalGroups as members.
    - `[Id <String>]`: Read-only.
    - `[Type <String>]`: identityType

ITEMS <IMicrosoftGraphExternalConnectorsExternalItem1[]>: Read-only. Nullable.
  - `[Id <String>]`: Read-only.
  - `[Acl <IMicrosoftGraphExternalConnectorsAcl1[]>]`: An array of access control entries. Each entry specifies the access granted to a user or group. Required.
    - `[AccessType <String>]`: accessType
    - `[IdentitySource <String>]`: identitySourceType
    - `[Type <String>]`: aclType
    - `[Value <String>]`: The unique identifer of the identity. In case of Azure Active Directory identities, value is set to the object identifier of the user, group or tenant for types user, group and everyone (and everyoneExceptGuests) respectively. In case of external groups value is set to the ID of the externalGroup.
  - `[Content <IMicrosoftGraphExternalConnectorsExternalItemContent>]`: externalItemContent
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Type <String>]`: externalItemContentType
    - `[Value <String>]`: The content for the externalItem. Required.
  - `[Properties <IMicrosoftGraphExternalConnectorsProperties>]`: properties
    - `[(Any) <Object>]`: This indicates any property can be added to this object.

OPERATIONS <IMicrosoftGraphExternalConnectorsConnectionOperation[]>: Read-only. Nullable.
  - `[Id <String>]`: Read-only.
  - `[Error <IMicrosoftGraphPublicError>]`: publicError
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Code <String>]`: Represents the error code.
    - `[Details <IMicrosoftGraphPublicErrorDetail[]>]`: Details of the error.
      - `[Code <String>]`: The error code.
      - `[Message <String>]`: The error message.
      - `[Target <String>]`: The target of the error.
    - `[InnerError <IMicrosoftGraphPublicInnerError>]`: publicInnerError
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Code <String>]`: The error code.
      - `[Details <IMicrosoftGraphPublicErrorDetail[]>]`: A collection of error details.
      - `[Message <String>]`: The error message.
      - `[Target <String>]`: The target of the error.
    - `[Message <String>]`: A non-localized message for the developer.
    - `[Target <String>]`: The target of the error.
  - `[Status <String>]`: connectionOperationStatus

QUOTA <IMicrosoftGraphExternalConnectorsConnectionQuota>: connectionQuota
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[ItemsRemaining <Int64?>]`: 

SCHEMA <IMicrosoftGraphExternalConnectorsSchema1>: schema
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[BaseType <String>]`: Must be set to microsoft.graph.externalItem. Required.
  - `[Properties <IMicrosoftGraphExternalConnectorsProperty1[]>]`: The properties defined for the items in the connection. The minimum number of properties is one, the maximum is 128.
    - `[Aliases <String[]>]`: A set of aliases or a friendly names for the property. Maximum 32 characters. Only alphanumeric characters allowed. For example, each string may not contain control characters, whitespace, or any of the following: :, ;, ,, (, ), [, ], {, }, %, $, +, !, *, =, &, ?, @, #, /, ~, ', ', <, >, `, ^. Optional.
    - `[IsQueryable <Boolean?>]`: Specifies if the property is queryable. Queryable properties can be used in Keyword Query Language (KQL) queries. Optional.
    - `[IsRefinable <Boolean?>]`: Specifies if the property is refinable.  Refinable properties can be used to filter search results in the Search API and add a refiner control in the Microsoft Search user experience. Optional.
    - `[IsRetrievable <Boolean?>]`: Specifies if the property is retrievable. Retrievable properties are returned in the result set when items are returned by the search API. Retrievable properties are also available to add to the display template used to render search results. Optional.
    - `[IsSearchable <Boolean?>]`: Specifies if the property is searchable. Only properties of type string or stringCollection can be searchable. Non-searchable properties are not added to the search index. Optional.
    - `[Labels <String[]>]`: Specifies one or more well-known tags added against a property. Labels help Microsoft Search understand the semantics of the data in the connection. Adding appropriate labels would result in an enhanced search experience (e.g. better relevance). Optional.The possible values are: title, url, createdBy, lastModifiedBy, authors, createdDateTime, lastModifiedDateTime, fileName, fileExtension, unknownFutureValue, iconUrl, containerName, containerUrl. Note that you must use the Prefer: include-unknown-enum-members request header to get the following values in this evolvable enum: iconUrl, containerName, containerUrl.
    - `[Name <String>]`: The name of the property. Maximum 32 characters. Only alphanumeric characters allowed. For example, each string may not contain control characters, whitespace, or any of the following: :, ;, ,, (, ), [, ], {, }, %, $, +, !, *, =, &, ?, @, #, /, ~, ', ', <, >, `, ^.  Required.
    - `[Type <String>]`: propertyType

SEARCHSETTINGS <IMicrosoftGraphExternalConnectorsSearchSettings>: searchSettings
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[SearchResultTemplates <IMicrosoftGraphExternalConnectorsDisplayTemplate[]>]`: Enables the developer to define the appearance of the content and configure conditions that dictate when the template should be displayed.
    - `[Id <String>]`: The text identifier for the display template; for example, contosoTickets.
    - `[Layout <IMicrosoftGraphJson>]`: Json
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Priority <Int32?>]`: Defines the priority of a display template. A display template with priority 1 is evaluated before a template with priority 4. Gaps in priority values are supported.
    - `[Rules <IMicrosoftGraphExternalConnectorsPropertyRule[]>]`: Specifies additional rules for selecting this display template based on the item schema. Optional.
      - `[Operation <String>]`: ruleOperation
      - `[Property <String>]`: The property from the externalItem schema. Required.
      - `[Values <String[]>]`: A collection with one or many strings. The specified string(s) will be matched with the specified property using the specified operation. Required.
      - `[ValuesJoinedBy <String>]`: binaryOperator

## RELATED LINKS

