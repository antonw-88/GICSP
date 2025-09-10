# Unlock the Power of Network Visibility in Industrial Environments
https://www.sans.org/webcasts/unlock-power-network-visibility-industrial-environments
2025-09-10

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

## ICS VISIBILITY AND MONITORING MAIN TOPIC

- Threat detection
  - Of core importance to have DPI to get threat detection capabilities. For example see modbus codes etc.
  - Lateral movement between commonly targeted systems can be monitored.
  - Can helpt in idenfityng malicious use of LotL techniques.
  - PCAPs can be gathered and analyzed for forensics etc.

- North-South visibility:
  - Often lacks ICS/OT insights.
  - Identifies beaconing out of operations and malicious domains.
  - Identifies cross site traffic.

- East-West visibility:
  - Most of comms between supervisory and control happen here.
  - The actual OT layer obviously will contain the most relevant data to be analyzed.
  - Find adversary lateral movement and OT system manipulation.
  - Use both, but start with east-west if has to choose.
  - Orgs sometimes start with north-south, and lose steam and skip east-west.

- SPAN vs TAP Considerations:
  - Span -> SPAN already available on modern swtiches; no outage required; risk-based and phased approach; 
  - TAP -> requires outage; potential SPoF, but supposed to keep letting traffic through it even if fails; extra cost.

## ICS visibility main takeaways:
1. Visibilty allows one to ensure that an architecture is adequately defendable.
2. Supports Incident Response.
3. Troubleshooting and Root Cause Analysis - network monitoring is not only security relevant, and this can help when arguing for the implementation of it(don't focus only on the direct security aspects).
4. Allows management of remote access securely.
5. Get the visibility implemented during the design phase -> XF team communication for this.
6. Control System and OT asset inventory, witch complementing infrastructure context awareness, is very important.
