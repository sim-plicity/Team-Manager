# Configuration Guide

The Configuration interface consists of two main tabs - **Settings** and **Advanced** - that work together to provide complete control over your steering wheelbase's performance characteristics. This guide explains each setting in detail, helping you understand how to optimize your wheelbase for different racing scenarios.

## Table of Contents
- [Settings Tab Overview](#settings-tab-overview)
- [Wheel Rotation](#wheel-rotation)
- [Torque Settings](#torque-settings)
- [Virtual Torque](#virtual-torque)
- [End Stops](#end-stops)
- [Maximum Speed](#maximum-speed)
- [Wheel Weight](#wheel-weight)
- [Weight & Max Speed Relationship](#weight--max-speed-relationship)
- [Details Boost](#details-boost)
- [Advanced Tab Overview](#advanced-tab-overview)
- [Controller Settings](#controller-settings)
- [Weighted Center Settings](#weighted-center-settings)
- [USB Mode](#usb-mode)
- [Action Buttons](#action-buttons)
- [Common Configuration Scenarios](#common-configuration-scenarios)
- [Configuration Optimization Workflow](#configuration-optimization-workflow)

## Settings Tab Overview

The Settings tab provides intuitive control over your wheelbase's fundamental parameters:

**Interface Layout:**
- **Left Side**: Horizontal sliders for visual, intuitive adjustments
- **Right Side**: Numerical input fields for precise value entry
- **Labels**: Each setting displays its name, current value, and unit of measurement
- **Tooltips**: Hover over any setting title to see detailed descriptions

**Getting Help:**
- **Hover over slider titles** to see helpful information about each setting
- **Use sliders** for quick, visual adjustments
- **Use number fields** for precise, exact values

## Wheel Rotation

**What it controls:** The maximum steering angle from full left lock to full right lock.

**Measurement:** Degrees of rotation (°)

**Range:** 180° - 2160° (consistent across all wheelbase models)

### Common Rotation Settings

| Use Case | Recommended Rotation | Why |
|----------|---------------------|-----|
| **General Racing** | 900° | Standard for most racing games |
| **Drifting** | 540° - 720° | Quick counter-steering capability |
| **Rally** | 720° - 900° | Balance of precision and quick response |
| **GT Racing** | 900° | Matches real GT car steering |
| **Formula Racing** | 270° - 360° | Matches F1 car steering ratios |
| **Truck Simulators** | 900° - 1080° | Realistic truck steering range |
| **Street Driving** | 900° - 1080° | Matches road car steering |

### How to Adjust
1. **Use the slider** for visual adjustment, or
2. **Enter exact value** in the number field
3. **Click "Apply"** to save changes to the wheelbase

### Pro Tips
- **Match your game settings**: Ensure your game's steering rotation matches this setting
- **Start conservative**: Begin with 900° and adjust based on your preference
- **Consider your space**: Larger rotation requires more physical movement

## Torque Settings

**What it controls:** The maximum force output of your wheelbase's motor system.

**Measurement:** Newton meters (Nm)

**Maximum by Model:**
- **SW7 Compact**: 7.2 Nm
- **SW10 Compact**: 10 Nm
- **SW15 Compact**: 15 Nm
- **SW20 Series**: 20-25 Nm
- **SW25/SW30 Series**: 25 Nm+

### Understanding Torque

**Newton meters (Nm)** measure rotational force:
- **1 Nm** = Force of 1 Newton at 1 meter distance
- **Higher Nm** = Stronger force feedback
- **Too high** = Can cause fatigue or reduce control precision

### Recommended Torque Levels

| User Level | Recommended Setting | Description |
|------------|-------------------|-------------|
| **Beginner** | 30-50% of max | Focus on control, build muscle memory |
| **Intermediate** | 50-70% of max | Good balance of feel and comfort |
| **Advanced** | 70-85% of max | Maximum detail and responsiveness |
| **Professional** | 85-95% of max | Maximum feedback for competitive racing |

### Torque Guidelines

**For Endurance Racing:**
- **Lower torque (40-60%)** reduces fatigue
- Maintains consistent feel over long sessions

**For Sprint Racing:**
- **Higher torque (60-80%)** provides maximum feedback
- Enables quick reactions and precise control

**For Drifting:**
- **Higher torque (70-85%)** for strong feedback
- Helps sense tire grip loss and recovery

### Safety Considerations
- **Start low**: Begin with conservative torque settings
- **Gradual increase**: Raise torque as you become accustomed to the wheelbase
- **Listen to your body**: Stop if you experience discomfort or fatigue

## Virtual Torque

**What it controls:** Software-based multiplication of the torque signal to provide additional force feedback.

**Measurement:** Multiplier (1.0x - 1.5x, model dependent)

**How it works:** Virtual torque analyzes the incoming force feedback signal and applies intelligent amplification to enhance detail and strength.

### When to Use Virtual Torque

**Enable Virtual Torque (1.1x - 1.2x):**
- **Additional force needed**: When you want stronger feedback than physical torque provides
- **Detail enhancement**: To emphasize subtle road surface and tire feedback
- **Games with weak FFB**: When the game's force feedback signal is weak

**Disable Virtual Torque (1.0x):**
- **Maximum accuracy**: For the most direct, unfiltered force feedback
- **Professional use**: When you want pure hardware response
- **Strong native FFB**: When the game provides excellent force feedback

### Model Limitations
- **SW7 Compact**: Limited to 1.2x for safety
- **Higher-end models**: May support up to 1.5x
- **Always follow manufacturer guidelines** for your specific model

### Recommended Settings
- **Purists**: 1.0x (disabled)
- **General use**: 1.1x
- **Maximum enhancement**: 1.2x (or model limit)

## End Stops

**What it controls:** Software-based force feedback that applies a continuous counterforce when the wheel rotates beyond the configured rotation limits.

**Measurement:** Percentage of maximum torque (%)

**How it works:**
- There are **no mechanical limits** - the motor shaft can theoretically spin forever
- When you rotate outside the configured rotation zone, the system applies continuous counterforce
- This counterforce pushes the wheel back into the valid rotation range
- The percentage determines how strong this counterforce will be

### Understanding End Stops Behavior

**When you hit the rotation limit:**
- The wheelbase doesn't physically stop
- Instead, it applies continuous force feedback pushing you back
- Higher percentages = stronger resistance to leaving the rotation zone
- Lower percentages = gentler pushback

### Recommended End Stop Settings

| Setting | Use Case | Effect |
|---------|----------|--------|
| **50-70%** | Gentle guidance | Soft reminder of rotation limits |
| **70-90%** | Balanced feel | Clear but not aggressive pushback |
| **90-100%** | Strong boundary | Firm resistance to over-rotation |

### Practical Considerations

**For Daily Use:**
- **70-90%** provides good feedback without being jarring
- Gives clear indication when approaching limits
- Maintains comfortable driving experience

**For Beginners:**
- **50-70%** offers gentler guidance
- Less jarring when accidentally hitting limits
- More forgiving learning experience

**For Competitive Use:**
- **80-100%** provides clear boundary feedback
- Helps maintain awareness of steering limits
- Prevents accidental over-rotation during intense moments

### Pro Tips
- **Start with 80%** for a good balance of feedback and comfort
- **Adjust based on your driving style**: Aggressive drivers may prefer stronger feedback
- **Consider your rotation setting**: Very high rotation may benefit from slightly lower end stops
- **Test the feel**: Different games may respond differently to end stop forces

## Maximum Speed

**What it controls:** The maximum rotational speed of your wheelbase motor and works in conjunction with Weight to prevent unrealistic or unsafe rotation speeds.

**Measurement:** Revolutions per minute (rpm)

**Range by Model:** 100 - 500 rpm (model dependent)

### Understanding Max Speed

**Primary Functions:**
- **Speed limiting**: Prevents wheel rotation faster than realistic or safe
- **Weight activation**: Governs when and how aggressively Weight is applied
- **Oscillation control**: Works with Weight to prevent overshoot and oscillation

**Higher Max Speed:**
- **Faster response** to quick steering inputs
- **Less weight intervention** at normal speeds
- **Better for counter-steering** in drift or recovery situations

**Lower Max Speed:**
- **More weight intervention** to control rotation
- **Smoother, more controlled** movements
- **Better for oscillation issues** in problematic sims/cars

### Recommended Settings by Use Case

| Use Case | Recommended Max Speed | Rationale |
|----------|---------------------|-----------|
| **Precision Racing** | 100-150 rpm | Strong weight control, smooth inputs |
| **GT Racing** | 150-200 rpm | Balance of control and response |
| **Rally** | 200-250 rpm | Quick steering with some weight control |
| **Drifting** | 250-300 rpm | Fast response with oscillation control |
| **Formula Racing** | 200-250 rpm | Quick response with stability |

## Wheel Weight

**What it controls:** Simulates the physical weight and rotational inertia of the steering wheel, accounting for both the wheel rim and the internal motor characteristics.

**Measurement:** Percentage (%)

**Range:** 0% - 5% (maximum configurable limit)
**Default:** 2.5%

**How it works:** Adds resistance to acceleration and deceleration of the wheel, simulating the feel of a heavier or lighter steering wheel. This setting is **especially important** as it provides configurable realism per car type and per wheelbase type.

### Understanding Wheel Weight Importance

**Critical for Realism:**
- **Different motors, different inertia**: Each wheelbase model uses different motors with unique internal inertia characteristics
- **No universal setting**: One value does not work for all wheelbases or car types
- **Expected values**: Much lower than the 2.5% default for most wheelbases
- **Motor size relationship**: Larger motors need less weight

**The Ideal Weight Setting:**
The goal is to find the **lowest possible value** while still being able to **keep the car traveling in a straight line at high speed with fingertip control**.

### Weight Settings by Wheelbase Type

**Understanding Motor Inertia Differences:**
- **Larger motors** = Higher internal inertia = Less needed weight
- **Smaller motors** = Lower internal inertia = More needed weight

**Expected Optimal Ranges:**
| Wheelbase Series | Expected Optimal Range |
|------------------|------------------------|
| **Compact Series** (SW7, SW10, SW15) | 1-3% |
| **Non-Compact Series** (SW20) | 0.5-1% (once comfortable) |
| **Large Series** (SW25, SW30) | Even lower than 0.5% |

**Starting Points by Model:**
| Wheelbase Series | Recommended Starting Range |
|------------------|---------------------------|
| **SW7/SW10/SW15** | 1-2% |
| **SW20 Series** | 0.5-1% |
| **SW25/SW30 Series** | 0.3-0.8% |

### Weight Settings by Car Type

| Vehicle Type | Typical Weight Range | Characteristics |
|--------------|---------------------|-----------------|
| **Formula Cars** | 0.2-0.8% | Very light, highly responsive steering |
| **GT Cars** | 0.5-2% | Moderate weight for realistic GT feel |
| **Rally Cars** | 1-3% | Some weight for stability over rough surfaces |
| **Road Cars** | 1-3% | Heavier feel matching road car steering |
| **Trucks/Heavy Vehicles** | 2-5% | Maximum weight for realistic heavy vehicle feel |

### Pro Tips for Weight Optimization

**Fine-Tuning Process:**
- **Start very low**: Begin with 0.5-1% wheel weight
- **High-speed testing** is essential for finding the right setting
- **Fingertip control test** should be done at racing speeds
- **Small adjustments** (0.1% increments) make a big difference
- **Consider your motor size**: Larger wheelbases need less weight

**Common Mistakes to Avoid:**
- **Using default 2.5%**: Usually too high for most applications
- **Too much weight**: Makes steering feel heavy and unnatural
- **Too little weight**: Car becomes unstable at high speeds
- **Same setting for all cars**: Different vehicles need different weight characteristics

## Weight & Max Speed Relationship

**Critical System Understanding:**
Weight and Max Speed work together as a coordinated system, not as independent settings.

### How They Work Together

**Max Speed Governs Weight:**
- **Max Speed determines** when and how aggressively Weight is applied
- **Lower Max Speed** = Weight activates earlier and more aggressively
- **Higher Max Speed** = Weight activates later and less aggressively

**Oscillation Control:**
If a simulation or specific car overshoots its expected position (oscillates):
- **Increase Weight** to provide more damping
- **Reduce Max Speed** to activate weight more aggressively
- **This combination** improves response characteristics and eliminates oscillation

### Practical Examples

**Problematic Car/Sim Combination:**
- **Issue**: Car oscillates or overshoots steering position
- **Solution**: Increase Weight by 0.2-0.5% AND reduce Max Speed by 25-50 rpm
- **Result**: More controlled response with eliminated oscillation

**Optimizing for Different Uses:**
- **Precision driving**: Lower Max Speed + appropriate Weight for maximum control
- **Quick response**: Higher Max Speed + minimal Weight for fast reactions
- **Problematic sims**: Moderate Max Speed + higher Weight for stability

### Tuning Process

**Step-by-Step Approach:**
1. **Set Weight first** using the fingertip stability method
2. **Set Max Speed** for your desired response characteristics
3. **Test for oscillations** in your target sims/cars
4. **If oscillation occurs**: Increase Weight AND decrease Max Speed
5. **Repeat** until stable, responsive behavior is achieved


## Advanced Tab Overview

The Advanced tab provides fine-tuning control over your wheelbase's internal controller behavior and communication protocols. These settings work together with the basic Settings tab to optimize response characteristics and system compatibility.

**Advanced Settings Groups:**
- **Controller Settings**: Internal controller mode and bandwidth tuning
- **Weighted Center**: Specialist centering force enhancement
- **USB Mode**: Communication protocol selection

## Controller Settings

### Controller Mode

**What it controls:** Sets the operational mode of the wheelbase's internal controller, affecting responsiveness and smoothness.

**Measurement:** Mode value (0-9)

**How it works:** Sets the mode in which the wheel operates with Mode 0 being most reactive and Mode 9 being the smoothest.

### Controller Bandwidth

**What it controls:** Alters the feel and response characteristics of the wheelbase.

**Measurement:** Bandwidth value (0.10 - 2.00)

**How it works:** Alters the feel of the wheel with lower values softening and higher values stiffening the response. Values above 1.0 are likely to cause audible motor noise.

### Controller Tuning Recommendations

**Ideal Settings:**
- **Controller Mode**: As close to 0 as possible for maximum responsiveness
- **Controller Bandwidth**: Between 0.5 and 1.0 for optimal feel without motor noise

**Practical Guidelines:**
- **Start with Mode 0**: Most responsive operation
- **Set Bandwidth 0.7-0.8**: Good balance of responsiveness and smoothness
- **Avoid bandwidth > 1.0**: Can cause motor noise without significant benefits
- **Fine-tune based on preference**: Small adjustments can make a noticeable difference

**When to Adjust:**
- **If wheel feels too soft**: Increase bandwidth slightly (0.8-1.0)
- **If wheel feels too harsh**: Decrease bandwidth slightly (0.4-0.7)
- **If response seems delayed**: Ensure Controller Mode is at or near 0

## Weighted Center Settings

**Note:** These are specialist features that most users will leave at default settings (disabled).

### Weighted Center Range

**What it controls:** Configures the range around center where the Weighted Center effect is active.

**Measurement:** Degrees (0-90°)

**How it works:** Configures the range (in degrees either side of center) within which the 'Weighted Center' effect is active. Set to 0° to disable the effect.

### Weighted Center Gain

**What it controls:** Configures the strength of the Weighted Center effect.

**Measurement:** Gain value (0-20)

**How it works:** Configures the strength of the 'Weighted Center' effect over its active range. Set to 0 to disable the effect.

### Weighted Center Usage

**General Recommendation:**
- **Most users**: Leave both settings at 0 (disabled)
- **Specialist use cases**: Only adjust if you specifically need enhanced centering force

**When to Consider Using:**
- **Games with weak centering**: Some sims provide poor center spring force
- **Personal preference**: If you prefer stronger centering feel
- **Specific wheel setups**: Certain wheel rims may benefit from enhanced centering

## USB Mode

**What it controls:** Selects the USB communication protocol for different platform compatibility.

**Available Options:**
- **Sim Mode**: Normal operation for most racing simulations (default)
- **Game Mode**: Alternate implementation for additional game support

**How it works:** Select what mode the USB interface will operate in. Sim is normal operation for most sims. Game is an alternate implementation for additional support.

### USB Mode Guidelines

**Default Recommendation:**
- **Use Sim Mode** for all racing simulations
- This provides the most compatible and reliable operation

**When to Use Game Mode:**
- **Compatibility issues**: If a game doesn't properly recognize the wheelbase in Sim Mode
- **Alternate implementation**: Some games may work better with Game Mode protocol
- **Troubleshooting**: Try Game Mode if you experience connection or recognition problems

**Selection Process:**
1. **Start with Sim Mode** (default)
2. **Test in your target games**
3. **Switch to Game Mode** only if you experience compatibility issues
4. **Re-test** to see if Game Mode resolves the problem

## Action Buttons

### Apply
**Purpose:** Saves all current settings from both Settings and Advanced tabs to the wheelbase hardware.
**When to use:** After making any changes to settings.
**Note:** Changes are not active until you click Apply.

### Center Wheel
**Purpose:** Returns the wheelbase to the center position and establishes the center reference.
**When to use:**
- **Initial setup**: After first connecting the wheelbase
- **After moving**: If the wheel has been physically moved
- **Calibration**: To reset center reference
**Important:** Ensure the physical wheel is centered before clicking this button.

### Close
**Purpose:** Closes the Configuration window.

## Common Configuration Scenarios

### Scenario 1: GT Racing Setup
**Settings for GT3-style racing:**

**Settings Tab:**
- **Rotation**: 900°
- **Torque**: 60-70% of maximum
- **Virtual Torque**: 1.0x (disabled)
- **End Stops**: 80%
- **Max Speed**: 150-180 rpm
- **Wheel Weight**: 0.5-2% (adjust for straight-line stability)
- **Details Boost**: 5-10%

**Advanced Tab:**
- **Controller Mode**: 0 (most responsive)
- **Controller Bandwidth**: 0.7-0.8
- **Weighted Center**: 0° range, 0 gain (disabled)
- **USB Mode**: Sim Mode

### Scenario 2: Drifting Setup
**Settings for drift cars:**

**Settings Tab:**
- **Rotation**: 540-720°
- **Torque**: 70-85% of maximum
- **Virtual Torque**: 1.1x
- **End Stops**: 90%
- **Max Speed**: 250-300 rpm
- **Wheel Weight**: 0.5-1.5% (lower for quick transitions)
- **Details Boost**: 10-15%

**Advanced Tab:**
- **Controller Mode**: 0 (most responsive)
- **Controller Bandwidth**: 0.6-0.7 (slightly softer for drifting)
- **Weighted Center**: 0° range, 0 gain (disabled)
- **USB Mode**: Sim Mode

### Scenario 3: Formula Racing Setup
**Settings for open-wheel racing:**

**Settings Tab:**
- **Rotation**: 270-360°
- **Torque**: 50-65% of maximum
- **Virtual Torque**: 1.0x (disabled)
- **End Stops**: 90%
- **Max Speed**: 200-250 rpm
- **Wheel Weight**: 0.2-0.8% (minimal for high sensitivity)
- **Details Boost**: 5-10%

**Advanced Tab:**
- **Controller Mode**: 0 (most responsive)
- **Controller Bandwidth**: 0.8-1.0 (slightly stiffer for precision)
- **Weighted Center**: 0° range, 0 gain (disabled)
- **USB Mode**: Sim Mode

### Scenario 4: Beginner Setup
**Safe settings for new users:**

**Settings Tab:**
- **Rotation**: 900°
- **Torque**: 30-40% of maximum
- **Virtual Torque**: 1.0x (disabled)
- **End Stops**: 70%
- **Max Speed**: 150 rpm
- **Wheel Weight**: 1-2% (adjust for straight-line stability)
- **Details Boost**: 0-5%

**Advanced Tab:**
- **Controller Mode**: 0 (most responsive)
- **Controller Bandwidth**: 0.8 (balanced feel)
- **Weighted Center**: 0° range, 0 gain (disabled)
- **USB Mode**: Sim Mode

### Scenario 5: Oscillation Problem Setup
**For problematic sims/cars that overshoot:**

**Settings Tab:**
- **Rotation**: (as desired)
- **Torque**: (as desired)
- **Virtual Torque**: (as desired)
- **End Stops**: (as desired)
- **Max Speed**: Reduce by 25-50 rpm from normal
- **Wheel Weight**: Increase by 0.2-0.5% from normal
- **Details Boost**: (as desired)

**Advanced Tab:**
- **Controller Mode**: 0
- **Controller Bandwidth**: 0.7-0.8
- **Weighted Center**: 0° range, 0 gain (disabled)
- **USB Mode**: Try Game Mode if Sim Mode has issues

## Configuration Optimization Workflow

### Step 1: Basic Setup (Settings Tab)
1. **Set Wheel Weight First** (most critical)
   - Start with 0.5-1% (well below 2.5% default)
   - Use the fingertip stability test at high speed
   - Find the lowest value that maintains straight-line stability

2. **Adjust Max Speed** for your driving style
   - Higher for quick response, lower for more control

3. **Set Torque** to comfortable level
   - Start low (30-50%) and increase gradually

4. **Configure Rotation** for your preference
   - Match your game's steering settings

### Step 2: Advanced Tuning (Advanced Tab)
1. **Set Controller Mode to 0** for maximum responsiveness
2. **Set Controller Bandwidth** between 0.5-1.0
   - Start with 0.7-0.8 for balanced feel
   - Adjust slightly based on preference
3. **Leave Weighted Center at 0** unless specifically needed
4. **Use Sim Mode** unless compatibility issues require Game Mode

### Step 3: Problem Solving
**If experiencing oscillation:**
- Increase Weight by 0.2-0.5%
- Decrease Max Speed by 25-50 rpm
- Test with Controller Bandwidth adjustments

**If compatibility issues:**
- Try switching USB Mode from Sim to Game
- Ensure game FFB settings are properly configured

### Step 4: Save and Organize
- **Save profiles** for different car types and racing disciplines
- **Test thoroughly** with familiar tracks and conditions
- **Fine-tune** based on real-world driving experience

## Pro Tips for Optimization

### The Weight Optimization Method (Most Important)
1. **Start very low**: Begin with 0.5% wheel weight (well below the 2.5% default)
2. **High-speed test**: Take a fast car on a long straight
3. **Fingertip challenge**: Try to maintain a straight line using only your fingertips
4. **Increase gradually**: Add 0.1% at a time until stability is achieved
5. **Record the sweet spot**: This is your optimal setting for that car/wheelbase combination

### Common Pitfalls to Avoid
- **Using default 2.5% weight**: Usually far too high for optimal performance
- **Ignoring motor size**: Larger wheelbases need much less weight
- **Treating Weight/Max Speed independently**: They work as a system
- **Too much torque**: Can cause fatigue and reduce precision
- **Ignoring rotation matching**: Game settings must match wheelbase rotation
- **Same settings for all cars**: Different vehicles require different configurations

### Best Practices
- **Save profiles** for different car types or racing disciplines
- **Test with familiar tracks** to evaluate setting changes
- **Always optimize wheel weight** for new car types (start very low!)
- **Consider your wheelbase model**: Larger motors need much less weight
- **Understand Weight/Max Speed relationship**: They work together to control oscillations
- **Use the oscillation fix**: Increase Weight + Decrease Max Speed for problematic cars
- **Start with Controller Mode 0**: Most responsive operation for all use cases

---

**Ready to save your configurations?** Continue to [Profiles Management](Profiles-Management.md) to learn how to save, organize, and manage multiple wheelbase configurations for different racing scenarios.