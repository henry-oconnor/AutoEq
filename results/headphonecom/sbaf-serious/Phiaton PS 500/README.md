# Phiaton PS 500
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -1.0; 23 -1.0; 25 -1.2; 28 -2.0; 31 -3.2; 34 -4.3; 37 -4.7; 41 -5.0; 45 -5.9; 49 -6.9; 54 -6.7; 60 -6.5; 66 -7.6; 72 -8.8; 79 -9.6; 87 -10.2; 96 -10.8; 106 -11.0; 116 -11.4; 128 -11.6; 141 -11.9; 155 -11.9; 170 -11.7; 187 -11.9; 206 -11.5; 227 -11.3; 249 -10.5; 274 -9.3; 302 -7.6; 332 -6.4; 365 -5.7; 402 -5.7; 442 -5.9; 486 -6.2; 535 -6.4; 588 -6.4; 647 -6.7; 712 -7.1; 783 -7.6; 861 -6.9; 947 -8.1; 1042 -8.8; 1146 -9.1; 1261 -9.3; 1387 -9.1; 1526 -9.0; 1678 -9.7; 1846 -10.6; 2031 -9.5; 2234 -7.2; 2457 -3.9; 2703 -1.3; 2973 -1.0; 3270 -1.0; 3597 -1.0; 3957 -1.0; 4353 -3.7; 4788 -0.5; 5267 -1.0; 5793 -3.5; 6373 -5.7; 7010 -6.3; 7711 -8.1; 8482 -9.3; 9330 -9.3; 10263 -7.0; 11289 -7.0; 12418 -7.0; 13660 -7.0; 15026 -7.0; 16529 -7.0; 18182 -7.0; 20000 -9.4
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Phiaton PS 500 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Phiaton PS 500 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.9dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 22 Hz   | 1.17 | 6.4 dB  |
| Peaking | 142 Hz  | 1    | -5.6 dB |
| Peaking | 1893 Hz | 1.51 | -5.9 dB |
| Peaking | 2963 Hz | 1.57 | 8.4 dB  |
| Peaking | 5051 Hz | 4.09 | 5.2 dB  |
| Peaking | 155 Hz  | 1.87 | 2.7 dB  |
| Peaking | 229 Hz  | 0.87 | -4.4 dB |
| Peaking | 355 Hz  | 1.18 | 4.7 dB  |
| Peaking | 1111 Hz | 4.54 | -1.4 dB |
| Peaking | 8688 Hz | 3.96 | -3.3 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.3dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 5.1 dB  |
| Peaking | 62 Hz    | 1.41 | -0.8 dB |
| Peaking | 125 Hz   | 1.41 | -5.1 dB |
| Peaking | 250 Hz   | 1.41 | -2.7 dB |
| Peaking | 500 Hz   | 1.41 | 2.7 dB  |
| Peaking | 1000 Hz  | 1.41 | -2.0 dB |
| Peaking | 2000 Hz  | 1.41 | -2.6 dB |
| Peaking | 4000 Hz  | 1.41 | 8.6 dB  |
| Peaking | 8000 Hz  | 1.41 | -2.4 dB |
| Peaking | 16000 Hz | 1.41 | 0.1 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Phiaton%20PS%20500/Phiaton%20PS%20500.png)