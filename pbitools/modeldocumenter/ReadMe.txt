Why create model documentation?
The Model Documenter report template produces essential information in very effective format. Creating model documentation is especially important if we want to share the dataset for reuse, or need to review or explain how the data is sourced and calculated in the report.

How to install Model Documenter?
To install the Power BI Model documenter, you can run an easy next-next-finish installer. In order to install the tool, you must have local admin permissions on your device. Without these permissions, it is not possible to install or run the Model Documenter.

# INSTALLATION STEPS

Installer Directory:
 https://github.com/sherlockspreadsheets/Sherlock-Public/tree/main/pbitools/modeldocumenter

A) Run the installer

ModelDocumenter.Installer_v2.1.0.msi
This installer creates a PBI External tool plugin for Power BI Desktop. 

B) Update 2 files using my own customizations, including custom visuals and insights created 

Update 2 files using PBIT customizations
Both files to copy are located in PBI VC document library. To update the files you must enter EP account credentials.

Copy File:
ModelDocumentationTemplate_v2.1.0_(MCSA-Brian).pbit
* The changes made give us custom visuals and insights 
Target Directory
 C:\Program Files (x86)\Common Files\Data-Marc\ModelDocumenter

Copy File:
Data-Marc_ModelDocumenter_v2.1.0.pbitool.json
* The changes made tells the PBI plugin to use the "Brian MCSA" template file, instead of the default template file
Target Directory
 C:\Program Files (x86)\Common Files\microsoft shared\Power BI Desktop\External Tools

# ORIGINAL CREDIT

marclelijveld | External-Tools-Model-Documentation
* The Github repo is the original creator and includes documentation to learn more about the tool, what an external tool is and a page-by-page explanation of the Model Documenter output. 
https://github.com/marclelijveld/External-Tools-Model-Documentation
