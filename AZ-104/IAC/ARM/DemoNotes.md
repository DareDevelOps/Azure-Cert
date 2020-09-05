# ARM template demo notes

## ARM Workflow and Lifecycle

- Author
- Validate
- Deploy
- Manage

### Author

There are 3 primary ways to author an ARM tempplate

- Create it from scratch
- Download prior to final deployment with download a template for automation
- Download after deployment from the export template

The other way to create ARM templates is to download a pre-built

template and modify it to meet your needs.

you can get pre-built templates from the [ARM Quickstart Templates](https://azure.microsoft.com/en-us/resources/templates/)

### Create template from scratch

- Create a code folder

``` PowerShell 
New-Item -Path . -Name arm -ItemType Directory
```

- Change to the new directory

``` PowerShell
New-Item -Path . -Name compute.json -ItemType File
```

- Open blank template in VSCode

``` PowerShell
code .\compute.json
```

- Initialize ARM template

``` PowerShell
arm! 
```
