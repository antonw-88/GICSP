# Modbus and Modbus TCP/IP overview

## Protocol aspects
- Application level protocol designed for interoperability.
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
  - TCP/IP version is simply Modbus with the address and error checksum removed, and then added to the the Modbus Application Protocol Header(MBAP).
  - MBAP is embedded into the data field of a TCP frame("packet").
- Communicates with up to 247 devices
- Multiple versions: ASCII/RS485/Binary/TCP+IP

## Security Weaknesses.
- No authentication.
- No authorization.
- No confidentiality.
- Only basic CRC error detection against unintentional effects. No cryptographic integrity checking.
- No replay protection.

In summary: if an attacker reaches into a Modbus network segment, it will have full visibility and extensive ability to affect the process.  

## Purdue Levels
- Modbus is used for both command and control and device level communications.

## Example Usecases
