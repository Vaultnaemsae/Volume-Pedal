<img width="810" height="613" alt="Volume Pedal GUI" src="https://github.com/user-attachments/assets/4148936b-82db-49db-a067-9089c905bdf8" />

# Volume Pedal

**Volume Pedal** is a simple, musical volume pedal plug-in for macOS, designed for guitarists, keyboard players, and anyone who wants smooth expression-style volume control inside a DAW.

It provides a clean virtual pedal control with adjustable heel/toe levels, response curves, MIDI assignment, DAW automation, presets, and license activation.

## Features

- AUv2 and VST3 plug-in formats for macOS
- Simple volume pedal style control
- Adjustable **Heel Level** and **Toe Level**
- Multiple response curves
- Curve shape control
- Invert mode for reverse pedal behaviour
- MIDI Assign for expression pedal control
- DAW parameter automation support
- Factory presets
- User preset save/load
- 14-day trial
- Lemon Squeezy license activation

## Supported Formats

Initial release:

- macOS AUv2
- macOS VST3

Not currently included:

- AUv3
- VST2
- CLAP
- Windows VST3

Additional formats may be considered later.

## Installation

Install the plug-in files to the standard macOS audio plug-in folders:

```text
/Library/Audio/Plug-Ins/Components/Volume Pedal.component
/Library/Audio/Plug-Ins/VST3/Volume Pedal.vst3
```

After installation, rescan plug-ins in your DAW if required.

## Activation and Trial

Volume Pedal includes a 14-day trial.

During the trial, the plug-in is fully usable. To activate:

1. Open Volume Pedal in your DAW.
2. Click **Activate**.
3. Enter your license key.
4. Click **Activate** again.

Once activated, Volume Pedal will show the registered license status.

The same activation is shared between AUv2 and VST3 on the same Mac.

## MIDI Assign

Volume Pedal includes a MIDI Assign function for controlling the Position parameter with an expression pedal or MIDI CC.

Important: MIDI Assign requires the plug-in to receive MIDI directly from the host.

DAW behaviour varies:

- In Logic Pro, MIDI input to audio effects is limited. Use the appropriate MIDI-controlled plug-in configuration if available.
- In Ableton Live, MIDI may need to be routed from a MIDI track to the audio track hosting Volume Pedal.
- If direct MIDI routing is inconvenient, use normal DAW parameter automation for the **Position** parameter instead.

## Parameter Automation

The following parameters can be automated in your DAW:

- Position
- Heel Level
- Toe Level
- Response Curve
- Curve Shape
- MIDI CC
- MIDI Channel
- Invert

The **Invert** parameter affects manual control, MIDI-assigned control, and DAW automation consistently.

## Presets

Volume Pedal includes a small set of factory presets intended as pedal setup starting points:

- Clean Sweep
- Guitar Pot
- Keyboard Swell
- Rhythm Trim
- Reverse Swell

User presets can also be saved and loaded from within the plug-in.

Presets should be thought of as pedal behaviour/setup presets rather than sound presets.

## Support

For support, contact:

```text
vaultnaemsae@icloud.com
```

Please include:

- Your DAW and version
- macOS version
- Plug-in format used, AUv2 or VST3
- A short description of the issue
- Any relevant MIDI routing details, if the issue involves MIDI Assign

## Known Notes

- MIDI routing into audio effects differs between DAWs.
- MIDI Assign only works when the host successfully sends MIDI to the plug-in.
- DAW parameter automation is often the simplest and most reliable way to control Position.
- AUv3 is not included in the initial release.

## License

Volume Pedal is commercial software.

A valid license is required after the trial period.
