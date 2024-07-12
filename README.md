# Adafruit Music Maker MP3 Shields PCB

<a href="http://www.adafruit.com/products/1788"><img src="assets/1788.jpg?raw=true" width="400px"></a>&nbsp; <a href="http://www.adafruit.com/products/1790"><img src="assets/1790.jpg?raw=true" width="400px"></a><br />
Click to purchase from the Adafruit Shop:
- [With 3W Amp](https://www.adafruit.com/product/1788)
- [Without 3W Amp](https://www.adafruit.com/product/1790)

These powerful shields feature the VS1053, an encoding/decoding (codec) chip that can decode a wide variety of audio formats such as MP3, AAC, Ogg Vorbis, WMA, MIDI, FLAC, WAV (PCM and ADPCM). They can also be used to record audio in both PCM (WAV) and compressed Ogg Vorbis. You can do all sorts of stuff with the audio as well such as adjusting bass, treble, and volume digitally.

All this functionality is implemented in a light-weight SPI interface so that any Arduino can play audio from an SD card. There's also a special MIDI mode that you can boot the chip into that will read 'classic' 31250Kbaud MIDI data from an Arduino pin and act like a synth/drum machine - there are dozens of built-in drum and sample effects! But the chip is a pain to solder, and needs a lot of extras. That's why we spun up the best shields, perfect for use with any Adafruit Metro or Arduino Uno, Leonardo or Mega.

There are two versions of the shield: the first has stereo line/headphone output. There is also a version with a 3W/channel class-D stereo speaker amplifier for easy use in projects that need to be loud.

Yjis repo contains PCB files for the Adafruit Music Maker VS1053 (MP3/MIDI/WAV/Ogg...) Shields for Arduino

Format is EagleCAD schematic and board layout

For more details, check out the product pages at

-----> https://www.adafruit.com/product/1788

-----> https://www.adafruit.com/product/1790

Revision history:

* As of Aug 23, 2023 - we've updated this PCB with Adafruit Pinguin to make a lovely and legible silkscreen. We've also updated the music maker to use the 2x3 SPI header instead of pins 11/12/13  and the terminal blocks now come pre-soldered on.
* Aug 20, 2014: We updated the analog section to have more filtering, which should improve audio output quality (even more!) There are no wiring or code changes.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

All text above must be included in any redistribution

Designed by Limor Fried/Ladyada for Adafruit Industries.
Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional information.
