# Lightsaber (hardware)

Circuit schematic and PCB files for the Lightsaber model controller

## Hardware parts

### High-level hardware architecture
![alt text](https://github.com/coreofbear/circuit_of_lightsaber/blob/master/hlha.png?raw=true)

### Core and BLE
- Microcontroller with BLE [nRF52840](https://lcsc.com/product-detail/RF-Transceiver-ICs_Nordic-Semicon-NRF52840-QIAA-R_C190794.html) and his [datasheet](https://datasheet.lcsc.com/lcsc/2009271002_Nordic-Semicon-NRF52840-QIAA-R_C190794.pdf)
- Chip antenna for BLE frequency [2450AT42A100E / JOHANSON](https://www.electronshik.ru/item/JOHANSON/2450AT42A100E) and her [datasheet](https://www.johansontechnology.com/datasheets/2450AT42A100/2450AT42A100.pdf)

### Sensors 
- Accelerometer and gyroscope [LSM6DSOXTR](https://www.electronshik.ru/item/ST/LSM6DSOXTR) and his [datasheet](https://www.electronshik.ru/pdf/l/lsm6dsox.pdf)

### LEDs and LED driver 
- LEDs CREE XP-E2 [XPEBRD-L1-0000-00501](https://www.digikey.com/en/products/detail/cree-inc/XPEBRD-L1-0000-00501/4177320), [XPEBBL-L1-0000-00Y02](https://www.digikey.com/en/products/detail/cree-inc/XPEBBL-L1-0000-00Y02/4177269), []() and they [datasheet (for XPEBRD-L1-0000-00501)](https://cree-led.com/media/documents/XLampXPE2.pdf)
- LED current driver [PAM2804AAB010](https://lcsc.com/product-detail/LED-Drivers_Diodes-Incorporated-PAM2804AAB010_C71463.html) and his [datasheet](https://datasheet.lcsc.com/lcsc/1809302114_Diodes-Incorporated-PAM2804AAB010_C71463.pdf)

### UX/UI
- Small SMD LEDs [APT1608CGCK](https://www.digikey.com/en/products/detail/kingbright/APT1608CGCK/1747514) and his [datasheet](https://www.kingbrightusa.com/images/catalog/SPEC/APT1608CGCK.pdf)
- Tactile buttons [PTS636 SM25J SMTR LFS](https://www.digikey.com/en/products/detail/c-k/PTS636-SM25J-SMTR-LFS/10071738) and his [datasheet](https://www.ckswitches.com/media/2779/pts636.pdf)

### Audio and amplifier 
- I2S amplifier [MAX98357](https://www.digikey.com/en/products/detail/maxim-integrated/MAX98357AEWL-T/4271383) and his [datasheet](https://datasheets.maximintegrated.com/en/ds/MAX98357A-MAX98357B.pdf)
- Speaker 4(Ohm) up to 3W [don't defined for now]() and his [datasheet]()

### SD card
- SD card slot [TF-002T-15](https://lcsc.com/product-detail/Card-Sockets-Connectors_SOFNG-TF-002T-15_C125616.html) and his [datasheet](https://datasheet.lcsc.com/lcsc/1810121710_SOFNG-TF-002T-15_C125616.pdf)

### Power management 
- DC/DC 3v buck-converter [ST1S03](https://www.digikey.com/en/products/detail/stmicroelectronics/ST1S03PUR/1642179) and his[datasheet](https://www.st.com/content/ccc/resource/technical/document/datasheet/57/3f/b9/13/fb/3b/46/4a/CD00046583.pdf/files/CD00046583.pdf/jcr:content/translations/en.CD00046583.pdf)
- Battery charger [MAX1551EZK+T](https://www.digikey.com/en/products/detail/maxim-integrated/MAX1551EZK-T/1475701) and his [datasheet](https://datasheets.maximintegrated.com/en/ds/MAX1551-MAX1555.pdf)
- Accumulator 3v7 with high discharge current [18650](https://www.chipdip.ru/product/robiton-li18650-3000) and his[datasheet](https://static.chipdip.ru/lib/333/DOC005333345.pdf)

### USB connect
- USB type-C port [don't defined for now]() and his[datasheet]()

### Discrette components
- Some resistors [don't defined for now]() and his [datasheet]()
- Some capacitors [don't defined for now]() and his [datasheet]()
- Some inductors [don't defined for now]() and his [datasheet]()
