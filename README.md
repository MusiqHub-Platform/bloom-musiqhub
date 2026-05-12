# Bloom - MusiqHub's Signature Sound

**Bloom** is the raw Faust version of the short signature sound used in MusiqHub outros and promotional videos.

The version heard in MusiqHub videos is processed further in FL Studio. This repository contains the raw procedural sound design source, before extra mixing, layering, cuts, and mastering.

## About

Bloom is a small generative audio patch written in Faust. It creates a rising, glowing chord sound with optional sparkle and selectable final chord colors.

The official MusiqHub outro version was made by combining and processing multiple renders from this patch. (Fmaj9 and Gsus9)

## Notes

The promotional version is not exactly this raw output.

For the current MusiqHub branding version:

- the sound was processed further in FL Studio
- the final cutoff was done in FL Studio
- Fmaj9 and Gsus9 renders were combined
- one of the renders used sparkle, but the exact one I am not sure of.

This repo is mostly here so people can study it, remix it, and make their own versions.

## Controls

| Control | Description |
|---|---|
| `Play` | Starts the sound |
| `Master` | Output volume |
| `Duration` | Length of the generated rise |
| `Sparkle` | Adds brightness/noise shimmer |
| `Final Chord` | Selects the final harmonic color |

Available final chords:

- Fmaj9
- Dm9
- Am7/add9
- Cmaj9
- Gsus/add9

## Usage

Open the `.dsp` file in the Faust IDE or compile it with Faust tools.

Example:

    faust2jack bloom.dsp

Or use the online Faust IDE:

https://faustide.grame.fr/

## License

The Faust source code is released under the BSD 3-Clause License.

You are free to use, modify, remix, and build on the code, including for commercial projects, as long as the license terms are followed.

## Brand Use

The code is open source, but the MusiqHub name, logo, and official Bloom audio identity are still part of MusiqHub’s branding.

Please do not use the unmodified official sound, MusiqHub name, or MusiqHub branding in a way that suggests your project is official, endorsed by, or partnered with MusiqHub.

Remixes, experiments, educational use, and derivative sounds are welcome.

## Credits

Written by @blvd for MusiqHub, 2026.
