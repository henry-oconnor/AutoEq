# Beyerdynamic DT 1770 (Leatherette Earpads)
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -10.9; 23 -11.1; 25 -11.2; 28 -11.2; 31 -11.0; 34 -10.7; 37 -10.4; 41 -10.2; 45 -9.9; 49 -9.6; 54 -9.8; 60 -10.6; 66 -11.5; 72 -12.7; 79 -13.3; 87 -13.8; 96 -14.4; 106 -14.9; 116 -15.5; 128 -15.7; 141 -15.0; 155 -14.6; 170 -13.9; 187 -11.8; 206 -9.4; 227 -7.4; 249 -6.2; 274 -6.3; 302 -6.9; 332 -7.3; 365 -7.5; 402 -7.7; 442 -7.8; 486 -7.8; 535 -7.6; 588 -7.4; 647 -6.9; 712 -6.8; 783 -6.9; 861 -7.0; 947 -7.1; 1042 -7.0; 1146 -6.7; 1261 -6.4; 1387 -5.9; 1526 -5.1; 1678 -3.7; 1846 -2.3; 2031 -1.8; 2234 -1.2; 2457 -1.5; 2703 -1.6; 2973 -1.1; 3270 -1.3; 3597 -1.5; 3957 -0.6; 4353 -0.5; 4788 -0.6; 5267 -3.8; 5793 -6.8; 6373 -7.6; 7010 -5.2; 7711 -8.7; 8482 -10.2; 9330 -8.3; 10263 -8.3; 11289 -9.3; 12418 -8.3; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Beyerdynamic DT 1770 (Leatherette Earpads) GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beyerdynamic DT 1770 (Leatherette Earpads) ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.5dB**.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 12 Hz   |  0.17 | -4.2 dB |
| Peaking | 123 Hz  |  1.27 | -8.6 dB |
| Peaking | 2271 Hz |  1.89 | 4.7 dB  |
| Peaking | 4215 Hz |  1.66 | 6.6 dB  |
| Peaking | 8552 Hz |  0.9  | -3.3 dB |
| Peaking | 79 Hz   |  5.94 | -1.4 dB |
| Peaking | 172 Hz  |  5.06 | -2.4 dB |
| Peaking | 249 Hz  |  2.45 | 3.1 dB  |
| Peaking | 537 Hz  |  0.67 | -0.9 dB |
| Peaking | 6987 Hz | 14.54 | 2.9 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.9dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -4.0 dB  |
| Peaking | 62 Hz    | 1.41 | -2.2 dB  |
| Peaking | 125 Hz   | 1.41 | -10.2 dB |
| Peaking | 250 Hz   | 1.41 | 1.5 dB   |
| Peaking | 500 Hz   | 1.41 | -0.8 dB  |
| Peaking | 1000 Hz  | 1.41 | -1.4 dB  |
| Peaking | 2000 Hz  | 1.41 | 3.9 dB   |
| Peaking | 4000 Hz  | 1.41 | 6.3 dB   |
| Peaking | 8000 Hz  | 1.41 | -3.7 dB  |
| Peaking | 16000 Hz | 1.41 | -0.1 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/oratory1990/harman_over-ear_2018/Beyerdynamic%20DT%201770%20(Leatherette%20Earpads)/Beyerdynamic%20DT%201770%20(Leatherette%20Earpads).png)