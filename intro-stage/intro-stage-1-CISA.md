For the initial stage, many recommended the CISA VLP learning platform's CSI modules and courses. While these often didn't go in-depth on concepts etc, 
they did provide a good overview of many concepts, terms. The platform's contents also described well the reasons for many contemporary ICS security issues etc.
Additionally, the courses contained multiple labs, and provided a good understanding of what kinds of tools that are of value when working with ICS security.

You can register on the CISA VLP via this link: https://ics-training.inl.gov/learn
The overview of the learning material is found here: https://www.cisa.gov/resources-tools/programs/ics-training-available-through-cisa

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

#Industrial Control System Cybersecurity Training(ICS300) - Similar to the modules, but with some additional concepts. The main difference is that the ICS300 is
built around a number of labs. The labs are not advanced, but they provide an understanding of what types of tools that are relevant for someone working with securing
the OT+IT side of ICS systems.
Some topics that I found valuable:
#All ICS devices are not able to handle unexpected packets. This may lead to issues during scans.
#When using tools, check how they can be used to minimize unnecessary network traffic. For example, disable NameResolution when running ARP("arp -a -i eth0 -n").
#A line of PLC code is called a "Rung", and a full program execution a "Scan".
