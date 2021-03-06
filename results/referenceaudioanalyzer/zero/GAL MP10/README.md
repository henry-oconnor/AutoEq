# GAL MP10
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -7.7; 23 -8.3; 25 -8.8; 28 -9.4; 31 -9.9; 34 -10.2; 37 -10.5; 41 -10.9; 45 -11.1; 49 -11.3; 54 -11.5; 60 -11.6; 66 -11.7; 72 -11.7; 79 -11.8; 87 -12.0; 96 -12.0; 106 -12.0; 116 -12.0; 128 -12.0; 141 -12.0; 155 -12.0; 170 -12.2; 187 -12.3; 206 -12.3; 227 -12.3; 249 -12.6; 274 -12.7; 302 -12.9; 332 -13.0; 365 -13.5; 402 -14.2; 442 -15.1; 486 -16.1; 535 -17.3; 588 -18.4; 647 -19.2; 712 -19.3; 783 -18.0; 861 -15.2; 947 -12.3; 1042 -10.4; 1146 -9.2; 1261 -8.0; 1387 -5.6; 1526 -3.1; 1678 -0.9; 1846 -0.5; 2031 -0.5; 2234 -0.5; 2457 -0.5; 2703 -0.5; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -0.5; 4788 -0.5; 5267 -0.5; 5793 -1.7; 6373 -6.0; 7010 -6.2; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`GAL MP10 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `GAL MP10 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.0dB**.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 47 Hz   | 0.6  | -2.7 dB  |
| Peaking | 172 Hz  | 0.32 | -4.2 dB  |
| Peaking | 699 Hz  | 1.08 | -13.6 dB |
| Peaking | 2312 Hz | 0.55 | 8.4 dB   |
| Peaking | 1276 Hz | 6.02 | -1.5 dB  |
| Peaking | 1693 Hz | 3.86 | 1.8 dB   |
| Peaking | 2554 Hz | 2.37 | -1.1 dB  |
| Peaking | 5488 Hz | 2.04 | 7.9 dB   |
| Peaking | 6233 Hz | 1.57 | -6.8 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -2.7 dB  |
| Peaking | 62 Hz    | 1.41 | -4.2 dB  |
| Peaking | 125 Hz   | 1.41 | -4.3 dB  |
| Peaking | 250 Hz   | 1.41 | -2.8 dB  |
| Peaking | 500 Hz   | 1.41 | -10.6 dB |
| Peaking | 1000 Hz  | 1.41 | -6.2 dB  |
| Peaking | 2000 Hz  | 1.41 | 7.8 dB   |
| Peaking | 4000 Hz  | 1.41 | 6.0 dB   |
| Peaking | 8000 Hz  | 1.41 | -0.8 dB  |
| Peaking | 16000 Hz | 1.41 | -0.1 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/GAL%20MP10/GAL%20MP10.png)