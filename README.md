# Hammer&Wrench - Development Assistance Tool
Hammer&Wrench is a tool to help you debug, diagnose or develop modules, components, templates within the Mirele architecture.

Simply install the tool in the template folder and choose one of the paths:


1. Connect the file directly to the template
2. Use it as a CLI utility


### How do I install the tool in your Mirele distribution?
> __ATTENTION__: If you have already installed and worked with the Mirele developer tools - __CREATE BACKUP package.json FILE__! During the following operations this file will be overwritten.
If you do not have this file - you can ignore this warning.

The distribution is the same as the theme. By 'distribution' we mean the theme installed in your WordPress. 
The tool is very easy to install. You can do it with just one command

```console
(curl "https://raw.githubusercontent.com/irtex-mirele/Hammer-Wrench/main/Hammer&Wrench.php" > "Hammer&Wrench.php" && curl "https://raw.githubusercontent.com/irtex-mirele/Hammer-Wrench/main/project.json" > "project.json" && print "\u001b[37mMirele — \u001b[32mInstallation is successfully completed. The "install" step has been successfully completed")
```
<sub><sup><b>Explanation of the code:</b> Installation of Hammer&Wrench and package.json file</sup></sub>

In your console you will see something like this. 
 
<img src="https://i.ibb.co/d7L0ms6/install.png" wdith="100%">

At this step, the installation phase of the tool is successfully completed!

### Introduction to CLI modes of the utility
#### Checking PHP
Make sure you have php 7+ installed, type the command in the terminal to do this:
```console
php -v
```
<sub><sup><b>Explanation of the code:</b> Checking the PHP version</sup></sub>

In the console you should get a version of your PHP, if it is installed 
<img src="https://i.ibb.co/WKqRCx3/php.png" wdith="100%">

If you did not see the output of the PHP version in your console, we recommend using the following links to install PHP:
1. https://www.php.net/manual/en/install.unix.debian.php
2. https://linuxize.com/post/how-to-install-php-on-ubuntu-18-04

Also make sure that your version of PHP is above version _7.0.0_.

#### Checking Hammer&Wrench
After checking the PHP version, you can start working. To access the utility, enter the command 

```console
php "Hammer&Wrench.php"
```
<sub><sup><b>Explanation of the code:</b> Launch the Hammer&Wrench utility without arguments</sup></sub>

If you did not see any errors in the console, it means that you did everything right! Congratulations on your first successes! 

#### The first use. Information about available commands
To know the available commands, pass the _--help_ argument to the utility.

```console
php "Hammer&Wrench.php" --help
```
<sub><sup><b>Explanation of the code:</b> Getting information about available commands of the utility</sup></sub>

The rest of the information on commands can be found in the [WiKi](https://github.com/irtex-mirele/Hammer-Wrench/wiki)

***
Good luck in diagnosis and development 
