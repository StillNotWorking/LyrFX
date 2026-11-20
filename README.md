# LyrFX

LyrFX is an server side equalizer plugin for Lyrion Music Server (LMS). More precisely, it provides a simple-to-use interface to FFmpeg’s complex filters through a transcoder wrapper linked to player-ID

## Version

0.1.0 — development release.

## Current behavior

- Registers as an LMS plugin. ✅
- Adds a plugin settings page under Settings / Advanced. ✅
- Provides ten filter slots, each supporting any of six filter types. ✅
- FIR Convolve filter with IR wav files management.
- BS2B headhone feed filter. ✅
- Player management. *- partially implemented*
- Filter preset management, load, add, remove. *- partially implemented*
- Tone Generator.
- 10 band PEQ import from REW

## Installation for development

Copy LyrFX directory to ../squeezeboxserver/Plugins/

## Development notes

Under development - Not ready for distribution

The plugin UUID in install.xml is a development identifier. Before public release,
generate and reserve a unique UUID and prepare the repository metadata and versioned
release archive required by the LMS plugin repository.

## License

GPL3
