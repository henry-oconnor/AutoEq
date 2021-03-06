# Polk Audio UltraFit 3000 sample B
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -16.3; 23 -16.3; 25 -16.4; 28 -16.6; 31 -16.7; 34 -16.7; 37 -16.7; 41 -16.7; 45 -16.8; 49 -16.8; 54 -16.9; 60 -16.9; 66 -17.0; 72 -17.0; 79 -17.0; 87 -17.0; 96 -16.8; 106 -16.7; 116 -16.4; 128 -16.3; 141 -16.0; 155 -15.7; 170 -15.3; 187 -14.9; 206 -14.3; 227 -13.7; 249 -13.2; 274 -12.5; 302 -11.8; 332 -11.0; 365 -10.2; 402 -9.5; 442 -8.9; 486 -8.2; 535 -7.5; 588 -6.9; 647 -6.3; 712 -5.8; 783 -5.5; 861 -4.9; 947 -5.3; 1042 -5.7; 1146 -5.9; 1261 -6.4; 1387 -7.2; 1526 -8.1; 1678 -8.8; 1846 -9.4; 2031 -9.8; 2234 -9.9; 2457 -9.3; 2703 -8.0; 2973 -6.4; 3270 -4.9; 3597 -4.3; 3957 -4.3; 4353 -2.5; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Polk Audio UltraFit 3000 sample B GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Polk Audio UltraFit 3000 sample B ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 18 Hz   | 0.4  | -7.5 dB |
| Peaking | 115 Hz  | 0.33 | -9.1 dB |
| Peaking | 776 Hz  | 0.8  | 3.1 dB  |
| Peaking | 2045 Hz | 1.69 | -4.5 dB |
| Peaking | 5221 Hz | 1.84 | 6.9 dB  |
| Peaking | 2547 Hz | 5.73 | -0.7 dB |
| Peaking | 3318 Hz | 5.27 | 1.4 dB  |
| Peaking | 6451 Hz | 4.66 | 3.6 dB  |
| Peaking | 7194 Hz | 1.65 | -2.3 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-5.1dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -10.2 dB |
| Peaking | 62 Hz    | 1.41 | -7.7 dB  |
| Peaking | 125 Hz   | 1.41 | -8.1 dB  |
| Peaking | 250 Hz   | 1.41 | -5.4 dB  |
| Peaking | 500 Hz   | 1.41 | -0.3 dB  |
| Peaking | 1000 Hz  | 1.41 | 2.7 dB   |
| Peaking | 2000 Hz  | 1.41 | -5.3 dB  |
| Peaking | 4000 Hz  | 1.41 | 5.2 dB   |
| Peaking | 8000 Hz  | 1.41 | 1.3 dB   |
| Peaking | 16000 Hz | 1.41 | -0.4 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Polk%20Audio%20UltraFit%203000%20sample%20B/Polk%20Audio%20UltraFit%203000%20sample%20B.png)