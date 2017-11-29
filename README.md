# Limn --- John MacCallum

## Requirements
* Max/MSP >7 running on a Macintosh
* [odot](https://github.com/CNMAT/CNMAT-odot)
* [CNMAT Externals](https://github.com/CNMAT/CNMAT-Externs)
* A MIDI fader box of some sort (BCF2000, Kork Nano, etc).
* A >4 channel audio interface (2 channels for the click tracks, and 2-8 for the electronics).

## Instructions
1. Open electronics/limn.maxpat and click/limn_click.maxpat.
1. Configure the Audio Setup in Max for your sound card.
1. Configure the part of the patch connected to [ctlin] for your MIDI device. In the simplest configuration, a single fader may be used to control all 7 faders, however, they may be controlled separately and adjusted dynamically throughout the performance.
1. Load a sound file using the [open] message at the top of the patch.
1. Press the toggle marked PLAY.
