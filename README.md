# Jalmus

### What is Jalmus?
Jalmus is a free, open source music education software helping the musicians, specially pianists, to improve their sight-reading. You can train to read music with both exercises on notes or rhythms.

Jalmus is developed in Java and so available on Microsoft Windows, Linux and Mac OS. Jalmus is a multilingual software supporting - English, French, Spanish, Italian, Danish and German : help us to translate it in your language.

### Prerequisites:

A compatible MIDI controller with USB MIDI capabilities

### How do I get Jalmus working with my MIDI controller on macOS?

First download the [latest release of Core4MidiJ](https://github.com/DerekCook/CoreMidi4J/releases)

Place the downloaded Core4MidiJ extension into your Java Extensions folder: `/Library/Java/Extensions`

Next download and the [latest release of Jalmus](https://github.com/FritzX6/jalmus/releases/download/v2.3/installjalmus23.jar) and run the installer

Next open the Jalmus application by navigating to it's folder (`/Applications/Jalmus/bin/`) and double-clicking the jalmus.jar file.

With Jalmus open, Click Settings > MIDI Options

Open the Midi In drop-down and select the option: `Core4MIDIJ - USB Midi`

If this option is unavailable, check that your MIDI controller (keyboard) is plugged in correctly (some cables have midi-in/midi-out cables labeled in reverse). If you connected your MIDI device after starting Jalmus you will need to close and relaunch the application.
