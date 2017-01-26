---
author: brianlic-msft-msft
description: 
external help file: Microsoft.IdentityServer.Management.dll-Help.xml
keywords: powershell, cmdlet
manager: alanth
ms.date: 2016-12-20
ms.prod: powershell
ms.technology: powershell
ms.topic: reference
online version: 
schema: 2.0.0
title: Get-AdfsAttributeStore
ms.assetid: F892F4E3-B6E3-4F1F-9632-22BE86788FAF
---

# Get-AdfsAttributeStore

## SYNOPSIS
Gets the attribute stores of the Federation Service.

## SYNTAX

```
Get-AdfsAttributeStore [[-Name] <String[]>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AdfsAttributeStore** cmdlet gets an attribute store of the Federation Service.
If you do not specify any parameters, the cmdlet gets all attribute stores of the Federation Service.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Name
Specifies an array of names of attribute stores that this cmdlet gets.

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: 

Required: False
Position: 0
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS

[Add-AdfsAttributeStore](./Add-AdfsAttributeStore.md)

[Remove-AdfsAttributeStore](./Remove-AdfsAttributeStore.md)

[Set-AdfsAttributeStore](./Set-AdfsAttributeStore.md)
