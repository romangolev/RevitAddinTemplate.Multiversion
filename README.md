# Revit Multiversion Addin Template for Visual Studio 2022
## Description
- This is basic Revit Add-in template for Visual Studio
- It uses configurations to target different versions of Revit
- Is targeting each version of Revit assummint that they have been installed in the default location
- Has a post-build event that copied all files to the Revit Addins folder located in ```%appdataAutodesk\Revit\Addins```
- Supports Revit 2020 to 2025

## Installation 
To install the template, download the zip file from the latest [Release](https://github.com/romangolev/RevitAddinTemplate.Multiversion/releases) and copy it to the following location:

```
%USERPROFILE%\Documents\Visual Studio 2022\Templates\ProjectTemplates
```

Or download and run VSIX file attached to the release in order to install the template. The template will apear as an extension for Visual Studio

Or simply install this extension from a Visual Studio Marketplace [Revit Multiversion Addin Template](https://marketplace.visualstudio.com/items?itemName=RomanGolev.RevitMultiversionAddinTemplate)

## Usage
- Create new project in Visual Studio and select the template from the list.
- Select the version of Revit in the list of configurations
- By starting project you'll trigger a new session of Revit attached to the template 
- Develop you plugin and have fun ;)


With <3 by [Roman Golev](https://www.romangolev.com/), 2024