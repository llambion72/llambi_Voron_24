# Voron 2.7018
This repo contains data on V2.7018. 

## Config
Klipper configs for V2.7018 (V2.4 300) printer running fluidd.
Macros and config files are separeted in folders.

## Main Components
#  Syboor Voron 2.4 300 Kit Jun'23

### Electronics
- A/B Motors: Stepperonline
- Z Motors: Stepperonline
- MCU: Spider 2.3 w/ TMC2209
- PSU 24v: Mean Well RSP-200-24
- PSU 5v: Mean Well LRS-50-5
- Host: Raspberry Pi 3 Model B+ 
- Display: BTT HDMI 5'
- Camera: Raspi Camera 
- Relay: Shelly 1PM+

### CAN BUS toolhead
- Board: BTT EBB2209
- Control board: BTT U2C


### Toolhead
- Toolhead: Stealthburner
- Hotend: Phaetus Dragon HF Blue
- Hotend fan: 40x40x10 Axial Fan (24V)
- Partcooling fan: 50×50×15 Centrifugal Fan (24V)
- Extruder: BMG extruder
- Probe: Cartographer

### Enclosure
- Coroplast Sheet - 420x420x4 mm	x2
- Coroplast Sheet - 420x420x4 mm	1
- Coroplast Sheet - 434x454x4 mm	1
- Acrylic Sheet Clear - 217x454x2.5 mm	2
- Acrylic Sheet Clear - 434x454x2.5 mm	2
- Acrylic Sheet Clear - 434x434x2.5 mm	1
- 3mm Foam

### Mechanics & Frame
- Frame: 
		Misumi NFSB5-2020-290mm	
		Misumi NFSB5-2020-380mm	
		Misumi NFSB5-2020-400mm	
		Misumi NFSB5-2020-420-TPW
		Misumi NFSB5-2020-480-LCP-RCP
- X linear rail: HIWIN MGN12H linear guide
- Y linear rail: Siboor MGN9H linear guide
- Z linear rail: Siboor MGN9H 400mm linear guide
- Foamtape: [XFasten Black Foam Seal Tape](https://www.amazon.com/dp/B07QYGN3C1)

### Bed
- SSR: Delixi SSR CDG1-1DA/10A DC control AC
- Heater pad: Silicone AC Heater w/ thermistor - 250x250mm (450W)
- Buildplate: Universal, 300x300x8mm
- PEI: Double-sided PEI platform 300×300mm

## Modifications
- [Nevermore v5 duo](https://github.com/nevermore3d/Nevermore_Micro/tree/master/V5_Duo/V2)
- Skirt mods
	* Move plug to left-back skirt
    * Add USB and LAN keystone inserts on left-front skirt
			LAN (https://es.aliexpress.com/item/1005005530128870.html?spm=a2g0o.order_list.order_list_main.202.3c7f194d6W0oNH&gatewayAdapt=glo2esp)
			USB (https://es.aliexpress.com/item/1005001386941952.html?spm=a2g0o.order_list.order_list_main.167.3c7f194d6W0oNH&gatewayAdapt=glo2esp)
	* In front, print 250mm front-left skirt and 350mm on front-right in order to maximize space for hotkeys
- Cartographer (https://cartographer3d.com/)
- Umbilical CanBus EBB2209 (https://biqu.equipment/collections/expansion-board/products/bigtreetech-ebb-sb2209-can-v1-0)
- 5' BTT HDMI Touch screen (https://biqu.equipment/products/bigtreetech-hdmi5-v1-0-hdmi7-v1-0)
- BTT SFS 2.0 filament detector (https://biqu.equipment/collections/expansion-board/products/btt-sfs-v2-0-smart-filament-sensor)
- 7 ports USB HUB for raspi (https://es.aliexpress.com/item/1005005777369351.html?spm=a2g0o.order_list.order_list_main.74.3c7f194d6W0oNH&gatewayAdapt=glo2esp)
- Stepdown 24/12 to 5v to power usb hub and raspberry pi (https://es.aliexpress.com/item/1005002411614827.html?spm=a2g0o.order_list.order_list_main.85.3c7f194d6W0oNH&gatewayAdapt=glo2esp)
- Front power 19mm button with voron logo (https://es.aliexpress.com/item/1005004326280128.html?spm=a2g0o.order_list.order_list_main.247.3c7f194d6W0oNH&gatewayAdapt=glo2esp)
- Front switch on/off nevermore filter 19mm button (https://es.aliexpress.com/store/910784019?spm=a2g0o.order_list.order_list_main.229.3c7f194d6W0oNH)
- Fysetc hot key buttons (https://www.fysetc.com/products/fysetc-hot-key-board-voron-skirt-button-pcb-voron-skirt-klipper-pre-installed-pcb-board-with-neopixel-led-for-voron-v2-4-trident-switchwire-3d-printers)
- Top chamber led strip lights (https://www.printables.com/es/model/84735-led-strip-holder-for-voron-24)
- Scrubber (https://www.printables.com/es/model/201999-nozzle-scrubber-with-a-little-bucket-for-voron-24)
   (https://es.aliexpress.com/item/1005005790811112.html?spm=a2g0o.order_list.order_list_main.95.3c7f194d6W0oNH&gatewayAdapt=glo2esp)
- Magnetic panels (https://mods.vorondesign.com/detail/GawFyXN2J0rlSecCAJUpZQ)
- 270° Front Panel Hinge (https://mods.vorondesign.com/detail/eeRCH8EJiLrIF5q5l3AQg)
