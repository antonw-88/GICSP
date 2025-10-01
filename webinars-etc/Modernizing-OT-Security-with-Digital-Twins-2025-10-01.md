# Modernizing OT Security: How Frenos Uses Digital Twin Technology, AI and Threat Emulation to Transform Security Posture & Compliance
https://www.sans.org/webcasts/modernizing-ot-security-how-frenos-uses-digital-twin-technology-ai-threat-emulation-transform-security-posture-compliance
2025-10-01

## Intro discussions

### Key business decision drivers for security decisions
- Supplier<->Customer relationships are long term in the OT space; 20-30-40 years. Can't just change suppliers in same way as in IT.
- Regulations are sector and location specific. The location itself will demand a certain structural implementation(NIS2; NERC CIP; etc).
- Extensive regulations within the OT cybersec space is something relatively new, and will transform the global industry over the coming years.
- Regulations are created in response to specific events. This may leave a gap for events that have not yet occurred.

### Risk assessment scans
A paper based assessment is less intrusive, but manual labor intensive.
An active assessment applies vendor tools and scripts. Automates polling of data, but requires careful considerations.
Both include, for example:
- Network topology review.
- Port and service identification.
- Vulnerability review of assets; rulesets; patch level; default account; SNMP; etc.
- Analysis of wireless network.

When conducting automated testing, this becomes tricky due to the risk of the production environment. The common way to manage this, is to use test environments. Then after the test environment, the secondary control center can be isolated, the scans can be run, and the repeat on the primary control center. However, for many parts of the environment there will be no full redundancy; requiring reliance on test environments.  

### Digital Twins
  
Digital twins for CyberSec purposes provides a new alternative for risk assessment scans:
- A data model that replicates the actual environment.
- Merges all the CyberSec data into this model.
- Instead of scanning the actual environment, the digital twin can be scanned. If a new patch is available, this can be identified quickly and without potential disruptions.

