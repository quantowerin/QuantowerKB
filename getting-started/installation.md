---
description: System requirements and 3 simple steps to successfully install the platform
---

# Installation

* [**System Requirements**](installation.md#pc-requirements)\*\*\*\*
* \*\*\*\*[**Installation Steps**](installation.md#installation-steps)\*\*\*\*
* \*\*\*\*[**Uninstallation**](installation.md#uninstall)\*\*\*\*

Once you downloaded Quantower application from Quantower official website — you are ready to start an installation process. From this point we must clarify the main differences between Quantower "installation process" and default Windows® install process, that most users are accustomed to.

{% embed url="https://youtu.be/PxP-BhDs-J4" caption="" %}

{% hint style="success" %}
Quantower does not copy it's files to the system folders \(AppData or Program Files\) of the OS, nor does write changes to the system registry
{% endhint %}

What does it mean? The program doesn't violate the integrity of the OS, and in case of removal, it will not leave any prints of its presence on your computer. Quantower’s "installer" literally extracts files to the user-specified folder.

This approach allows you to store \(and launch\) the Quantower on removable drive for use on any other computer as the portable application. It can be convenient when you need to move Quantower with all of its settings to another PC; just copy Quantower folder and paste where you need.

## PC requirements

{% hint style="info" %}
* Windows 7, 10
* .NET Framework v.4.7.2
* Available disk space — 1 GB \(depends on the volume of loaded history\)
{% endhint %}

{% hint style="warning" %}
Microsoft has officially stopped supporting Windows 8. Therefore, when you purchase a license, you will not be able to log in to the application under your account. In the free version, all available functionality of the platform will work properly.  
We recommend updating Windows to version 10.
{% endhint %}

## Installation steps

![Quantower installer screen](../.gitbook/assets/extract-files-quantower.png)

1. [**Download the app installer**](https://updates.quantower.com/Quantower/x64/latest/Quantower.exe) and launch the _**Quantower.exe**_ file
2. Select the folder to extract application files
3. Once an extraction process being finished the platform will start automatically with **Binance connection** in Info Mode and with the default workspace

{% hint style="warning" %}
Please note, that you may need to allow an in-going and outgoing connection for _**Starter.exe**_ file \(the main executable of Quantower terminal\) in your Firewall settings
{% endhint %}

![](../.gitbook/assets/default-workspace.png)

## Uninstall

If you need to uninstall the application, just _**delete the folder with all application files**_. You may also keep your personal settings \(connection information & workspaces\) by copying the Settings folder \(can be found right in Quantower folder\) before application delete. These Settings folder can be pasted to any other Quantower folder later.

You may also refer to [**Backup & Restore manager**](backup-and-restore-manager.md) to backup your settings in one file and restore them later.

