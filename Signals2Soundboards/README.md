# Introduction

This patch is mainly intended to generate different test signals that can be useful when performing vibroacoustic tests on soundboards (e.g. Chladni patterns \cite{chladni2015treatise}). Nevertheless, its application could be extended to other measurements scenarios if needed (e.g. room acoustics purposes). This patch was built starting from previous work conducted within the [NEMUS ERC project](https://site.unibo.it/nemus-numerical-sound-restoration/en) available at: https://github.com/Nemus-Project/pd-utilities.

## Patch Sections and Guidelines

The test signals implemented in the patch include:
1. Frequency oscillator
2. Noise generator
3. Exponential sine sweep
4. External audio file

All the above mentioned sections are routed into a final output stage which allows you to monitor and control
the output gain level of your signal.

## Usage
![image](file:///c%3A/STUFF/PUREDATA/overview.png)


```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.