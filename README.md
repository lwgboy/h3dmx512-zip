U-Boot images for Allwinner H2+/H3

*First time setup*: Select the uboot-*.img.zip for your board. Unzip the file and use an img writer; for example [Etcher](https://etcher.io).

U-Boot Orange Pi Zero: [uboot-orangpi_zero.img.zip](https://github.com/vanvught/h3dmx512-zip/blob/master/uboot-orangpi_zero.img.zip?raw=true)

U-Boot Orange Pi One: [uboot-orangpi_one.img.zip](https://github.com/vanvught/h3dmx512-zip/blob/master/uboot-orangpi_one.img.zip?raw=true) 

U-Boot NanoPi NEO: [uboot-nanopi_neo.img.zip](https://github.com/vanvught/h3dmx512-zip/blob/master/uboot-nanopi_neo.img.zip?raw=true) 

uImage's:

- RDM Controller with USB [Compatible with **Enttec USB Pro protocol**] {[zip](https://github.com/vanvught/h3dmx512-zip/blob/master/h3_dmx_usb_pro.zip?raw=true)}  {*Orange Pi Zero only*}
- **Art-Net 3 Ethernet** DMX Node / **RDM** Controller / **Pixel (WS28xx/SK6812) controller** {[zip](https://github.com/vanvught/h3dmx512-zip/blob/master/h3_emac_artnet_dmx.zip?raw=true)}
- **Art-Net 3 Ethernet** DMX Node / RDM Controller **4 Ports** {[zip](https://github.com/vanvught/h3dmx512-zip/blob/master/h3_emac_artnet_dmx_multi.zip?raw=true)}
- **Art-Net 3 Wifi** DMX Node / RDM Controller / Pixel (WS28xx/SK6812) controller {[zip](https://github.com/vanvught/h3dmx512-zip/blob/master/h3_wifi_artnet_dmx.zip?raw=true)}
- sACN **E1.31 Ethernet** DMX Node / Pixel (WS28xx/SK6812) controller {[zip](https://github.com/vanvught/h3dmx512-zip/blob/master/h3_emac_e131_dmx.zip?raw=true)}
- sACN **E1.31 Wifi** DMX Bridge  / Pixel (WS28xx / SK6812) controller {[zip](https://github.com/vanvught/h3dmx512-zip/blob/master/h3_wifi_e131_dmx.zip?raw=true)}
- RDM Responder / **DMX Pixel (WS28xx) controller** {[zip](https://github.com/vanvught/h3dmx512-zip/blob/master/h3_rdm_responder.zip?raw=true)}


Current limitation Ethernet versions:

1. All nodes must be in the same network 


Orange Pi Zero: From the zip file, copy file `orangepi_zero.uImage` to SDCard as `uImage`

Orange Pi One: From the zip file, copy file `orangepi_one.uImage` to SDCard as `uImage` {*Art-Net 3 Ethernet DMX/RDM only*}

NanoPi NEO: From the zip file, copy file `nanopi_neo.uImage` to SDCard as `uImage`

All implementations are fully according to the standards.

Detailed information can be found here : [http://www.raspberrypi-dmx.org](http://www.raspberrypi-dmx.org)

> Special thanks to [@trebisky](https://github.com/trebisky/orangepi) (Thomas J. Trebisky), who helped me in understanding the H3 SoC. 