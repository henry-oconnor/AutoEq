# Sennheiser HD 700
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.9; 23 -1.5; 25 -2.0; 28 -2.7; 31 -3.3; 34 -3.7; 37 -4.1; 41 -4.6; 45 -5.0; 49 -5.4; 54 -5.8; 60 -6.2; 66 -6.6; 72 -6.9; 79 -7.2; 87 -7.6; 96 -7.8; 106 -8.0; 116 -8.3; 128 -8.7; 141 -8.8; 155 -9.1; 170 -9.0; 187 -9.2; 206 -9.1; 227 -9.1; 249 -9.0; 274 -9.0; 302 -8.7; 332 -8.4; 365 -8.0; 402 -7.7; 442 -7.6; 486 -7.3; 535 -7.1; 588 -6.8; 647 -6.4; 712 -6.2; 783 -6.0; 861 -6.1; 947 -5.5; 1042 -5.5; 1146 -4.8; 1261 -4.7; 1387 -4.2; 1526 -4.0; 1678 -3.2; 1846 -2.5; 2031 -1.8; 2234 -2.4; 2457 -0.9; 2703 -0.5; 2973 -1.9; 3270 -1.2; 3597 -1.1; 3957 -2.6; 4353 -7.5; 4788 -8.3; 5267 -7.4; 5793 -5.3; 6373 -11.0; 7010 -8.8; 7711 -6.2; 8482 -6.1; 9330 -6.1; 10263 -6.1; 11289 -6.1; 12418 -6.1; 13660 -6.1; 15026 -6.1; 16529 -9.4; 18182 -12.6; 20000 -12.6
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser HD 700 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 700 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.7dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 15 Hz    | 0.59 | 6.5 dB   |
| Peaking | 194 Hz   | 0.47 | -3.2 dB  |
| Peaking | 3634 Hz  | 0.77 | 12.7 dB  |
| Peaking | 4731 Hz  | 1.02 | -11.7 dB |
| Peaking | 19050 Hz | 1.04 | -7.9 dB  |
| Peaking | 3043 Hz  | 7.54 | -2.3 dB  |
| Peaking | 4577 Hz  | 5.03 | -3.5 dB  |
| Peaking | 5287 Hz  | 0.89 | 2.2 dB   |
| Peaking | 5932 Hz  | 6.9  | 3.4 dB   |
| Peaking | 6554 Hz  | 6.27 | -7.5 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-5.5dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 3.9 dB  |
| Peaking | 62 Hz    | 1.41 | -0.6 dB |
| Peaking | 125 Hz   | 1.41 | -2.2 dB |
| Peaking | 250 Hz   | 1.41 | -2.8 dB |
| Peaking | 500 Hz   | 1.41 | -0.7 dB |
| Peaking | 1000 Hz  | 1.41 | -0.2 dB |
| Peaking | 2000 Hz  | 1.41 | 4.8 dB  |
| Peaking | 4000 Hz  | 1.41 | 1.5 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.8 dB |
| Peaking | 16000 Hz | 1.41 | -2.6 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sennheiser%20HD%20700/Sennheiser%20HD%20700.png)