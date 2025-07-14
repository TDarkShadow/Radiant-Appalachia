# Radiant Appalachia
A Fallout 76 Wabbajack modlist to add some Quality of Life mods to the game.

> [!WARNING]
> This is an early work-in-progess modlist.

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]
[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Requirements

### Hardware requirements

* CPU equal to i5 6600K or better
* GPU equal to GTX 1070 or better 

>[!TIP]
> An SSD is very beneficial to the play the game and modlist.  
> If you have storage space issues, you can store the downloads on an hard drive, and remove them after a succesful installation. 

### Software requirements

* Windows 10 (22H2, build 19045.6093) or Windows 11 (24H2, build 26100.4652)
* Steam
* Fallout 76 on Steam
* A NexusMods account (Premium is not necessary)

>[!TIP]
> Press `Win Key + R`, and type in `winver`.  
> Press **OK** and you'll see your Windows build version.  

>[!NOTE]
> Only official **Windows 10** and **11** operating systems are supported.
> I cannot support Windows LTSC, special variants, lightened / debloated editions or any other modified variant.  
> I do not use Linux myself so I can't support Linux installations.

>[!WARNING]
> Ideally, but optional, Fallout 76 should be installed **outside** Program Files.  
> I recommend using this tool by LostDragonist to have a second Steam Library configured outside your Program Files directory.  
> https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide

# Installation

If you are updating the modlist, you can safely skip to the [updating section](#updating-the-modlist).

## Pre-Installation

These steps are only required for installing the modlist for the first time. Additionally, many of these steps may be covered in other modlist installs, for new users I suggest reading through here regardless.

### Installing Microsoft Visual C++ and .NET

 1. Install [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe).
 2. Install [.NET Runtime 9.X.X Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/9.0).
 3. Install [.NET 6.0 Runtime Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.30-windows-x64-installer).

>[!WARNING]
>If you already have Visual C++ installed, please make sure you install it again and use the `Repair` option to get the latest version of the redistributables. **Do NOT skip this step or MO2 and the game may fail to launch.**

### Setting Shader Cache Size (NVIDIA Users Only)

>[!IMPORTANT]
>For NVIDIA users, it is recommended to boost the size of the shader cache. These settings have been shown to improve stability, while it may not be entirely necessary, it is still recommended.

**To do this:**

- Right-click on your desktop and select `NVIDIA Control Panel`
- Navigate and click `Manage 3D Settings`
- Scroll down the **Global Settings** tab until you see **Shader Cache Size**
- Double-click `Driver Default` to the right of **Shader Cache Size** and select `10 GB`
- Click `Apply` in the bottom right hand corner
- Exit out of the application
![](https://raw.githubusercontent.com/iAmMe27/Tahrovin/main/img/ShaderCache.png)

### Changing the Game Language

>[!WARNING]
>**Only the English Steam version of Fallout 76 is supported.**

I understand that this may be frustrating for non-English speaking users, but due to the file differences between the different translation, and lingual skill issues on my part, I am only able to support the English game version.

To change your Fallout 76's language:

 1. Right click on **Fallout 76** in **Steam**.
 2. Click `Properties`.
 3. Click `Language`.
 4. Set the Language to `English`.

## Wabbajack Installation

### Installing Wabbajack

Once you have completed the pre-installation section, follow these steps to install Wabbajack:

1. Create an empty folder named `Wabbajack` on the root of your drive, such as `C:\Wabbajack` for example.
    > - **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, OneDrive, etc.), in your Skyrim's Steam folder, or in any folders related to the modlist itself (the downloads or install folder).**
    > - The `Wabbajack` folder does not need to be on an SSD, but it makes installing faster. You can set this location to be on an HDD for the sake of saving space.

2. Download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe) and place the `Wabbajack.exe` file inside the Wabbajack folder you created in Step 1.

3. Double-click the `Wabbajack.exe` file that is now inside your Wabbajack folder to set up the program.

>[!IMPORTANT]
>The list requires Wabbajack version **4.0.2.0 or later**. Installing the modlist on older versions of Wabbajack will result in issues.

### Downloading and Installing Radiant Appalachia

Downloading and installing Radiant Appalachia should be relatively quick as it is a lightweight modlist, depending on your internet connection, PC specs, and wether or not you have NexusMods Premium.
Without Nexusmods Premium, you will need to manually click the **Slow Download** button for each mod.

To install Radiant Appalachia, complete the following steps.

 1. Download the latest `RadiantAppalachia.wabbajack` from https://github.com/TDarkShadow/Radiant-Appalachia/releases/latest.
 2. Open Wabbajack and on the left side, click **Browse Modlists**.
 3. In the top right, click **Install from Disk**.
 4. Select the downloaded `RadiantAppalachia.wabbajack` file.
 5. Set the `Modlist Installation Location` to a folder such as `C:\RadiantAppalachia`.

> [!CAUTION]
> **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, OneDrive, etc.), or in your Fallout 76 folder**

