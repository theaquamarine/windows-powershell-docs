---
author: coreyp-at-msft
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
external help file: Microsoft.IdentityServer.Management.dll-Help.xml
keywords: powershell, cmdlet
manager: jasgro
Module Name: ADFS
ms.assetid: F892F4E3-B6E3-4F1F-9632-22BE86788FAF
ms.author: coreyp
ms.date: 12/20/2016
ms.mktglfcycl: manage
ms.prod: w10
ms.sitesec: library
ms.technology: powershell-windows
ms.topic: reference
online version: 
schema: 2.0.0
title: Get-AdfsAttributeStore
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

[Add-AdfsAttributeStore](./add-adfsattributestore.md)

[Remove-AdfsAttributeStore](./remove-adfsattributestore.md)

[Set-AdfsAttributeStore](./set-adfsattributestore.md)


