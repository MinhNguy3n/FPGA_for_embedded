# FPGA evaluation kit and development boards

## Summary table (grouped by Vendor, sorted by increasing price within each vendor)

### Table of contents (grouped by vendor)

#### 1bitsquared
- [1bitsquared iCEBreaker](#1bitsquared-icebreaker) — €79.95

#### Aloriumtech
- [Aloriumtech SNO ARDUINO](#aloriumtech-sno-arduino) — €42  
- [Aloriumtech SNOMAKRR10](#aloriumtech-snomakrr10) — €26.59

#### Altera
- [Altera EK-10M08E144](#altera-ek-10m08e144) — €54.04

#### Crowdsupply
- [Crowdsupply TinyFPGA](#crowdsupply-tinyfpga) — €12.90  
- [Crowdsupply FireAnt](#crowdsupply-fireant) — €32.68

#### Digilent
- [Digilent Cmod A7 35T](#digilent-cmod-a7-35t) — $99  
- [Digilent Basys 3](#digilent-basys-3) — $165

#### Lattice-Semi
- [Lattice-Semi iCEstick Evaluation Kit](#lattice-semi-icestick-evaluation-kit) — €130.73

#### Olimex
- [Olimex iCE40HX1K-EVB](#olimex-ice40hx1k-evb) — €15  
- [Olimex GateMateA1-EVB](#olimex-gatematea1-evb) — €53

#### RealDigital
- [RealDigital Boolean (no BLE)](#realdigital-boolean) — $84

#### Renesas
- [Renesas SLG7EVBFORGE](#renesas-slg7evbforge) — €81

#### Seeed-Studio
- [Seeed-Studio RUNBER FPGA](#seeed-studio-runber-fpga) — €25  
- [Seeed-Studio Spartan Edge Accelerator (SEA) Board](#seeed-studio-spartan-edge-accelerator-sea-board) — $39.50

#### SIPEEED
- [SIPEEED TANG PRIMER 25K](#sipeeed-tang-primer-25k) — €37

#### TUL
- [TUL PYNQ-Z2](#tul-pynq-z2) — €156.76

#### Trenz-electronic
- [Trenz-electronic S7 Mini](#trenz-electronic-s7-mini) — €36.41
- [Trenz-electronic MAX1000](#trenz-electronic-max1000) — €40.46  
- [GOWIN LittleBee](#gowin-littlebee) — €41.77  
- [Trenz-electronic TE0722](#trenz-electronic-te0722) — €70.21

#### VHDPlus
- [VHDPlus MAX1000](#vhdplus-max1000) — €39.98  
- [VHDPlus CYC1000](#vhdplus-cyc1000) — €41.82  
- [VHDPlus CORE_MAX10](#vhdplus-core_max10) — €49.98

> Note: Prices are taken verbatim from the document. Sorting within each vendor was done by numeric price value in increasing order but I did not convert between currencies (€, $, US$). For vendors with mixed currencies the ordering is by the numeric amount only; tell me if you'd like a single-currency conversion and resorting.


## [**VHDPlus MAX1000**](https://vhdplus.com/docs/components/max1000/)
(**€39.98**) inexpensive way to start with FPGAs (VHDPlus IDE)
![](https://shop.vhdplus.com/wp-content/uploads/2021/02/TEI0001-03-08-C8_2.jpg)
### Features:
#### Hardware Overview
![](https://vhdplus.com/assets/images/Top_labled-f008c9fb99e310ed584b827dcd6c15ca.png)
#### Specs
- MAX 10 FPGA (10M08SAU169C8G):
  - Logic Elements          - 8,000
  - RAM                     - 378 Kb
  - Configuration Memory    - 2.24 Mb
  - ADC                     - 1 Mio. Samples/s
                            - 12 Bit
                            - 8 Inputs
  - PLL                     - 2
                            - > 300 MHz
  - 18 x 18 Multiplier      - 24
  - Configuration Images    - 2
- SDRAM (W9864G6JT-6):        - 64 Mb
- Flash (W74M64FVSSIQ):       - 64 Mb
- Oscillator (DSC6011ME2A):   - 12 MHz

### [VHDPlus Resources](#vhdplus-resources)

### Projects
- [Example Projects, by Victor PM](https://github.com/vpecanins/max1000-tutorial)

### Distributor
- [VHDPlus](https://shop.vhdplus.com/product/max1000/)

---
## [**VHDPlus CORE_MAX10**](https://vhdplus.com/docs/components/vhdpcore_max10/)
(**€49.98**) entry into FPGA programming for everybody who wants to use all the power of FPGAs
![](https://shop.vhdplus.com/wp-content/uploads/2020/05/Core.png)
### Features
- CRUVI High Speed Connector
- CRUVI Low Speed Connector
- MAX 10 FPGA (10M08SAU169C8G):
  - Logic Elements: 8,000
  - RAM: 378 Kb
  - Configuration Memory: 2.24 Mb
- ADC:
  - 8 Channels
  - 1 Mio. Samples/s
  - 12 Bit
- 2x PLL:
  - > 300 MHz
  - 18 x 18 Multiplier: 24
  - Configuration Images: 2
- Arrow USB-Programmer (with USB to Serial Interface)
- SDRAM (W9864G6JT-6): 64 Mb
- Flash (W74M64FVSSIQ): 64 Mb
- Oscillator (DSC6011ME2A): 12 MHz

#### Core Overview
![](https://vhdplus.com/assets/images/Items2-6e3162122f4a1171d5630fe7dbe17dcb.png)

### VHDPlus Resources
- [VHDPlus Getting started](https://vhdplus.com/docs/getstarted/): Getting started guide with VHDPlus IDE, Driver installation, simulation tools
- [Arrow USB Driver](https://vhdplus.com/docs/getstarted/drivers/): Programmer for VHDPlus FPGAs.
- [VHDPlus Libraries and Examples](https://github.com/VHDPlus/VHDPlus_Libraries_and_Examples/): Collection of libraries and examples on VHDPlus IDE 

### Projects
![](https://vhdplus.com/img/community/robot_demo.mp4)
- [Logic Analyzer](https://vhdplus.com/docs/community/logic_analyzer/) - tutorial to convert the Core MAX10 or MAX1000 FPGA into a Logic Analyzer. Because of the high performance, even sample rates of 200MHz and more would be possible. And if you would buy a logic analyzer with this sample rates, you would have to spend more than 100€. With the FPGA you can also modify the sample speed, depth and input channels.[github](https://github.com/leonbeier/OLS_Logic_Analyzer)
![](https://vhdplus.com/assets/images/LA-c58b31669438a0e69bf257834e8fc28a.png)

- [Your first Robot](https://vhdplus.com/docs/community/motor/) - tutorial of making a robot that can drive a pre defined route and surround objects blocking the route. [github](https://github.com/VHDPlus/VHDPlus_Libraries_and_Examples/tree/master/Examples/Hardware/Output/Motor_Route)
![](demonstration.gif)

- [Camera and Object Detection](https://vhdplus.com/docs/community/camera/) - tutorial on how to use [OnSemi Camera](https://vhdplus.com/docs/components/onsemi_camera) with HDMI,  how to apply filters to the received images and finally create an object detection. [github](https://github.com/leonbeier/VHDPlus_Libraries_and_Examples/tree/master/Examples/Hardware/Input/Object_Recogition)
![](https://vhdplus.com/assets/images/Camera-56a78e85dd2f9b8aaaba217d491196d3.webp)

- [Simple Neural Net](https://vhdplus.com/docs/community/neural_net/)- tutorial on training a simple Neural Net with an FPGA, available on [github](https://github.com/leonbeier/NN_RGB_FPGA), the neural net is trained for colors. With the IAS Camera Exptension, the performance of this filter is tested.
![](https://vhdplus.com/assets/images/nn_t-2ec20389ce22c56a2f20f2a449da7620.png)
- [Light Tracker](https://vhdplus.com/docs/community/light_tracker/) - learn how to use a camera and servos. The white parts of the camera image are detected and with two servos the camera is turned into the direction of the light. [github](https://github.com/leonbeier/Light_Tracker)
![](https://vhdplus.com/assets/images/light_track_2-483977f5667bdba14ced885b056fc6a4.jpg)

- [LED Matrix](https://vhdplus.com/docs/community/matrix/) - In this tutorial we want to make an LED matrix that can display a custom text or show an image. This can be extended into a clock, games or a spectrum analyzer. [github](https://github.com/VHDPlus/VHDPlus_Libraries_and_Examples/tree/master/Examples/Hardware/Output/LED_Matrix)
-  ![](matrix-demonstration.gif)

### Distributors

---

## [**Crowdsupply TinyFPGA**](https://tinyfpga.com/) 
(**€12.90**) A range of tiny, low-cost, well-supported, and open FPGA dev boards
![](https://www.crowdsupply.com/img/bf66/73137f1b-5f2e-4247-9876-d5a7dcdabf66/tinyfpga-front-back-1-1_jpg_gallery-lg.jpg)
### Features
- Height: 1.4 inches, width: 0.7 inches
- Programming interface: USB 2.0 full-speed (12 mbit/sec)
- ICE40LP8K FPGA
  - 7680 four-input look-up-tables
  - 128 KBit block RAM
  - Phase Locked Loop
  - 41 user IO pins
- 8 MBit of SPI Flash
- Onboard 3.3 V (300 mA) and 1.2 V (150 mA) LDO regulators
- Low-Power 16 MHz MEMs Oscillator
  - 1.3 mA power when active
  - 50 ppm stability.

#### Variants
  | Variant            | AX1                | AX2                | BX                | EX                |
  |--------------------|--------------------|--------------------|-------------------|-------------------|
  | **FPGA Chip**      | XO2-256            | XO2-1200           | ICE40LP8K         | LFE5U-25F         |
  | **Programming**    | JTAG               | JTAG               | USB               | USB               |
  | **Logic Cells**    | 256                | 1200               | 7680              | 24,288            |
  | **Distributed RAM**| 2 KBit             | 10 KBit            | —                 | 194 KBit          |
  | **Block RAM**      | —                  | 64 KBit            | 128 KBit          | 1008 KBit         |
  | **User Flash**     | —                  | 64 KBit            | 6 MBit            | 96 MBit           |
  | **PLLs**           | —                  | 1                  | 1                 | 2                 |
  | **DLLs**           | —                  | —                  | —                 | 2                 |
  | **User IO Pins**   | 22 (18+4)          | 22 (18+4)          | 41 (31+10)        | 56 (49+7)         |

#### TinyFPGA Programmer, PIC16F1455 USB microcontroller
![](https://www.crowdsupply.com/img/5c2e/af39c001-ed77-414f-93a8-298ee6dc5c2e/tinyfpga-programmer-1_jpg_gallery-lg.jpg)
- A simple, open-source USB JTAG programmer for TinyFPGA AX1 and AX2 boards
- Slots onto the JTAG pins of the A-series FPGA boards. 
- Using the TinyFPGA Programmer Application you can program .jed files generated by Lattice Diamond.

### Resources
 - [TinyFPGA user guide](https://tinyfpga.com/a-series-guide.html)
 - [TinyFPGA Bootloader repository](https://github.com/tinyfpga/TinyFPGA-Bootloader)
 - [IceStorm Toolchain](https://github.com/cliffordwolf/icestorm)
 - [IceStudio IDE](https://github.com/FPGAwars/icestudio)
 - [APIO-IDE project](https://github.com/FPGAwars/apio-ide/wiki)

### Distributors
- [Mouser](https://www.mouser.fi/ProductDetail/Crowd-Supply/CS-TINYFPGA-04?qs=xZ%2FP%252Ba9zWqYTMXmT%2F9UHzg%3D%3D)
- [Digikey, AX2](https://www.digikey.fi/en/products/detail/sparkfun-electronics/14828/9561755)
---
## [**Crowdsupply FireAnt**](https://www.crowdsupply.com/jungle-elec/fireant) 
(**€32.68**) A low-cost, thumb-sized, breadboard-friendly FPGA dev board for makers and hardware designers
![](https://www.crowdsupply.com/img/4a9f/17c84a05-9973-4c69-abe4-ffa922d74a9f/fireant-boarddescription-withoutlegend_png_gallery-lg.jpg)
1. Efinity Trion T8F81C2 FPGA
2. FTDI FT232HQ UART/FIFO IC
3. Winbond W25Q80DV Serial NOR Flash
4. 3.3 V LDO regulator
5. Micro USB female connector
6. Button: CRESET
7. BTN1
8. BTN2
9. LED_PWR
10. LED_CDN
11. LED1, LED2, LED3, LED4
### Features
- Efinix Trion T8 FPGA
  - 7384 LE counts
  - 8 embedded multipliers
  - 1 low-power oscillator
  - 1 PLL
  - 122.88 kbit internal RAM
  - Package size: BGA-81 5x5 mm
- Board dimensions: 51.4 x 18.3 mm
- Supply voltage: VBUS 5 V | VCC 3.3 V
- VCCIO: 3.3 V
- Onboard 33.333 MHz crystal oscillator for PLL
- GPIOs: 35
- LED: 6 (incl. 4 user-configurable LEDs)
- Flash: 8 Mbit serial NOR Flash
- Programming interface:
  - USB 2.0 Hi-Speed(480 Mb/s)
  - JTAG (with exposed pin in bottom layer via external JTAG programmer)
  - Development platform: Efinity Software

### Resource
- [Board Schematic](https://github.com/jungle-elec/FireAnt/raw/master/FireAnt_Schematic.pdf)

### Projects
- [BonFire RISC-V on FireAnt](https://github.com/ThomasHornschuh/bonfire-soc-fireant)
- [Sobel Filter Demo with FireAnt](https://www.crowdsupply.com/xips-technology/fireant/updates/awesome-sobel-filter-demo-with-fireant)

### Distributors
- [Mouser](https://www.mouser.fi/ProductDetail/Crowd-Supply/CS-FIREANT-01?qs=%252B6g0mu59x7Lg6xgf1btVXQ%3D%3D)
---
## [**Seeed-Studio Spartan Edge Accelerator (SEA) Board**](https://www.seeedstudio.com/Spartan-Edge-Accelerator-Board-p-4261.html) 
(**$39.50/board**, **10+ bulk $35.10/board**) a Xilinx Spartan FPGA development board in the Arduino UNO shield form factor.
![](https://media-cdn.seeedstudio.com/media/catalog/product/cache/bb49d3ec4ee05b6f018e93f896b8a25d/s/p/spartan-edge-accelerater-board-v1.0-preview-2.jpg)

### Features
#### High-speed image processing
- Support Raspberry Pi camera v1.0(OV5640)
- Support max 30fps image transmission
- Encrypted Internet of Things
- Support cloud services （AWS, Azure, etc.）
- Support software encryption algorithm
#### Multiple I/O port extensions
- 20 extended I/O ports（FPGA stand-alone mode）
- 10 extended I/O ports（Arduino shield mode）
- Support for Arduino expansion interface

#### Hardware Overview
![](https://github.com/SeeedDocument/Spartan-Edge-Accelerator-Board/raw/master/img/Spartan-Edge-Accelerater-Board-v1.0-pin.jpg)

### Resources
- [Spartan Edge Accelerator Board v1.0 eagle file](https://github.com/SeeedDocument/Spartan-Edge-Accelerator-Board/raw/master/res/Spartan%20Edge%20Accelerator%20Board%20v1.0.zip)
- [Spartan-7 FPGAs Data Sheet.pdf](https://github.com/SeeedDocument/Spartan-Edge-Accelerator-Board/raw/master/res/Spartan-7%20FPGAs%20Data%20Sheet.pdf)
- [ESP32-datasheet.pdf](https://github.com/SeeedDocument/Spartan-Edge-Accelerator-Board/raw/master/res/ESP32-datasheet.pdf)
- [Spartan Edge Accelerator Board Wiki](http://wiki.seeedstudio.com/Spartan-Edge-Accelerator-Board/)

### Projects
- [MIPI Imaging with Edge accelerator](https://www.hackster.io/adam-taylor/mipi-imaging-with-the-spartan-edge-accelerator-board-50cab1)
- [Vivado Board file](https://www.hackster.io/shengr/xilinx-vivado-board-files-for-spartan-edge-accelerator-1-e99826)
- [Accelerator Graphics with Spartan Edge Accelerator, WIP](https://hackaday.io/project/175763-spartan-edge-accelerator-graphics-esp32fpga): Xilinx Spartan 7 [hardware design](https://github.com/smartperson/spartan-edge-accelerator-graphical-system) and [ESP32 work](https://github.com/smartperson/spartan-edge-accelerator-esp32-qspi-to-fpga)  
### Distributors
[Seeed Studio](https://www.seeedstudio.com/Spartan-Edge-Accelerator-Board-p-4261.html)
[Digikey](https://www.digikey.fi/en/products/detail/seeed-technology-co-ltd/102030005/10492205)

---
## [**GOWIN LittleBee**](https://www.trenz-electronic.de/en/FPGA-Module-with-GOWIN-LittleBee-and-8-MByte-internal-SDRAM/TEC0117-01-A)
(**€41.77 / board - bulk 10**) FPGA Module with GOWIN LittleBee and 8 MByte internal SDRAM
![](https://www.trenz-electronic.de/thumbnail/20/b0/e2/1755614260/TEC0117-01_1_800x800.jpg?ts=1755614260)
### Features
- GOWIN LittleBee 1NR9 FPGA
  - 8 MByte internal SDRAM
- 8 MByte SPI Flash for user applications
- JTAG and UART over Micro USB2 connector
- 1 x 6-pin header for JTAG access to FPGA SoC
- 1 x Pmod header providing 8 I/O
- 2 x 14-pin headers (2,54 mm pitch) providing 22 I/O
- 8 x user LEDs
- 1 x user push button
- 100 MHz user clock (MEMS oscillator)
- 5V single power supply with on-board voltage regulators
- Size: 61.5 x 25 mm

### Resources
- [**TEC0117 - LittleBee**](https://wiki.trenz-electronic.de/display/PD/TEC0117+-+LittleBee) - Wiki with TRM, reference projects, application notes and more
  - [TEC0117 Getting Started](https://wiki.trenz-electronic.de/display/PD/TEC0117+Getting+Started) - basic information
  - [TEC0117 TRM](https://wiki.trenz-electronic.de/display/PD/TEC0117+TRM) - Technical Reference Manual
  - [TEC0117 Reference Designs](https://wiki.trenz-electronic.de/display/PD/TEC0117+Reference+Designs)
- **Links**
  - [Trenz Electronic download area](https://shop.trenz-electronic.de/Download/?path=Trenz_Electronic/Modules_and_Module_Carriers/2.5x6.15/TEC0117) - various schematics, hardware designs and more
  - [Gowin Software download](http://www.gowinsemi.com/support/home/) - free design software (need apply for free license)
  - [Pinout/Tracelength Table](https://shop.trenz-electronic.de/Download/?path=Trenz_Electronic/Pinout) - illustration of pinout, tracelength and cross reference Information of modules with different baseboards
- **3rd Party Links**
  - [TEC0117_ApNote.pdf - Provided by ALSE-FR](https://shop.trenz-electronic.de/trenzdownloads/Trenz_Electronic/Modules_and_Module_Carriers/2.5x6.15/TEC0117/Reference_Design/Factory_Image/TEC0117_ApNote.pdf)
- **Support**
  - For support, please go to Trenz Electronic Forum or contact support@trenz-electronic.de.

### Distributors
- [Trens-electronics](https://www.trenz-electronic.de/en/FPGA-Module-with-GOWIN-LittleBee-and-8-MByte-internal-SDRAM/TEC0117-01-A)
---
## [**Trenz-electronic S7 Mini**](https://www.trenz-electronic.de/en/S7-Mini-Fully-Open-Source-Module-with-AMD-Spartan-7S25-1C-64-Mbit-HyperRAM/TE0890-02-P1C-5-A): 
(**€36.41 / board** - bulk 10) Fully Open-Source Module with AMD Spartan™ 7S25-1C, 64 Mbit HyperRAM
![](https://www.trenz-electronic.de/thumbnail/23/9c/db/1754558670/TE0890-02-P1C-5-A_1_800x800.webp?ts=1754558673)
### Features
- AMD Spartan™ 7 XC7S25-1FTGB196C FPGA
- Dimensions: 2.7 x 5.2 cm
- Fully Open-Source Spartan™ 7 Module
- 7S25 target with 23K logic cells, 29K flops, 45 36Kb BRAMs, 80 mults.
- Footprint compatible with 7S6, 7S15, 7S50 FTGB-196 devices
- Devices fully supported by free "Web Pack" Vivado for Synthesis, Place + Route
- Dual-pinout DIP-40 or 50mil 80 pin connectors for 32 or 64 FPGA 3.3V I/Os
- 64 Mbit Config PROM for dual-boot and/or SW code storage
- 64 Mbit HyperRAM DRAM (may be used as video frame buffer)
- Standard 1x6 FTDI cable serial interface to Host-PCs
- Standard 1x6 Digilent HS2 JTAG header for initial PROM programming
- 5V supply input (4.0V-5.5V per PAM2305 spec)

### Resources
  - [TE0890 - S7 Mini](https://wiki.trenz-electronic.de/display/PD/TE0890+-+S7+Mini) - Wiki with TRM, reference projects, application notes and more

    - TE0890 TRM - Technical Reference Manual (tba)
    - [TE0890 Reference Designs](https://wiki.trenz-electronic.de/display/PD/TE0890+Reference+Designs) - Reference Design description
    - [TE0890 "S7 Mini" Product Change Notifications](https://wiki.trenz-electronic.de/pages/viewpage.action.dir/pageId=3925729) - PCN (see also Schematic Change History and TRM
  #### Links
  - [Download area](https://shop.trenz-electronic.de/en/Download/?path=Trenz_Electronic/Modules_and_Module_Carriers/2.7x5.2/TE0890) - various reference designs, schematics, hardware designs and more
  - [Test Board Design](https://wiki.trenz-electronic.de/display/PD/TE0890+Test+Board) for the "S7 Mini" TE0890
  - [Example design](https://github.com/blackmesalabs/s7_mini_fpga) - for the "S7 Mini"
  - [LiteX soc platform project](https://github.com/micro-FPGA/CRUVI/tree/master/tools/LiteX) - for "S7 Mini"
  - [FuseSoC Blinky](https://github.com/fusesoc/blinky) - included is support for "S7 Mini"
  - [Pinout/Tracelength Table](https://shop.trenz-electronic.de/Download/?path=Trenz_Electronic/Pinout) - illustration of pinout, tracelength and cross reference Information of modules with different baseboards
  - [Developer resource page](https://blackmesalabs.wordpress.com/2019/05/19/bml-s7-mini-fpga-module/)
  #### Support
  - For support, please go to http://forum.trenz-electronic.de/ or contact support@trenz-electronic.de

### Distributors
- [Trenz-electronics](https://www.trenz-electronic.de/en/S7-Mini-Fully-Open-Source-Module-with-AMD-Spartan-7S25-1C-64-Mbit-HyperRAM/TE0890-02-P1C-5-A)
---
## [**Trenz-electronic TE0722**](https://www.trenz-electronic.de/en/DIPFORTy1-Soft-Propeller-with-AMD-Zynq-7010-1C-16-MByte-Flash/TE0722-04-41C-4-A)
(**€70.21**) DIPFORTy1 "Soft Propeller" with AMD Zynq™ 7010-1C, 16 MByte Flash
![](https://www.trenz-electronic.de/thumbnail/60/87/b7/1754554221/TE0722-04-41I-4-A_0_800x800.webp?ts=1754554223)
### Features
  - AMD Zynq™ 7 XC7Z010-1CLG225C
    - 16 MByte SPI Flash (primary boot)
    - 33.333 MHz Clock (MEMS Oscillator)
    - dual-core ARM Cortex®-A
  - DIP40 form factor
    - 2 x 20 holes for socket pins or pin-header
    - Size: 18 x 51 mm
  - Total user accessible PL I/O: 46 (+3 Input only)
    - DIP40 header pins: 34 I/O
    - XMOD J1: 6 I/O
    - XMOD J2: JTAG + 2 I/O (or 3 input + 2 I/O)
    - XMOD J3: 4 I/O
- 3.3 V single supply
- RGB LED (PL I/O connected)
- "Done" LED (inverted polarity)
- User LED (ARM CPU MIO GPIO)
- MicroSD Card socket (MIO, ZYNQ secondary boot media)

### Resources:
  - [TE0722 "DIPFORTy"](https://wiki.trenz-electronic.de/display/PD/TE0722+-+DIPFORTy) - Wiki with TRM, reference projects, application notes and more
    - [TE0722 TRM](https://wiki.trenz-electronic.de/display/PD/TE0722+TRM) - Technical Reference Manual
    - [TE0722 Getting Started](https://wiki.trenz-electronic.de/display/PD/TE0722+Getting+Started) - basic information
    - [TE0722 Product Change Notifications - PCN](https://wiki.trenz-electronic.de/display/PD/TE0722+Product+Change+Notifications) (see also schematic change history and TRM)
    - [TE0722 Reference Designs](https://wiki.trenz-electronic.de/display/PD/TE0722+Reference+Designs) - reference design description for Vivado 2017.2 and newer
  - **Downloads**:
    - [Download area](https://shop.trenz-electronic.de/Download/?path=Trenz_Electronic/Modules_and_Module_Carriers/special/TE0722) - various reference designs, schematics, hardware designs and more
    - [B2B Pinout Table](https://shop.trenz-electronic.de/Download/?path=Trenz_Electronic/Pinout) - cross reference of modules with board connectors
  - **Accessories**
    - [TE0790 Resources](https://wiki.trenz-electronic.de/display/PD/TE0790+Resources) - XMOD JTAG Programmer documentation
    - [TE0790 CPLD - XMOD DIP40](https://wiki.trenz-electronic.de/pages/viewpage.action.dir/pageId=3925817) - special firmware for XMOD used with TE0722
  - **Notes**:
    - [DDR less ZYNQ Design](https://wiki.trenz-electronic.de/display/PD/DDR+less+ZYNQ+Design) - important notes for DDR less Zynq 

### [*XMOD (TE0790)*](https://www.trenz-electronic.de/en/XMOD-FTDI-JTAG-Adapter-AMD-compatible/TE0790-03) TE0722 Programmer with special firmware 
![](https://www.trenz-electronic.de/thumbnail/03/cf/fa/1745994962/TE0790-03_1_800x800.jpg?ts=1746175386)

### Related resource:
- [**Trenz-electronic TE0790-XMOD**](https://wiki.trenz-electronic.de/display/PD/TE0790+-+XMOD) - Wiki with TRM, reference projects, application notes and more
  - [TE0790 TRM](https://wiki.trenz-electronic.de/display/PD/TE0790+TRM) - XMOD Technical Reference Manual
  - [TE0791 TRM](https://wiki.trenz-electronic.de/display/PD/TE0791+TRM) - Adapter to convert XMOD 2 x 6 Pin Header to different connector types
  - [TE0790 CPLD Firmware](https://wiki.trenz-electronic.de/display/PD/TE0790+CPLD+Firmware) - CPLD Firmware Description and Variants
  - [TE0790 Identification](https://wiki.trenz-electronic.de/display/PD/TE0790+Identification) - Identify variant with AMD/Digilent License Key preprogrammed.
- **Links**
  - [TE0790 Download area](https://shop.trenz-electronic.de/Download/?path=Trenz_Electronic/JTAG_Programmer/TE0790) - schematics, Step models, CPLD Firmware and Source code and more
  - [AMD FTDI JTAG Programmer](https://wiki.trenz-electronic.de/display/PD/AMD+FTDI+JTAG+Programmer) - Modification to use free AMD License

- **Support**
  - For support, please go to http://forum.trenz-electronic.de/ or contact support@trenz-electronic.de

### Distributor
- [Trenz-Electronics TE0722](https://www.trenz-electronic.de/en/DIPFORTy1-Soft-Propeller-with-AMD-Zynq-7010-1C-16-MByte-Flash/TE0722-04-41C-4-A)
- [Trenz-Electronics TE790](https://www.trenz-electronic.de/en/XMOD-FTDI-JTAG-Adapter-AMD-compatible/TE0790-03)
- [Digikey TE0722](https://www.digikey.fi/en/products/detail/trenz-electronic-gmbh/TE0722-04-41I-4-A/22081844)
- [Digikey TE790](https://www.digikey.fi/en/products/detail/trenz-electronic-gmbh/TE0790-03L/11594256)

---
## [**Trenz-electronic MAX1000**](https://www.trenz-electronic.de/en/MAX1000-IoT-Maker-Board-8kLE-8-MByte-SDRAM-8-MByte-Flash-6.15-x-2.5-cm/TEI0001-04-DBC87A)
(**€40.46**, VAT and shipping included) IoT Maker Board, 8kLE, 8 MByte SDRAM, 8 MByte Flash, 6.15 x 2.5 cm
![](https://www.trenz-electronic.de/thumbnail/4b/9f/b4/1746171278/TEI0001-04-FBC88A_1_1920x1920.webp?ts=1746171282)

### Features

#### FPGA 
- Device: Intel MAX 10
- Logic Size:  02 / 04 / 08 / 16
- Speedgrade:  6 / 7 / 8
- Temperature Range: C / I / A
- Package: U169
#### RAM/Storage
- 8 MByte SDRAM 1
- 8 MByte SPI Flash 1
- 4 KBit EEPROM for FTDI
#### On Board
- ST Microelectronics LIS3DH 3-axis accelerometer
- JTAG and UART over Micro USB2 connector
- 8x user LEDs
- 1x user push button
- 1x reset button
- MEMS Oscillator 2)
#### Interface
- 2x 14-pin headers (2.54 mm pitch) for 7 analog, 15 digital inputs and various connections.
- 1x PMOD header providing 8 GPIOs
- 1x 6 pin header for JTAG access to FPGA SoC
- 1x 3 pin header providing 2 analog inputs or 1 GPIO
#### Power
- 5.0 V single power supply via Micro USB or Pin Header
#### Dimension
- 61.5 mm x 25 mm

### Resources:
#### MAX1000 2.5 x 6.15 cm FPGA module with Intel MAX10 FPGA
- [TEI0001 - MAX1000](https://wiki.trenz-electronic.de/display/PD/TEI0001+-+MAX1000) - Wiki with TRM, reference projects, application notes and more
- [TEI0001 TRM](https://wiki.trenz-electronic.de/display/PD/TEI0001+TRM)- Technical Reference Manual
- [TEI0001 Getting Started](https://wiki.trenz-electronic.de/display/PD/TEI0001+Getting+Started)  - basic information
- [TEI0001 Reference Designs](https://wiki.trenz-electronic.de/display/PD/TEI0001+Reference+Designs)  - Reference Design Description for Quartus 17.1 and newer
- [TEI0001 PCN](https://wiki.trenz-electronic.de/display/PD/TEI0001+PCN) - Product Change Notification  (see also Schematic Change History and TRM)
- [Arrow USB Programmer](https://wiki.trenz-electronic.de/display/PD/Arrow+USB+Programmer) - Arrow USB Programmer 2 driver setup installation instruction and Troubleshoot
#### Links
- [Download area](https://shop.trenz-electronic.de/Download/?path=Trenz_Electronic/Modules_and_Module_Carriers/2.5x6.15/TEI0001) - various schematics, hardware designs and more
- [Arrow USB Programmer Setup Libraries](https://shop.trenz-electronic.de/Download/?path=Trenz_Electronic/Software/Drivers/Arrow_USB_Programmer) - driver
- [Pinout/Tracelength Table](https://shop.trenz-electronic.de/Download/?path=Trenz_Electronic/Pinout) - illustration of pinout, tracelength and cross reference Information of modules with different baseboards
#### Forum
- [MAX1000 community projects](https://forum.trenz-electronic.de/index.php/board,36.0.html)
- [DEMO MAX1000: USER GUIDE](https://forum.trenz-electronic.de/index.php/topic,756.0.html) .... first steps with MAX1000 - User Guide
- [MAX1000 Hardware](https://forum.trenz-electronic.de/index.php/topic,741.0.html) - Hardware Notes
- [MAX1000 Driver and Setup Files](https://forum.trenz-electronic.de/index.php/topic,740.0.html) - Driver Notes
- [MAX1000 Demo Projects](https://forum.trenz-electronic.de/index.php/topic,739.0.html) - Shipped LED DEMO Design

### Distributor
- [Trenz-Electronics](https://www.trenz-electronic.de/en/MAX1000-IoT-Maker-Board-8kLE-8-MByte-SDRAM-8-MByte-Flash-6.15-x-2.5-cm/TEI0001-04-DBC87A)

---
## [**Lattice-Semi iCEstick Evaluation Kit**](https://www.latticesemi.com/icestick) 
(**€130.73**) easy-to-use USB thumb-drive form-factor development board.
![](https://hackaday.com/wp-content/uploads/2016/11/ice.png)

### Features
- USB thumb drive form factor
- iCE40HX-1k on board
- 2 x 6 position Digilent Pmod™ connector for other peripheral connections
- FTDI 2232H USB device allows iCE device programming and UART interface to a PC
- Vishay TFDU4101 IrDA transceiver
- Five user LEDs
- Discera 12 Mhz MEMS oscillator
- Micron 32 Mbit N25Q32 SPI flash
- USB connector provides the power supply
- 16 LVCMOS/LVTTL (3.3 V) digital I/O connections on 0.1” through-hole connections
#### iCEstick with Pmod™
iCEstick contains a Digilent Pmod™ connector to attach various peripheral modules. The accelerometer reference design using Pmod™-ACL is an example. Purchased separately, this HDL design showcases how the iCE40 device interfaces to an acceleromter sensor, enabling the user to integrate additional sensors for their particular product.
#### IrDA Tx & Rx Reference Designs
Designers can use the included reference designs (IRDA UART TX and IRDA UART RX) to simplify the prototyping of a wide variety of applications involving wireless transmission of data or control signals utilizing the onboard IrDA transceiver. Examples include wireless data transmission between two mobile devices such as smartphones, tablets, gaming devices, etc. Wireless control applications such as high-end remote controls, TVs, LED lighting control and others can also be implemented.

### Resources
- [User manual](https://www.latticesemi.com/view_document?document_id=50701)
- [Programming cable user guide](https://www.latticesemi.com/view_document?document_id=143)
- [Case study: Using Low-cost, Non-volatile PLDs in System Application](https://www.latticesemi.com/view_document?document_id=39270)
#### Design file:
- [Default LED Rotation bitmap for iCEstick](https://www.latticesemi.com/view_document?document_id=50013)
- [iCEstick LED Rotation](https://www.latticesemi.com/view_document?document_id=50033)
- [IRDA UART RX](https://www.latticesemi.com/view_document?document_id=51470)
- [IRDA UART TX](https://www.latticesemi.com/view_document?document_id=51145)
- [Pmod Accelerometer](https://www.latticesemi.com/view_document?document_id=50034)

### Distributor
- [Digikey](https://www.digikey.fi/en/products/detail/lattice-semiconductor-corporation/ICE40HX1K-STICK-EVN/4289604)

---

## [**Aloriumtech SNO ARDUINO**](https://aloriumtech.com/sno/)
(**€42**)Arduino-compatible FPGA development board
![](https://aloriumtech.com/wp-content/uploads/2017/01/Sno_Top_Final-min.jpg)

### Features
- Intel® MAX® 10 FPGA (16K LEs)
- 10M16SAU169C8G
- Programmable with Arduino IDE
- Embedded 8-bit AVR instruction set compatible microcontroller
- Configurable with custom XBs on the FPGA
- Digital I/O pins: 32
- Analog pins: 6
- ADC performance: 1 MHz
- ADC resolution: 12-bit sustained
- ADC sample rate: 254k samples/second
- Program FLASH 32 KB
- Data memory SRAM: 2 KB
- Connectivity: solderable vias
- Programming interface: FTDI

### [**Aloriumtech SNOMAKRR10**](https://aloriumtech.com/snomakr/)
(**€26.59**) Arduino Breakout board for SNO
![](https://aloriumtech.com/wp-content/uploads/2018/03/snomakr_sno-min.png)
### Resources:
- [Github](https://github.com/AloriumTechnology)
- [Tutorial](http://www.aloriumtech.com/xlr8-quickstart/)

### Distributors:
- [Digikey SNO](https://www.digikey.fi/en/products/detail/alorium-technology-llc/SNOR21M16V3/9607424)
- [Digikey SNOMAKKR10](https://www.digikey.fi/en/products/detail/alorium-technology-llc/SNOMAKRR10/9607425)

## [**Olimex GateMateA1-EVB**](https://www.olimex.com/Products/FPGA/GateMate/GateMateA1-EVB/open-source-hardware) 
(**53€**) Low cost/performance ratio, addresses all application requirements of small to medium size FPGA projects
![](https://www.olimex.com/Products/FPGA/GateMate/GateMateA1-EVB/images/GateMateA1-EVB.jpg)

### Features
- CCGM1A1 FPGA with 20480 logic cells
- PSRAM 64Mbit
- RP2040 processor for programming and debugging
- 2MB configuration Flash
- 4 buttons
- USB-C for power supply and programming
- PS2 connector
- VGA connector
- 4 Banks with signals with selectable levels 1.2V, 1.8V, 2.5V
- PMOD with level shifters
- UEXT with level shifters
- Power LED
- User LED
- 4 sections configuration slide switch
- Dimensions: 120 x 80 mm

### Resources:
- [CologneChip web page with datasheet](https://www.colognechip.com/programmable-logic/gatemate/)
- [GateMateA1-EVB user manual](https://github.com/OLIMEX/GateMateA1-EVB/blob/main/DOCUMENTS/GateMateA1-EVB-user-manual.pdf)
- [GateMateA1-EVB EU declaration of conformity](https://www.olimex.com/Products/FPGA/GateMate/GateMateA1-EVB/resources/EU-DOC-GateMateA1-EVB.pdf)
- [GateMateA1-EVB UKCA declaration of conformity](https://www.olimex.com/Products/FPGA/GateMate/GateMateA1-EVB/resources/UKCA-DOC-GateMateA1-EVB.pdf)
- [Important note](https://github.com/OLIMEX/GateMateA1-EVB/blob/main/HARDWARE/GateMateA1-EVB-Rev.A/IMPORTANT-NOTE.txt) for GateMateA1-EVB customers purchased before March 1, 2024

**HARDWARE**
- [GateMateA1-EVB schematic in PDF format](https://github.com/OLIMEX/GateMateA1-EVB/blob/main/HARDWARE/GateMateA1-EVB-Rev.A/GateMateA1-EVB_Rev_A.pdf)
- [GateMateA1-EVB repository with sources in KiCAD format](https://github.com/OLIMEX/GateMateA1-EVB)

**SOFTWARE**
- [GateMate toolchain installation guide](https://www.colognechip.com/docs/ug1002-toolchain-install-latest.pdf)
- [pico-dirtyJtag binary and README](https://github.com/OLIMEX/GateMateA1-EVB/tree/main/SOFTWARE/dirtyJtag)
- [Gatemate ILA (Integrated Logic Analyzer) repository](https://github.com/colognechip/gatemate_ila)

### Distributor
- [Digikey](https://www.digikey.fi/en/products/detail/olimex-ltd/gatematea1-evb/22258042)

---
## [**Renesas SLG7EVBFORGE**](https://www.renesas.com/en/design-resources/boards-kits/slg7evbforge) 
(**€81**): compact, easy-to-use, USB-powered hardware tool that provides SLG47910V 1K lookup table (LUT) ForgeFPGA IC hardware support for design emulation, programming, and real-time testing (with Verilog)
![](https://www.renesas.com/sites/default/files/1890-SLG7EVEBForge-ANGLE.jpg)

### Features
- USB-C connection to computer
- Configurable VDD and VDDIO power sources
- Design emulation and programming ability
- 2x Pmod™ connectors
- Zero Insertion Force (ZIF) socket allows for fast, easy removal, and replacement of SLG47910V silicon. Useful for programming and testing individual parts

### Resources: 
- [User Manual](https://www.renesas.com/en/document/mah/forgefpga-evaluation-board-r20-users-manual?r=25546646)
- [Quick Start Guide](https://www.renesas.com/en/document/qsg/forgefpga-evaluation-board-quick-start-guide?r=25546646)
- [HW Configuration guide](https://www.renesas.com/en/document/mah/forgefpga-configuration-guide?r=25546646)
- [SW Simulation guide](https://www.renesas.com/en/document/mas/forgefpga-software-simulation-user-guide?r=25546646)
- [Go Configure software](https://www.renesas.com/en/software-tool/go-configure-software-hub)

### Distributor:
- [Digikey](https://www.digikey.fi/en/products/detail/renesas-electronics-corporation/slg7evbforge/22972057)
- [Mouser](https://www.mouser.fi/ProductDetail/Renesas-Dialog/SLG7EVBFORGE?qs=2wMNvWM5ZX5HC1b2oIQaEg%3D%3D)

---
## [**SIPEEED TANG PRIMER 25K**](https://wiki.sipeed.com/hardware/en/tang/tang-primer-25k/primer-25k.html)
(**37€**) The ultra-small core board size can be applied in any volume-restricted scenarios.The simple base board can connect a USB joystick, plug in a 40Pin SDRAM module, and three PMOD interfaces can connect to an HDMI display, PS2 joystick to form a typical RetroGame console configuration. It can also be paired with the series of PMOD modules produced by Sipeed, for use in FPGA university teaching.

![](https://www.sparkfun.com/media/catalog/product/cache/a793f13fd3d678cea13d28206895ba0c/2/4/24511-Tang-Primer-25K-Feature.jpg)
### Features:
- FPGA: GW5A-LV25MG121
- Logic Unit (LUT4) - 23040
- Register (FF) - 23040
- Distributed Static Random Access Memory S-SRAM (bits) - 180K
- Block Static Random Access Memory B-SRAM (bits) - 1008K
- Number of Block Static Random Access Memory B-SRAM - 56
- Multiplier (18x18 Multiplier) - 28
- Phase-Locked Loop (PLLs) - 6
- Total I/O Bank - 8
- Flash: 64Mbits NOR Flash
- Overall Packaging: 2x60P BTB Core Board
- General I/O - 75
- MIPI I/O - 4 Lane Data

### Online resources
+ Wiki page: https://wiki.sipeed.com/hardware/en/tang/tang-primer-25k/primer-25k.html
+ Documentation: https://dl.sipeed.com/shareURL/TANG/Primer_25K 

### Projects
Hackster: https://www.hackster.io/news/sipeed-unveils-the-ultra-compact-tang-primer-25k-fpga-module-and-dock-carrier-board-69a6b1cd7910

### Distributors:
- [Digikey](https://www.digikey.fi/en/products/detail/sparkfun-electronics/24511/22257498)
- [Aliexpress](https://www.aliexpress.com/item/1005007252284709.html)

---
## [**Olimex iCE40HX1K-EVB**](https://www.olimex.com/Products/FPGA/iCE40/iCE40HX1K-EVB/open-source-hardware)
(**15€**): low-cost, open-source FPGA development board (*designed with Verilog)

![](https://www.olimex.com/wiki/images/e/ee/ICE40HX1K-EVB.jpg)

### Features
- iCE40HX1K-VQ100 FPGA 1280 Logic cells, 64 K embedded RAM bits
- 512KB SRAM organized as 256Kx16bit 10ns
- 2MB Serial Flash
- 2 user status LEDs
- Programming successful status LED
- 2 user buttons
- Reset button
- Power jack for 5V DC external power supply
- PGM connector (all signals at PGM1 @ 3.3V DC)
- 34 pin connector bus
- 100 Mhz oscillator
- Power supply DCDC regulators
- Power supply status LED
- Dimentions: 50x50mm ~ (2x2)"

### Available resource

- [iCE40HX1K-EVB wiki page](https://www.olimex.com/wiki/ICE40HX1K-EVB "‌")
- [Lattice iCE40 product page](http://www.latticesemi.com/Products/FPGAandCPLD/iCE40.aspx "‌")
- [Getting started under Linux tutorial](https://www.olimex.com/wiki/ICE40HX1K-EVB#Get_started_under_Linux "‌")
- [Getting started under Windows tutorial](https://github.com/OLIMEX/iCE40HX1K-EVB/blob/master/windows/icecube2/HowTo%20iCE40%20under%20Windows.pdf "‌")
- [iCE40HX1K-EVB European Declaration of Conformity](https://www.olimex.com/Products/FPGA/iCE40/iCE40HX1K-EVB/resources/EU-DOC-iCE40HX1K-EVB.pdf "‌")

[https://github.com/OLIMEX/iCE40HX1K-EVB](https://github.com/OLIMEX/iCE40HX1K-EVB "smartCard-inline")

### Projects

[Hello world with Verilog](https://olimex.wordpress.com/2016/07/12/hello-world-with-verilog-on-ice40hx1k-evb-with-open-source-tool-icestorm/)

‌### Distributors:
- [Olimex](https://www.olimex.com/Products/FPGA/iCE40/iCE40HX1K-EVB/open-source-hardware)
- [Mouser](https://www.mouser.fi/ProductDetail/Olimex-Ltd/ICE40HX1K-EVB?qs=K5ytOU5dogqDm9Cy2ZyazQ%3D%3D)

---

## [**Seeed-Studio RUNBER FPGA**](https://www.seeedstudio.com/Gowin-RUNBER-Development-Board-p-4779.html "‌") 
(**25€**): Development board adopts GOWIN GW1N-UV4LQ144 solution.

### Features:

![](https://files.seeedstudio.com/products/114992325/1.png)

- FPGA Development Board based on GOWIN GW1N-UV4LQ144
- Wide range of ports/peripherals for expandability
- Easily connect to PC with the help of USB-to-JTAG module
- Can run on low voltage (3.3V)
- Built-in oscillator with 12MHz frequency
- Numeric display for status display
- Eight monochrome LEDs for IO control and power indication
- RGB LEDs for IO control
- Integrated DIP switch and soft-touch keys for status control
- 2 set of 2.54mm pin headers (20 pins) for expandability

### Available resource

‌- [Hardware Instructions](https://files.seeedstudio.com/products/114992325/RUNBER_Development_Board_Hardware_Instructions_en.pdf "‌")
- [Instructions for Experiments](https://files.seeedstudio.com/products/114992325/Runber_Development_Board_Instructions_for_Experiments.pdf "‌")
- [Software User Guide](https://files.seeedstudio.com/products/114992325/Gowin_device&Software_User_Guide.zip "‌")
- [Source Code](https://files.seeedstudio.com/products/114992325/Gowin_RUNBER_BOARD_source_code.zip "‌")
- [Schematics](https://files.seeedstudio.com/products/114992325/Runber_Development_Board_Schematics.pdf "‌")

### Example project:

[https://files.seeedstudio.com/products/114992325/Runber\_Development\_Board\_Instructions\_for_Experiments.pdf](https://files.seeedstudio.com/products/114992325/Runber_Development_Board_Instructions_for_Experiments.pdf "‌")

### Distributor:

- [Digikey](https://www.digikey.fi/en/products/detail/seeed-technology-co-ltd/114992325/13635854 "smartCard-inline")
---
## [VHDPlus CYC1000](https://vhdplus.com/docs/components/cyc1000/) 
(**€41.82**): FPGA Development Board is for everybody who needs more logic elements than you get with the MAX1000.
![](https://vhdplus.com/assets/images/TEI0003-d9195bcec9449e4eead67d87a13e59d7.png)
### Features:
#### Board Overview
![](https://vhdplus.com/assets/images/Top_labled-1b5bc8d920ca9254728bfa2788a95d05.png)
#### Specs 
- Cyclone 10 FPGA (10CL025YU256C8G):
  - Logic Elements          - 25,000
  - RAM                     - 594 Kb
  - PLL                     - 4
                            - > 300 MHz
  - 18 x 18 Multiplier      - 66
- SDRAM (W9864G6JT-6):        - 64 Mb
- Flash (EPCQ16A):            - 16 Mb
- Oscillator (DSC6011ME2A):   - 12 MHz

### Resources:
- [Cyclone 10 LP FPGA product table](https://www.intel.com/content/www/us/en/content-details/714190/cyclone-10-lp-fpga-product-table.html), Check Product line **10CL025**.
- [Intel® Cyclone® 10 LP Device Overview](https://www.intel.com/content/www/us/en/docs/programmable/683879/current/device-overview.html)
- [Intel® Cyclone® 10 LP Datasheet](https://www.intel.com/content/www/us/en/docs/programmable/683251/current/device-datasheet.html)

### Projects:
- [Simple Projects walking LED and loopback for the serial port, by Tim Michals](https://github.com/tcmichals/cyc1000)
### Distributors:
[Digikey](https://www.digikey.fi/en/products/detail/trenz-electronic-gmbh/TEI0003-03-QFCR4A/22081856)

---
## [**Altera EK-10M08E144**](https://www.altera.com/products/devkit/a1jui0000049uttmam/max-10-fpga-10m08-evaluation-kit-power-soln-1) 
(**€54.04**) Altera MAX 10 Evaluation kit: compact, entry-level platform designed to evaluate the capabilities of the MAX 10 FPGA family
![](https://www.altera.com/sites/default/files/offering-assets/image_68e7d5cdbb382_max-10-eval-board.jpg)

### Features
- MAX 10 FPGA with 8K logic elements and integrated ADC
- Supports configuration via JTAG and internal flash with dual-image capability
- Includes Arduino UNO R3-compatible headers for analog and digital I/O expansion
- Provides 40 general-purpose I/Os and 8 analog input channels
- Offers 5 user LEDs, 6 DIP switches, and 2 pushbuttons for user interaction
- Powered via USB with onboard power measurement test points
- Includes a 50 MHz oscillator for general-purpose clocking
- Enables analog signal scaling through onboard op-amp circuits
- Supports power monitoring and temperature sensing via integrated ADC
- Compact, through-hole prototyping area for custom component integration

### Resource
- [Evaluation Kit user guide](https://www.intel.com/content/www/us/en/docs/programmable/812857/current/overview.html)
- [Kit Installation](https://cdrdv2.intel.com/v1/dl/getContent/776420)

### Distributors
[Digikey](https://www.digikey.fi/en/products/detail/altera/EK-10M08E144/4976140)
[Mouser](https://eu.mouser.com/ProductDetail/Altera/EK-10M08E144?qs=AX3SRYwdf7FCUbD2xGBE%252BQ%3D%3D)

---

## [**Digilent Basys 3**](https://digilent.com/shop/basys-3-amd-artix-7-fpga-trainer-board-recommended-for-introductory-users/ "‌")
(**$165**): best in-the-market, entry-level FPGA with a large number of designs to be completed without the need for any additional hardware.

![](https://cdn11.bigcommerce.com/s-7gavg/images/stencil/1280x1280/products/106/6259/Basys3-Rev.C-top-1000__75348.1730220608.png)

### **Features:**

- 33,280 logic cells in 5200 slices (each slice contains four 6-input LUTs and 8 flip-flops)
- 1,800 Kbits of fast block RAM
- Five clock management tiles, each with a phase-locked loop (PLL)
- 90 DSP slices
- Internal clock speeds exceeding 450 MHz
- On-chip analog-to-digital converter (XADC)
- Digilent USB-JTAG port for FPGA programming and communication
- Serial Flash
- USB-UART Bridge
- 12-bit VGA output
- USB HID Host for mice, keyboards and memory sticks
- 16 user switches
- 16 user LEDs
- 5 user pushbuttons
- 4-digit 7-segment display
- 4 Pmod ports: 3 Standard 12-pin Pmod ports, 1 dual purpose XADC signal / standard Pmod port

### [Reference manual](https://digilent.com/reference/programmable-logic/basys-3/start "‌")

**FPGA Design tutorial** [https://blackmesalabs.wordpress.com/2024/05/27/bml-fpga-design-tutorial-part-intro/](https://blackmesalabs.wordpress.com/2024/05/27/bml-fpga-design-tutorial-part-intro/ "smartCard-inline")

**Abacus Project**: using switches, LEDs, pushbuttons, and 7-segment display [https://digilent.com/reference/programmable-logic/basys-3/demos/abacus](https://digilent.com/reference/programmable-logic/basys-3/demos/abacus "‌")

**Keyboard Demo**: usage of the Basys3's USB-HID and USB-UART ports [https://digilent.com/reference/programmable-logic/basys-3/demos/keyboard](https://digilent.com/reference/programmable-logic/basys-3/demos/keyboard "‌")

**General I/O Demo**: use Basys3 switches, LEDs, pushbuttons, seven-segment display, VGA connector, USB HID Host port and USB UART bridge [https://digilent.com/reference/programmable-logic/basys-3/demos/gpio](https://digilent.com/reference/programmable-logic/basys-3/demos/gpio "‌")

**Digital Design projects**: [https://digilent.com/reference/learn/courses/digital-projects/start](https://digilent.com/reference/learn/courses/digital-projects/start "‌")

### **Distributors**:

[https://www.digikey.fi/fi/products/detail/digilent-inc/410-183/4970275](https://www.digikey.fi/fi/products/detail/digilent-inc/410-183/4970275 "smartCard-inline")

---

## [**Digilent Cmod A7 35T**](https://digilent.com/shop/cmod-a7-35t-breadboardable-artix-7-fpga-module/)
(**$99**) offers quick and flexible integration of FPGAs into embedded projects with breadboardable, solderless designs

![cmod-a7-0.png](https://cdn11.bigcommerce.com/s-7gavg/images/stencil/1280x1280/products/516/4032/Cmod_A7-top-600__97587.1670978506.png)

### Features

- **System Features**
  - 512KB SRAM with an 8-bit bus and 8ns access times
  - 4MB Quad-SPI Flash
  - USB-JTAG Programming Circuitry
  - Powered from USB or an external 3.3-5.5V supply connected to DIP pins
- **System Connectivity**
  - USB-UART bridge
- **Interaction and Sensory Devices**
  - 2 LEDs
  - 1 RGB LED
  - 2 Push Buttons
- **Expansion Connectors**
  - 48-pin DIP connector with 44 Digital I/O and 2 Analog inputs (0-3.3V)
  - One Pmod connector with 8 Digital I/O

### [Reference manual](https://digilent.com/reference/programmable-logic/cmod-a7 "‌")

**GPIO Demo project**: [https://digilent.com/reference/programmable-logic/cmod-a7/demos/gpio](https://digilent.com/reference/programmable-logic/cmod-a7/demos/gpio "‌")

**ADC project**: [https://digilent.com/reference/programmable-logic/cmod-a7/demos/xadc](https://digilent.com/reference/programmable-logic/cmod-a7/demos/xadc "‌")

**Stopwatch** [https://digilent.com/reference/cmod\_a7/cmod\_a7/cmod\_a7\_stopwatch/start](https://digilent.com/reference/cmod_a7/cmod_a7/cmod_a7_stopwatch/start "‌")

**MicroBlaze** **Out-of-the-box + RGB LED demo**: [https://digilent.com/reference/programmable-logic/cmod-a7/demos/oob](https://digilent.com/reference/programmable-logic/cmod-a7/demos/oob "‌")

### **Distributors**:

[Digikey](https://www.digikey.fi/en/products/detail/digilent-inc/410-328-35/6133793)
[Farnell](https://fi.farnell.com/digilent/410-328-35/development-kit-artix-7-fpga/dp/2614574 "smartCard-inline")

---

## [**TUL PYNQ-Z2**](https://www.tulembedded.com/FPGA/ProductsPYNQ-Z2.html) 
(**€156.76**): a more capable development board, allows development with Python.

“Designers can exploit the benefits of programmable logic and micro-processors to build more capable and exciting electronic systems”

![](https://www.amd.com/content/dam/amd/en/images/products/boards/2410750-zynq-xc7z020-board-product.jpg)

### Features:

**ZYNQ XC7Z020-1CLG400C**

- 650MHz dual-core Cortex-A9 processor
- DDR3 memory controller with 8 DMA channels and 4 High Performance AXI3 Slave ports
- High-bandwidth peripheral controllers: 1G Ethernet, USB 2.0, SDIO
- Low-bandwidth peripheral controller: SPI, UART, CAN, I2C
- Programmable from JTAG, Quad-SPI flash, and MicroSD card
- Programmable logic equivalent to Artix-7 FPGA
- 13,300 logic slices, each with four 6-input LUTs and 8 flip-flops
- 630 KB of fast block RAM
- 4 clock management tiles, each with a phase-locked loop (PLL) and mixed-mode clock manager (MMCM)
- 220 DSP slices
- On-chip analog-to-digital converter (XADC)

**Memory**

- 512MB DDR3 with 16-bit bus \@ 1050Mbps
- 16MB Quad-SPI Flash with factory programmed 48-bit globally unique EUI-48/64™ compatible identifier
- MicroSD slot

**Power**

- Powered from USB or 7V-15V external power sourceUSB and Ethernet
- Gigabit Ethernet PHY
- Micro USB-JTAG Programming circuitry
- Micro USB-UART bridge
- USB 2.0 OTG PHY (supports host only)

**Audio and Video**

- HDMI sink port (input)
- HDMI source port (output)
- I2S interface with 24bit DAC with 3.5mm TRRS jack
- Line-in with 3.5mm jack

**Switches, Push-buttons and LEDs**

- 4 push-buttons
- 2 slide switches
- 4 LEDs
- 2 RGB LEDs

**Expansion Connectors**

- Two standard Pmod ports
- 16 Total FPGA I/O (8 shared pins with Raspberry Pi connector)
- Arduino Shield connector
- 24 Total FPGA I/O
- 6 Single-ended 0-3.3V Analog inputs to XADC
- Raspberry Pi connector
- 28 Total FPGA I/O (8 shared pins with Pmod A port)

### [User manual](https://dpoauwgwqsy2x.cloudfront.net/Download/pynqz2_user_manual_v1_0.pdf "‌")

[https://www.pynq.io/embedded.html](https://www.pynq.io/embedded.html "smartCard-inline")

Hackster projects: [https://www.hackster.io/search?q=pynq%20z2&i=projects](https://www.hackster.io/search?q=pynq%20z2&i=projects "smartCard-inline")

### Distributors:

[Farnell](https://fi.farnell.com/en-FI/tul-corporation/1m1-m000127dvb/basic-kit-32bit-arm-cortex-a9/dp/2913032)

---

## [**1bitsquared iCEBreaker**](https://1bitsquared.de/products/icebreaker)
(**€79.95**): an open-source, educational FPGA development board

![](https://1bitsquared.de/cdn/shop/files/icebreaker-v1_1a-iso-1_large.jpg?v=1736439243)

### HW Specifications:

- iCE40UP5K in QFN48 (SG48) package
  - [iCE40 UltraPlus 5K](http://www.latticesemi.com/-/media/LatticeSemi/Documents/DataSheets/iCE/iCE40-UltraPlus-Family-Data-Sheet.ashx "‌")
  - 5280 Logic Cells (4-LUT + Carry + FF)
  - 128 KBit Dual-Port Block RAM
  - 1 MBit (128 KB) Single-Port RAM
  - PLL, Two SPI and two I2C hard IPs
  - Two internal oscillators (10 kHz and 48 MHz)
  - 8 DSPs (16x16 multiply + 32 bit accumulate)
  - 3x 24mA drive and 3x hard PWM IP
- QSPI-DDR-capable flash 128 MBit (16 MB)
  - We selected to use the Winbond [W25Q128JVSIM](http://www.winbond.com/resource-files/w25q128jv_dtr%20revc%2003272018%20plus.pdf "‌")
  - We want to enable projects that access the flash and we want to provide the highest flash access speed possible.
- [FT2232H](http://www.ftdichip.com/Support/Documents/DataSheets/ICs/DS_FT2232H.pdf "‌") interface (microUSB plug)
  - Programming compatible with iCEstick and HX8K board
    - works with [Dimond Programmer](http://www.latticesemi.com/programmer "‌") and [iceprog](https://github.com/cliffordwolf/icestorm/tree/master/iceprog "‌")
  - serial port compatible with iCEstick and HX8K breakout board
  - 12 MHz XTAL oscillator (shared with FPGA)
  - Solder jumpers to offer direct SRAM programming (like on HX8K breakout board)
- 39 I/O capable pins:
  - 4 pins for config (SDI, SDO, SCK, CSB)
    - Either loading config from the onboard FLASH chip or provided through the FTDI chip with direct SRAM config.
  - 2 extra GPIO pins for QSPI
    - Together with the config pins, allows storage of additional data in the FLASH chip, and high speed QSPI DDR access. For example [picosoc](https://github.com/cliffordwolf/picorv32/tree/master/picosoc "‌") firmware.
  - 3 PINs for RGB LED (pin header)
  - 2 LEDs (one on output-only PLL pin)
  - 1 Clock pin (on PLL GBIN)
  - 1 UART Rx Pin via FTDI
  - 1 UART Tx Pin via FTDI
  - 1 Push Button
  - 16 PINs on dual PMOD
  - 8 PINs on single PMOD / snap-off section
- Support for FTDI Async FIFO mode
  - We want to support FTDI Async mode via some (unpopulated by default) zero-ohm resistors
  - This shares 8 GPIOs with the single PMOD / snap-off section
  - This would also enable the use of full list of RS232 signals
  - BDATA[0] -- Tx on FTDI / Rx on FPGA (always connected, no zohm resistor required)
  - BDATA[1] -- Rx on FTDI / Tx on FPGA (always connected, no zohm resistor required)
  - BDATA[7:2] -- Shared with snap-off section (via zohm resistor footprint)
  - RX Full -- Shared with snap-off section (via zohm resistor footprint)
  - TX Empty -- Shared with snap-off section (via zohm resistor footprint)
  - Read -- Shared with LED 1 (via zohm resistor footprint, LED used as RX indicator)
  - Write -- Shared with LED 2 (via zohm resistor footprint, LED used as TX indicator)
  - WakeUp -- Shared with Push Button (via zohm resistor footprint)
  - This configuration uses the following pins when the jumpers are reconfigured:
    - The two on-board red and green LED pins
    - The on-board user button pin
    - Snap off the section of single PMOD pins
- Snap-off section (convertible to PMOD host / PMOD device)
  - 5 LEDs in a similar arrangement to iCEstick
  - 3 Push Buttons
- Other stuff
  - Status LEDs for Power and CDONE (Configuration DONE)
  - Header with supply rails: 5V, 3V3, 1V2, GND
  - Debug header for all 6 QSPI pins
  - Test points for UART Rx / Tx signals
  - Jumpers or zohm resistors on all rails for measuring currents
  - Four 3mm mounting holes on the main section and two more on the snap-off section
  - The two LEDs on the main section should be wired "active low" so they work well as indicator LEDs for FIFO read/write.
  - The five LEDs on the snap-off section should be wired "active high"
  - A zohm resistor for Bank 2 supply, so that the IO voltage can be changed. Use Bank 2 for one of the ports on the double PMOD.
  - There should be auxiliary 5V pin headers available for the PMODs. Some PMODs need either a higher voltage or need to regulate their own voltage from 5V.
- Unpopulated parts shipped with the board
  - 3x Host PMOD (2x for dual PMOD port, 1x for snap-off section)
  - 1x Device PMOD (for other side of snap-off section)
#### iCEBreaker Block Diagram
 ![](https://docs.icebreaker-fpga.org/assets/img/icebreaker/icebreaker-v1_0b-legend.jpg)

#### Pinouts
 ![](https://docs.icebreaker-fpga.org/assets/img/icebreaker/icebreaker-v1_0b-legend-jumpers.jpg)

### Resource
 - [iCE40 UltraPlus 5K](https://latticesemi.com/-/media/LatticeSemi/Documents/DataSheets/iCE/iCE40-UltraPlus-Family-Data-Sheet.ashx)
 - [iCEBreaker workshop Github](https://github.com/icebreaker-fpga/icebreaker-workshop)

### Projects ([github](https://github.com/icebreaker-fpga/icebreaker "‌"))

- [7-Segment Display PMOD](https://1bitsquared.de/products/pmod-7-segment-display "‌")
- [DIP Switch PMOD](https://1bitsquared.de/products/pmod-dip-switch "‌")
- [Digital Video Interface PMOD](https://1bitsquared.de/products/pmod-digital-video-interface "‌")
- [HyperRAM PMOD](https://1bitsquared.de/products/pmod-hyperram "‌")
- [RGB LED Panel Matrix Driver Pmod](https://1bitsquared.de/products/pmod-led-panel-driver "‌")[Gamepad and Audio Pmod](https://1bitsquared.de/products/pmod-gamepad-and-audio "‌")

---

## [**RealDigital Boolean**](https://www.realdigital.org/hardware/boolean "‌") 
(without BLE, **$84,** with BLE: **$97**): an educational FPGA platform explicitly designed for electrical and computer engineering students.

![1bfa8a56e075cdc92c0b03204c6c5618.png](https://www.realdigital.org/img/1bfa8a56e075cdc92c0b03204c6c5618.png)

### Features:

The board is centered on a Xilinx Spartan-7 FPGA (XC7S50) that can be configured into a virtually unlimited number of hardware circuits. The Spartan-7 FPGA includes:

- more than 8,000 FPGA slices, each containing four 6-input look-up tables and 8 flip-flops, equivalent to 52K logic cells;
- 120 DSP blocks, each with dual 24-bit adders, a 2’s complement multiplier, and a 48-bit accumulator;
- 337Kbytes of high-speed, dual-port RAM;
- Five clock management tiles that can generate a wide variety of clock signals from a single outside source.
- A 12-bit, 1MSPS analog-to-digital converter;
- And many other circuits and functions.

### [**Reference manual**](https://www.realdigital.org/doc/02013cd17602c8af749f00561f88ae21 "‌")

Digital Logic course, (by RealDigital): [https://www.realdigital.org/course/digital-logic-for-the-boolean-board](https://www.realdigital.org/course/digital-logic-for-the-boolean-board)

### Distributor:

from RealDigital store in US: https://www.realdigital.org/hardware/boolean

---
