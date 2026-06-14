# GPS-Synchronized Watch
A nRF52840-based smartwatch that synchronizes its time from GPS satelites, featuring a waterproof enclosure and month-long battery life.

## Why I made this
Commonly used time synchronization methods such as NTP commonly used by smartwatches only provide accuracy of around 5-50ms, which is honestly not that good. GPS time is accurate to 10-50 nanoseconds, which is very good. I also care a lot about privacy so I wanted to make an air-gapped smartwatch that still is able to get very accurate time.

## BOM
| Value | Qty | Link |
|-------|-----|------|
| DSGP.1575.18.4.A.02 | 1 | [Digikey](https://www.digikey.com/en/products/detail/taoglas-limited/DSGP-1575-18-4-A-02/8275269) |
| Adafruit Wireless Chg Module | 1 | [Digikey](https://www.adafruit.com/product/1901) |
| 100nF | 9 | [C1525](https://www.lcsc.com/product-detail/C1525.html) |
| 100pF | 1 | [C1546](https://www.lcsc.com/product-detail/C1546.html) |
| 12pF | 2 | [C1547](https://www.lcsc.com/product-detail/C1547.html) |
| 47nF | 1 | [C1622](https://www.lcsc.com/product-detail/C1622.html) |
| red | 1 | [C2286](https://www.lcsc.com/product-detail/C2286.html) |
| green | 1 | [C2297](https://www.lcsc.com/product-detail/C2297.html) |
| USBLC6-2SC6 | 1 | [C7519](https://www.lcsc.com/product-detail/C7519.html) |
| 4.7uF | 5 | [C19666](https://www.lcsc.com/product-detail/C19666.html) |
| 1.13k | 1 | [C22833](https://www.lcsc.com/product-detail/C22833.html) |
| nRF52840 | 1 | [C23186](https://www.lcsc.com/product-detail/C23186.html) |
| 100k | 1 | [C25741](https://www.lcsc.com/product-detail/C25741.html) |
| 10k | 3 | [C25744](https://www.lcsc.com/product-detail/C25744.html) |
| 1.5k | 4 | [C25867](https://www.lcsc.com/product-detail/C25867.html) |
| 22uF | 1 | [C45783](https://www.lcsc.com/product-detail/C45783.html) |
| 1uF | 5 | [C52923](https://www.lcsc.com/product-detail/C52923.html) |
| BQ24074RGT | 1 | [C54313](https://www.lcsc.com/product-detail/C54313.html) |
| RV-3028-C7 | 1 | [C3019759](https://www.lcsc.com/product-detail/C3019759.html) |
| 1A/1.8A | 1 | [C70082](https://www.lcsc.com/product-detail/C70082.html) |
| 10uH | 2 | [C88182](https://www.lcsc.com/product-detail/C88182.html) |
| 10uF | 1 | [C96446](https://www.lcsc.com/product-detail/C96446.html) |
| 15nH | 1 | [C98055](https://www.lcsc.com/product-detail/C98055.html) |
|  | 1 | [C127355](https://www.lcsc.com/product-detail/C127355.html) |
| LiPo (JST-PH Connector) | 1 | [C295747](https://www.lcsc.com/product-detail/C295747.html) |
| TPS63802DLAR | 1 | [C2845237](https://www.lcsc.com/product-detail/C2845237.html) |
| 91k | 1 | [C2906973](https://www.lcsc.com/product-detail/C2906973.html) |
| 4.12k | 2 | [C2930007](https://www.lcsc.com/product-detail/C2930007.html) |
| 511k | 1 | [C2930114](https://www.lcsc.com/product-detail/C2930114.html) |
| USB_C_Receptacle_USB2.0_14P | 1 | [C2988369](https://www.lcsc.com/product-detail/C2988369.html) |
| 1.18k | 1 | [C3016052](https://www.lcsc.com/product-detail/C3016052.html) |
| TPS2116DRL | 1 | [C3235557](https://www.lcsc.com/product-detail/C3235557.html) |
| MAX-M10S | 1 | [C4153167](https://www.lcsc.com/product-detail/C4153167.html) |
| 46.4k | 1 | [C5126026](https://www.lcsc.com/product-detail/C5126026.html) |
| 32MHz | 1 | [C5441424](https://www.lcsc.com/product-detail/C5441424.html) |
| 0.47uH | 1 | [C18221164](https://www.lcsc.com/product-detail/C18221164.html) |
| TPS7A20xxxDQN | 1 | [C46459900](https://www.lcsc.com/product-detail/C46459900.html) |
