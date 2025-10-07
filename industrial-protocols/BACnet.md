# BACnet overview
Building Automation Control Network.

## Protocol aspects
- Object oriented model where every BACnet device contains a device object that defines certain device information.
- Application services model, where services are formal requests that one BACnet device sends to another BACnet device to ask it to do something.
  - Object access (read, write, create, delete).
  - Device management (discover, time synchronization, initialize, backup and restore database).
  - Alarm and event (alarms and changes of state).
  - File transfer (trend data, program transfer).
  - Virtual terminal (human machine interface via prompts and menus).
- Extensive interoperability design.
  - Data Sharing.
  - Trending.
  - Scheduling.
  - Alarm & Event Management.
  - Device & Network Management.
- Mainly well known for HVAC applications, but can be applied for a multitude of building automation purposes.

## Security Weaknesses.
- No default authentication.
- No confidentiality.
- No integrity checks.
- Broad-cast based device discovery.

Security features exist via the BACnet/SC version:
- Authentication: TLS certificates.
- Confidentiality: TLS certificates.
- Integrity: TLS certificates.
However, BACnet/SC is unevenly implemented by different vendors(affecting interoperability).

## Main Purdue Levels
- 1 <-> 2: BACnet/IP.
- 2 <-> 3: BACnet/SC.

Ethernet is preferred in modern installations, but with legacy systems the above protocols may need to be adjusted.

## Example Usecases
- 
