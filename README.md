# `rFXGen` - Forked for custom used.

A simple and easy-to-use fx sounds generator, based on the amazing [Dr.Petter's sfxr](http://www.drpetter.se/project_sfxr.html).

- Fixed some code to use within Windows.

## Features

 - Predefined **sound presets** (Coin, Shoot, Explosion, PowerUp...)
 - Multiple wave types supported (Square, Sawtooth, Sine, Noise)
 - Up to **5 sound slots** to store generated sound (temporary save)
 - Load `.rfx` files with sound generation parameters
 - Save `.rfx` files with sound generation parameters (**104 bytes only**)
 - Export wave data as `.wav`, `.raw` data or `.h` code file (byte array)
 - Configurable sample-rate, bits-per-sample and channels on export
 - Multiple GUI styles with support for custom ones (`.rgs`)
 - Command-line support for `.rfx` to `.wav` batch conversion
 - Command-line audio player for `.wav`, `.ogg`, `.mp3` and `.flac`
 - **Completely portable (single-file, no-dependencies)**
 - **Free and open-source**

## Screenshot

![rFXGen Cyber UI style](screenshots/rfxgen_v300_cyber_shot01.png)
 
## Usage

Open the tools and use the buttons to generate random sounds. Use the sliders to customize sound parameters.
Sounds could be saved as `.rfx` (sound generation parameters) and also exported to `.wav`, `.raw` (samples data) and `.h` (byte array code file). 

`rFXGen Standalone` comes with command-line support for batch conversion and audio playing. For usage help:

 > rfxgen.exe --help
