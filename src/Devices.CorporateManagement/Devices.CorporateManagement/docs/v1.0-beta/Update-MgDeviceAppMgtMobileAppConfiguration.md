---
external help file:
Module Name: Microsoft.Graph.Devices.CorporateManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devices.corporatemanagement/update-mgdeviceappmgtmobileappconfiguration
schema: 2.0.0
---

# Update-MgDeviceAppMgtMobileAppConfiguration

## SYNOPSIS
The Managed Device Mobile Application Configurations.

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgDeviceAppMgtMobileAppConfiguration -ManagedDeviceMobileAppConfigurationId <String>
 [-AdditionalProperties <Hashtable>]
 [-Assignments <IMicrosoftGraphManagedDeviceMobileAppConfigurationAssignment[]>] [-CreatedDateTime <DateTime>]
 [-Description <String>] [-DeviceStatuses <IMicrosoftGraphManagedDeviceMobileAppConfigurationDeviceStatus[]>]
 [-DeviceStatusSummary <IMicrosoftGraphManagedDeviceMobileAppConfigurationDeviceSummary>]
 [-DisplayName <String>] [-Id <String>] [-LastModifiedDateTime <DateTime>] [-RoleScopeTagIds <String[]>]
 [-TargetedMobileApps <String[]>]
 [-UserStatuses <IMicrosoftGraphManagedDeviceMobileAppConfigurationUserStatus[]>]
 [-UserStatusSummary <IMicrosoftGraphManagedDeviceMobileAppConfigurationUserSummary>] [-Version <Int32>]
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update
```
Update-MgDeviceAppMgtMobileAppConfiguration -ManagedDeviceMobileAppConfigurationId <String>
 -BodyParameter <IMicrosoftGraphManagedDeviceMobileAppConfiguration> [-PassThru] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgDeviceAppMgtMobileAppConfiguration -InputObject <IDevicesCorporateManagementIdentity>
 -BodyParameter <IMicrosoftGraphManagedDeviceMobileAppConfiguration> [-PassThru] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgDeviceAppMgtMobileAppConfiguration -InputObject <IDevicesCorporateManagementIdentity>
 [-AdditionalProperties <Hashtable>]
 [-Assignments <IMicrosoftGraphManagedDeviceMobileAppConfigurationAssignment[]>] [-CreatedDateTime <DateTime>]
 [-Description <String>] [-DeviceStatuses <IMicrosoftGraphManagedDeviceMobileAppConfigurationDeviceStatus[]>]
 [-DeviceStatusSummary <IMicrosoftGraphManagedDeviceMobileAppConfigurationDeviceSummary>]
 [-DisplayName <String>] [-Id <String>] [-LastModifiedDateTime <DateTime>] [-RoleScopeTagIds <String[]>]
 [-TargetedMobileApps <String[]>]
 [-UserStatuses <IMicrosoftGraphManagedDeviceMobileAppConfigurationUserStatus[]>]
 [-UserStatusSummary <IMicrosoftGraphManagedDeviceMobileAppConfigurationUserSummary>] [-Version <Int32>]
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
The Managed Device Mobile Application Configurations.

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Assignments
The list of group assignemenets for app configration.
To construct, please use Get-Help -Online and see NOTES section for ASSIGNMENTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphManagedDeviceMobileAppConfigurationAssignment[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
An abstract class for Mobile app configuration for enrolled devices.
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphManagedDeviceMobileAppConfiguration
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CreatedDateTime
DateTime the object was created.

```yaml
Type: System.DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
Admin provided description of the Device Configuration.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceStatuses
List of ManagedDeviceMobileAppConfigurationDeviceStatus.
To construct, please use Get-Help -Online and see NOTES section for DEVICESTATUSES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphManagedDeviceMobileAppConfigurationDeviceStatus[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceStatusSummary
Contains properties, inherited properties and actions for an MDM mobile app configuration device status summary.
To construct, please use Get-Help -Online and see NOTES section for DEVICESTATUSSUMMARY properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphManagedDeviceMobileAppConfigurationDeviceSummary
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
Admin provided name of the device configuration.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IDevicesCorporateManagementIdentity
Parameter Sets: UpdateViaIdentity, UpdateViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -LastModifiedDateTime
DateTime the object was last modified.

```yaml
Type: System.DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ManagedDeviceMobileAppConfigurationId
key: id of managedDeviceMobileAppConfiguration

```yaml
Type: System.String
Parameter Sets: Update, UpdateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RoleScopeTagIds
List of Scope Tags for this App configuration entity.

```yaml
Type: System.String[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TargetedMobileApps
the associated app.

```yaml
Type: System.String[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserStatuses
List of ManagedDeviceMobileAppConfigurationUserStatus.
To construct, please use Get-Help -Online and see NOTES section for USERSTATUSES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphManagedDeviceMobileAppConfigurationUserStatus[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserStatusSummary
Contains properties, inherited properties and actions for an MDM mobile app configuration user status summary.
To construct, please use Get-Help -Online and see NOTES section for USERSTATUSSUMMARY properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphManagedDeviceMobileAppConfigurationUserSummary
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Version
Version of the device configuration.

```yaml
Type: System.Int32
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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

### Microsoft.Graph.PowerShell.Models.IDevicesCorporateManagementIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphManagedDeviceMobileAppConfiguration

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

### Update-MgDeviceAppManagementMobileAppConfiguration

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


ASSIGNMENTS <IMicrosoftGraphManagedDeviceMobileAppConfigurationAssignment[]>: The list of group assignemenets for app configration.
  - `[Id <String>]`: Read-only.
  - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DeviceAndAppManagementAssignmentFilterId <String>]`: The Id of the filter for the target assignment.
    - `[DeviceAndAppManagementAssignmentFilterType <String>]`: Represents type of the assignment filter.

BODYPARAMETER <IMicrosoftGraphManagedDeviceMobileAppConfiguration>: An abstract class for Mobile app configuration for enrolled devices.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[Assignments <IMicrosoftGraphManagedDeviceMobileAppConfigurationAssignment[]>]`: The list of group assignemenets for app configration.
    - `[Id <String>]`: Read-only.
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DeviceAndAppManagementAssignmentFilterId <String>]`: The Id of the filter for the target assignment.
      - `[DeviceAndAppManagementAssignmentFilterType <String>]`: Represents type of the assignment filter.
  - `[CreatedDateTime <DateTime?>]`: DateTime the object was created.
  - `[Description <String>]`: Admin provided description of the Device Configuration.
  - `[DeviceStatusSummary <IMicrosoftGraphManagedDeviceMobileAppConfigurationDeviceSummary>]`: Contains properties, inherited properties and actions for an MDM mobile app configuration device status summary.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[ConfigurationVersion <Int32?>]`: Version of the policy for that overview
    - `[ConflictCount <Int32?>]`: Number of devices in conflict
    - `[ErrorCount <Int32?>]`: Number of error devices
    - `[FailedCount <Int32?>]`: Number of failed devices
    - `[LastUpdateDateTime <DateTime?>]`: Last update time
    - `[NotApplicableCount <Int32?>]`: Number of not applicable devices
    - `[NotApplicablePlatformCount <Int32?>]`: Number of not applicable devices due to mismatch platform and policy
    - `[PendingCount <Int32?>]`: Number of pending devices
    - `[SuccessCount <Int32?>]`: Number of succeeded devices
  - `[DeviceStatuses <IMicrosoftGraphManagedDeviceMobileAppConfigurationDeviceStatus[]>]`: List of ManagedDeviceMobileAppConfigurationDeviceStatus.
    - `[Id <String>]`: Read-only.
    - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires
    - `[DeviceDisplayName <String>]`: Device name of the DevicePolicyStatus.
    - `[DeviceModel <String>]`: The device model that is being reported
    - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
    - `[Platform <Int32?>]`: Platform of the device that is being reported
    - `[Status <String>]`: complianceStatus
    - `[UserName <String>]`: The User Name that is being reported
    - `[UserPrincipalName <String>]`: UserPrincipalName.
  - `[DisplayName <String>]`: Admin provided name of the device configuration.
  - `[LastModifiedDateTime <DateTime?>]`: DateTime the object was last modified.
  - `[RoleScopeTagIds <String[]>]`: List of Scope Tags for this App configuration entity.
  - `[TargetedMobileApps <String[]>]`: the associated app.
  - `[UserStatusSummary <IMicrosoftGraphManagedDeviceMobileAppConfigurationUserSummary>]`: Contains properties, inherited properties and actions for an MDM mobile app configuration user status summary.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[ConfigurationVersion <Int32?>]`: Version of the policy for that overview
    - `[ConflictCount <Int32?>]`: Number of users in conflict
    - `[ErrorCount <Int32?>]`: Number of error Users
    - `[FailedCount <Int32?>]`: Number of failed Users
    - `[LastUpdateDateTime <DateTime?>]`: Last update time
    - `[NotApplicableCount <Int32?>]`: Number of not applicable users
    - `[PendingCount <Int32?>]`: Number of pending Users
    - `[SuccessCount <Int32?>]`: Number of succeeded Users
  - `[UserStatuses <IMicrosoftGraphManagedDeviceMobileAppConfigurationUserStatus[]>]`: List of ManagedDeviceMobileAppConfigurationUserStatus.
    - `[Id <String>]`: Read-only.
    - `[DevicesCount <Int32?>]`: Devices count for that user.
    - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
    - `[Status <String>]`: complianceStatus
    - `[UserDisplayName <String>]`: User name of the DevicePolicyStatus.
    - `[UserPrincipalName <String>]`: UserPrincipalName.
  - `[Version <Int32?>]`: Version of the device configuration.

DEVICESTATUSES <IMicrosoftGraphManagedDeviceMobileAppConfigurationDeviceStatus[]>: List of ManagedDeviceMobileAppConfigurationDeviceStatus.
  - `[Id <String>]`: Read-only.
  - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires
  - `[DeviceDisplayName <String>]`: Device name of the DevicePolicyStatus.
  - `[DeviceModel <String>]`: The device model that is being reported
  - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
  - `[Platform <Int32?>]`: Platform of the device that is being reported
  - `[Status <String>]`: complianceStatus
  - `[UserName <String>]`: The User Name that is being reported
  - `[UserPrincipalName <String>]`: UserPrincipalName.

DEVICESTATUSSUMMARY <IMicrosoftGraphManagedDeviceMobileAppConfigurationDeviceSummary>: Contains properties, inherited properties and actions for an MDM mobile app configuration device status summary.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[ConfigurationVersion <Int32?>]`: Version of the policy for that overview
  - `[ConflictCount <Int32?>]`: Number of devices in conflict
  - `[ErrorCount <Int32?>]`: Number of error devices
  - `[FailedCount <Int32?>]`: Number of failed devices
  - `[LastUpdateDateTime <DateTime?>]`: Last update time
  - `[NotApplicableCount <Int32?>]`: Number of not applicable devices
  - `[NotApplicablePlatformCount <Int32?>]`: Number of not applicable devices due to mismatch platform and policy
  - `[PendingCount <Int32?>]`: Number of pending devices
  - `[SuccessCount <Int32?>]`: Number of succeeded devices

INPUTOBJECT <IDevicesCorporateManagementIdentity>: Identity Parameter
  - `[AndroidManagedAppProtectionId <String>]`: key: id of androidManagedAppProtection
  - `[AppLogCollectionRequestId <String>]`: key: id of appLogCollectionRequest
  - `[AssignmentFilterEvaluationStatusDetailsId <String>]`: key: id of assignmentFilterEvaluationStatusDetails
  - `[BundleId <String>]`: Usage: bundleId={bundleId}
  - `[Count <Int64?>]`: Usage: count={count}
  - `[DefaultManagedAppProtectionId <String>]`: key: id of defaultManagedAppProtection
  - `[DeviceAppManagementTaskId <String>]`: key: id of deviceAppManagementTask
  - `[DeviceCompliancePolicyStateId <String>]`: key: id of deviceCompliancePolicyState
  - `[DeviceConfigurationStateId <String>]`: key: id of deviceConfigurationState
  - `[DeviceEnrollmentConfigurationId <String>]`: key: id of deviceEnrollmentConfiguration
  - `[DeviceId <String>]`: Usage: deviceId={deviceId}
  - `[DeviceInstallStateId <String>]`: key: id of deviceInstallState
  - `[DeviceLogCollectionResponseId <String>]`: key: id of deviceLogCollectionResponse
  - `[DeviceManagementTroubleshootingEventId <String>]`: key: id of deviceManagementTroubleshootingEvent
  - `[EnrollmentConfigurationAssignmentId <String>]`: key: id of enrollmentConfigurationAssignment
  - `[EnterpriseCodeSigningCertificateId <String>]`: key: id of enterpriseCodeSigningCertificate
  - `[IosLobAppProvisioningConfigurationAssignmentId <String>]`: key: id of iosLobAppProvisioningConfigurationAssignment
  - `[IosLobAppProvisioningConfigurationId <String>]`: key: id of iosLobAppProvisioningConfiguration
  - `[IosManagedAppProtectionId <String>]`: key: id of iosManagedAppProtection
  - `[ManagedAppOperationId <String>]`: key: id of managedAppOperation
  - `[ManagedAppPolicyId <String>]`: key: id of managedAppPolicy
  - `[ManagedAppRegistrationId <String>]`: key: id of managedAppRegistration
  - `[ManagedAppStatusId <String>]`: key: id of managedAppStatus
  - `[ManagedDeviceId <String>]`: key: id of managedDevice
  - `[ManagedDeviceMobileAppConfigurationAssignmentId <String>]`: key: id of managedDeviceMobileAppConfigurationAssignment
  - `[ManagedDeviceMobileAppConfigurationDeviceStatusId <String>]`: key: id of managedDeviceMobileAppConfigurationDeviceStatus
  - `[ManagedDeviceMobileAppConfigurationId <String>]`: key: id of managedDeviceMobileAppConfiguration
  - `[ManagedDeviceMobileAppConfigurationStateId <String>]`: key: id of managedDeviceMobileAppConfigurationState
  - `[ManagedDeviceMobileAppConfigurationUserStatusId <String>]`: key: id of managedDeviceMobileAppConfigurationUserStatus
  - `[ManagedEBookAssignmentId <String>]`: key: id of managedEBookAssignment
  - `[ManagedEBookCategoryId <String>]`: key: id of managedEBookCategory
  - `[ManagedEBookId <String>]`: key: id of managedEBook
  - `[ManagedMobileAppId <String>]`: key: id of managedMobileApp
  - `[MdmWindowsInformationProtectionPolicyId <String>]`: key: id of mdmWindowsInformationProtectionPolicy
  - `[MobileAppAssignmentId <String>]`: key: id of mobileAppAssignment
  - `[MobileAppCategoryId <String>]`: key: id of mobileAppCategory
  - `[MobileAppId <String>]`: key: id of mobileApp
  - `[MobileAppInstallStatusId <String>]`: key: id of mobileAppInstallStatus
  - `[MobileAppIntentAndStateId <String>]`: key: id of mobileAppIntentAndState
  - `[MobileAppProvisioningConfigGroupAssignmentId <String>]`: key: id of mobileAppProvisioningConfigGroupAssignment
  - `[MobileAppRelationshipId <String>]`: key: id of mobileAppRelationship
  - `[MobileAppTroubleshootingEventId <String>]`: key: id of mobileAppTroubleshootingEvent
  - `[OfficeClientConfigurationAssignmentId <String>]`: key: id of officeClientConfigurationAssignment
  - `[OfficeClientConfigurationId <String>]`: key: id of officeClientConfiguration
  - `[PolicySetAssignmentId <String>]`: key: id of policySetAssignment
  - `[PolicySetId <String>]`: key: id of policySet
  - `[PolicySetItemId <String>]`: key: id of policySetItem
  - `[SecurityBaselineSettingStateId <String>]`: key: id of securityBaselineSettingState
  - `[SecurityBaselineStateId <String>]`: key: id of securityBaselineState
  - `[SideLoadingKeyId <String>]`: key: id of sideLoadingKey
  - `[Status <String>]`: Usage: status={status}
  - `[TargetedManagedAppConfigurationId <String>]`: key: id of targetedManagedAppConfiguration
  - `[TargetedManagedAppPolicyAssignmentId <String>]`: key: id of targetedManagedAppPolicyAssignment
  - `[UserAppInstallStatusId <String>]`: key: id of userAppInstallStatus
  - `[UserId <String>]`: key: id of user
  - `[UserInstallStateSummaryId <String>]`: key: id of userInstallStateSummary
  - `[UserPrincipalName <String>]`: Usage: userPrincipalName={userPrincipalName}
  - `[VppTokenId <String>]`: key: id of vppToken
  - `[WindowsDefenderApplicationControlSupplementalPolicyAssignmentId <String>]`: key: id of windowsDefenderApplicationControlSupplementalPolicyAssignment
  - `[WindowsDefenderApplicationControlSupplementalPolicyDeploymentStatusId <String>]`: key: id of windowsDefenderApplicationControlSupplementalPolicyDeploymentStatus
  - `[WindowsDefenderApplicationControlSupplementalPolicyId <String>]`: key: id of windowsDefenderApplicationControlSupplementalPolicy
  - `[WindowsDeviceMalwareStateId <String>]`: key: id of windowsDeviceMalwareState
  - `[WindowsInformationProtectionDeviceRegistrationId <String>]`: key: id of windowsInformationProtectionDeviceRegistration
  - `[WindowsInformationProtectionPolicyId <String>]`: key: id of windowsInformationProtectionPolicy
  - `[WindowsInformationProtectionWipeActionId <String>]`: key: id of windowsInformationProtectionWipeAction

USERSTATUSES <IMicrosoftGraphManagedDeviceMobileAppConfigurationUserStatus[]>: List of ManagedDeviceMobileAppConfigurationUserStatus.
  - `[Id <String>]`: Read-only.
  - `[DevicesCount <Int32?>]`: Devices count for that user.
  - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
  - `[Status <String>]`: complianceStatus
  - `[UserDisplayName <String>]`: User name of the DevicePolicyStatus.
  - `[UserPrincipalName <String>]`: UserPrincipalName.

USERSTATUSSUMMARY <IMicrosoftGraphManagedDeviceMobileAppConfigurationUserSummary>: Contains properties, inherited properties and actions for an MDM mobile app configuration user status summary.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[ConfigurationVersion <Int32?>]`: Version of the policy for that overview
  - `[ConflictCount <Int32?>]`: Number of users in conflict
  - `[ErrorCount <Int32?>]`: Number of error Users
  - `[FailedCount <Int32?>]`: Number of failed Users
  - `[LastUpdateDateTime <DateTime?>]`: Last update time
  - `[NotApplicableCount <Int32?>]`: Number of not applicable users
  - `[PendingCount <Int32?>]`: Number of pending Users
  - `[SuccessCount <Int32?>]`: Number of succeeded Users

## RELATED LINKS

