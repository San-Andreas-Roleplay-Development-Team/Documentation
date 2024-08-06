# Introduction
*This document is property of San Andreas RP and its creator(s)*

* [Installing Git](#installing-git) <br>
      + [Basic Install Info](#basic-install-info) <br>
      + [Default editor](#default-editor) <br>
      + [Initial Branch Name](#initial-branch-name) <br>
      + [PATH & SSH & HTTPS & Line endings & Terminal & git pull & Manager & Caching & Expermintal](#path-ssh-https-line-endings-terminal-git-pull-manager-caching-expermintal) <br>
      + [Checking Install](#checking-install) <br>
      + [Updating Git Config](#updating-git-config)
* [Installing Code Editor](#installing-code-editor) <br>
      + [Visual Studio Code](#visual-studio-code) <br>
* Other Information <br>
      + [Roster and Equivalently Structure](Roster-and-Equivalently.md) <br>
      + [FiveM Natives](https://docs.fivem.net/natives/) <br>
      + [FiveM CLRCore](https://github.com/citizenfx/fivem/tree/master/code/client/clrcore)

<a name="installing-git"></a>

## Installing Git

<a name="basic-install-info"></a>

### Basic Install Info
[!NOTE]
***This selection can be skipped if already install on members computer***

Go to https://git-scm.com/downloads and download the correct file for your system. In this tutorial we will be installing the Windows 64-bit version.

After downloading open the install file, in this case the file is called `Git-245.2-64-bit.exe`. Apon opening the install file you should see the Licensing Info for the software. Make sure to read the License.

The next screen should be where you want to install git. This option will not effect and thing other then some settings later, so choose where ever you want.

Next is what components should be installed with git. The default selection is all you need to install.

<a name="default-editor"></a>

### Default editor
This will set the text editor that is used when using commands like `git commit -a` where you do not input a message already.
I would recommend just like Git does a modern GUI editor. If you know Vim keybinds then I would recommand that as it will not open another window.

<a name="initial-branch-name"></a>

### Initial Branch Name
Set to override with `development` as the default. You can always change the branch with `git branch -m <old-name> <new-name>`.

<a name="path-ssh-https-line-endings-terminal-git-pull-manager-caching-expermintal"></a>

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

<a name="checking-install"></a>

### Checking Install
You can check to see if git install correctly by open a terminal of your choose and doing `git --version`, this will display the version of git installed, in this case its `git version 2.45.2.windows.1`

<a name="updating-git-config"></a>

### Updating Git Config
There is a few configuration options that need to be changed before you can get started using git. The two main options are user.email and user.name, as they are the email and name that is showed when signing is enabled as well as in github. To set these options you can do `git config --system --add <OPTION> <VALUE>`, please follow the name format that is used in the discord, which is `First L. | Number`. To check they are set corretly you can do `git config --list`.

<a name="installing-code-editor"></a>

## Installing Code Editor
[!NOTE]
***This selection can be skipped if any are already install on members computer***

<a name="visual-studio-code"></a>

### Visual Studio Code


<br>

*This document is property of San Andreas RP and its creator(s)* <br>
*Updated Date: August 6, 2024* <br>
*Approved Date: August 6, 2024* <br>
*Approved By* <br>
&nbsp;&nbsp;*Director ----------- Darian H.* <br>
&nbsp;&nbsp;*Deputy Director -- Vacant*