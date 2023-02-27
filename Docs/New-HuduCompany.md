---
external help file: HuduAPI-help.xml
Module Name: HuduAPI
online version:
schema: 2.0.0
---

# New-HuduCompany

## SYNOPSIS
Create a company

## SYNTAX

```
New-HuduCompany [-Name] <String> [[-Nickname] <String>] [[-CompanyType] <String>] [[-AddressLine1] <String>]
 [[-AddressLine2] <String>] [[-City] <String>] [[-State] <String>] [[-Zip] <String>] [[-CountryName] <String>]
 [[-PhoneNumber] <String>] [[-FaxNumber] <String>] [[-Website] <String>] [[-IdNumber] <String>]
 [[-ParentCompanyId] <Int32>] [[-Notes] <String>] [[-Slug] <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Uses Hudu API to create a new company

## EXAMPLES

### EXAMPLE 1
```
New-HuduCompany -Name 'Company name'
```

## PARAMETERS

### -Name
Company name

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Nickname
Company nickname

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CompanyType
Company type

```yaml
Type: String
Parameter Sets: (All)
Aliases: company_type

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AddressLine1
Address line 1

```yaml
Type: String
Parameter Sets: (All)
Aliases: address_line_1

Required: False
Position: 4
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AddressLine2
Address line 2

```yaml
Type: String
Parameter Sets: (All)
Aliases: address_line_2

Required: False
Position: 5
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -City
City

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 6
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -State
State

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 7
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Zip
Zip

```yaml
Type: String
Parameter Sets: (All)
Aliases: PostalCode, PostCode

Required: False
Position: 8
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CountryName
Country

```yaml
Type: String
Parameter Sets: (All)
Aliases: country_name

Required: False
Position: 9
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PhoneNumber
Phone number

```yaml
Type: String
Parameter Sets: (All)
Aliases: phone_number

Required: False
Position: 10
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FaxNumber
Fax number

```yaml
Type: String
Parameter Sets: (All)
Aliases: fax_number

Required: False
Position: 11
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Website
Website

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 12
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IdNumber
Company id number

```yaml
Type: String
Parameter Sets: (All)
Aliases: id_number

Required: False
Position: 13
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ParentCompanyId
Parent company id number

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: parent_company_id

Required: False
Position: 14
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### -Notes
Parameter description

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 15
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Slug
Url identifier

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 16
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS
