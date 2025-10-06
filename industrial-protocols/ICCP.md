# Inter Control Center Communications Protocol(ICCP) overview
Intended to provide control centers with a means to exchange SupervisoryControlAndDataAcquisition(SCADA)/EnergyManagementSystem(EMS) data between themselves. This includes control centers from different providers that need to coordinate with each other to ensure the stability of the grid. 

## Protocol aspects
- OSI layers 5(ACSE)/6(ASN.1)/7(TASE.2)
- Dynamically employed API structure depending on stakeholder requirements; not objectively specified.
- Server/Client based. Control Center A(client) requests data from Control Center B(server). Or vice-versa.
  - CC A can make a one time request from CC B, or a periodic transfer can be established, so that updates are received according to the configuration.
- One-to-many structure. CC A <-> CC B + CC C + CC D, etc.
- ICCP traffic can be organized in QoS as high/low priority.
- ICCP services are provided via ICCP server objects.
  - ICCP operation: client-initiated request and followed by server response.
  - ICCP action: server-initiated; a report to the client that for example a breaker was tripped, or some other pre-specified data-point.
- CCs are interconnected via "associations". Three different operations for association objects exist.
  - Associate: client establishes an association with server.
  - Conclude: client or server terminates the association in an orderly fashion.
  - Abort: client or server terminates association when there are failures in the underlying communications mechanisms.
  - No actions defined for association objects.   

## Security Considerations.
- Authentication via the "Associate" operation.
- No confidentiality.
- No authorization.

## Purdue Levels
- Core level is 3.
- Transfers over CC A's 3.5 < WAN > CC B's 3.5.
- May interconnect with 4 & 5 for business data and overview related reasons, but not for control related reasons. For example sending data to an extra historian. 

## Example Usecases
- 

It is designed specifically for real-time data exchange between ISO (Independent System Operator) control centers, power pools, regional control centers, transmission utilities, distribution utilities, and generation facilities over LAN and WAN.  
Clear text, but secure ICCP exists.  
