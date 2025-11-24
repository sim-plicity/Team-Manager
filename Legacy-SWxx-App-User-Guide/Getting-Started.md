# Getting Started Guide

Welcome to the Sim-plicity Legacy SWxx Desktop Application! This guide will walk you through the complete setup process for your steering wheelbase, from software installation to first-time configuration.

## Table of Contents
- [System Requirements](#system-requirements)
- [Software Installation](#software-installation)
- [Physical Setup](#physical-setup)
- [First Power On & Initialization](#first-power-on--initialization)
- [Initial Configuration](#initial-configuration)
- [Testing Your Setup](#testing-your-setup)
- [Next Steps](#next-steps)

## System Requirements

Before you begin, ensure your system meets the following requirements:

**Operating System:**
- Windows 7 SP1 or later
- Windows 8/8.1
- Windows 10 or 11

**Software:**
- .NET Framework 4.5 or later (usually included with Windows)
- .NET 8.0 Runtime (required for Windows 11 Driver Installation Utility only)

**Hardware:**
- USB 2.0 or higher port
- Compatible Sim-plicity steering wheelbase
- Sufficient USB power (use a powered USB hub if needed)

## Software Installation

### Step 1: Install Base Driver Package (Required)

**⚠️ Important Prerequisite:** You must install the Base Driver Package before attempting to use the Configuration Tool.

1. **Download the Base Driver Package** from:
   https://github.com/sim-plicity/SW-firmware-releases/releases/download/v21.07.05/swdrvpkg_setup_signed.exe

2. **Run the installer** with your wheelbase powered OFF
3. **Follow the installation prompts** - this installs all necessary USB drivers for your wheelbase

### Step 2: Install Wheel Firmware & Configuration Tool

1. **Run the Firmware & Configuration Tool installer** (v21.07.05)
2. **Important:** During this first installation, ignore any "remove USB cable" prompts - your wheelbase is not yet connected
3. **Complete the installation**

### Step 3: Launch Configuration Tool

After installation, the Configuration Tool should launch automatically. You will see:
- **Red status icon** labeled "Not Connected" in the bottom left corner
- This is normal since the wheelbase is not yet connected

### Troubleshooting: Configuration Tool Won't Launch (Windows 11)

If the Configuration Tool does not launch on Windows 11:

1. **Download and run the Windows 11 Driver Installation Utility**
2. **Run as Administrator** (right-click → "Run as administrator")
3. **Ensure Microsoft .NET 8.0 Runtime is installed** (required by this utility)
4. **Relaunch the Configuration Tool** after the utility completes

## Physical Setup

### Step 1: Emergency Stop Connection (Critical for >15Nm Wheelbases)

**⚠️ Safety Requirement:** For any wheelbase with torque capability greater than 15Nm, the Emergency Stop (E-stop) device is mandatory.

1. **Connect the E-stop** to the designated RJ45 port on your wheelbase
2. **Twist the red button right and release** to enable game force feedback
3. **Verify the connection** is secure

### Step 2: USB Connection

1. **Connect the USB cable** from your wheelbase to a USB port on your computer
2. **Use a direct connection** if possible - avoid USB hubs for initial setup
3. **Ensure the connection is secure**

## First Power On & Initialization

### Step 1: Power On the Wheelbase

1. **Power on your wheelbase** while keeping the USB cable connected
2. **Wait for initialization** - this process takes 10-30 seconds

### Step 2: Critical: Hands-Off Initialization

**⚠️ Important Safety Note:** During initialization (10-30 seconds), the wheelbase performs automatic calibration. **DO NOT TOUCH the wheel** during this process.

- The wheelbase measures system coefficients and calibrates itself
- Touching the wheel during this time can cause incorrect calibration
- Wait until the process completes before proceeding

### Step 3: Verify Connection

Once initialization is complete:
- **Status icon changes** from "Not Connected" (red) to "Online"
- **Wheelbase is now recognized** by the Configuration Tool
- **You can proceed** to configuration

## Initial Configuration

### Step 1: Center Your Physical Steering Wheel

1. **Manually center** your physical steering wheel
2. **Ensure it's positioned** at the neutral/center position
3. **Hold it steady** for the next step

### Step 2: Set Wheelbase Center Reference

1. **In the Configuration Tool, click "Center Wheel"**
2. **The wheelbase will** establish its center reference point
3. **This reference is saved** on the wheelbase for future startups
4. **This step is essential** for proper operation after assembly/reassembly

### Step 3: Basic Settings Overview

Your wheelbase ships with safe default settings that provide usable response for any simulation. The Configuration Tool displays these settings with sliders and numerical inputs.

**Safe Default Settings (as shipped):**
- **Rotation**: Appropriate for your wheelbase model
- **Torque**: Conservative levels for comfort
- **Virtual Torque**: Disabled (1.0x)
- **End Stops**: Protective limits enabled
- **Max Speed**: Safe operational speed
- **Wheel Weight**: Minimal simulation

### Getting Information About Settings

**Hover over any slider title** to see helpful information about what that setting controls and how it affects your wheelbase performance.

## Testing Your Setup

### Basic Functionality Test

1. **Start any racing game or simulator**
2. **Enable force feedback** in the game's controller settings
3. **Turn the wheel** to feel resistance and feedback
4. **Drive slowly** to test basic force response

### Verification Checklist

- [ ] Status indicator shows "Online" (green)
- [ ] Wheel responds to input
- [ ] Force feedback is working in games
- [ ] Center position is correctly set
- [ ] Emergency Stop is connected (for >15Nm wheelbases)

## Optional Enhancements (Advanced)

For users of specific racing simulations, the **Sim Presets Installer** can configure games for native wheelbase support. This is covered in the [Advanced Configuration](Advanced-Configuration.md) section.

**Supported simulations:**
- rFactor2
- DiRT Rally 2.0
- GRID (2019)
- F1 2018-24
- RaceRoom Racing Experience
- Le Mans Ultimate
- EA SPORTS WRC

## Next Steps

Congratulations! Your wheelbase is now set up and ready for use. Here's what to explore next:

### Recommended Reading Order:
1. **[Basic Configuration](Basic-Configuration.md)** - Detailed explanation of all settings
2. **[Profiles Management](Profiles-Management.md)** - Save and manage multiple configurations
3. **[Optimization Guide](Optimization-Guide.md)** - Recommended setups for different types of racing

### Advanced Features (when ready):
- **[Advanced Configuration](Advanced-Configuration.md)** - Controller tuning and USB modes
- **[Inputs Configuration](Inputs-Configuration.md)** - Pedal and expansion device setup
- **[Telemetry Monitoring](Telemetry-Monitoring.md)** - Performance monitoring and diagnostics

## Quick Reference

### Essential Setup Sequence
1. Install Base Driver Package (wheelbase OFF)
2. Install Configuration Tool
3. Connect E-stop (if required)
4. Connect USB
5. Power ON and wait 10-30 seconds (DON'T TOUCH)
6. Verify "Online" status
7. Center physical wheel
8. Click "Center Wheel" in software

### Safety Reminders
- **Never touch wheel** during initialization
- **E-stop required** for >15Nm wheelbases
- **Start with conservative torque** settings
- **Keep hands clear** during automatic centering

### Troubleshooting Quick Tips
- **Configuration Tool won't launch?** Run Windows 11 Driver Utility as Administrator
- **Status still "Not Connected"?** Try different USB port or cable
- **No force feedback?** Check game FFB settings and verify torque > 0%

### Technical Support
- **Download drivers**: https://github.com/sim-plicity/SW-firmware-releases/releases/
- **Firmware version**: v21.07.05
- **Required**: .NET Framework 4.5+
- **Windows 11 users**: May need .NET 8.0 Runtime for driver utility

---

**Ready to fine-tune your wheelbase?** Continue to [Basic Configuration](Basic-Configuration.md) to learn about each setting in detail and optimize your force feedback experience.