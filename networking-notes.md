# Computer Networking Notes 🌐

##  What Is a Computer Network?

A computer network is a group of interconnected devices that communicate and share data and resources with each other.

**Examples:**
- Computers connected in an office.
- Mobile phones connected to Wi-Fi.
- Computers connected in a college laboratory.

##  Methods of Connecting Devices

There are two main methods of connecting devices in a network:

### A. Wired Connection

A wired connection uses physical cables to transfer data between devices.

**Types of wired cables:**

** Coaxial Cable**
- Contains a central conductor surrounded by insulation and shielding.
- Used in cable television and some internet connections.

** Twisted-Pair Cable**
- Consists of pairs of insulated copper wires twisted together.
- Commonly used in Ethernet networks.
- Types:
  - UTP (Unshielded Twisted Pair)
  - STP (Shielded Twisted Pair)

** Optical Fibre Cable**
- Transfers data using pulses of light.
- Offers high speed and supports long-distance communication.
- Commonly used in internet backbones and fibre broadband.

### B. Wireless Connection

A wireless connection transfers data without requiring a physical cable between communicating devices.

**Examples:**
- Wi-Fi
- Bluetooth
- Cellular networks

##  Types of Computer Networks

###  PAN — Personal Area Network

A network that connects devices within a very short range around an individual.

**Example:** Connecting wireless headphones to a mobile phone using Bluetooth.

###  LAN — Local Area Network

A network that connects devices within a limited geographical area.

**Example:** A network in a home, office, or computer laboratory.

###  MAN — Metropolitan Area Network

A network that connects devices or smaller networks across a city or metropolitan area.

**Example:** A network connecting multiple offices across a city.

###  WAN — Wide Area Network

A network that covers a large geographical area, such as multiple cities or countries.

**Example:** The Internet is the most well-known example of a global network of interconnected networks.

##  OSI Model

OSI stands for **Open Systems Interconnection**.

The OSI model is a conceptual, seven-layer model that helps explain how data is communicated between networked systems.

### The Seven Layers of the OSI Model

| Layer | Name | Main Function |
|---|---|---|
| 7 | Application | Provides network services to applications. |
| 6 | Presentation | Handles data formatting, encryption, and compression. |
| 5 | Session | Establishes, manages, and terminates communication sessions. |
| 4 | Transport | Supports end-to-end data delivery and reliability. |
| 3 | Network | Handles logical addressing and routing between networks. |
| 2 | Data Link | Handles local network delivery using frames and MAC addresses. |
| 1 | Physical | Transmits raw bits through physical media or signals. |

### OSI Layers: Easy Way to Remember

From Layer 7 to Layer 1:

**A**ll **P**eople **S**eem **T**o **N**eed **D**ata **P**rocessing.

- Application
- Presentation
- Session
- Transport
- Network
- Data Link
- Physical

##  Quick Revision

- A computer network allows devices to communicate and share resources.
- Wired connections use physical cables.
- Wireless connections use radio waves or other wireless signals.
- Coaxial, twisted-pair, and optical fibre are types of wired media.
- PAN, LAN, MAN, and WAN classify networks by their geographical coverage.
- The OSI model contains seven layers and helps explain network communication.

  ## TCP/IP Model

## Full Form: Transmission Control Protocol / Internet Protocol

The TCP/IP model describes how data is transmitted between devices over a network and the internet.

## Four Layers of the TCP/IP Model

## Application Layer

Provides network services to applications.


## Transport Layer

Provides communication between applications on different devices.


## Internet Layer

Handles logical addressing and routing packets between networks.


## Network Access Layer

Handles communication over the local network, including framing and physical transmission.


## TCP and UDP

# TCP — Transmission Control Protocol

TCP is a connection-oriented transport protocol that provides reliable and ordered data delivery.


## Examples of applications that use TCP:

HTTP

HTTPS

FTP

SMTP

## UDP — User Datagram Protocol

UDP is a connectionless transport protocol that sends data without guaranteeing delivery or order.


