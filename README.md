# Documentation

## Contents
 - [Description](#description)
 - [How to run](#how-to-run)
 - [Windows build support](#windows-build-support)
 - [Frequently asked questions](#faq)
 - [Contributors list](#contributors-list)
 
&nbsp;

## Description
This is a PowerShell script that automates tasks usually done after a fresh installation of Microsoft™ Windows® operating system. Please do not proceed ahead if you do not have any idea of what this script does.

&nbsp;

## How to run
1. Download the appropriate variant of the script. Extract the ZIP file and place the Win10.ps1 file to your OS drive (Local Disk C primarily).
2. Open PowerShell, go two folders back by doing ```cd ../../```.
3. Type ```Set-ExecutionPolicy Unrestricted``` and press Enter, in the warning that follows, press ```a``` key.
4. Finally, to run the script, do ```./Win10.ps1```. If it prompts with an alert, press ```r``` key.

&nbsp;

## Windows build support
This script currently supports Build 19041 of the May 2020 Update. However, it perfectly runs on Windows 20H2 builds (Build 19042) of the upcoming October 2020 Update.  
**Notes:**  
- Functions of the script that need ```winget``` dependency will not be able to run over properly on Build 19041 of May 2020 update.  
- The tweak concerning Theme aware tiles in start menu needs Build 19041.508 of the May 2020 update to work correctly.  
If any of the above criteria are not met, the script would still continue to run but will throw errors on those particular tasks.

&nbsp;

## FAQ

**Q:** Can I run the script safely?  
**A:** No, you have to understand what the functions do and what will be the implications for you if you run them. Some functions lower security, hide controls and uninstall applications. **If you're not sure what the script does, do not attempt to run it!**

**Q:** I've run the script and it did something I don't like, how can I undo it?  
**A:** For every tweak, there is also a corresponding function which restores the default settings. The default is considered freshly installed Windows 10 or Windows Server 2016 with no adjustments made during or after the installation. Use the tweaks to create and run new preset. Alternatively, since some functions are just automation for actions which can be done using GUI, find appropriate control and modify it manually.

**Q:** I've run the script and it broke my computer / killed someone / caused an apocalypse.  
**A:** I don't care, and that's not a question.

**Q:** I'm using a tweak for &lt;feature&gt; on my installation, can you add it?  
**A:** Submit a PR, create a feature request issue or drop me a message. 

**Q:** Can I use the script or modify it for my / my company's needs?  
**A:** You're allowed to do that as long as your project has references to this repository for picking up further updates that I'll do here.

&nbsp;

## Contributors list
Special thanks to:  
 [Microsoft (MSFT)](https://microsoft.com)  
 [Microsoft Community](https://community.microsoft.com)  
 [Windows Central](https://windowscentral.com)  
 [Chris Titus](https://github.com/ChrisTitusTech)  
 [Davesh](https://t.me/Mr_Agarwal)  
 [Vancel](https://t.me/bancelhub)  
 [Keshav](https://t.me/KeshavJ0shi)  
 [Pulkit](https://t.me/Pulkit077)  
and everyone else who was directly or indirectly involved in this project.

&nbsp;