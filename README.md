# BloodHound-Queries
Custom queries list for BloodHound

![image](https://github.com/chryzsh/awesome-bloodhound/raw/master/bh.png)

## Introduction
This is mostly a compilation of some awesome queries I've found out there, with a few additions according to my needs and also some bug fixes.

Currently, these queries are based on:
  - [hausec's custom queries](https://github.com/hausec/Bloodhound-Custom-Queries)
  - [CompassSecurity's custom queries](https://github.com/CompassSecurity/BloodHoundQueries)

## Get Started
On Linux, you can simply install the queries using this curl command:
```sh
$ curl -o "~/.config/bloodhound/customqueries.json" "https://raw.githubusercontent.com/mchoji/BloodHound-Queries/main/customqueries.json"
```

On Windows, you can simply install the queries using this PowerShell command:
```powershell
PS C:\> Invoke-WebRequest -Uri "https://raw.githubusercontent.com/mchoji/BloodHound-Queries/main/customqueries.json" -OutFile "$env:USERPROFILE\AppData\Roaming\bloodhound\customqueries.json"
```

## Extras
Besides the previously cited repos, you may also find useful content about BloodHount at [awesome-bloodhound by chryzsh](https://github.com/chryzsh/awesome-bloodhound).
