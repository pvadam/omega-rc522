# Python RC522 library for Onion Omega 2+
Port of [MFRC522-python](https://github.com/mxgxw/MFRC522-python/blob/master/README.md) and [pi-rc522](https://github.com/ondryaso/pi-rc522/blob/master/README.md) to Onion Omega 2+.

__Note:__ The library currently is in progress and not yet working.

## Prerequisites

```sh
opkg update
opkg install python-light pyOnionSpi pyOnionGpio
```

## Connecting
Connecting RC522 module to SPI is pretty easy. You can use [this neat website](http://pi.gadgetoid.com/pinout) for reference.

| Board pin name | Omega GPIO |
|----------------|------------|
| SDA            | 6          |
| SCK            | 7          |
| MOSI           | 8          |
| MISO           | 9          |
| IRQ            | -          |
| GND            | GND        |
| RST            | RST        |
| 3.3V           | 3.3V       |


## Usage
```sh
ptyhon read.py
```