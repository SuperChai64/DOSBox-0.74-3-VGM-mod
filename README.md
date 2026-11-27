# DOSBox 0.74-3 VGM mod

DOSBox 0.74-3, modded to log VGMs.

Based on:
- DOSBox 0.74-3
- [DOSBox-VGM by NewRisingSun (originally based on DOSBox SVN r4000)](https://vgmrips.net/forum/viewtopic.php?t=2585)

The emulator is currently a work in progress.

## How to use

To log a VGM, press Ctrl + Alt + F7

To log Sound Blaster DAC, set capturepcm to "true" in dosbox-0.74-3.conf

To log PC speaker, set capturespeaker to "true" in dosbox-0.74-3.conf

## Supported Chips

- YM3812
- YMF262
- Sound Blaster DAC (via YM2612)
- PC speaker (via AY-3-8910)

## TODO

- implement SAA1099 logging
- implement SN76496 + Tandy SL/TL/RL DAC (via YM2612) logging
- test VGM logging

## Contributing

DOSBox 0.74-3 VGM mod is currently in early stages, so contributors are strongly appreciated.

The emulator currently has no AI-generated code. Non-AI contributions are strongly preferred. Do not generate a large amount of code via AI alone; it will not be accepted. If AI is used in your commit(s), please disclose it.
