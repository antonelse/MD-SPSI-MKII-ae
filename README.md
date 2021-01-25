# MD-SPSI-MKII-ae
A bunch of drum/synth kits that I made for the  [_Elektron_](https://www.elektron.se/) _MachineDrum SPSI MKII_.

## How To
For this task you have to connect your machine to your PC through a MIDI cable. 
In order to load the [sysex](http://midi.teragonaudio.com/tech/midispec/sysex.htm) file into your machine, you can use the official [C6 SysEx Manager](https://www.elektron.se/wp-content/uploads/2019/10/Elektron_C6_MAC_AND_WIN_1.51.zip). **But**, keep in mind that from _macOS 10.15 Catalina_, Apple will not support 32-bit software, so it will no longer be possible to use C6 with your Elektron devices. \
To overcome this problem, an alternative solution could be [SysEx Librarian](https://www.snoize.com/SysExLibrarian/). \ 
More info [here](https://www.elektronauts.com/news/486).


If you are not familiar with sysex transfer, please refere to the [official manual](https://www.elektron.se/wp-content/uploads/2016/05/machinedrum_manual_OS1.63.pdf), section `global settings / file / sysex receive` (page 66). \
In addition, if you want to place this kit after your personal kit, please refere to the section `./ specific place sysex receive` (page 68).

## Configuration Details

![Screenshot](machinedrum_top.jpeg)

<!---
<p align="center"><img src="machinedrum_top.jpeg"></p>
-->

## Specifics

### Audio Files
sample frequency | bit depth | bitrate | channels | coding
--- | --- | --- | --- | --- 
`44.1 kHz` | `24bit` | `1411.2 kbp/s` | 2 | PCM Little/Signed

### Sysex Files
name | global | kit | pattern | song | dsp engine | machine name | # machines | notes
--- | --- | --- | --- | --- | --- | --- | --- | ---
`distorted.syx` | 0 | 1 | 0 | 0 | EFM | XT | 16 | general fixed distortion

### Global FX Settings
name | FX | param 1 | param 2 | param 3 | param 4 | param 5 | param 6 | param 7 | param 8
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- 
`distorted.syx` | RHYTHM**ECHO** | 32 | 0 | 32 | 0 | 0 | 127 | 0 | 72
`distorted.syx` | GATE**BOX** | 0 | 0 | 63 | 0 | 0 | 127 | 127 | 96
`distorted.syx` | MASTER**EQ** | 63 | 0 | 63 | 0 | 63 | 0 | 63 | 63
`distorted.syx` | DYNAMIX™ | 127 | 127 | 127 | 127 | 127 | 127 | 0 | 0



## Other Resources
All samples are available in my [Bandcamp](https://antonelse.bandcamp.com/) page. \
More useful resources regarding this beatiful machine can be found [here](https://www.elektron.se/support/?connection=x-machinedrum#resources) (_official_) and [here](http://tarekith.com/assets/machinedrum_tipsandtricks.htm) (_unofficial_).

## Machinedrum Models
* Machinedrum SPS-1 MKI (2001)
* Machinedrum SPS-1 MKII (2007)
* Machinedrum SPS-1UW MKII (2007)
* Machinedrum SPS-1UW+ MKII (2010)

## License
This project is licensed under the GNU General Public License v3 - see ```LICENSE.txt``` for details.

___

**MD-SPSI-MKII-ae** - drum kits.\
Copyright (C) 2021  Antonio Giganti - ae
