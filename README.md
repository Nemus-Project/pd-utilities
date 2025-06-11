# NEMUS PureData Utilities
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15641239.svg)](https://doi.org/10.5281/zenodo.15641239)

A suite of PureData utility patches for experiments and measurements carried out at the NEMUS project.

## Tools

### Signals to Soundboards

Signal generator for performaing vibroacoustic tests on soundboards. See patch [README](./signals_2_soundboards/README.md).

### Utilities

General utility patches are contained in the `utils/` directory,

- `osc_choice`: Waveform selection using the `else` library
- `osc_controller`: Frequency of an oscillator using two MIDI controller values. One for 'broad' and a second for 'fine' frequency control
- `play_wav`: Simple audio file playback using the `else` library
- `sweep`: Exponential sine sweep

## Dependencies

- [`else` library](https://github.com/porres/pd-else)