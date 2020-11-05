# Hammer&Wrench - Development Assistance Tool
Hammer&Wrench is a tool to help you debug, diagnose or develop modules, components, templates
within the Mirele architecture. Simply install the tool in the template folder
and choose one of the paths:
1. Connect the file directly to the template
2. Use it as a CLI utility

### How do I install the tool in my Mirele distribution?
> __ATTENTION__: If you have already installed and worked with the Mirele developer tools - __CREATE BACKUP package.json FILE__! During the following operations this file will be overwritten.
If you do not have this file - you can ignore this warning.

The distribution is the same as the theme. By 'distribution' we mean the theme installed in your WordPress. 
The tool is very easy to install. You can do it with just one command

```console
(curl "https://raw.githubusercontent.com/irtex-mirele/Hammer-Wrench/main/Hammer&Wrench.php" > "Hammer&Wrench.php" && curl "https://raw.githubusercontent.com/irtex-mirele/Hammer-Wrench/main/project.json" > "project.json" && print "\u001b[37mMirele — \u001b[32mInstallation is successfully completed. The "install" step has been successfully completed")
```
<sub><sup>Installation of Hammer&Wrench and package.json file</sup></sub>

In your console you will see something like this. 
 
<img src="https://i.ibb.co/d7L0ms6/install.png" wdith="100%">

At this step, the installation phase of the tool is successfully completed!

### Introduction
In console mode, the utility can accept a set of arguments

##### `options`

###### `--binders`
Build a script to automatically connect files of templates and Compound components

###### `--compound`
Building the script of automatic connection of files of elements of the Compound framework

###### `--requests`
Building a script to automatically connect files with the bodies of web request handlers 
