## Modbus and Modbus TCP/IP overview

### Protocol aspects
- Application level protocol.
- Port 502 as default.
- Low cost development.
- Minimum hardware requirement to support.
- Master/slave(client/server) structure:
  - Only client can initiate transactions(queries).
  - Server responds to request, or takes action as ordered.
  - Client can address single server, or broadcast to all.
  - Servers return response to individual queries, but not to broadcast queries.
  - Client query consists of: server/broadcast address; function code; data; error checking field.
  - Server response consists of: client address; field confirming function; return data; error checking field. In case of error, server returns an exception.
  - TCP/IP version is simply Modbus with a TCP/IP wrapper(reliability and routing enhancements) with the address and error checksum removed(this functionality exists in the Modbus Application Protocol Header(MBAP)).
- Communicates with up to 247 devices
- Uses standard TCP/IP protocols
- Unlike most other protocols, however, Modbus is used for both command and control and device level communications.
- Multiple versions: ASCII/RS485/Binary/TCP+IP
- no authentication or authorization is required to communicate with a Modbus device. The default port that Modbus/TCP uses is 502.
- CRC checks  

### Common usecases
