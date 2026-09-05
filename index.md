---
title: Home
layout: home
nav_order: 1
---

# Let's RP Technical Support

Welcome to the **Let's RP Technical Support Repository**.

This documentation site is a knowledge base used to provide technical support to the Let's RP community. This includes troubleshooting guides and user assistance procedures.

{: .highlight }
> **Disclaimer:**  This documentation is intended for use by Let's RP staff members when assisting players with troubleshooting and technical support. All instructions contained within are designed to resolve common FiveM and system-related issues. However, some steps may involve changes to game files, settings, or system configurations. Staff should ensure players are informed before proceeding with any troubleshooting steps that could affect their system or game installation. Players follow all guidance at their own discretion. Let's RP is not responsible for any unintended changes, data loss, or system issues that may occur while applying these instructions. If a player is unsure or uncomfortable with any step, they should be advised to stop and seek further assistance. This repository is not affiliated with Rockstar Games or FiveM and does not replace official support channels. While we aim to keep all information accurate and up to date, fixes and steps may vary depending on individual systems and game updates.

---

## PC Requirements & Troubleshooting Guide

This guide provides the recommended PC specifications, network requirements, and common troubleshooting steps for playing **Lets RP on FiveM**.

If you are experiencing crashes, connection problems, voice issues, stuttering, or general performance problems, please work through the checks below before contacting support.

---

## Recommended PC Specifications

For the best experience on Lets RP, we recommend the following hardware or better:

| Component | Recommended |
|---|---|
| **CPU** | Intel Core i5-9600K / AMD Ryzen 5 3600 or better |
| **RAM** | 16 GB or more |
| **GPU** | NVIDIA GeForce RTX 3060 / AMD Radeon RX 6600 or better |
| **Storage** | 130 GB SSD or more |
| **Operating System** | Windows 10 or Windows 11 |
| **Preferred OS** | Windows 11 |
| **Download Speed** | 40 Mbps or better |
| **Upload Speed** | 10 Mbps or better |
| **Network Connection** | Wired Ethernet recommended |

> [!IMPORTANT]
> We recommend having at least **20 GB of additional free space** available while playing.

Low available storage can cause installation, update, caching, and general FiveM issues.

---

## Network Requirements

A stable network connection is particularly important for FiveM.

Connection quality can affect:

- Server connectivity
- Voice chat
- Player synchronization
- Loading times
- Server assets
- Random disconnects
- Lag and packet loss

### Wired Ethernet

A **wired Ethernet connection is strongly recommended**.

Wi-Fi can work, but wireless interference can cause instability, particularly in:

- Apartments
- Student accommodation
- Large residential buildings
- Areas with many nearby Wi-Fi networks
- Homes with multiple connected devices

If you are experiencing connection or voice issues while using Wi-Fi, your local wireless network should be investigated before assuming the FiveM server is responsible.

### If You Must Use Wi-Fi

If Ethernet is not possible:

1. Stay as close to your Wi-Fi router as reasonably possible.
2. Use a prioritisation/QoS feature on your router if available.
3. Avoid Wi-Fi extenders where possible.
4. Pause intensive downloads and uploads while playing.
5. Close or pause applications such as OneDrive that may be synchronising files.
6. Avoid other devices heavily using the network while playing.

> [!TIP]
> If possible, consider purchasing a sufficiently long Ethernet cable. A wired connection is often the simplest way to eliminate local Wi-Fi interference as a potential cause of FiveM issues.

### Test Your Connection

