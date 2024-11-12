[[CompTIA A+ Full Course for Beginners - Module 4 - Comparing Local Networking Hardware](https://www.youtube.com/watch?v=TxObqd7GU8c&list=PLc6LqxQFwub_rksUc1FnWB9rwO2rf7qoz&index=5)]

![[Pasted image 20241112190353.png]]

# Network Types
---
## Personal Area Network (PAN)

- One of the most common networks found
- Within arms each on table
- One of the smallest networks found
- Usually involves only 1 person in most cases
- Bluetooth, Infrared, NFC (Near field communication?)
---
## Local Area Network (LAN)

- Network generally in one building but could possibly extend to multiple buildings (up to 100 meters cable but can connect with wireless)
- Not just limited to desktop computers and laptop computers

---
## Wireless Local Area Network (WLAN)

- A Lan Network which is just wireless
- Uses 802.11 technologies [11 indicates it's wireless most often]
- Sometimes good to use in hard-to-reach areas in buildings
- Lots of flexibility
- Extends easy with additional access points
- Very good security

---
## Metropolitan Area Network (MAN)

- Usually larger than a Local Area Network (LAN)
- Usually smaller than a Wide Area Network (WAN)
- Usually multiple LAN's in multiple buildings

---
## Wide Area Network (WAN)

- Usually used to connect networks over great distances
- Generally multiple MAN networks connected together
- Could possibly extend over multiple countries
- Usually way slower than LAN


---
# Compare Networking Hardware
---
## Network Interface Cards

- Commonly known as NIC
- Desktop Computers normally come out with only Ethernet NIC
- Laptops computers normally come out with both a Ethernet and wireless NIC

---
## Hubs

- It's a dumb device
- Sends signals out of all ports (means can't send private information to a connected network)
- Performance reduced by contention (More devices = slower)
- Half-duplex 10/100 Mbps Ethernet Only

---
## Switches

- Only sends data to intended recipient 
- Switch forwards traffic to a specific destination port by learning MAC addresses [MAC  addresses are unique only to a specific device]
- Allows each port to operate at full-duplex and full speed
- Required for Gigabit and Ethernet

### Unmanaged and Managed Switches

- Unmanaged Switch
	- Works without configuration

- Managed Switch
	- Configuration interface
	- Addition functionality
	- Web or command-line interface [Like a router]

---
## Power over Ethernet

- Usually known as PoE
- Sends Power over an Ethernet Cable (Usually where it's difficult to provide power to an access point)
- Commonly used in areas where power is not easily accessible
- Commonly used on Access Points (AP's) and VoIP Phones (Mostly companies that want to look professional without plugging into the socket)
- Can be something like a small PoE box
- Can be a full blown PoE Switch

---
# Network Cable Types
---
##  Unshielded Twisted Pair (UTP)

![[Pasted image 20241112192820.png]]

- Copper wire carrying electrical signals
- Four balanced wire pairs
- Twisted one to another is to reduce interference 
- Signal attenuation limits maximum to 100m (In reality 80-95 meters in practice)

---
## Shielded Twisted Pair (STP)

![[Pasted image 20241112193205.png]]

- Screening or shielding as extra protection against interference
- Screened cable has one outer foil shield around all pairs
- Fully shielded cabling has a braided outer screen and foiled-shielded pairs
- Extra costs

---
## CAT Standards

- CAT - Category
	![[Pasted image 20241112193407.png]]

- POTS - Plain Old Telephone System (Landline , CAT 3)

---
## Copper Cabling Installation Tools

- Cable Crimper
- Punchdown Tool

---
## Copper Cabling Testing Tools

- Cable Tester
- Toner Probe

---
## Optical Cabling

![[Pasted image 20241112200225.png]]

- Ethernet cables are not limited to LAN cables, they can be other types like Optical Cables
- Fiber (Glass) Cables
- Light gets sent through the Fiber Cable

- Fiber Optic Cable Types
	- Single-mode fiber (Over long, great distances)
	- Multi-mode fiber (Short distances, mostly inside)

- Connector Types
	- Straight  Tip (ST)
	- Subscriber (SC)
	- Lucent connector (LC)

---
## Coaxile Cabling

![[Pasted image 20241112200209.png]]
- Coaxile Cabling without F-Connector

- Uses
	- Used as Antenna behind TV (OLD analog signals)
	- Plug into a machine for digital signals

- Coaxile F-Connector

---
# Wireless Networking Types
---

## Access Points

- IEEE 802.11 [ .11 - Wireless]
	- 802.11a [Commonly used Wi-Fi 5GHz]
	- 802.11b [Bluetooth 2.4GHz]
	- 802.11g [Most commonly used Wi-Fi but with another frequency 2.4Ghz]
	- 802.11n [long range communication, must have line of sight 2.4Ghz or 5Ghz]
	- 802.11ac
	- 802.11ax [2021 released]

- Since we most commonly use 802.11g with 2.4GHz frequency, there may be a lot of interference, near things such as:
	- Port less phones (Not cellphones) can interfere
	- Microwaves
	- Baby monitors

	- IEEE 802.11 AP simply connects to the network and broadcasts it wirelessly
	- Can bridge with wired networks via switch
	- Interconnects wireless clients (stations)