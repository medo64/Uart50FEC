### Uart50FEC Parts

|  # | Part                                              | RefDes  | Preferred Part Number       |
|---:|---------------------------------------------------|---------|-----------------------------|
|  1 | C 10nF X7R 16V (0805)                             | C1      | 399-17617-1-ND              |
|  3 | C 100nF X7R 16V (0805)                            | C2-C4   | 478-5311-1-ND               |
|  1 | C 1uF X5R 16V (0805)                              | C5      | 1276-6470-1-ND              |
|  1 | C 4.7uF X5R 16V (0805)                            | C6      | 1276-1244-1-ND              |
|  1 | C 10uF X5R 16V (0805)                             | C7      | 490-18664-1-ND              |
|  1 | D TVS 5V SM05T1G (SOT23-3)                        | D1      | SM05T1GOSCT-ND              |
|  2 | DS LED (0805)                                     | DS1-DS2 | 475-1415-1-ND               |
|  1 | J USB C, plug, straddle 0.8mm                     | J1      | WM12855-ND                  |
|  1 | J JST XH Vertical (4w)                            | J2      | 455-B4B-XH-A-ND             |
|  1 | L Ferrite 600R@100Mhz                             | L1      | 240-2390-1-ND               |
|  1 | Q P-MOSFET DMP3099L-13 (SOT23)                    | Q1      | DMP3099L-13DICT-ND          |
|  3 | R 1K 0.125W (0805)                                | R1-R3   | RMCF0805FT1K00CT-ND         |
|  1 | R 5.1K 0.125W (0805)                              | R4      | RMCF0805FT5K10CT-ND         |
|  1 | R 10K 0.125W (0805)                               | R5      | RMCF0805FT10K0CT-ND         |
|  1 | U Transciever Uart [FT232R] (SSOP-28)             | U1      | 768-FT232RNL-TUBE-ND        |
|  1 | U LoadSwitch 500mA [MIC2005A-1] (SOT23-5)         | U2      | 576-3462-1-ND               |
|  2 | H Screw M2x3mm                                    | -       | -                           |


#### Board Size

|       |      Dimensions | Area    | Thickness |
|-------|-----------------|---------|-----------|
| PCB   |  24.0 x 27.9 mm | 1.1 in² |    0.8 mm |


#### FTDI Configuration

| Setting | Value  |
|---------|--------|
| CBUS0   | TXLED# |
| CBUS1   | RXLED# |
| CBUS2   | TXDEN  |
| CBUS3   | PWREN# |
| CBUS4   | SLEEP# |


#### Power

|          | Voltage | Current |
|----------|--------:|--------:|
| Total    |     5 V |  550 mA |
| Output   |     5 V |  500 mA |