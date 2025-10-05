# OPC UA overview
Focuses on integration/monitoring/data-exchange of various OT related systems, not on the actual real-time(RT) control related to the physical processes. IT does not represent a network protocol in the traditional sense, but rather a capability to support the interfacing and interconnection with disparate vendor technologies.

## Protocol Aspects
- Non-proprietary/platform independent.
- Non-deterministic.
- Backwards compatible with OPC(the classic version is insecure).
- Service-oriented and object-based.
- Can choose between Pub/Sub and client/server models.
- Server translates from deterministic protocol data format into OPC UA data format; can thus standardize data exchange.
- Can be sent over MQTT instead of for example TCP or UDP.
- Encoded in binary/JSON/XML.
- Data tags or points can be grouped and given context, making governance and maintenance easier.  

## Security Weaknesses/Strenghts.
- Strengths:
  - Application and user authentication/authorization.
  - Signed transfers.
  - Encrypted transfers.
  - Audit functionality.
  - User can choose which security mechanisms to activate. Since OPC UA often bridges different Purdue levels, a correct configuration is important.
- Weaknesses:
  - Poorly secured OPC UA servers.

## Common Purdue Levels
- Can be used in 2-5. For 4-5 it generally applies the Pub/Sub model.

## Example Usecases
- M2M
- Machine to Cloud
