# Chipset and Buses
___

**Lane**:
- Two serial wires that enable the sending and receiving of data simultaneously

___
## Motherboard communication chips

Two main chips controlling communication on a PC motherboard
1. **Northbridge**:
	- Also called Memory Controller  Hub (MCH)
	- High data transfer speed
	- **High Speed Graphics**
	- **Memory (RAM)**
2. **Southbridge**:
	- Also called I/O Controller Hub (ICH)
	- **Secondary controllers**
	- **Most input/output devices**
	- **Hard drives, USB, ethernet, etc.**

![[Pasted image 20241101145752.png]]

**Direct Media Interface** (**MDI**) connects each chip (also called **Internal Bus**).

___

## Buses


These two have different names but are basically the same, only other companies call them differently:
- **FRONT SIDE BUS (FSB)** -  Intel
- **HYPERTRANSPORT**        - AMD

- **FSB** is what allows **CPU** to communicate with Motherboard (**Northbridge**)
- **Memory bus** is where are the **RAM** is plugged in.
- **Expansion buses** are all the other buses that expand the capabilities of the motherboard.

___
# Expansion Buses and Storage Technology
___
## Expansion Buses

- **ISA**  - Industry Standard Architecture *OUTDATED*

- **AGP** - Accelerated Graphics Port *OUTDATED*
	-  Displays and Graphics mostly while PCIs were still slow

