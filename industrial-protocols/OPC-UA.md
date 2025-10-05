# OPC UA overview

## Protocol Aspects
- Non-proprietary/platform independent.
- Backwards compatible with OPC.
- Can choose between Pub/Sub and client/server models.
- Can be sent over MQTT instead of for example TCP or UDP.
- 

## Security Weaknesses/Strenghts.
- Strengths:
  - Application and user authorization.
  - Signed transfers.
  - Encrypted transfers.
  - Audit functionality.
  - User can choose which security mechanisms to activate.

## Purdue Levels
- 1-3

## Example Usecases
- M2M
- Machine to Cloud

#OPC does not represent a network protocol in the traditional sense, but rather a capability to support the interfacing and interconnection with disparate vendor technologies.  
#UA - platform independent service-oriented architecture  
#Another important UA feature is its ability to use structures and models, so data tags or points can be grouped and given context, making governance and maintenance easier.  
#The OPC server supports almost any ICS protocol imaginable, including Modbus, DNP3, ICCP, and Foundation Fieldbus.  
