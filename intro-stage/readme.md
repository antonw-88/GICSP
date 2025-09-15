For the initial stage, many recommended the CISA VLP learning platform's CSI modules and courses. While these often didn't go in-depth on concepts etc, 
they did provide a good overview of many concepts, terms. The platform's contents also described well the reasons for many contemporary ICS security issues etc.  
Additionally, the courses contained multiple labs, and provided a good understanding of what kinds of tools that are of value when working with ICS security.  
  
You can register on the CISA VLP via this link(American Citizenship not required): https://ics-training.inl.gov/learn  
The overview of the learning material is found here: https://www.cisa.gov/resources-tools/programs/ics-training-available-through-cisa  

Additional resources that I found valuable were:  
#SANS Webinars on ICS security. Recurring and found under the "Focus Area -> ICS Security" at: https://www.sans.org/webcasts  
#Following various OT security related individuals on LinkedIn. via their posts one finds invites to seminars, labs, technical/organizational/legal insight etc.  
#Chris Foreman's slides on "[Cyber-security in Industrial Control Systems](https://engineering.purdue.edu/VAAMI/ICS-modules.pdf)".  

See below short descriptions for the respective CISA modules and courses:  
#100W, Industrial Control Systems(ICS) Cybersecurity Practices - Basic cybersecurity topics, not much about ICS.  
#210W-01, Differences in Deployments of Industrial Control Systems - Basic overview of types of ICS and interconnections between them.  
#210W-02, Influence of IT Components on ICS - Basic overview of IT components and IT security tenets/vulnerabilities.  
#210W-03, Common ICS components - For someone with more traditional IT background, this section gave a good overview of various OT components/concepts/etc.  
#210W-04, Cybersecurity Within IT and ICS Domains - Basic overview of cybersecurity.  
#210W-05, ICS Cybersecurity risks - Basic overview of cybersecurity risk(risk= threat x consequence x vulnerabilitiy) and related topics.  
#210W-06, ICS cybersecurity threats - Basic overview of threat actors and related topics.  
#210W-07, ICS cybersecurity vulnerabilities - Highlighting how many ICS vulnerabilities are somehow related to availability prioritization.  
#210W-08, ICS cybersecurity consequences - How failure of equipment, bad processes, people issues may lead to consequences.  
#210W-09, Attack methodologies in IT and ICS - Basic overview of the steps of how an attack occurs - some differences between how attacks against ICS and IT occur.  
#210W-10 and 210W-11, Mapping IT DoD to ICS 1&2 - basic overview of how to apply security measures common for IT, in OT environments. Purdue model intro.   


#Industrial Control System Cybersecurity Training(ICS300) - Similar to the modules, but with some additional concepts. The main difference is that the ICS300 is built around a number of labs. The labs are not advanced, but they provide an understanding of what types of tools that are relevant for someone working with securing the OT+IT side of ICS systems.  

#Industrial Control Systems Evaluation(401V) - An overview of various steps that can be taken when evaluating the security of an IT+OT system. This includes what kind of tools that are suitable to use, and how they should be used. As with the rest of the CISA material, the course does not go particularly in-depth, but provides an interesting overarching understanding of an evaluation process.  

#In addition to the CISA materials of this introductory section, the [first video](https://www.youtube.com/watch?v=CCIrntyqe64&list=PLOSJSv0hbPZAlINIh1HcB0L8AZcSPc80g) in Mike Holcomb's ICS/OT Security series is relevant at this stage. 

Some topics that I found valuable among the CISA material:  
#All ICS devices are not able to handle unexpected packets. This may lead to issues during scans.  
#When using tools, check how they can be used to minimize unnecessary network traffic. For example, disable NameResolution when running ARP("arp -a -i eth0 -n").  
#A line of PLC code is called a "Rung", and a full program execution a "Scan" and occur multiple times per second.  
#After initiating tcpdump/windump as an Admin, the process should be forwarded to a regular user as part of zero-trust mentality.  
#Capture traffic with tcpdump, and analyze it with Wireshark. This optimizes resource usage.  
#Nmap with the "--reason" flag provides insight into how the program reached various conclusions.  
#Zero-trust is a very extensive concept, not only concering topics such as for example AAA or security zones, but also having an IDS to scan OT traffic to ensure that no unexpected traffic is present.  
#NMAP flags that start with -P are likely related to host discovery, while -s is most likely a port scan.  
#PLC Fiddle can be used to learn about PLC programming concepts: https://www.plcfiddle.com/  
#NMAP can run syn/ack scans that only send the initial syn, if run with root permissions(-sS). In OT-nets, the non-priv connection scan(-sT) should be used to avoid hanging connections. Also avoid OS and Version detection scans in OT nets.  
#Exclusion lists are valuable when scanning, to minimize the risk that particular devices are affected.  
#The openPLC project provides virtualized PLCs(https://openplcproject.com/getting-started/)  
#IEC 61131 contains info about various PLC programming languages, which may be valuable for labs.  
#Deterministic traffic - repeatable, predictable, and designed so that fluctuations are easily detected.  
#Issues with legacy systems include: weak/no auth; plain text traffic; no least priv; no integrity checks; easy connectivity.  
#It is vital to understand how security requirements differ between ICS sectors, and what kinds of interdependencies that exist.  
#Low WiFi frequency(900MHZ) reaches far and through walls, but low speed.  
#Medium 2.4ghz is often a good inbetween tradeoff.  
#High 5.8ghz is very fast but lacks distance and obstacle penetration.  
#With old systems that are not secure(e.g WEP). What does that affect? Sometimes the non-secure aspects doesn't matter that much.  
#Can't encrypt Beacon or Probe data for WiFi since any system needs to be able to read.  
#Many wi-fi attacks start during the initialization phase.  
