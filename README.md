# 🛠️ Visual-Quick-Fixes / Troubleshooting Guide
Quick fixes / Troubleshooting Guide for visual (sybau miguel)

<sub> not made by me, made by [LilahCodes](https://github.com/LilahCodes) all credits go to her i just use this as a template and adjust some things, thanks tho (hope she doesn't get mad :gulp:)


> [!IMPORTANT]
> [Only official download](https://getvisual.cc/)  
> **Status:** 🟢 WORKING, Use alt (just in case)</br>
> **Last updated version:** `1.3.0` **VersionGuid:**: `version-e00a4ca39fb04359`
> **Join the best community fr:** [Visual Discord](https://discord.gg/getvisual)

> [!NOTE]
> If your issue isn't listed here or the solutions didn't help, please create a new issue.
>
> If you know how to fix it or how to reproduce the error, be sure to include that information in your report.
---

## 📋 Table of Contents

> [!NOTE]
> Some files are required for Visual to work, refer to [Dependencies](#dependencies)

Before everything please do uninstalling and installing [here](#fully-uninstall-and-install)

### Misc
- [How do I disable my antivirus?](#how-do-i-disable-my-antivirus)
- [Roblox Version Management](#roblox-version-management)
- [Using Older Roblox Versions (Downgrading)](#using-older-roblox-versions-downgrading)
- [Issues with No Fix / Planned Features](#issues-with-no-fix--planned-features)
### Website
- [Dangerous - Blocked Page](#dangerous---blocked-page)
### App
- [Crash on inject](#crash-on-inject)
- [White screen](#white-screen-or-crash)
- [Not executing](#not-executing)
- [Dependencies](#dependencies)

---

## Roblox Version Management
- It is recommended to use the official Roblox launcher to ensure you are on the correct and latest supported version.
- If you suspect Roblox is not updating correctly or is stuck on an old version, try a full reinstall as described in [Fully Uninstall and Install](#fully-uninstall-and-install) or use the [Roblox LIVE forcer tool](https://github.com/LilahCodes/swift/blob/main/support%20files/roblox%20LIVE%20forcer.bat).

---

## Issues with No Fix / Planned Features

> [!NOTE]
> These are known issues or upcoming features that are being worked on.

Planned:
- Multi-instance is not yet supported. official support is coming soon.

---

## Dangerous - Blocked Page

> [!NOTE]
> If u can't access the page, search for "Show more" and press, "Continue the page (not recommended)" or something like that
> IF STILL can't enter the page, go to support and ask for the file (we only can provide the gofile page where the last visual release is.)


---

# Fully Uninstall and Install
## Please do this first if you are having issues.

- Press "Windows + r" and type `%localappdata%` and delete the **Roblox** folder.
- Open `%localappdata%`, find the **Visual** folder and delete it. Then, go to the place where you downloaded **Visual** (the folder with the `.exe`, `autoexe`, etc.) and delete that Visual folder too.
- Type "windows + r" and type `%appdata%`, delete the **Visual** folder (If you have important scripts, backup your scripts and paste them here after you finish this).
- Make sure you are using the standard Roblox launcher.
- Make a Visual folder and set that folder to [exceptions](#how-do-i-disable-my-antivirus).
- After disabling the antivirus, head to the Visual [download page](https://getvisual.gg/) and download Visual into the folder that you added to exceptions. Don't launch it yet.
- Install the [Dependencies](#dependencies) if you don't have them.

Now it should work. If it doesn't, and you get errors before you could even finish or after finishing, head to the [App errors list](#app), select your error, and try the fix.

---

## Using Older Roblox Versions (Downgrading)

> [!CAUTION]
> **Downgrading is NOT recommended and likely DETECTED.** Roblox actively warns against and may take action on accounts using modified or outdated clients. Using an older version significantly increases your risk of detection and bans. Proceed at your own extreme risk, preferably on alternate accounts you are willing to lose.

> [!IMPORTANT]
> Often, using an older version of Roblox will cause Visual to **not execute or inject correctly**. It is best to wait for Visual to update for the latest Roblox version.

If you still choose to ignore these warnings and attempt to use an older version:
- You would need to find a source for older Roblox client files. This is not provided or endorsed here due to the risks.
- If you manage to run an older version, attempt to inject Visual as usual, but expect issues.

---

## How do I disable my antivirus?

> [!TIP]
> Visual often triggers false positives because of how it operates. Disabling antivirus or adding exceptions is necessary.

### Windows Defender (default on all Windows PCs)

- [Windows 10 Disable Guide](https://www.youtube.com/watch?v=1GgtAxWxhMQ)  
- [Windows 11 Disable Guide](https://www.youtube.com/watch?v=o0OTed9c_GQ)

### Add Exceptions Instead (Recommended)
- [Windows 10 Exceptions Guide](https://www.youtube.com/watch?v=BonLkFNnO9w)  
- [Windows 11 Exceptions Guide](https://www.youtube.com/watch?v=zGiNGnX5dYg)

Add this path:
- Your Visual folder

Using McAfee, Norton, AVG, Avast? Just search how to disable or make folder exceptions for your antivirus on YouTube.

---

## White screen or crash

- Make sure you are running Visual as admin  
- Ensure your Windows account has admin privileges
- Make sure to install [Dependencies](#dependencies)

---

## Not executing

- SPAM the execute button, wait, spam more, wait, spam more. Sometimes it just bugs out like that.
- If it's still not executing:
    - Ensure Visual injected successfully
    - Perform a full uninstall and reinstall of both Roblox and Visual as per the [Fully Uninstall and Install](#fully-uninstall-and-install) section.
    - Ensure you are on the latest official Roblox version. If you suspect Roblox is not updating, use the [Roblox LIVE forcer tool](https://github.com/LilahCodes/swift/blob/main/support%20files/roblox%20LIVE%20forcer.bat).

---

## Dependencies

> [!NOTE]
> Make sure all the following are installed and your drivers are up-to-date:

- [.NET SDK 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)  
- [VC Redist x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)  
- [VC Redist x86](https://aka.ms/vs/17/release/vc_redist.x86.exe)  
- [Microsoft Edge WebView2 Runtime](https://go.microsoft.com/fwlink/p/?LinkId=2124703)  
- [DirectX Runtime](https://www.microsoft.com/en-us/download/details.aspx?id=8109)
- [d3d](https://www.microsoft.com/en-us/download/details.aspx?id=35)

---

## Crash on inject

- Make sure to attach Visual **In-Game** not on Homepage.
- Download [roblox](https://www.roblox.com/download) again from the official website. You might be using an outdated or corrupted version.
- If Roblox keeps launching an outdated version, use [this](https://github.com/LilahCodes/swift/blob/main/support%20files/roblox%20LIVE%20forcer.bat) tool to help force an update to the LIVE channel.