- **PCI** - Peripheral Component Interconnect (has it's own address)
	- PCIx - extended (32-bit)
	- PCIe - express
	- Mini-PCI - laptops, smaller computers

- **AMR & CMR** - Audio/Modem *OUTDATED*

- **PCMCIA** - Personal Computer Memory Card International Association (For laptops)

![[Pasted image 20241101151940.png]]

**PCIe** is so fast because it has up to 16 Serial lanes with 1GB/s each.

___
## Storage Technology

- **PATA / IDE** : (Integrated Drive Electronics -> **Parallel AT Attachment**)
	- 40-pin bus
	- Molex
	- Can only put in certain way
	- Red cord determines power source
	- Can hold 2 devices

- **SATA** - **Serial AT Attachment**:
	- Reads and Writes in Serial
	- Takes less space

___
# Input / Output Ports and Front Panel Connectors

# Older Ports

-  **PS/2** - <font color="#7030a0">Keyboard</font> and <font color="#00b050">Mouse</font>
-  **RJ45** - Ethernet 
-  **RJ11** - Phone / Modems
-  **Serial** (Gaming ports) - Joysticks:
	- 9-pin
	- 15-pin
-  **Parallel** (LPT) - Printers
-  **SVGA** - Graphics
	- 15-pin DB connector
	- 3 rows
-  **Audio 1/8'' Cluster** - Mic, speaker, line in

___
## Newer Ports

-  **USB**
-  **DVI** -  Digital Video (Monitor)
-  **HDMI** - (Television)
-  **Display Port** - same as DVI but used from a different competitor (Monitor) 
-  **eSATA** - External SATA
-  **RJ45** - Ethernet
-  **Audio 1/8'' Cluster** 
-  **Optical Audio** - Digital audio OUT

-  **Firewire** (IEEE-1394) -  Cameras / Camcorders
-  **SD / Multimedia Cards** - Mostly front-panel slots to insert your multimedia cards

___
# Adapters And Converters
___
## Introduction to Adapters and Converters

-  **Adapters** and **Converters** provide connection between two incompatible interfaces, making them interoperable.
-  An **Adapter** connects two incompatible interfaces without changing the form of the medium passing through it.
-  A Convertor not only connects two incompatible but also converts the form of medium passing through it.

___
## DVI to HDMI

-  **DVI  (Digital Visual Interface)** to **HDMI (High-Definition Multimedia Interface)** bidirectional  adapters allow you to do the following:
	- Connect a computer with a DVI port to a new monitor, an HDTV, or a projector with  an  HDMI port
	- Connect a monitor with a DVI port to a computer, a Blu-ray player, a TV box, or a game console with an HDMI port
	
	- DVI doesn't support audio when connecting to an HDMI port, so the audio has to be transferred using a separate cable.

___
## USB A to USB B

-  The USB A connector is the type-A connector, and the USB B connector is the type-B connector.
- The type-A connector has an elongated rectangular cross-section, whereas the type-B has a square-like cross-section.
- A USB cable may have a type-A and type-B connector on both ends allowing  for conversion between these connectors on the same cable.

___
## USB to Ethernet

- This adapter is useful when your computer doesn't have a dedicated Ethernet port, and you want to physically connect it  to a network using the USB port.
- For securities reasons

___
## DVI to VGA

-  A DVI-to-VGA converter converts a digital DVI output from your computer to a standard analog VGA output for CRT monitors.
-  DVI being digital, and VGA being analog, the adapter converts DVI output into analog VGA output.

___
## Thunderbolt to DVI

-  Thunderbolt technology provides a port that carries both DisplayPort and PCI Express data.
-  A Thunderbolt-to-DVI adapter allows you to connect an Apple Thunderbolt port to a DVI display device.
-  This adapter is compatible with Mini DisplayPort.

___
## PS/2 to USB

- The PS/2-to-USB adapters let you convert a PS2 keyboard and mouse port on your computer to a USB port.

___
## HDMI to VGA

-  The HDMI-to-VGA converter is an active device that allows you to convert a digital HDMI signal to an analog VGA signal.
-  In addition, the converter may also have a 3.5'' audio port for sending the audio from the converter to a device.
-  This converter is useful  when you want to connect from your laptop to an older projector or monitor.
- The converter is an active device because active processing is required to convert HD content for  an analog display.
- The converter is bus powered from the HDMI port so does not require an additional power source.

___
# Form  Factors
___

![[Pasted image 20241102080922.png]]

___
## ATX and Micro-ATX

-  **ATX** - Advanced technology extended
___
## ITX

- **Mini-ITX** - for HTPC (Home theatre with passive cooling)
- Nano-ITX - Set top boxes, small computers in cars, other stuff
- Pico-ITX - UMPC (Ultra mobile PC)

___
## BTX

-  **BTX** - Balance Technology Extended
	-  Uses a lot of energy and releases a lot of heat
	-  For servers because of how powerful

![[Pasted image 20241102081604.png]]

___
# BIOS
___

- **BIOS** - Basic Input Output System
	- It is the FIRST  thing that runs when you boot your PC
	- Identifies, tests, and initializes system components:
		- RAM
		- Storage (internal and external)
		- Optical Drives
		- CPU

___
## CMOS

- **Complementary Metal-Oxide Semiconductor**
	-   Stores  the contents of what the BIOS  finds
		- Type and  Speed  of  CPU
		- Drive Capacities
		- Date/Time
	- It is VOLATILE (Disappears)
		- When the power is off,  it loses it's content
		- Need a CMOS battery to maintain the information

___
## POST

- **Power On Self Test**
	- The First step in the boot Process
	- Passes errors on to the BIOS and User
	- Uses code numbers and Audio beeps
		- POST codes differ from vendor to vendor

___
## "FLASHING"  The BIOS

- Erasing and rewriting the BIOS firmware
- **Firmware** = Persistent memory and code stored in it
- Non-Volatile
- **Flashing** = the new firmware is electronically "flashed" onto the circuit
	- If you stop the process during flashing (lose power, etc.), your computer may not be bootable.

___
##  Configuring BIOS

- Time and Date (Kept current by the battery, so if it dies, date/time will reset)
- Boot device priority - Tells the BIOS to look in which order to try to boot up.
- BIOS Password - Once set, it is maintained by the battery.

___
## Wake-On-Lan

-  Allows the computer to be "woken up" through a network message
- LAN  - Local Area Network

___
## Monitoring

- BIOS Monitors several things,  including:
	- Temperature
	- Fan  Speeds
	- Intrusion Detected (not viruses or hacking, just opening the computer physically for old PCS)
	- Voltage
	- Clock
	- Bus Speed