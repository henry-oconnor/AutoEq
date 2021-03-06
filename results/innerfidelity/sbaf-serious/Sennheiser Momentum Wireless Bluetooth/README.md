# Sennheiser Momentum Wireless Bluetooth
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -6.1; 23 -7.2; 25 -7.9; 28 -8.4; 31 -8.3; 34 -8.0; 37 -7.6; 41 -7.2; 45 -6.9; 49 -6.7; 54 -6.5; 60 -6.3; 66 -6.2; 72 -6.1; 79 -6.0; 87 -6.0; 96 -6.0; 106 -5.9; 116 -5.7; 128 -5.7; 141 -5.5; 155 -5.4; 170 -5.2; 187 -4.9; 206 -4.7; 227 -4.4; 249 -4.1; 274 -3.9; 302 -3.7; 332 -3.5; 365 -3.2; 402 -3.5; 442 -3.8; 486 -4.7; 535 -5.7; 588 -6.3; 647 -7.3; 712 -8.3; 783 -8.8; 861 -9.7; 947 -10.3; 1042 -11.0; 1146 -11.5; 1261 -12.4; 1387 -13.6; 1526 -15.0; 1678 -16.2; 1846 -16.5; 2031 -16.2; 2234 -14.7; 2457 -11.9; 2703 -9.7; 2973 -7.0; 3270 -5.0; 3597 -3.0; 3957 -1.1; 4353 -0.5; 4788 -9.0; 5267 -8.2; 5793 -3.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser Momentum Wireless Bluetooth GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser Momentum Wireless Bluetooth ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.6dB**.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 31 Hz   | 2.51 | -2.1 dB  |
| Peaking | 375 Hz  | 0.76 | 4.5 dB   |
| Peaking | 2028 Hz | 0.74 | -19.6 dB |
| Peaking | 2993 Hz | 0.64 | 12.3 dB  |
| Peaking | 4064 Hz | 6.26 | 5.0 dB   |
| Peaking | 4494 Hz | 9.88 | 5.7 dB   |
| Peaking | 4926 Hz | 6.61 | -9.0 dB  |
| Peaking | 6314 Hz | 4.06 | 6.0 dB   |
| Peaking | 7758 Hz | 1.92 | -1.5 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -1.7 dB  |
| Peaking | 62 Hz    | 1.41 | 0.6 dB   |
| Peaking | 125 Hz   | 1.41 | 0.2 dB   |
| Peaking | 250 Hz   | 1.41 | 2.6 dB   |
| Peaking | 500 Hz   | 1.41 | 2.5 dB   |
| Peaking | 1000 Hz  | 1.41 | -3.5 dB  |
| Peaking | 2000 Hz  | 1.41 | -10.9 dB |
| Peaking | 4000 Hz  | 1.41 | 6.4 dB   |
| Peaking | 8000 Hz  | 1.41 | 0.3 dB   |
| Peaking | 16000 Hz | 1.41 | -0.2 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20Momentum%20Wireless%20Bluetooth/Sennheiser%20Momentum%20Wireless%20Bluetooth.png)