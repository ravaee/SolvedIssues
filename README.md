# SolvedIssues
## You can find all the resolved issues and errors that Mohamad Ravaei has been solved them. It is a guide for my own to don`t waste my time for already resolved problems.

HINT: The Questions Are Purple the Errors are in Red :)

# Questions

```diff
+ 1. How to change colors in Readme.md files?

# you can use ```diff tag in your readme file also check the text of this read me file you will understand :)

+ 2. Installing and Uninstalling powershell`s packages?

Below you can see an example of installing Azure-modules for powershell 

# Install-Module -Name Az -Repository PSGallery -Force -AllowClobber
# Uninstall-Module -Name Az 
```


# Errors

```diff
- 1. How to resolve not running the ps1 files or any script with the error text below? 
- File C:\Projects\tests\ForcastApp-master\dashagh\Create-AzureResources.ps1 cannot be loaded. The file C:\Projects\tests\ForcastApp-master\dashagh\Create-AzureResources.ps1 is not digitally signed.

# Run the Script below
# Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```