You can test your connection using the [Waveform Bufferbloat Test](https://www.waveform.com/tools/bufferbloat).

Bufferbloat can cause increased latency when your connection is being heavily used, which can result in noticeable lag and voice-chat problems.

---

## Internet Speed Requirements

We recommend a minimum internet connection of approximately:

- **40 Mbps download**
- **10 Mbps upload**

Higher speeds are beneficial, particularly when multiple devices are using the connection simultaneously.

> [!NOTE]
> Internet speed alone does not determine connection quality. Latency, packet loss, Wi-Fi interference, routing, and bufferbloat can all contribute to FiveM connectivity issues.

### Pause Intensive Network Activity

Before playing, pause or close applications that may be using significant bandwidth.

Examples include:

- OneDrive
- Google Drive
- Dropbox
- Steam downloads
- Windows Update downloads
- Game updates
- Large file uploads/downloads
- Video streaming on multiple devices

---

## Windows Updates

Keeping Windows fully updated can resolve compatibility, stability, and security issues.

### Check for Updates

1. Open the **Start Menu**.
2. Search for **Check for updates**.
3. Open **Windows Update**.
4. Select **Check for updates**.
5. Install all available updates.
6. Restart your PC.

### Microsoft Product Updates

In Windows Update settings, ensure the following option is enabled:

> **Receive updates for other Microsoft products**

### Optional Updates

Also check for optional hardware and driver updates:

1. Open **Windows Update**.
2. Select **Advanced options**.
3. Select **Optional updates**.
4. Install any relevant available updates.
5. Restart your PC.

> [!IMPORTANT]
> Always restart your PC after completing Windows updates before testing FiveM again.

---

## Graphics Driver Updates

Outdated or corrupted graphics drivers can cause:

- Game crashes
- Graphical glitches
- Poor performance
- Freezing
- Driver timeouts
- FiveM instability

Update your graphics drivers using the software provided by your GPU manufacturer.

### NVIDIA

If you have an NVIDIA graphics card, use the **NVIDIA App** to check for and install the latest driver.

### AMD

For AMD graphics cards, use the appropriate AMD graphics software to check for driver updates.

### Intel

For supported Intel graphics hardware, use Intel's official driver update tools.

> [!IMPORTANT]
> After installing a graphics driver update, **restart your PC** before testing FiveM.

---

## BIOS & Firmware Updates

Your motherboard manufacturer may release BIOS and firmware updates that improve:

- Hardware compatibility
- System stability
- CPU compatibility
- Memory compatibility
- Security
- PCIe/GPU compatibility

### Before Updating

Identify your exact motherboard model.

You can usually find this by:

- Checking your motherboard documentation
- Checking the manufacturer's software
- Looking at your motherboard directly
- Using Windows System Information

Once you know the model, visit the **official motherboard manufacturer's website** and check for available BIOS/firmware updates.

> [!WARNING]
> BIOS updates are hardware-specific. Follow the manufacturer's instructions exactly. Do not interrupt the PC during a BIOS update.

If you are unsure how to update your BIOS, contact your motherboard manufacturer's support team or consult their official documentation.

## Clear FiveM Cache

Clearing the FiveM cache can resolve issues caused by corrupted or outdated cached data.

### Locate FiveM

1. Right-click your **FiveM** shortcut.
2. Select **Open file location**.

### Open the Data Folder

Navigate to: FiveM Application Data → Data
Delete the following folders:
- cache
- server-cache
- server-cache-priv

> [!WARNING]
> Do not delete other FiveM files or folders unless specifically instructed

After deleting the cache, launch FiveM again.

FiveM will recreate the required cache files automatically.

## Verify GTA V Installation

Corrupted or missing GTA V files can cause FiveM to crash or behave unexpectedly.

You should verify your GTA V installation through the launcher you purchased the game from.

### Steam

If you own GTA V through Steam:

Open Steam.
Go to your Library.
Right-click Grand Theft Auto V.
Select Properties.
Open Installed Files.
Select Verify integrity of game files.
Allow Steam to complete the process.

### Rockstar Games Launcher

If you own GTA V through Rockstar Games Launcher:

Open the Rockstar Games Launcher.
Navigate to your GTA V installation.
Open the game's settings/options.
Select the option to Verify Integrity.
Allow the launcher to complete the verification process.

Once verification has finished, restart your PC and try launching FiveM again.

--- 

## Reinstall FiveM

If clearing the FiveM cache does not resolve the issue, a complete reinstallation of FiveM may be required.

This process removes the existing FiveM installation and its associated application data before installing a fresh copy.

### Before Reinstalling

Make sure FiveM is completely closed before continuing.

Also close any related processes that may still be running.

### Remove FiveM

1. Right-click your **FiveM** shortcut.
2. Select **Open file location**.
3. Close FiveM if it is currently running.
4. Navigate back to the main FiveM installation folder.
5. Delete the **FiveM application folder**.

If FiveM was installed in a different location, remove the existing FiveM installation from that location.

### Remove FiveM Application Data

FiveM can retain application data outside of the main installation folder.

Check the following location:

**%localappdata%**

To open it:

1. Press **Windows Key + R**.
2. Enter `%localappdata%`.
3. Press **Enter**.
4. Locate the **FiveM** folder.
5. Delete the FiveM folder.

> **Important:** Only remove folders and files associated with FiveM. Do not delete your GTA V installation.

### Restart Your PC

Once the existing FiveM installation and associated application data have been removed:

1. Restart your PC.
2. Allow Windows to fully load.
3. Do not launch FiveM until the reinstallation is ready.

### Download and Reinstall FiveM

Download FiveM again from the official FiveM website.

Install FiveM using the newly downloaded installer.

Once the installation has completed:

1. Launch FiveM.
2. Allow FiveM to complete any required updates.
3. Allow FiveM to locate your GTA V installation if prompted.
4. Log in if required.
5. Connect to Lets RP and test the issue again.

### After Reinstallation

If the problem continues after a complete FiveM reinstallation, continue with the remaining troubleshooting steps or contact Lets RP Support.

When contacting support, let us know that you have completed a **full FiveM removal and reinstallation**, rather than only clearing the FiveM cache.

---

## Recommended Troubleshooting Order

If you are experiencing problems with Lets RP, we recommend completing the following checks in order.

###  Basic Checks
- Confirm your PC meets the recommended specifications.
- Ensure at least 20 GB of free storage is available on the FiveM drive.
- Install all Windows updates.
- Install relevant optional Windows updates.
- Update your graphics drivers.
- Check for BIOS/firmware updates.
- Restart your PC.

### FiveM Checks
- Clear the FiveM cache.
- Verify your GTA V installation.
- Restart FiveM.
- Restart your PC if the issue persists.

### Network Checks
- Use a wired Ethernet connection where possible.
- Pause OneDrive and other synchronisation software.
- Pause downloads/uploads.
- Check for other devices heavily using the network.
- Test for bufferbloat.
- Check for packet loss or unstable Wi-Fi.


---
## Contacting Lets RP Support

If the above steps do not resolve your issue, contact Lets RP Support with as much information as possible.

Please include:

- A description of the issue
- What you were doing when the issue occurred
- Any error messages
- Screenshots or videos of the issue
- Whether the issue happens every time or intermittently
- Whether you are using Ethernet or Wi-Fi
- Your PC specifications
- Any troubleshooting steps you have already completed

Providing this information helps the support team identify the cause of the problem more quickly.

## Important Information

Many FiveM issues are caused by the local PC or network environment, rather than the Lets RP server itself.

In particular, the following can cause problems:

- Unstable Wi-Fi
- Packet loss
- Bufferbloat
- Background downloads/uploads
- Outdated drivers
- Insufficient free storage
- Corrupted game files
- Outdated Windows installations

Working through this guide before contacting support can significantly reduce troubleshooting time.

---

