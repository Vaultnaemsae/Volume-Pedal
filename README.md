<img width="810" height="613" alt="Volume Pedal GUI" src="https://github.com/user-attachments/assets/4148936b-82db-49db-a067-9089c905bdf8" />
# Volume Pedal

**Volume Pedal** is a focused volume-control plug-in for macOS.

Built for guitarists, keyboard players and live performers, it turns MIDI, automation or mouse movement into smooth, musical volume control—with adjustable range, response curves and pedal behaviour.

## Features

- AUv2 and VST3 for macOS
- Smooth expression-style volume control
- Adjustable **Min** and **Max** levels
- Five response curves
- Adjustable curve **Shape**
- **Reverse** operation
- Direct MIDI Learn
- Full DAW automation
- Factory and user presets
- 14-day fully functional trial
- Lemon Squeezy licence activation

## Response Curves

Choose from:

- Linear
- Natural
- Fast Rise
- Slow Rise
- S-Curve

Use **Shape** to fine-tune the selected curve.

The graph shows how pedal position is translated into output level, while **Min** and **Max** define the available gain range.

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

Logic does not normally route MIDI directly to standard AU audio effects. In Logic, automate or MIDI-map the **Position** parameter through the host instead.

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

- Clean Sweep
- Guitar Pot
- Keyboard Swell
- Rhythm Trim
- Reverse Swell

User presets can also be saved and loaded from within the plug-in.

Presets store pedal behaviour and response settings. Direct MIDI controller assignments remain separate.

## Formats

Included:

- macOS AUv2
- macOS VST3

Not currently included:

- AUv3
- VST2
- CLAP
- Windows VST3

Additional formats may be considered later.

## Installation

Run the supplied macOS installer.

The plug-ins are installed in the standard macOS audio plug-in locations:

```text
/Library/Audio/Plug-Ins/Components/Volume Pedal.component
/Library/Audio/Plug-Ins/VST3/Volume Pedal.vst3
```

Rescan plug-ins in your DAW if Volume Pedal does not appear immediately.

## Trial and Activation

Volume Pedal includes a fully functional 14-day trial.

To activate:

1. Open Volume Pedal in your DAW.
2. Click **Activate**.
3. Enter your licence key.
4. Click **Activate** again.

A single activation covers both AUv2 and VST3 on the same Mac.

After activation, the footer displays **Licensed**. Click **Account** to view the registered email address or deactivate the licence.

## Support

Email:

```text
vaultnaemsae@icloud.com
```

Please include:

- DAW and version
- macOS version
- AUv2 or VST3
- A brief description of the issue
- Relevant MIDI-routing details

## Notes

- MIDI routing to audio effects varies between DAWs.
- Direct MIDI works only when the host sends MIDI to the plug-in.
- Host automation is often the simplest option for controlling Position.
- AUv3 is not included in the current release.

## Licence

Volume Pedal is commercial software.

A valid licence is required after the 14-day trial.
