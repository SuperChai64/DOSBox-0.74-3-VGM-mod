# DOSBox 0.74-3 VGM mod

DOSBox 0.74-3, modded to log VGMs.

Based on:
- [DOSBox 0.74-3](https://www.dosbox.com/)
- [DOSBox-VGM by NewRisingSun (originally based on DOSBox SVN r4000)](https://vgmrips.net/forum/viewtopic.php?t=2585)

The emulator is currently WIP and not yet recommended for general usage.

## How to use

To log a VGM, press Ctrl + Alt + F7

To log Sound Blaster DAC, set capturepcm to "true" in dosbox-0.74-3.conf

To log PC speaker, set capturespeaker to "true" in dosbox-0.74-3.conf

## Supported chips

- YM3812
- YMF262
- Sound Blaster DAC (via YM2612)
- PC speaker (via AY-3-8910)

## TODO

- implement SAA1099 logging
- implement SN76496 logging
- implement Tandy SL/TL/RL DAC (via YM2612) logging (this will only be implemented once SN76496 logging is implemented)
- test VGM logging

## Contributing

DOSBox 0.74-3 VGM mod is currently in early stages, so contributors are strongly appreciated.

The emulator currently has no AI-generated code.

To those who fork the repository and open pull requests, it is recommended to _not_ submit AI-generated code. However, if any AI-generated code is submitted:
- Please disclose your AI usage if you used AI in your commit(s) at all.
- Do not submit code that is mostly or entirely AI-generated. It will be rejected.
