<p align="center"><img src="https://dl.ascoos.com/images/ascoos.png" height=120 /></p>

# ASCOOS CMS Snippets

## Description

These is Visual Studio Code snippets and code examples, for the ASCOOS CMS.

All code snippets are based on and follow the [Ascoos CMS Documantation](https://docs.ascoos.com/cms/ascoos)

## Contributing

This is an open source project, open to anyone. 

Contributions are welcome [github](https://github.com/ascoos/vsc-ascoos-cms-snippets)


## Feedback

Please send any feedback or suggestions to [@ascoos](https://twitter.com/ascoos) (Twitter) or [create an issue](https://github.com/ascoos/vsc-ascoos-cms-snippets/issues) on GitHub.

 
## Disclaimer

Important: This extension due to the nature of it's purpose will create files on your hard drive and if necessary create the respective folder structure.
While it should not override any files during this process, I'm not giving any guarantees or take any responsibility in case of lost data.

 
## License

[AGL-F (ASCOOS General License - Free)](http://docs.ascoos.com/lics/ascoos/AGL-F.html)

<BR>

***

<BR>

## Download

[VSIX Package](https://dl.ascoos.com/vscode/vsc-ascoos-cms-snippets.vsix)

<BR>

***

<BR>

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

<BR>

***

<BR>

# ASCOOS CMS Snippets

## Snippet Prefixes

In the table below you can see the prefixes of the snippets of **`Ascoos Cms`** as well as their implementation rate in the current version of this extension of **`Visual Studio Code`**

| Prefix   | Completes                    | Description 
| -------- | ---------------------------- | -------------------------
| **`***`**    | ■■■■■■■■□□□□□□□□□□□□ 40%     | Information & Comments Snippets
| **`php`**    | ■■■■□□□□□□□□□□□□□□□□ 20%     | Create php tag with Information Comments
| **`alf_`**   | ■■□□□□□□□□□□□□□□□□□□ 10%     | Ascoos Library Function (ALF) Snippets
| **`a-g-`**   | ■□□□□□□□□□□□□□□□□□□□ 5%      | General Snippets
| **`act-`**   | ■□□□□□□□□□□□□□□□□□□□ 3%      | ASCOOS Snippet Templates for codes
| **`a-c-`**   | ■□□□□□□□□□□□□□□□□□□□ 1%      | Consts Snippets
| **`a-d-`**   | ■□□□□□□□□□□□□□□□□□□□ 1%      | Defines Snippets
| **`a-f-`**   | □□□□□□□□□□□□□□□□□□□□ 0%      | Functions Snippets
| **`a-v-`**   | ■□□□□□□□□□□□□□□□□□□□ 1%      | Variables Snippets
| **`a-o-`**   | ■□□□□□□□□□□□□□□□□□□□ 2%      | Objects Implementation Snippets
| **`a-css-`** | □□□□□□□□□□□□□□□□□□□□ 0%      | Ascoos CSS Snippets
| **`jas-`**   | □□□□□□□□□□□□□□□□□□□□ 0%      | jAscoos Library Snippets (Javascript)

<br>

***

<br>

## COMMENTS & INFORMATIONS   [ `***` ]

All ASCOOS CMS comment snippets are generated using the keyword [///] inside a php file.

[Documantation for this snippets](https://docs.ascoos.com/vscode/comment-snippets.html)

 Prefix  |      Alternative Prefix       | Purpose                                    
-------- | ----------------------------- | ----------------------------------------
  `///`  | `a-i-comments-file-info`      | Add file comment.
  `///`  | `a-i-comments-functions-info` | Add function comment.
  `///`  | `a-i-comments-variables-info` | Add Variable (var or property) comment.

<br>

***

<br>

## GENERAL   [ `a-g-` ]

[Documantation for general snippets](https://docs.ascoos.com/vscode/general-snippets.html)

Snippet                             | Purpose                                    
----------------------------------- | -------------------------------------------------------
`a-g-add-define-run-cms`            | Add define the ASCOOS CMS execution variable
`a-g-new-class`                     | Add class.
`a-g-new-interface`                 | Add interface.
`a-g-new-function`                  | Add public function.
`a-g-new-class-method-private`      | Add private method.
`a-g-new-class-method-puplic`       | Add puplic method.
`a-g-new-class-property-private`    | Add private property in class.
`a-g-new-class-property-public`     | Add public property in class.
`a-g-new-global-constant`           | Add global constant

<br>

***

<br>

## CODE TEMPLATES

Snippet                                  | Purpose                                    
---------------------------------------- | --------------------------------------------------------
`act-install-file`                       | Add code template for ASCOOS install file.

<BR>

***

<BR>

## CONSTANTS - DEFINES

Snippet                                  | Type          | Purpose                                    
---------------------------------------- | ------------- | --------------------------------------------------------
`ADMIN_SIDE`                             | BOOLEAN       | Contains the Administration Side of the website.
`ASCOOS_PROGRAM_NAME`                    | STRING        | Contains the official name of the program

<BR>

***

<BR>

## $objInstaller   [ `TInstallerHandler Class` ]

See: [Installer Class Documentation](https://docs.ascoos.com/cms/ascoos/core.class.TInstaller.html)

It is the main object for the installation/uninstall operation of the various components of Ascoos CMS, such as Apps, Blocks, Themes, Plugins, etc.

Constants                      | Type      | Purpose                                    
------------------------------ | --------- | --------------------------------------------------------
`INS_ADMIN_APP`                | INTEGER   | Install Application (In Administration - [CAN BE UNINSTALL])
`INS_ADMIN_BLOCK`              | INTEGER   | Install Block (In Administration - [CAN BE UNINSTALL])
`INS_ADMIN_PLUGIN`             | INTEGER   | Install Plugin (In Administration - [CAN BE UNINSTALL])
`INS_ADMIN_WIDGET`             | INTEGER   | Install Widget (In Administration - [CAN BE UNINSTALL])
`INS_BLOCK`                    | INTEGER   | Install Block
`INS_DEMO`                     | INTEGER   | Fake Install (For Demo use)
`INS_NOTHING`                  | INTEGER   | NO ACTION
`INS_PLUGIN`                   | INTEGER   | Install Plugin
`INS_PLUGIN_ARTICLE`           | INTEGER   | Install Plugin (For Articles)
`INS_PLUGIN_CONTENT`           | INTEGER   | Install Plugin (For Contents)
`INS_PLUGIN_EDITOR`            | INTEGER   | Install Plugin (For Editors)
`INS_PLUGIN_EDITOR_BTN`        | INTEGER   | Install Plugin (For Editor Buttons)
`INS_PLUGIN_SEARCH`            | INTEGER   | Install Plugin (For Search)
`INS_PLUGIN_SYSTEM`            | INTEGER   | Install Plugin (For System)
`INS_PLUGIN_TOOL`              | INTEGER   | Install Plugin (For Tools)
`INS_PLUGIN_WIDGET`            | INTEGER   | Install Plugin (For Widgets)
`INS_SYSTEM`                   | INTEGER   | Installation of ASCOOS CMS system components.
`INS_SYSTEM_APP`               | INTEGER   | Install System Program (CANNOT UNINSTALL).
`INS_THEME`                    | INTEGER   | Install Theme (Package 3LT Template - [Front, Frontpage, EFP])
`INS_THEME_3LT_FRONT`          | INTEGER   | Install Theme (For Front)	
`INS_THEME_3LT_FRONTPAGE`      | INTEGER   | Install Theme (For Frontpage)
`INS_THEME_3LT_EFP`            | INTEGER   | Install Theme (For EFP - Encapsulation Frotnpage)
`INS_THEME_ADMIN_APP`          | INTEGER   | Install Theme (For Administration Applications)
`INS_THEME_ADMIN_BLOCK`        | INTEGER   | Install Theme (For Administration Block)
`INS_THEME_ADMIN_DESKTOP`      | INTEGER   | Install Theme (For Administration Desktop)
`INS_THEME_ADMIN_LOGIN`        | INTEGER   | Install Theme (For Administration Login page)
`INS_THEME_ADMIN_PLUGIN`       | INTEGER   | Install Theme (For Administration Plugins)
`INS_THEME_ADMIN_SET`          | INTEGER   | Install Full Theme (For Administration)
`INS_THEME_ADMIN_TASKBAR`      | INTEGER   | Install Theme (For Administration Desktop Taskbar)
`INS_THEME_ADMIN_WALLPAPER`    | INTEGER   | Install Wallpaper (In Administration)
`INS_THEME_ADMIN_WINDOW`       | INTEGER   | Install Theme (For Administration Desktop Windows)
`INS_THEME_ADMIN_WIDGET`       | INTEGER   | Install Theme (For Administration Desktop Widgets)
`INS_THEME_APP`                | INTEGER   | Install Theme (For Application)
`INS_THEME_BLOCK`              | INTEGER   | Install Theme (For Block)
`INS_THEME_CONTACT`            | INTEGER   | Install Theme (For Contact pages)
`INS_THEME_FORM`               | INTEGER   | Install Theme (For Forms)
`INS_THEME_MENU`               | INTEGER   | Install Theme (For Menus)
`INS_THEME_NEWSLETTER`         | INTEGER   | Install Theme (For Newsletter)
`INS_THEME_PAGERANK`           | INTEGER   | Install Theme (For Pageranks)
`INS_THEME_PLUGIN`             | INTEGER   | Install Theme (For Plugin)
`INS_THEME_PRINT`              | INTEGER   | Install Theme (For Print pages)
`INS_THEME_RATE`               | INTEGER   | Install Theme (For Rates)
`INS_THEME_STATE_CONSTRUCTION` | INTEGER   | Install Theme (For Construction pages)
`INS_THEME_STATE_ERROR`        | INTEGER   | Install Theme (For Error pages)
`INS_THEME_STATE_OFFLINE`      | INTEGER   | Install Theme (For Offline pages)
`INS_THEME_TYPOGRAPHY`         | INTEGER   | Install Typography
`INS_USER_APP`                 | INTEGER   | User program installation (CAN BE UNINSTALL).

<BR>
<BR>

Function                        | Version | Purpose
------------------------------- | ------- | --------------------------------------------------------------------------
`addPosition`                   |  0.0.1  | We add a display location for the extension we install. This is useful if we want to have unique display positions for each of our extensions.
`addSQL`                        |  0.0.1  | Executes an insert query to the database
`afterSetParams`                |  0.0.1  | We declare whether after installation, the configuration of the installed extension will be performed.
`cancelInstallation`            |  0.0.1  | Cancels the installation process, removing all actions the installer has taken so far.
`clear`                         |  0.0.1  | Deletes the installed package, the installation file and resets the installation parameters to their default values.
`createPath`                    |  0.0.1  | Creates the given installation path
`deletePackage`                 |  0.0.1  | Delete the installation package
`deleteTempData`                |  0.0.1  | Delete temporary files
`existExtension`                |  0.0.1  | We check if the extension exists in the extension registry
`extractPackage`                |  0.0.1  | Extract the installation package to the appropriate system directory.
`extractThemes`                 |  0.0.1  | We move the internal folder with the themes to the final folder
`getOrderPosition`              |  0.0.1  | We take the sort order for the new extension based on the display position.
`getPosition`                   |  0.0.1  | We get the ID of the position where the installed extension will appear.
`getType`                       |  0.0.1  | We get the type of extension managed by the installation object
`installData`                   |  0.0.1  | We install the components of the extension.
`isInstalled`                   |  0.0.1  | Returns a reasonable value. TRUE = The path exists, FALSE = Does not exist
`removePath`                    |  0.0.1  | Delete the installation package
`resetInstall`                  |  0.0.1  | Resets the default values of the properties of the installation object.
`setExtension`                  |  0.0.1  | We set the extension that will manage the installation object.
`setInstallFile`                |  0.0.1  | We define and load the installation file.
`setInstallIdentifierFile`      |  0.0.1  | Set and load installation Identifier file.
`setPackageFile`                |  0.0.1  | We set the compressed installation package containing the files of the extension to be installed
`setType`                       |  0.0.1  | We set the type of extension that the installation object will manage
`tempExtracts`                  |  0.0.1  | Extracts the installation package to a temporary directory in Cache for checking
