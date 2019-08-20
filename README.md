# Jalmus

### What is Jalmus?
Jalmus is a free, open source music education software helping the musicians, specially pianists, to improve their sight-reading. You can train to read music with both exercises on notes or rhythms.

Jalmus is developed in Java and so available on Microsoft Windows, Linux and Mac OS. Jalmus is a multilingual software supporting - English, French, Spanish, Italian, Danish and German : help us to translate it in your language.

### Prerequisites:

A compatible MIDI controller with USB MIDI capabilities

### How do I get Jalmus working with my MIDI controller on macOS 10.14 (Mojave) or later?

1. Download the [latest release of Core4MidiJ](https://github.com/DerekCook/CoreMidi4J/releases)

2. Place the downloaded Core4MidiJ extension into your Java Extensions folder: `/Library/Java/Extensions`

3. Download and the [latest release of Jalmus](https://github.com/FritzX6/jalmus/releases/download/v2.3/installjalmus23.jar) and run the installer

4. Open the Jalmus application by navigating to it's folder (`/Applications/Jalmus/bin/`) and double-clicking the jalmus.jar file.

5. With Jalmus open, Click Settings > MIDI Options

6. Open the Midi In drop-down and select the option: `Core4MIDIJ - USB Midi`
If this option is unavailable, check that your MIDI controller (keyboard) is plugged in correctly (some cables have midi-in/midi-out cables labeled in reverse). If you connected your MIDI device after starting Jalmus you will need to close and relaunch the application.
