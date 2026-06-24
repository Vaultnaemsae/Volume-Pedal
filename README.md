<img width="810" height="653" alt="Screenshot 2026-06-24 at 12 26 50 PM" src="https://github.com/user-attachments/assets/cb6ceedc-c069-4e85-8eda-81bf80a72252" />

# Volume Pedal

**Volume Pedal** is a focused volume-control plug-in for macOS, Windows and iOS/iPadOS/macOS (Universal AUv3).

Built for guitarists, keyboard players and live performers, Volume Pedal offers smooth, musical volume control—with adjustable range, response curves and pedal behaviour, via direct MIDI or DAW/host automation.

## Features

- macOS: AUv2/VST3
- Windows: x64 / x64ARM / x64ARMEC
- Smooth expression-style volume control
- Adjustable **Min** and **Max** levels
- Adjustable curve **Shape**
- **Reverse** operation
- Direct MIDI Learn
- Full DAW automation
- Factory and user presets
- 14-day fully functional trial
- Lemon Squeezy licence activation

## Response Curves and Gain Range

Drag curve handles (taper/focus parameters) for different responses, such as:
- Linear
- Natural
- Fast Rise
- Slow Rise
- S-Curve

The graph shows how pedal position maps to output level, while the **Min** and **Max** define the available gain range.

## Direct MIDI

Direct MIDI maps a learned MIDI CC directly to the **Position** parameter.

To assign a controller:

1. Enable **Direct MIDI**.
2. Click **Learn**.
3. Move your expression pedal or MIDI controller.
4. The detected CC and MIDI channel will be displayed.

Click **Clear** to remove the assignment.

> ⚠ Mapping the same CC to Position in both Direct MIDI and your host creates a second control path and may cause conflicting movement.

Direct MIDI requires the host to send MIDI to the plug-in.

### Ableton Live

Place Volume Pedal on an audio track, then route MIDI from a MIDI track to the track hosting the plug-in.

### Logic Pro

Logic does not normally route MIDI directly to standard AU audio effects. In Logic, automate or MIDI-map the **Position** parameter through the host instead. For Direct MIDI control, use a software instrument track and instantiate Volume Pedal as an AU MIDI-controlled effect. When using the plug-in in this manner, be sure to give it an audio input via the side chain selector in the Logic-generated plug-in header above the GUI.

## DAW Automation

The following parameters are available to the host:

1. Position
2. Response Curve
3. Min
4. Max
5. Shape
6. Reverse
7. Direct MIDI

The learned MIDI CC and channel remain private plug-in settings and are not exposed as automation parameters.

## Presets

Factory presets include:

- Linear
- Natural Pedal
- Audio Taper
- Fast Rise
- Slow Swell
- Holdsworth (New)
- Holdsworth (Old)
- Soft S-Curve
- Rhythm to Lead
- Reverse Swell

User presets can also be saved and loaded from within the plug-in.

User presets store pedal behaviour, response settings and Direct MIDI controller assignments.

## Formats

Included:

- macOS AUv2
- macOS VST3
- Windows VST3
- [Universal AUv3 (iOS/iPadOS/macOS) is available on the App Store](https://apps.apple.com/us/app/volume-pedal/id6780228417)

Not currently included:
- VST2
- CLAP

## Installation

## Installation

Run the supplied macOS `.pkg` or Windows `.exe` installer.

On macOS, the plug-ins are installed in the standard audio plug-in locations:

```text
/Library/Audio/Plug-Ins/Components/Volume Pedal.component
/Library/Audio/Plug-Ins/VST3/Volume Pedal.vst3
```
On Windows, the VST3 plug-in is installed in the standard VST3 location:
```text
C:\Program Files\Common Files\VST3\Volume Pedal.vst3
```
Rescan plug-ins in your DAW if Volume Pedal does not appear immediately.

## Trial and Activation (Desktop)

Volume Pedal includes a fully functional 14-day trial.

To activate:

1. Open Volume Pedal in your DAW.
2. Click **Activate**.
3. Enter your licence key.
4. Click **Activate** again.

A single activation covers every supported format on the same Mac or Windows computer.

After activation, the footer displays **Licensed**. Click **Account** to view the registered email address or deactivate the licence.

## Support

Email:

```text
vaultnaemsae@icloud.com
```

Please include:

- DAW and version
- Operating system
- Plugin type
- A brief description of the issue
- Relevant MIDI-routing details

## Notes

- MIDI routing to audio effects varies between DAWs.
- Direct MIDI works only when the host sends MIDI to the plug-in.
- Host automation is often the simplest option for controlling Position.

## Licence

Volume Pedal is commercial software.

A valid licence is required after the 14-day trial.
