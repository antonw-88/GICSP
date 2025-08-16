###Field controllers - omvandlar elektriska signaler till digitala, och visavi.  
#IED - power system controller -> circuit breakers, capacitors, transformers, etc. Can be/include: protective relaying devices, load tap changer controllers, circuit breaker controllers, capacitor bank switches, re-closer controllers, and voltage regulators.  
#PLC - automates processes/machine function/  
#PAC - any type of automation controller that incorporates higher-level instructions. PAC combine the best features of RTU, PLC, and Distributed Control System (DCS) controllers into a universal controller for use across multiple sectors. The onboard processor and memory, along with the network capabilities, make this device particularly interesting from a cybersecurity perspective.  
#RTU(remote terminal/telemetry unit) - interfaces fysiska enheter till en DCS eller SCADA. Telemetri->master system. Control messages->rtu. Long distance comms. Can be used as data concentrator and protocol converter. Controls geographically dispersed/very large facilities.  
#DCS - DCS has each machine or group of machines controlled by a dedicated controller. These distributed individual automatic controllers are connected to the field devices.  
#PCS - The main difference between PCS and SCADA system is that a PCS communicates with the field controllers using a plant network, while SCADA systems traditionally use serial communications and remote networks for the same task.  
  
###SCADA:  
#a computer system  for gathering and analyzing real time data. Often over large areas.  
#Möjliggör flexibilitet, då enheter från olika vendors kan integreras om de använder samma protokoll(eller kan översättas).  
#SCADA is used to describe an ICS that monitors and controls transmission and distribution facilities  
#Event driven – not scanned regularly, waits for an event to trigger actions  
