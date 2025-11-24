# Inputs Configuration Guide

The Inputs tab lets you configure pedals, shifters, and other expansion devices that connect to your wheelbase through RJ45 ports. This guide covers connecting and setting up these additional input devices.

## Table of Contents
- [Inputs Tab Overview](#inputs-tab-overview)
- [RJ45 Port Connection](#rj45-port-connection)
- [Pedal Configuration](#pedal-configuration)
- [Shifter Setup](#shifter-setup)
- [Button Box Configuration](#button-box-configuration)
- [Emergency Stop Setup](#emergency-stop-setup)
- [Device Detection and Troubleshooting](#device-detection-and-troubleshooting)

## Inputs Tab Overview

The Inputs tab provides controls for managing expansion devices:

**Main Sections:**
- **Left RJ45 Port**: 8-channel expansion port
- **Right RJ45 Port**: 6-channel expansion port
- **Input Configuration**: Pedals, shifters, and buttons setup
- **Device Status**: Shows what's currently connected

**What You Can Configure:**
- Pedal response curves and sensitivity
- Shifter button assignments
- Button box functions
- Emergency stop behavior

## RJ45 Port Connection

### Understanding the Ports

**Left RJ45 Port (Digital Expansion):**
- Supports up to 3 Sim-plicity add-on devices simultaneously
- Uses proprietary digital communication protocol
- Handles multiple devices through one connection
- Compatible with official Sim-plicity expansion devices

**Right RJ45 Port (Emergency Stop Only):**
- Reserved specifically for Emergency Stop (E-stop) connection
- Required on wheelbases with 15Nm+ torque capability
- Safety-critical connection, not for general expansion
- Used exclusively for the E-stop safety device

### Connecting Sim-plicity Add-on Devices

**Left Port Connection Process:**
1. **Power off your wheelbase** before connecting devices
2. **Connect first device** to the Left RJ45 port
3. **Power on wheelbase** and wait for device detection
4. **Configure device** using the appropriate setup button
5. **Power off and add additional devices** (up to 3 total)
6. **Verify all devices are recognized** in the Inputs tab

**Connection Tips:**
- **Use official Sim-plicity devices** - third-party devices may not work
- **Secure connections** - make sure cables are fully inserted
- **Connect one at a time** - add devices sequentially to ensure proper detection
- **Avoid hot-swapping** - connect devices when wheelbase is powered off

### Emergency Stop Setup

**E-stop Connection (Right Port):**
1. **Connect E-stop device** to the Right RJ45 port
2. **Power on wheelbase** - E-stop should be detected automatically
3. **Test E-stop** by pressing the button to verify FFB cuts out
4. **Turn right and release** to re-enable force feedback
5. **Verify E-stop indicator** shows correct status

**E-stop Safety Notes:**
- **Always connect E-stop** on wheelbases with 15Nm+ torque
- **Test regularly** to ensure it's working properly
- **Keep easily accessible** - mount within immediate reach
- **Never bypass** the E-stop safety system

## Pedal Configuration

### Accessing Pedal Setup
1. **Go to Inputs tab**
2. **Click "Configure Pedals"**
3. **Select your pedal type** from the options

### Pedal Types Supported
- **Sim-plicity Pedals**: Official pedals with auto-detection
- **Generic analog pedals**: Most standard racing pedals
- **Load cell pedals**: Advanced pressure-sensitive brakes
- **Custom pedals**: Configurable analog inputs

### Pedal Response Curves

**What are response curves?**
Response curves determine how your pedal movement translates to in-game input. A linear curve means 50% pedal movement = 50% game input. A curved response can make pedals more or less sensitive.

**Common Curve Types:**
- **Linear**: Consistent response throughout pedal travel
- **Progressive**: More sensitive at the beginning, less at the end
- **Aggressive**: Less sensitive initially, very sensitive at the end
- **Custom**: 5-point curve you can adjust manually

### Setting Up Pedal Response

**5-Point Curve Adjustment:**
1. **Select pedal** (throttle, brake, or clutch)
2. **Adjust points** at 0%, 25%, 50%, 75%, and 100%
3. **Test in real-time** using the live preview
4. **Fine-tune** based on your driving style

**Practical Examples:**

**Comfortable Brake Setup:**
- 0%: 0%
- 25%: 15% (less sensitive initially)
- 50%: 50% (linear middle)
- 75%: 85% (more sensitive for strong braking)
- 100%: 100%

**Responsive Throttle:**
- 0%: 0%
- 25%: 35% (quick initial response)
- 50%: 60% (progressive increase)
- 75%: 85% (maintaining response)
- 100%: 100%

### Pedal Calibration

**Automatic Calibration:**
1. **Click "Auto Calibrate"**
2. **Press each pedal fully** when prompted
3. **Release pedals** when instructed
4. **Confirm calibration** results

**Manual Calibration:**
1. **Set minimum values** with pedals at rest
2. **Set maximum values** with pedals fully pressed
3. **Test movement** using live preview
4. **Save calibration** when satisfied


## Sim-plicity Add-on Devices

### Supported Add-on Devices
The Left RJ45 port supports up to 3 official Sim-plicity devices simultaneously using the proprietary digital communication protocol. These can include:
- **Sim-plicity Pedals**: Official pedal sets with advanced features
- **Sim-plicity Shifters**: H-pattern and sequential shifter modules
- **Sim-plicity Button Boxes**: Professional button modules
- **Sim-plicity Handbrakes**: Progressive handbrake modules

### Setting Up Multiple Devices

**Device Limit:**
- **Maximum 3 devices** can be connected simultaneously
- **Digital protocol** ensures all devices work together without conflicts
- **Hot-swapping not supported** - power off when adding/removing devices

**Configuration Process:**
1. **Connect first device** to Left RJ45 port
2. **Power on and configure** first device completely
3. **Power off wheelbase**
4. **Add second device** (connect to daisy-chain port on first device or hub)
5. **Power on and detect** both devices
6. **Configure second device**
7. **Repeat for third device** if needed

**Device Detection:**
- **Automatic recognition** of Sim-plicity devices
- **Individual configuration** for each connected device
- **Status indicators** showing which devices are active
- **Error messages** if device limits are exceeded


## Emergency Stop Setup

### What is the Emergency Stop?
The Emergency Stop (E-stop) is a safety button that immediately cuts force feedback when pressed. It's a critical safety device, especially for high-torque wheelbases (15Nm+).

### Physical Setup

**Connection Location:**
- Usually connects to the right side RJ45 port
- Check your wheelbase manual for exact port location
- Some wheelbases have a specific E-stop port

**Physical Installation:**
1. **Mount E-stop button** within easy reach
2. **Connect RJ45 cable** to the correct port
3. **Secure cable** to prevent accidental disconnection
4. **Test connection** by pressing the button

### E-stop Operation

**How It Works:**
- **Press button**: Immediately disables force feedback
- **Turn right and release**: Re-enables force feedback
- **Status indicator**: Shows when E-stop is active
- **Permanent safety**: Always available regardless of game

**When to Use E-stop:**
- **Force feedback issues**: If FFB becomes erratic or too strong
- **Calibration problems**: When wheel behaves unexpectedly
- **Emergency situations**: Quick disable during technical issues
- **Testing**: Safely disable FFB during setup

## Device Detection and Troubleshooting

### Checking Device Status

**In the Inputs Tab:**
- **Connected devices** show as detected

### Common Detection Issues

**Device Not Detected:**
- **Check cable connections** - unplug and reconnect firmly
- **Verify port compatibility** - some devices only work in specific ports
- **Restart wheelbase** - power cycle and try again
- **Test device individually** - disconnect other devices temporarily

**Input Not Working:**
- **Check game settings** - ensure device is enabled in your game
- **Verify button assignments** - buttons may need remapping in-game
- **Test calibration** - recalibrate if response seems wrong
- **Check for conflicts** - multiple devices might interfere with each other

**Erratic Behavior:**
- **Cable issues** - replace RJ45 cables if they're old or damaged
- **Power problems** - ensure wheelbase has adequate power supply
- **Interference** - keep cables away from power cables and motors
- **Firmware updates** - check if your wheelbase needs updates

### Input Lag and Response Issues

**Minimizing Input Lag:**
- **Use direct USB connections** - avoid USB hubs when possible
- **Quality cables** - good quality RJ45 cables make a difference
- **Proper calibration** - well-calibrated devices respond faster
- **Regular testing** - check input response periodically

**Testing Input Response:**
1. **Watch input preview** in Configuration while pressing buttons
2. **Test in-game response** - verify actions happen immediately
3. **Check for delays** - any lag might indicate connection issues
4. **Compare to known good setup** - test against direct USB connections

---

**Ready to monitor your wheelbase performance?** Continue to [Telemetry Monitoring](Telemetry-Monitoring.md) to learn about real-time performance tracking and system diagnostics.