# SteelSeries Arctis Pro Wireless
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -5.3; 23 -5.4; 25 -5.5; 28 -5.7; 31 -5.5; 34 -5.0; 37 -4.4; 41 -3.7; 45 -3.6; 49 -3.9; 54 -4.3; 60 -4.8; 66 -5.1; 72 -5.3; 79 -5.4; 87 -5.6; 96 -5.8; 106 -5.9; 116 -5.9; 128 -6.0; 141 -5.9; 155 -5.9; 170 -5.7; 187 -5.4; 206 -5.2; 227 -4.9; 249 -4.7; 274 -4.6; 302 -4.5; 332 -4.3; 365 -3.9; 402 -4.0; 442 -4.6; 486 -4.8; 535 -4.9; 588 -5.0; 647 -5.0; 712 -5.1; 783 -5.1; 861 -4.9; 947 -4.4; 1042 -3.7; 1146 -3.4; 1261 -3.7; 1387 -3.9; 1526 -3.8; 1678 -5.9; 1846 -7.7; 2031 -7.9; 2234 -7.8; 2457 -7.4; 2703 -7.3; 2973 -7.2; 3270 -5.1; 3597 -0.5; 3957 -1.2; 4353 -4.3; 4788 -4.5; 5267 -5.6; 5793 -8.1; 6373 -8.7; 7010 -8.3; 7711 -6.2; 8482 -5.1; 9330 -5.1; 10263 -5.1; 11289 -5.2; 12418 -9.5; 13660 -11.6; 15026 -10.8; 16529 -8.0; 18182 -5.1; 20000 -5.1
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`SteelSeries Arctis Pro Wireless GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `SteelSeries Arctis Pro Wireless ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.9dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 1417 Hz  | 1.35 | 4.2 dB  |
| Peaking | 2034 Hz  | 1.18 | -5.1 dB |
| Peaking | 3768 Hz  | 5.53 | 7.1 dB  |
| Peaking | 6385 Hz  | 4.53 | -3.8 dB |
| Peaking | 14285 Hz | 2.07 | -7.2 dB |
| Peaking | 45 Hz    | 3.12 | 1.7 dB  |
| Peaking | 123 Hz   | 1.37 | -1.0 dB |
| Peaking | 352 Hz   | 2.34 | 1.2 dB  |
| Peaking | 11233 Hz | 2.17 | 2.1 dB  |
| Peaking | 12647 Hz | 5.04 | -3.0 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-2.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 0.2 dB  |
| Peaking | 62 Hz    | 1.41 | 0.7 dB  |
| Peaking | 125 Hz   | 1.41 | -1.4 dB |
| Peaking | 250 Hz   | 1.41 | 0.8 dB  |
| Peaking | 500 Hz   | 1.41 | -0.1 dB |
| Peaking | 1000 Hz  | 1.41 | 2.0 dB  |
| Peaking | 2000 Hz  | 1.41 | -3.1 dB |
| Peaking | 4000 Hz  | 1.41 | 2.4 dB  |
| Peaking | 8000 Hz  | 1.41 | -2.0 dB |
| Peaking | 16000 Hz | 1.41 | -5.5 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/SteelSeries%20Arctis%20Pro%20Wireless/SteelSeries%20Arctis%20Pro%20Wireless.png)