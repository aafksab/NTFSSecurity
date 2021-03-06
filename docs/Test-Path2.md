---
external help file: NTFSSecurity.dll-Help.xml
Module Name: ntfssecurity
online version:
schema: 2.0.0
---

# Test-Path2

## SYNOPSIS
{{ Fill in the Synopsis }}

## SYNTAX

```
Test-Path2 [-Path] <String[]> [-PathType <TestPathType>] [<CommonParameters>]
```

## DESCRIPTION
{{ Fill in the Description }}

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -Path
{{ Fill Path Description }}

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: FullName

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -PathType
{{ Fill PathType Description }}

```yaml
Type: TestPathType
Parameter Sets: (All)
Aliases:
Accepted values: Any, Container, Leaf

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### System.String[]

### NTFSSecurity.TestPathType

## OUTPUTS

### Alphaleonis.Win32.Filesystem.FileInfo

### Alphaleonis.Win32.Filesystem.DirectoryInfo

## NOTES

## RELATED LINKS
