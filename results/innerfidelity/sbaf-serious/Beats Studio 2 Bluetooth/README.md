# Beats Studio 2 Bluetooth
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -1.0; 25 -1.8; 28 -3.0; 31 -4.0; 34 -4.8; 37 -5.2; 41 -5.6; 45 -5.9; 49 -6.1; 54 -6.3; 60 -6.5; 66 -6.7; 72 -7.0; 79 -7.2; 87 -7.6; 96 -7.9; 106 -7.9; 116 -7.8; 128 -7.8; 141 -7.7; 155 -7.6; 170 -7.4; 187 -7.2; 206 -6.9; 227 -6.6; 249 -6.3; 274 -5.7; 302 -5.2; 332 -4.5; 365 -3.7; 402 -2.3; 442 -1.1; 486 -1.4; 535 -3.6; 588 -5.6; 647 -7.4; 712 -9.3; 783 -10.5; 861 -11.2; 947 -11.3; 1042 -10.0; 1146 -9.7; 1261 -10.4; 1387 -10.0; 1526 -9.2; 1678 -8.5; 1846 -7.3; 2031 -6.1; 2234 -5.4; 2457 -4.9; 2703 -5.4; 2973 -6.4; 3270 -8.9; 3597 -9.5; 3957 -8.8; 4353 -5.8; 4788 -3.3; 5267 -4.2; 5793 -3.8; 6373 -1.3; 7010 -4.0; 7711 -6.2; 8482 -6.6; 9330 -8.8; 10263 -8.7; 11289 -6.7; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Beats Studio 2 Bluetooth GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beats Studio 2 Bluetooth ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.0dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 22 Hz   | 2.18 | 5.9 dB  |
| Peaking | 457 Hz  | 2.46 | 6.6 dB  |
| Peaking | 853 Hz  | 1.88 | -5.3 dB |
| Peaking | 1359 Hz | 3.57 | -2.9 dB |
| Peaking | 6287 Hz | 4.55 | 5.3 dB  |
| Peaking | 118 Hz  | 1.34 | -1.7 dB |
| Peaking | 2581 Hz | 2.76 | 2.9 dB  |
| Peaking | 3640 Hz | 2.43 | -4.4 dB |
| Peaking | 4720 Hz | 4.81 | 4.1 dB  |
| Peaking | 9743 Hz | 4.37 | -3.0 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.5dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 3.6 dB  |
| Peaking | 62 Hz    | 1.41 | -0.8 dB |
| Peaking | 125 Hz   | 1.41 | -1.8 dB |
| Peaking | 250 Hz   | 1.41 | 0.1 dB  |
| Peaking | 500 Hz   | 1.41 | 5.2 dB  |
| Peaking | 1000 Hz  | 1.41 | -6.8 dB |
| Peaking | 2000 Hz  | 1.41 | 1.1 dB  |
| Peaking | 4000 Hz  | 1.41 | -0.1 dB |
| Peaking | 8000 Hz  | 1.41 | 1.1 dB  |
| Peaking | 16000 Hz | 1.41 | -0.4 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Beats%20Studio%202%20Bluetooth/Beats%20Studio%202%20Bluetooth.png)