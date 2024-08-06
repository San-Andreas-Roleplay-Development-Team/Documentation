# Introduction
*This document is property of San Andreas RP and its creator(s)*

### Table of Contents
* <a href="install-git">Installing Git</a>

## [Installing Git](#install-git)

### Basic Install Info
***This selection can be skipped if already install on members computer***

Go to https://git-scm.com/downloads and download the correct file for your system. In this tutorial we will be installing the Windows 64-bit version.

After downloading open the install file, in this case the file is called `Git-245.2-64-bit.exe`. Apon opening the install file you should see the Licensing Info for the software. Make sure to read the License.

The next screen should be where you want to install git. This option will not effect and thing other then some settings later, so choose where ever you want.

Next is what components should be installed with git. The default selection is all you need to install.

### Default editor
This will set the text editor that is used when using commands like `git commit -a` where you do not input a message already.
I would recommend just like Git does a modern GUI editor. If you know Vim keybinds then I would recommand that as it will not open another window.

### Initial Branch Name
Set to override with `development` as the default. You can always change the branch with `git branch -m <old-name> <new-name>`.

### PATH & SSH & HTTPS & Line endings & Terminal & git pull & Manager & Caching & Expermintal
PATH - Use default selected <br>
SSH - If you do not know of what ssh or do not have openssh installed on your computer is keep the use bundled. <br>
HTTPS - Use default selected <br>
Endings - Use default selected <br>
Terminal - Use default selected <br>
Pull - Use default selected <br>
Manager - Use default selected <br>
Caching - Use default selected <br>
Experimental - None are needed <br>

### Checking Install
You can check to see if git install correctly by open a terminal of your choose and doing `git --version`, this will display the version of git installed, in this case its `git version 2.45.2.windows.1`

### Updating Git Config
There is a few configuration options that need to be changed before you can get started using git. The two main options are user.email and user.name, as they are the email and name that is showed when signing is enabled as well as in github. To set these options you can do `git config --system --add <OPTION> <VALUE>`, please follow the name format that is used in the discord, which is `First L. | Number`. To check they are set corretly you can do `git config --list`.

## Installing Code Editor
***This selection can be skipped if any are already install on members computer***

#### Visual Studio Code


<br>

*This document is property of San Andreas RP and its creator(s)* <br>
*Updated: August 6, 2024* <br>
*Approved By* <br>
&nbsp;*August 6, 2024* <br>
&nbsp;&nbsp;*Director ----------- Darian H.* <br>
&nbsp;&nbsp;*Deputy Director -- Vacant*