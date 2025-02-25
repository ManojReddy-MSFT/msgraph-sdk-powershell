---
external help file:
Module Name: Microsoft.Graph.DeviceManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement/new-mgdevicemanagementuserexperienceanalyticbatteryhealthappimpact
schema: 2.0.0
---

# New-MgDeviceManagementUserExperienceAnalyticBatteryHealthAppImpact

## SYNOPSIS
User Experience Analytics Battery Health App Impact

## SYNTAX

### CreateExpanded (Default)
```
New-MgDeviceManagementUserExperienceAnalyticBatteryHealthAppImpact [-ActiveDevices <Int32>]
 [-AdditionalProperties <Hashtable>] [-AppDisplayName <String>] [-AppName <String>] [-AppPublisher <String>]
 [-BatteryUsagePercentage <Double>] [-Id <String>] [-IsForegroundApp] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### Create
```
New-MgDeviceManagementUserExperienceAnalyticBatteryHealthAppImpact
 -BodyParameter <IMicrosoftGraphUserExperienceAnalyticsBatteryHealthAppImpact> [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
User Experience Analytics Battery Health App Impact

## EXAMPLES

## PARAMETERS

### -ActiveDevices
Number of active devices for using that app over a 14-day period.
Valid values -2147483648 to 2147483647

```yaml
Type: System.Int32
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppDisplayName
User friendly display name for the app.
Eg: Outlook

```yaml
Type: System.String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppName
App name.
Eg: oltk.exe

```yaml
Type: System.String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppPublisher
App publisher.
Eg: Microsoft Corporation

```yaml
Type: System.String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BatteryUsagePercentage
The percent of total battery power used by this application when the device was not plugged into AC power, over 14 days computed across all devices in the tenant.
Unit in percentage.
Valid values -1.79769313486232E+308 to 1.79769313486232E+308

```yaml
Type: System.Double
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
The user experience analytics battery health app impact entity contains battery usage related information at an app level for the tenant.
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserExperienceAnalyticsBatteryHealthAppImpact
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Id
Read-only.

```yaml
Type: System.String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsForegroundApp
true if the user had active interaction with the app.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserExperienceAnalyticsBatteryHealthAppImpact

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserExperienceAnalyticsBatteryHealthAppImpact

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphUserExperienceAnalyticsBatteryHealthAppImpact>: The user experience analytics battery health app impact entity contains battery usage related information at an app level for the tenant.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[ActiveDevices <Int32?>]`: Number of active devices for using that app over a 14-day period. Valid values -2147483648 to 2147483647
  - `[AppDisplayName <String>]`: User friendly display name for the app. Eg: Outlook
  - `[AppName <String>]`: App name. Eg: oltk.exe
  - `[AppPublisher <String>]`: App publisher. Eg: Microsoft Corporation
  - `[BatteryUsagePercentage <Double?>]`: The percent of total battery power used by this application when the device was not plugged into AC power, over 14 days computed across all devices in the tenant. Unit in percentage. Valid values -1.79769313486232E+308 to 1.79769313486232E+308
  - `[IsForegroundApp <Boolean?>]`: true if the user had active interaction with the app.

## RELATED LINKS

