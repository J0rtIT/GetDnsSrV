# Powershell Module

Uses Regex to transfor the output of NSLOOKUP into a PS object and show it on screen.

## Requires
- Fully updated computer with .Net 4.5

## What is this domain made for?
As an Powershell and Exchange expert, makes easier to query if a domain has the DNS SRV record for autodiscover service 

## How to use it?
```Powershell
$> Set-executionPolicy Unrestricted
$> import-module .\GetDnsSrvRecord.dll

```


## How many Cmdlets it has?
- 1 => Get-DNSSrvRecord

##How to use the module:
```Powershell
$> Get-DNSSrvRecord <domain.com> -SoloSRV
```
### Example, query the domain j0rt3g4.com
```Powershell
$> Get-DNSSrvRecord <domain.com> -SoloSRV
```

Code Published on [TechNet](https://gallery.technet.microsoft.com/office/PSModule-GetDns-ecords-89b7d665)

Thank you and don't forget to rate it on [TechNet](https://gallery.technet.microsoft.com/office/PSModule-GetDns-ecords-89b7d665)
