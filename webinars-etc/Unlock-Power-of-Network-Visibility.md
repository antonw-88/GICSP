# Unlock the Power of Network Visibility in Industrial Environments
https://www.sans.org/webcasts/unlock-power-network-visibility-industrial-environments  

## INTRO
- Technology trends in ICS network visibility: 
  - AI - low contemporary usage in ICS/OT(10% but growing).
  - Current state of AI should not make decisions for the environment.
  - Cloud service usage is growing quite rapidly. Historians/HMI etc.
  - How do attackers get in -> 
  - Only 56% of orgs have a dedicated ICS/OT IR plan.
  - Approx 50% of compromises move from IT networks.
  - External connections are the heavily main reason for initial vectors.
  - Segmentation very important for supporting qualitative IR.

- The top 5 that orgs are budgeting for:
  - Defensible architecture -> important for point 2 as well.
  - Visibility and monitoringh
  - IR plan etc -> 
  - Secure remote access
  - Risk based vuln mgmt

## MAIN TOPIC - ICS VISIBILITY AND MONITORING BENEFITS

###Threat detection
#Core to have DPI to get threat detection capabilities. For example see modbus codes etc.
#Lateral movement between commonly targeted systems.
#How to idenfity use of LotL techniques.

###Industrial incident response
#PCAP, triage and forensic analysis.

###Safe vuln mgmt
#asset firmware, asset registry. Asset context important.

###Control System and OT asset inventory

###Troubleshooting and Root Cause Analysis - network monitoring is not only security relevant.
#ICS-protocol aware. Understands function codes etc.

###North-South often lacks ICS/OT insights.
#beaconing out of operations and malicious domains.
#identify cross site traffic.

###East-west:
#Most of comms between supervisory and control happen here.
#The actual OT layer obviously will contain the most relevant data to be analyzed.
#Find adversary lateral movement and OT system manipulation.
#Use both, but start with east-west if has to choose.
#Orgs sometimes start with north-south, and lose steam and skip east-west.

###VISIBILITY CONSIDERATIONS:
#Span -> SPAN already available; no outage required; risk-based; phased approach; 
#TAP -> outage; potential SPoF; supposed to keep letting traffic through it even if fails; extra cost.

Get the visibility implemented during the design phase -> XF team communication for this.

###ICS visibility top takeaways:
1. Allows to ensure defensible architecture.
2. Supports IR.
3. Manage remote access securely.

ICS515
