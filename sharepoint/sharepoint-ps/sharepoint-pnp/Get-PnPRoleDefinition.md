---
external help file:
online version: https://docs.microsoft.com/powershell/module/sharepoint-pnp/get-pnproledefinition
applicable: SharePoint Server 2013, SharePoint Server 2016, SharePoint Server 2019, SharePoint Online
schema: 2.0.0
title: Get-PnPRoleDefinition
---

# Get-PnPRoleDefinition

## SYNOPSIS
Retrieves a Role Definitions of a site

## SYNTAX 

```powershell
Get-PnPRoleDefinition [-Identity <RoleDefinitionPipeBind>]
                      [-Connection <PnPConnection>]
```

## EXAMPLES

### ------------------EXAMPLE 1------------------
```powershell
Get-PnPRoleDefinition
```

Retrieves the Role Definitions (Permission Levels) settings of the current site

### ------------------EXAMPLE 2------------------
```powershell
Get-PnPRoleDefinition -Identity Read
```

Retrieves the specified Role Definition (Permission Level) settings of the current site

## PARAMETERS

### -Identity
The name of a role definition to retrieve.

```yaml
Type: RoleDefinitionPipeBind
Parameter Sets: (All)

Required: False
Position: 0
Accept pipeline input: True
```

### -Connection
Optional connection to be used by the cmdlet. Retrieve the value for this parameter by either specifying -ReturnConnection on Connect-PnPOnline or by executing Get-PnPConnection.

```yaml
Type: PnPConnection
Parameter Sets: (All)

Required: False
Position: Named
Accept pipeline input: False
```

## OUTPUTS

### Microsoft.SharePoint.Client.RoleDefinition

## RELATED LINKS

[SharePoint Developer Patterns and Practices](https://aka.ms/sppnp)