# Power-Consumption-Model-Unstandardized
## Coefficient Values with RB<sub>DL</sub> as input
| Technology   |   RB<sub>DL</sub> |   Intercept |
|:-------------|------------------:|------------:|
| LTE800       |        0.00117947 |   0.118751  |
| LTE1800      |        0.00139003 |   0.070084  |
| LTE2100      |        0.00141801 |   0.0427121 |
| LTE700       |        0.00172415 |   0.0869485 |
| LTE2600      |        0.00128475 |   0.0512108 |
| NR3700       |        0.0121161  |   0.147418  |


## Coefficient Values with RB<sub>UL</sub> as input
| Technology   |   RB<sub>UL</sub> |   Intercept |
|:-------------|------------------:|------------:|
| LTE800       |        0.0019032  |   0.112044  |
| LTE1800      |        0.00323397 |   0.0577311 |
| LTE2100      |        0.0030269  |   0.0307328 |
| LTE700       |        0.00400507 |   0.0477366 |
| LTE2600      |        0.00355902 |   0.0314413 |
| NR3700       |        0.00850539 |   0.135734  |


## Coefficient Values with V<sub>DL</sub> as input
| Technology   |   V<sub>DL</sub> |   Intercept |
|:-------------|-----------------:|------------:|
| LTE800       |      1.934e-08   |   0.123347  |
| LTE1800      |      7.39765e-09 |   0.0792292 |
| LTE2100      |      9.02079e-09 |   0.0486984 |
| LTE700       |      3.13804e-08 |   0.0869999 |
| LTE2600      |      5.49077e-09 |   0.0597127 |
| NR3700       |      1.02173e-08 |   0.163233  |


## Coefficient Values with V<sub>UL</sub> as input
| Technology   |   V<sub>UL</sub> |   Intercept |
|:-------------|-----------------:|------------:|
| LTE800       |      7.41163e-08 |   0.122385  |
| LTE1800      |      3.84679e-08 |   0.0801344 |
| LTE2100      |      4.69804e-08 |   0.0517213 |
| LTE700       |      7.02632e-08 |   0.106027  |
| LTE2600      |      3.83975e-08 |   0.0624466 |
| NR3700       |      5.69984e-08 |   0.160808  |


## Coefficient Values with RB<sub>DL</sub>, RB<sub>UL</sub>, V<sub>DL</sub>, V<sub>UL</sub> as input
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|------------:|
| LTE800       |       0.000253093 |       0           |      8.20982e-09 |      3.81714e-08 |   0.115552  |
| LTE1800      |       0.000931939 |       0.00132163  |      0           |      0           |   0.0616055 |
| LTE2100      |       0.00110348  |       0           |      6.74894e-10 |      1.07786e-08 |   0.0421162 |
| LTE700       |       0           |       0.00281633  |      1.49164e-08 |      0           |   0.0506151 |
| LTE2600      |       0.00101853  |       0.000868693 |      0           |      0           |   0.0451512 |
| NR3700       |       0.0045106   |       0.00616799  |      0           |      0           |   0.136548  |


## Coefficient Values with RB<sub>DL</sub>, RB<sub>UL</sub>, V<sub>DL</sub>, V<sub>UL</sub>, A, P<sub>Max</sub> as input
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |         A |   P<sub>Max</sub> |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|----------:|------------------:|------------:|
| LTE800       |       0.000574234 |       0.00171824  |      7.64898e-09 |      0           | 0.612048  |        0.00155765 |  -0.688611  |
| LTE1800      |       0.000946454 |       0.000870192 |      6.21697e-10 |      0           | 0.0565801 |        0.00165207 |  -0.0454267 |
| LTE2100      |       0.00104296  |       0           |      1.22758e-09 |      9.07664e-09 | 0.0211215 |        0.00181031 |  -0.026072  |
| LTE700       |       0.000204687 |       0.000289284 |      2.24048e-08 |      0           | 0         |        0.0109408  |  -0.173376  |
| LTE2600      |       0.00101461  |       0.000906289 |      0           |      0           | 0         |        0.00139793 |   0.0158078 |
| NR3700       |       0.0045106   |       0.00616799  |      0           |      0           | 0         |        0          |   0.136548  |


## Unit of measurement of the different features
RB<sub>DL</sub>: % <br>
RB<sub>UL</sub>: % <br>
V<sub>DL</sub> : kbyte <br>
V<sub>UL</sub> : kbyte <br>
A: linear power ratio $10^{\frac{dB}{10}}$ <br>
P<sub>Max</sub>: dBm <br>
Power Demand: kW
