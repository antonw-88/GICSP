# Modernizing OT Security: How Frenos Uses Digital Twin Technology, AI and Threat Emulation to Transform Security Posture & Compliance
https://www.sans.org/webcasts/modernizing-ot-security-how-frenos-uses-digital-twin-technology-ai-threat-emulation-transform-security-posture-compliance  
2025-10-01

## Intro discussions

### Key business decision drivers for OT security decisions
- Supplier<->Customer relationships are long term in the OT space; 20-30-40 years. Can't just change suppliers in same way as in IT.
- Regulations are sector and location specific. The location itself will demand a certain structural implementation(NIS2; NERC CIP; etc).
- Extensive regulations within the OT cybersec space is something relatively new, and will transform the global industry over the coming years.
- Regulations are created in response to specific events. This may leave a gap for events that have not yet occurred.
- Safety, reliability and cost, are the main drivers for efficiency improvements within critical infrastructure.
- Consistency, repeatibility and cost, are the main driver for efficiency improvements within automation.

### Risk assessment scans
A paper based assessment is less intrusive, but manual labor intensive.  
An active assessment applies vendor tools and scripts. Automates polling of data, but requires careful considerations.
Both include, for example:
- Network topology review.
- Port and service identification.
- Vulnerability review of assets; rulesets; patch level; default account; SNMP; etc.
- Analysis of wireless network.

When conducting automated testing, this becomes tricky due to the risk of the production environment. The common way to manage this, is to use test environments. Then after the test environment, the secondary control center can be isolated, the scans can be run; then repeat on the primary control center. However, for many parts of the environment there will be no full redundancy; requiring reliance on test environments.  

### Vulnerability mitigation
- Environments contain legacy stuff, mix of technologies, are often very large; just trying to identify vulnerabilities is difficult.
- An asset inventory to scan for vulnerabilites is vital, but further consideration is necessary; which assets to prioritize for patching etc.
- A test environment is not a luxury that everyone can afford.
- Standard vulnerability plans sometimes only focus on the business critical assets, but these can often be reached via low or medium priority assets.
- Consider potential circumventory defensive mechanisms. Is there somewhere earlier in the attack path that the attack could be stopped.
- Consider downtime cost of patch, and potential for service failure due to patching. Risk assessment of patch also costs time.
- Quantify the cost relative to value for defense; can that vulnerability even be exploited?
- System modeling is a long journey. Need to identify and analyze device types; vendors; various environments. The network is the biggest lever and frames almost everything else related to the CyberSec posture.
- Focus on transition points in the system, where an attacker can enter new areas of the system or gather extensive data from.
- Ensure a structured method for analyzing assets; allows for more targeted and efficient efforts.
- How is the environment segmented(that the vulnerable asset exists within). Can we build mitigation around it instead(for example with highly specific firewall or IPS rules).

### Priortized actions for vulnerability management
- Which threat-actors use techniques that exploit our vulnerabilities; how do these actors behave.
- Which mitigations are most cost effective.
- Ensure that mitigatory techniques increases defenses in a measurable manner.
- Focus patching efforts to the most vital points; both specific and transition oriented.   

## Digital Twins

Digital twins may be used in ICS environments for testing code changes and training operators. However, digital twins for CyberSec purposes provides a new alternative for risk assessment scans:
- A data model that replicates the actual environment.
- Merges all the CyberSec relevant data into this model. Data can be merged from other digital twins.
- Instead of scanning the actual environment, the digital twin can be scanned. If for example a new patch is available, this can be identified quickly and without potential disruptions.
- Can find new TTPs, so that a new risk assessment can be made for that asset.

Likely early adopters of digital twins:
- Entities that are required due to regulatory demands.
- CyberSec consulting firms and service providers.
  - How do we drive consistency of solutions regardless of specific assets.
  - What kind of methodology.
  - How to reduce the risk for all the stakeholders(including oneself) regardless of environments.
- CyberSec insurance industry, will help identify if the client is required to implement digital twins 

## Seminar main takeaways:
1. _What is our crown jewel(s)_ and move from there to identify the possible attack paths.
2. Conduct targeted and effective risk assessments. Don't just trash around and risk damaging stuff.
3. Narrow scope of analysis doesn't work, because it's not how an attacker approaches the environment.
4. Automated scanning tools are headed towards AI agents giving recommendations on risks and mitigations.
5. Document everything and apply lessons learned.
