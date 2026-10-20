# Project Q

Free tools and research for the Alesis QS series and QuadraSynth keyboards and racks.

Project Q is a set of apps in the making:

- **QEngine** plays the sounds of a QS keyboard on a Mac or iPad: the panel, the programs and mixes, the PCMCIA sound cards, and the
  effects, from the owner's own sample ROM and firmware. It is also a patch library and editor for a real keyboard over MIDI.
- **QForge** builds new sound cards from your own recordings: sample editing and looping, key maps, programs, and burning a real card.

The apps are not released yet. This repository will collect the research and documentation behind them as it is written up, and the apps
themselves when they are ready.

## Help now: the MIDI test

If you own a QS or QuadraSynth, keyboard or rack, a short test in your browser shows what your unit can tell a computer over MIDI, and
helps Project Q work with more models. It only reads: nothing on your unit is changed or stored.

**[Open the QS MIDI Test](https://brianpeat.github.io/project-q/midi-test/)** (Chrome or Edge, with your MIDI interface connected both ways).

## Coming here

- How a QS sound card is laid out, and how cards are burned over MIDI
- The keyboard's sysex: reading and writing programs, mixes, effects and global settings
- How the voice engine behaves, measured from the firmware: envelopes, detune, pitch, filters, levels
- How the effects chip works
- Loop finding for sampled instruments

## Not affiliated

Project Q is an independent project. Alesis, QS and QuadraSynth are trademarks of their owners, used here only to say what the tools work
with. Project Q does not include or distribute Alesis's sample ROMs, firmware or factory sounds.

Project Q is also not connected in any way to [ProjectQ](https://github.com/ProjectQ-Framework/ProjectQ), the open-source quantum
computing framework; the names are only similar.
