# ASCOOS CMS Snippets

## Description

These is Visual Studio Code snippets and code examples, for the ASCOOS CMS.

All code snippets are based on and follow the [Ascoos CMS Documantation](https://docs.ascoos.com)

## Contributing

This is an open source project, open to anyone. 

Contributions are welcome [github](https://github.com/ascoos/vsc-ascoos-cms-snippets)


## Feedback

Please send any feedback or suggestions to [@ascoos](https://twitter.com/ascoos) (Twitter) or [create an issue](https://github.com/ascoos/vsc-ascoos-cms-snippets/issue) on GitHub.

 
## Open Source

This is an open source project and if you want to contribute I've added issues on github that are easy to start with. [![first-timers-only](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](https://github.com/ascoos/vsc-ascoos-cms-snippets/labels/first-timers-only)

 
## Disclaimer

Important: This extension due to the nature of it's purpose will create files on your hard drive and if necessary create the respective folder structure.
While it should not override any files during this process, I'm not giving any guarantees or take any responsibility in case of lost data.

 
## License

AGL-F (ASCOOS General License - Free)

***

## Download

[VSIX Package](https://dl.ascoos.com/vscode/vsc-ascoos-cms-snippets.vsix)

***

# Installation

## Installation (Mac)

1. Launch VS Code
1. Quick Open (⌘+P)
1. Enter the following 'ext install...' command and select: 'EXTENSIONS: Install drom VSIX'
1. Reload Visual Studio Code

## Installation (Windows, Linux)

1. Launch VS Code
1. Quick Open (Ctrl-Shift-P)
1. Enter the following 'ext install...' command and select: 'EXTENSIONS: Install drom VSIX'
1. Reload Visual Studio Code

***

# ASCOOS CMS Snippets

## Snippet Prefixes

| Prefix   | Description 
| -------- | ------------------------------------------
| `a-`     | General Snippets
| `act-`   | ASCOOS Snippet Templates for codes
| `a-c-`   | Consts Snippets
| `a-d-`   | Defines Snippets
| `a-f-`   | Functions Snippets
| `a-i-`   | Information & Comments Snippets
| `a-v-`   | Variables Snippets
| `a-o-`   | Objects Implementation Snippets
| `a-css-` | Ascoos CSS Snippets
| `jas-`   | jAscoos Library Snippets (Javascript)

***

## COMMENTS & INFORMATIONS   [ `a-i-` ]

Snippet                                  | Purpose                                    
---------------------------------------- | -------------------------------------------------------
`a-i-comments-file-info`                 | Add informations for this ASCOOS file.

***

## CONSTS

Snippet                                  | Type          | Purpose                                    
---------------------------------------- | ------------- | --------------------------------------------------------
`ADMIN_SIDE`                             | BOOLEAN       | Contains the Administration Side of the website.
`ASCOOS_PROGRAM_NAME`                    | STRING        | 

***

## Variables   [ `a-v-` ]

Snippet                                  | Type          | Purpose                                    
---------------------------------------- | ------------- | --------------------------------------------------------
`a-v-admin-side`                         | BOOLEAN       | Contains the Administration Side of the website.             
`a-v-cms-path`                           | STRING        | Contains the physical path of the website
`a-v-cms-site`                           | STRING        | Contains the url of the website.
`a-v-INI-GetSection`                     | STRING        | To get the INI Section.
`a-v-ip`                                 | STRING        | Contains the Remote IP Address

***

## $app   [ `Application Class` ]

Function                        | Version | Purpose
------------------------------- | ------- | --------------------------------------------------------------------------
`setTitle`                      |  0.0.1  | Sets the title of the document
`setMetaData`                   |  0.0.1  | We set or change a meta tag.
`init`                          |  0.0.1  | 
`done`                          |  0.0.1  | 
`removeMetaData`                |  0.0.1  | We remove and release a meta tag from the list.
`addStyleFromFile`              |  0.0.1  | Adds a linked stylesheet to the page
`addStylesFromFile`             |  0.0.1  | Adds a linked stylesheet to the page
`addTypographyStyles`           |  0.0.1  | Adds a linked typo stylesheet to the page
`addStyle`                      |  0.0.1  | Adds a stylesheet declaration to the page
`addImportStyle`                |  0.0.1  | Adds a linked stylesheet to the page
`addScriptFromFile`             |  0.0.1  | 
`addScriptFromCDN`              |  0.0.1  | 
`addScript`                     |  0.0.1  | 
`addJAScript`                   |  0.0.1  | 
`addLink`                       |  0.0.1  | 
`writeTitle`                    |  0.0.1  | 
`writeHeadLinks`                |  0.0.1  | 
`writeLink`                     |  0.0.1  | 
`writeMetaTags`                 |  0.0.1  | 
`writeDefLinks`                 |  0.0.1  | 
`writeCSSLinks`                 |  0.0.1  | 
`writeCombinedCSSLinks`         |  0.0.1  | 
`writeDefCSSLinks`              |  0.0.1  | 
`writeCSSImports`               |  0.0.1  | 
`writeDynamicSendCSS`           |  0.0.1  | 
`writeScriptFiles`              |  0.0.1  | 
`writeCombinedScriptFiles`      |  0.0.1  | 
`writeDefScripts`               |  0.0.1  | 
`writeJAScripts`                |  0.0.1  | Γράφει τα jAscoos και τα jQuery javascripts στο τέλος της σελίδας.... μαζεμένα...
`writeCustomHead`               |  0.0.1  | 
`dynamicLoadScript`             |  0.0.1  | 
`getName`                       |  0.0.1  | Παίρνουμε το το όνομα ή τίτλο από ένα πεδίο Text
`setOffline`                    |  0.0.1  | Θέτει εκτός λειτουργία ή επναφέρει σε λειτουργία το frontend του ιστοχώρου.
`writeDocType`                  |  0.0.1  | 
`headDOCInfo`                   |  0.0.1  | 
`startHead`                     |  0.0.1  | 
`endHead`                       |  0.0.1  | 
`getPath`                       |  0.0.1  | 
`redirect`                      |  0.0.1  | 
`Run`                           |  0.0.1  | 
`standardHeaders`               |  0.0.1  | 
`fixedCSSFile`                  |  0.0.1  | 
`dynamicScript`                 |  0.0.1  | 
`dynamicCSS`                    |  0.0.1  | 
`writeFavicon`                  |  0.0.1  | 

***

## $objInstaller   [ `Installer Class` ]

It is the main object for the installation/uninstall operation of the various components of Ascoos CMS, such as Blocks, Themes, Plugins, etc.


Function                        | Version | Purpose
------------------------------- | ------- | --------------------------------------------------------------------------
`setExtension`                  |  0.0.1  | We set the extension that will manage the installation object.
`setPackageFile`                |  0.0.1  | We set the compressed installation package containing the files of the extension to be installed
`createPath`                    |  0.0.1  | 
`removePath`                    |  0.0.1  | 
`setInstallIntetifierFile`      |  0.0.1  | 
`setInstallFile`                |  0.0.1  | 
`getPath`                       |  0.0.1  | Returns the actual path of the component that is to be installed or uninstalled.
`isInstalled`                   |  0.0.1  | Returns a reasonable value. TRUE = The path exists, FALSE = Does not exist
`extractPackage`                |  0.0.1  | Extract the installation package to the appropriate system directory.
`extractThemes`                 |  0.0.1  | We move the internal folder with the themes to the final folder
`getPosition`                   |  0.0.1  | We take the position id, show called "article_details"
`addPosition`                   |  0.0.1  | 
`getOrderPosition`              |  0.0.1  | We take the sort order for the new extension based on the display position.
`existExtension`                |  0.0.1  | 
`afterSetParams`                |  0.0.1  | 
`resetInstall`                  |  0.0.1  | 
`cancelInstallation`            |  0.0.1  | 
`clear`                         |  0.0.1  | 

***

## $objHeader   [ `Header Class` ]

Function                        | Version | Purpose
------------------------------- | ------- | --------------------------------------------------------------------------
`deleteAll`                     |  0.0.1  | 
`setMetaData`                   |  0.0.1  | 

***

## $objRequest  [ `Request Class` ]

Function                        | Version | Purpose
------------------------------- | ------- | --------------------------------------------------------------------------
`setExcludeStrip`               |  0.0.1  | Δηλώνουμε ποιες ετικέτες θα αφαιρέσουμε από το κείμενο
`get`                           |  0.0.1  | 
`getCurrent`                    |  0.0.1  | 
`removeKey`                     |  0.0.1  | 

***

## $objError  [ `Error Class` ]

Function                        | Version | Purpose
------------------------------- | ------- | --------------------------------------------------------------------------
`addError`                      |  0.0.1  | 
`getErrorsFromSession`          |  0.0.1  | 
`setErrorsInSession`            |  0.0.1  | 
`SOL`                           |  0.0.1  | Εμφάνιση του πλαισίου που ενημερώνει ότι ο ιστοχώρος είναι offline βάσει λάθους στην Βάση Δεδομένων.
