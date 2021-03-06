# Klipsch X11i
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -14.1; 23 -14.1; 25 -14.1; 28 -14.1; 31 -14.1; 34 -14.1; 37 -14.1; 41 -14.1; 45 -14.1; 49 -14.1; 54 -14.1; 60 -14.1; 66 -14.1; 72 -13.9; 79 -13.8; 87 -13.8; 96 -13.7; 106 -13.5; 116 -13.4; 128 -13.2; 141 -13.0; 155 -12.8; 170 -12.5; 187 -12.3; 206 -12.0; 227 -11.7; 249 -11.3; 274 -11.0; 302 -10.5; 332 -10.2; 365 -10.2; 402 -9.9; 442 -9.4; 486 -8.8; 535 -8.3; 588 -7.8; 647 -7.4; 712 -6.9; 783 -6.3; 861 -5.8; 947 -5.3; 1042 -4.8; 1146 -4.4; 1261 -4.0; 1387 -3.6; 1526 -3.3; 1678 -3.1; 1846 -3.1; 2031 -3.4; 2234 -3.9; 2457 -5.0; 2703 -7.0; 2973 -8.9; 3270 -8.9; 3597 -6.7; 3957 -3.7; 4353 -2.5; 4788 -1.6; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Klipsch X11i GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Klipsch X11i ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.7dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 33 Hz   | 0.09 | -7.6 dB |
| Peaking | 1702 Hz | 0.75 | 4.0 dB  |
| Peaking | 3080 Hz | 3.34 | -5.8 dB |
| Peaking | 5381 Hz | 2.11 | 6.3 dB  |
| Peaking | 4137 Hz | 7.25 | 1.5 dB  |
| Peaking | 6489 Hz | 4.51 | 3.8 dB  |
| Peaking | 6990 Hz | 1.56 | -2.5 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-3.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -7.8 dB |
| Peaking | 62 Hz    | 1.41 | -5.6 dB |
| Peaking | 125 Hz   | 1.41 | -5.4 dB |
| Peaking | 250 Hz   | 1.41 | -3.8 dB |
| Peaking | 500 Hz   | 1.41 | -2.1 dB |
| Peaking | 1000 Hz  | 1.41 | 2.2 dB  |
| Peaking | 2000 Hz  | 1.41 | 1.7 dB  |
| Peaking | 4000 Hz  | 1.41 | 1.9 dB  |
| Peaking | 8000 Hz  | 1.41 | 1.9 dB  |
| Peaking | 16000 Hz | 1.41 | -0.4 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/Klipsch%20X11i/Klipsch%20X11i.png)