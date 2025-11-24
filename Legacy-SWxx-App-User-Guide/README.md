# Sim-plicity Steering Wheelbase Configuration Guide

Welcome to the comprehensive user guide for configuring and optimizing your Sim-plicity steering wheelbase using the Legacy SWxx Desktop Application.

## Overview

This guide covers the complete configuration process for Sim-plicity steering wheelbases, supporting multiple wheelbase models including:
- SW4 Compact, SW6 Compact, SW7 Compact, SW7 Compact+
- SW8 Compact V2, SW8 Compact+, SW10 Compact, SW10 Compact+
- SW10 Esport, SW12 Compact, SW12 Compact+, SW13 Compact+
- SW15 Compact+, SW15 Esport, SW15, SW20 Series
- SW25, SW25 V2, SW30, SW30 V2
- Team Wheel Zero, One, Two, Three

## Quick Start

1. **Connect your wheelbase** to your computer via USB
2. **Launch the application** (ensure your wheelbase model version is running)
3. **Basic Setup** - Adjust rotation and torque to your preference
4. **Save a Profile** - Store your settings for future use
5. **Start Racing!**

## Guide Contents

### 🚀 Getting Started
- [Getting Started Guide](Getting-Started.md) - Installation, connection, and first-time setup

### ⚙️ Configuration
- [Configuration Guide](Configuration.md) - Complete Settings and Advanced tab reference
- Wheelbase rotation, torque settings, controller tuning, USB modes

### 📁 Profile Management
- [Profiles Management](Profiles-Management.md) - Creating, saving, and managing configurations
- Simple profile workflow for different racing scenarios

### 🎮 Input Devices
- [Inputs Configuration](Inputs-Configuration.md) - Pedals, shifters, and expansion devices
- Sim-plicity add-on devices, RJ45 port connection, E-stop setup

### 📊 Performance Monitoring
- [Telemetry Monitoring](Telemetry-Monitoring.md) - Real-time data and system health
- Force feedback monitoring, system diagnostics, performance tracking

### 🎯 Optimization Guide
- [Optimization Guide](Optimization-Guide.md) - Best practices and setup recommendations
- Wheelbase-specific tuning, racing discipline optimizations

## Features Overview

### Core Configuration
- **Wheelbase Rotation**: 180° - 2160° (consistent across all models)
- **Torque Control**: Up to 25Nm on high-end models with model-specific limits
- **Virtual Torque**: Software-based force multiplication (1.0x - 1.5x)
- **End Stops**: Software-based force feedback (no mechanical limits)
- **Weight Simulation**: Configurable inertia simulation (0% - 5%)

### Advanced Features
- **USB Modes**: Sim/Game compatibility (Console/Linux not generally available)
- **Controller Tuning**: Mode 0-9 (0 = most responsive), Bandwidth 0.10-2.00
- **Weighted Center**: Enhanced centering force (specialist feature)
- **Real-time Telemetry**: Performance monitoring and system diagnostics

### Device Management
- **Hot-plug Support**: Connect/disconnect devices safely
- **Profile System**: Save/load configurations instantly
- **RJ45 Expansion**: Left port supports up to 3 Sim-plicity devices
- **Emergency Stop**: Right port dedicated to E-stop (15Nm+ wheelbases)

## Launch Options

The application supports command-line arguments for enhanced functionality:

```bash
# Enable debug mode (Diagnostics tab)
SWxx.exe /d

# Load specific profile
SWxx.exe /p "ProfileName"
```


## System Requirements

- **OS**: Windows 7 SP1 or later
- **Framework**: .NET Framework 4.5 or later
- **USB**: USB 2.0 or higher port
- **Hardware**: Compatible Sim-plicity steering wheelbase

## Navigation Tips

### For Beginners
1. Start with [Getting Started Guide](Getting-Started.md)
2. Read [Configuration Guide](Configuration.md) for core settings
3. Use [Optimization Guide](Optimization-Guide.md) for recommended setups

### For Advanced Users
1. Review [Configuration Guide](Configuration.md) for technical tuning
2. Explore [Telemetry Monitoring](Telemetry-Monitoring.md) for performance analysis
3. Customize [Inputs Configuration](Inputs-Configuration.md) for expansion devices

## Version Information

This guide covers the Legacy SWxx Desktop Application (v21.07.05 and later). The application provides professional-grade wheelbase configuration for sim racing enthusiasts and professionals.

## Key Optimizations

### Most Important Setting: Wheel Weight
- **Start low**: Begin with 0.5-1% (not the 2.5% default)
- **High-speed test**: Find the lowest value that maintains straight-line stability
- **Motor-specific**: Larger wheelbases need less weight
- **Goal**: Maximum detail with minimum weight

### USB Port Configuration
- **Left RJ45**: Connect up to 3 Sim-plicity add-on devices simultaneously
- **Right RJ45**: Reserved for Emergency Stop on 15Nm+ wheelbases
- **Digital protocol**: Proprietary communication for reliable multi-device support

### Controller Tuning
- **Controller Mode**: Use 0 for maximum responsiveness
- **Controller Bandwidth**: Keep between 0.5-1.0 for optimal feel
- **Avoid >1.0**: Higher values may cause motor noise

## Need Help?

While this guide focuses on setup and optimization, ensure your wheelbase is properly connected via USB and that you have the correct application version for your wheelbase model.

---

**Ready to configure your wheelbase?** Start with the [Getting Started Guide](Getting-Started.md) to begin your setup journey.