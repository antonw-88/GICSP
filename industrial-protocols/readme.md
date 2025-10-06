# Commonly Used Industrial Protocols
The goal of this section is to understand common industrial protocols. This understanding includes: 
- Name.
- OSI layer.*   
- Standard ports.
- Conceptual protocol structure.
- Security weaknesses.
- Related purdue level(s).
- Example use-cases.
- The goal is not to be able to configure and pratically implement the protocol.  

*The layer(s) specified are the ones that the protocol itself controls. ICCP for example has direct control over 5-7, and relies on supporting protocols for handling the 1-4 mechanics.  
_Note: for someone without an IT background, reading up on the OSI-model and related topics is seemingly necessary._

## Commonalities between Industrial Protocols
While there exist OT related protocols that prioritize other values, a core value of industrial protocols that handle the physical processes themselves is **determinism**. This guarantees that a packet is sent/received in a finite and predictable amount of time. This relates to how, instead of the CIA model commonly used for IT, OT applies AIC. The **availability** requirement overrides the need for confidentiality, to ensure low-latency control; encryption adds overhead. Depending on where in the Purdue model that the protocol in a certain scenario is operating, considerations can be made for applying encryption(for example between two control centers exchanging supervisory data). The closer to the control of the physical process that one gets, the less focus on standard IT security and the more focus on OT safety. While determinism is a common goal for industrial protocols, they may apply different techniques in order to achieve it. The level of determinism required may also vary(see for example Profinet IR vs Profinet RT). Determinism is of vital importance to ensure process quality, and most importantly **safety**. Safety within ICS refers to the physical process remaining under strict control, to avoid the risk of the physical process having unintended real-world consequences. Such consequences may include a robot's movement hurting a human being; an electrical overload resulting in a fire; a nuclear reactor entering an unstable state. In addition to industrial protocols being designed to support safety, isolated [Safety Instrumented Systems(SIS)](https://github.com/antonw-88/GICSP/tree/main/Safety-Instrumented-Systems-and-Functions) serve as backup systems for safely shutting down physical processes.  

Traditional Ethernet was non-deterministic, but modern versions support deterministic behaviour(referred to as Switched Ethernet). For more on this topic, see the Modbus whitepaper(p.6-7).

![OT-IT-protocols-SHIV-KATARIA](https://github.com/user-attachments/assets/4e5cf9f2-d675-43a5-a1aa-eb569b722056)  
_OSI Layer for IT and OT Protocols - Shiv Kataria_

## Mike Holcomb: Getting Started with Industrial ICS/OT Cyber Security
- [Part 3](https://www.youtube.com/watch?v=WReeJDw-AV4&list=PLOSJSv0hbPZAlINIh1HcB0L8AZcSPc80g&index=3).

## Protocol Specific References:
Note that some of the protocol links will download/open the PDF directly. The summaries will forward you to the respective summary located in this repo.
- [Fieldbus](https://www.isa.org/getmedia/ec938d63-ccd5-4022-9a90-2baf5a616d34/Fieldbus-for-Process-Control_Berge_Chapter1.pdf) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/Fieldbus.md).
- [Profinet](https://us.profinet.com/resources/white-papers/) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/Profinet.md).
- [Modbus](https://www.acromag.com/wp-content/uploads/2019/08/White-Paper-Introduction-to-ModbusTCP_765B-.pdf) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/ModBus.md).
- [DNP3](https://www.acectrl.com/white-papers/dnp3/) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/DNP3.md).
- [ICCP](https://scadahacker.com/library/Documents/ICS_Vulnerabilities/EPRI%20-%20ICCP%20Protocol%20-%20Threats%20to%20Data%20Security%20and%20Potential%20Solutions.pdf) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/ICCP.md).
- [OPC UA](https://opcfoundation.org/wp-content/uploads/2023/05/OPC-UA-Interoperability-For-Industrie4-and-IoT-EN.pdf) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/OPC-UA.md).
- [IEC 61850](https://www.se.com/ww/en/tools/npag-online/pdf/D3-IEC_61850_and_Applications.pdf) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/IEC-61850.md).
- [IEC 60870-5-104](https://library.e.abb.com/public/c86995f2d7c54b7da2d9f8a30276f58a/REX640_iec104prot_2NGA000223_ENb.pdf?x-sign=Hq7DkYPcA+Y4nmjLgKMS7XxVP0EWcfqBlvuQSF7eWGt1eZT5kUkCUhLoiosCeEqm) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/IEC-60870-5-104.md).
- [BACnet](https://www.ccontrols.com/pdf/BACnetIntroduction.pdf) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/BACnet.md).
- [Ethernet/IP](https://literature.rockwellautomation.com/idc/groups/literature/documents/wp/enet-wp001_-en-p.pdf) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/Ethernet-IP.md).
- [EtherCAT](https://www.ethercat.org/download/documents/Whitepaper_EtherCAT_and_TSN.pdf) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/EtherCAT.md).
- [Profibus DP](https://www.profibus.com/fileadmin/media/downloadsection/PROFIBUS_Systembeschreibung_ENG_web.pdf) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/Profibus.md).
- [MQTT](https://mqtt.org/getting-started/) and [summary](https://github.com/antonw-88/GICSP/blob/main/industrial-protocols/MQTT.md).

## Core concepts mentioned in the SANS course syllabus:
_The note "chapter" refers to the "Practical Industrial Cyber Security" book._ 
- Ethernet and TCP/IP  -> chapter 2
- Ethernet Concepts  -> chapter 2
- TCP/IP Concepts  -> chapter 2
- Network Hardening -> Chapter 4, p.189.
- ICS Protocols over TCP/IP  -> chapter 2
- Wireshark and ICS Protocols  -> chapter 2
- Attacks on Networks -> chapter 3
- Enforcement Zone Devices -> chapter 3
- Firewalls and NextGen Firewalls -> chapter 3
- Modern Data Diodes -> chapter 3
- NIDS/NIPS and Netflow -> chapter 3
- Sniffing, DoS, Masquerading, Rogue AP -> Chapter 5 
- USB Scanning and Honeypots
- Understanding Basic Cryptography -> Chapter 5
- Crypto Keys -> Chapter 5
- Encryption, Hashing, and Signatures -> chapter 3
- Secure ICS Network Architectures - Defense-in-depth: 800-82 p.3
- Fieldbus Protocol Families -> chapter 2
- Remote Access  -> chapter 3
- Identify vulnerabilities in Modbus, DNP3, OPC, Ethernet/IP etc -> [See the lab section](https://github.com/antonw-88/GICSP/tree/main/labs).
- OSI model -> Modbus whitepaper(p.8).