> [!TIP]
> The `Resource Download Location` does not need to be on an SSD, but it makes installing faster. You can set this location to an HDD, and delete the files after installation, for the sake of saving space.

 6. Press the play arrow to begin.
 7. Turn on your favorite show or a nice video essay as Wabbajack does its thing. Alternatively read through this readme again.
 8. If the installation is successful, then rejoice and move onto [post installation](#post-installation-and-optional-setup). If the installation is unsuccessful, follow the tips below.

## Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

<Details>
<summary>I'm having trouble downloading Non-Nexus files or specific files!</summary>

Big files can fail to download due to connection issues or website issues. You can either run Wabbajack again or download the missing file manually. If you decide to manually download the file, make sure to place the file(s) inside the folder you set as the `Resource Download Location`.

This issue can also occur with files sources from Google Drive, MEGA, Patreon, and other sites.

</Details>

<Details>
<summary>Unable to download Fallout76.ini or Fallout76Prefs.ini:</summary>

This error means you failed to follow this Readme. Go back and follow the steps outlines in the [Changing the Game Language](#changing-the-game-language) section

</Details>  

<Details>
<summary>Could not find part of the path "TEMP_BSA_FILES"</summary>

This is typically caused by a problem extracting zip files.  

The quickest solution is as follows:  
 1. Close Wabbajack.
 2. Go to your install folder and locate the `TEMP_BSA_FILES` folder (if it exists).
 3. Delete that folder (if it exists).
 4. Restart Wabbajack.
 5. Restart the modlist installation.  

If the `TEMP_BSA_FILES` folder does not exist, then delete the download file for the mod being referenced before restarting Wabbajack.  

**Note**: Using the retry button will not work as Wabbajack does not understand that there was an issue with extraction and will not retry extraction steps.

</Details>  

<Details>
<summary>My antivirus reports a virus with the program or modlist!</summary>

Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](#antivirus-exceptions).  

</Details>

<Details>
<summary>Sanity check error extracting file:</summary>

Wabbajack will sometimes have issues extracting files if they use special characters. If you encounter this issue in a Wabbajack log, please try the steps down below:

 1. Press `Win Key + R`.
 2. Type `intl.cpl` and hit `ENTER`.
 3. Navigate to *Administrative* and click `Change system locale...`.
 4. Change the *Current system locale:* to `English (United Kingdom)`.
 5. **Uncheck** `Beta: Use Unicode UTF-8 for worldwide language support`
 6. Click `OK`
 7. **Restart your PC** and rerun the Wabbajack installer.

</Details>  

<Details>
<summary>Wabbajack is crashing during the installation!</summary>

If you find yourself struggling to run Wabbajack without it crashing, freezing up, or blue-screening your PC, please try lowering Wabbajack's resource usage with these steps:

 1. Open Wabbajack.
 2. Click the **Settings** button in the bottom left corner of the Wabbajack window.
 3. Under the **Performance** box, lower each number for each category to half of what it is currently set.
 4. Continue Installation.

>[!TIP]
> It is suggested to have a program installed on your PC that can open `.json` files, like [Notepad++](https://notepad-plus-plus.org/) or [Visual Studio Code](https://code.visualstudio.com/)

</Details>

## Post-Installation and Optional Setup

### Antivirus Exceptions

>[!WARNING]
>Antivirus programs are notorious for false flagging [MO2's Virtual File System](https://stepmodifications.org/wiki/Guide:Mod_Organizer/Advanced), which can and will cause crashes and other problems.  
> Antivirus programs like BitDefender, Norton, and Webroot are especially aggressive, and you will need to fully remove them from your PC in order to be able to use Mod Organizer 2.  

If you use Windows Defender, it is advised that you set up an exception for the modlist.

<Details>
<summary>Setting up Windows Defender Exceptions:</summary>

 1. Press the Windows Key.
 2. Type "Windows Defender" in the search bar and select "Windows Security".
 3. Click on "Virus & threat protection" in the left pane.
 4. Click the "Manage settings" option under "Virus & threat protection settings".
 5. Scroll down to "Exclusions" and click "Add or remove exclusions".
 6. Windows Defender will prompt you with a run as administrator screen, just hit yes.
 7. Click the "Add an exclusion" button at the top and choose "Folder".
 8. Navigate to the Modlist installation folder and click "Select Folder".
 9. **(OPTIONAL)** You can repeat these steps for the executables:
    - ModOrganizer.exe (`[Path to Modlist]\ModOrganizer.exe`)

</Details>  

## Launching the modlist

 1. Launch the "Play" Executable in MO2. The game may take a minute to load on your first launch. Please be patient and **DO NOT** click the `Unlock` button on the MO2 prompt.
   >[!CAUTION]
   >**FOR THE LOVE OF TODD, DO NOT CLICK THE UNLOCK BUTTON!**
 2. Start to play :)

## Uninstalling the Modlist

1. Delete the Radiant Appalachia folder.  

Congratulations, you have uninstalled Apostasy.

# Credits and Thanks

- ***YOU*** for reading this.
- [ylikollikas](https://github.com/ylikollikas) for the very detailed but comprehensive Readme of [Apostasy](https://github.com/Oghma-Infinium/Apostasy).
- Bethesda Game Studios for Skyrim and the Creation Kit.
- [Halgari](https://www.nexusmods.com/skyrimspecialedition/users/17252164) and the Wabbajack Team for the amazing platform that is Wabbajack.
- [LivelyDismay](https://github.com/LivelyDismay) and [The Animonculory](https://github.com/The-Animonculory) for their modding guides.
- All mod authors whose work is included, this list would not be possible without the greater modding community.