## Examples of protocols and services that can use UDP:

DNS

DHCP

TFTP

NTP


##  Addresses in Computer Networks

An address in a computer network helps identify a device or network interface so that data can be delivered to the correct destination.

There are two important types of addresses:

1. Logical Address
2. Physical Address

### Logical Address

A logical address is used to identify a device at the network layer.

**Example:** IP address

### Physical Address

A physical address is generally used to identify a network interface on a local network.

**Example:** MAC address

| Logical Address | Physical Address |
|---|---|
| Usually an IP address | Usually a MAC address |
| Used for communication across networks | Used for communication on a local network |
| IPv4 or IPv6 | Commonly 48 bits |
| Can change depending on network configuration | Can be randomized or changed in software |


##  IP Address

- IP stands for **Internet Protocol**.

- An IP address is a logical address used to identify a network interface and help route data between networks.

There are two main versions of IP:

- IPv4
- IPv6


##  IPv4 — Internet Protocol Version 4

IPv4 is the older and still widely used version of the Internet Protocol.

### Features of IPv4

- It uses **32 bits**.
- It is written in dotted-decimal notation.
- It contains four groups.
- Each group contains 8 bits.



## IPv6 — Internet Protocol Version 6

IPv6 is the newer version of the Internet Protocol, designed in part to provide a much larger address space than IPv4.

### Features of IPv6

- It uses **128 bits**.
- It normally contains eight groups.
- Each group represents 16 bits.


## Binary Number System

- Computers understand and process information using binary language. The binary number system uses only two digits:

- `0`
- `1`

Computers represent numbers and other types of data using binary at the hardware level.

### Example: Convert Decimal 10 into Binary

The binary place values are powers of 2.

| Power | Calculation | Value |
|---|---|---:|
| 2⁷ | 2 × 2 × 2 × 2 × 2 × 2 × 2 | 128 |
| 2⁶ | 2 × 2 × 2 × 2 × 2 × 2 | 64 |
| 2⁵ | 2 × 2 × 2 × 2 × 2 | 32 |
| 2⁴ | 2 × 2 × 2 × 2 | 16 |
| 2³ | 2 × 2 × 2 | 8 |
| 2² | 2 × 2 | 4 |
| 2¹ | 2 | 2 |
| 2⁰ | 1 | 1 |

To convert decimal `10` into binary, select the place values that add up to 10.

- 8 fits into 10 → `1`
- 4 does not fit into the remaining 2 → `0`
- 2 fits into the remaining 2 → `1`
- 1 is not needed → `0`

Therefore:

**Decimal 10 = Binary 1010**

In 8-bit form:

`00001010`

### Binary Place Values

| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
|---:|---:|---:|---:|---:|---:|---:|---:|
| 0 | 0 | 0 | 0 | 1 | 0 | 1 | 0 |

This represents the decimal number 10.

---

##  Cisco Packet Tracer

- Cisco Packet Tracer is a network simulation tool used to create, configure, and test network devices virtually.



##  Router Configuration Using CLI

- The following commands configure a router interface with an IP address and subnet mask.

### Commands

- enable
- configure terminal
- interface fa0/0
- ip address 192.168.1.1 255.255.255.0
- no shutdown

  ### IP Address Details

- IP Address: `192.168.1.1`
- Subnet Mask: `255.255.255.0`
- Network Address: `192.168.1.0`
- Default Gateway for devices on this LAN: `192.168.1.1` (when this router interface is their gateway)

---

##  Testing the Local Area Network

After configuring the router and connected devices, use the `ping` command to test connectivity.

### Example

ping 192.168.1.1


This tests connectivity to the device with IP address `192.168.1.1`.

To test communication between two PCs, ping the destination PC's IP address from the source PC's command prompt.





## Learning Goal 🎯

My goal is to strengthen my networking fundamentals and understand how devices communicate, how data travels, and how networks support cybersecurity.


**Learning today to build stronger skills for tomorrow! 🚀**
