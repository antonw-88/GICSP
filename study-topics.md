# Core Material
This section is aimed at providing a concise overview of the material that seems the absolutely most relevant/vital for GICSP exam preparation.  
Note: doing labs is important when preparing for the exam, and I've gathered some in a [separate section](https://github.com/antonw-88/GICSP/tree/main/labs).

## Introductory Overview Material
The CISA course is very superficial, but good for getting used to potentially new terminology.  
- [CISA ICS Virtual Learning Portal.](https://www.cisa.gov/resources-tools/training/ics-virtual-learning-portal)
- [Cyber-security in Industrial Control Systems.](https://engineering.purdue.edu/VAAMI/ICS-modules.pdf)
- [CISA overview of critical infrastructure sectors](https://www.cisa.gov/topics/critical-infrastructure-security-and-resilience/critical-infrastructure-sectors). For the exam, it is not required to understand the in-depth differences between the system architectures. Rather, establish a general sense of how they differ.
- Install the OT Security Huddle AI chatbot.
- On LinkedIn there are a lot of good posts from various individuals. Add for example Mike Holcomb, Robert M. Lee, Shiv Kataria and via their reposts you will find more interesting individuals. Sometimes there are posts about signing up to CTF events or seminars etc.
- [SANS ICS Webinars.](https://www.sans.org/webcasts) Click the "Focus Area" button and check "ICS Security". Industry leaders are presenting during these webinars. Going to these is both interesting technically, and a really nice look into the community. A good break from just standard preparation.

## Books & Cheatsheets
- "_Practical Industrial Cyber Security: ICS, Industry 4.0 & IIoT_" by Charles J. Brooks & Philip A. Craig, Jr.  
Intended as a study guide for the GICSP exam. Contains 25 practice questions per chapter. Has a seemingly great reputation among ICS Security professionals. Offers a break from the dense reading of NIST and ISA/IEC standards.
- "_Sandworm_" by Andy Greenberg is highly recommended. Both for the content itself, but also as a break from highly technical/regulatory/process-oriented reading.

## NIST 800-X Publications
In-depth details, with a lot of good references in the Appendix sections etc. _Note: Check for the latest revisions_.    
- 800-53, Security and Privacy Controls for Information Systems and Organizations.  
- 800-61, Incident Response Recommendations and Considerations for Cybersecurity Risk Management.  
- 800-82, Guide to Operational Technology (OT) Security.  

## ISA/IEC 62443-X Standards
In-depth details. Since the material is quite extensive, going through the Quick Start Guide helps with gaining an understanding of how to approach the reading of the standards. The standards below are the ones I found to be most frequently referenced by industry professionals as being relevant for the GICSP exam. Additionally, in the 4-2 standard(p.14), it is stated that "_the primary standards for system integrators are ISA‑62443‑2‑1 [5], ISA‑62443‑2‑4 [8], ISA‑62443‑3‑2 [10] and ISA‑62443‑3‑3_". However, since the contents of 2-4 is more directed towards third-parties/service providers than operators, I didn't add it to the list. Of course, the 2-4 information would also be valuable for the exam, but the material added to the reference manual has to be demarked somewhere, in order to ensure that there is a clear focus on the material that is the most vital for the exam focus areas. _Note: Check for the latest revisions_.       
- Quick Start Guide: An Overview of the ISA/IEC 62443 Standards  
- 1-1, Terminology, concepts and models. While a good overview of various topics, the other standards provide more in-depth details. 
- 2-1, Establishing an industrial automation and control system security program.  
- 3-2, Security risk assessment for system design.  
- 3-3, System security requirements and security levels.

# Recommended Material

## Youtube Channels/Videos:  
- [Getting Started in ICS/OT Cyber Security with Mike Holcomb](https://www.youtube.com/watch?v=CCIrntyqe64&list=PLOSJSv0hbPZAlINIh1HcB0L8AZcSPc80g).  
- [SANS ICS Security Channel](https://www.youtube.com/@SANSICSSecurity/videos). Search for "ics410" for topics directly related to GICSP.
- [The Five Critical CyberSec Controls for ICS](https://www.youtube.com/watch?v=Ta7kcirzT8o). You can have the [Whitepaper](https://www.sans.org/white-papers/five-ics-cybersecurity-critical-controls) available while viewing. 
- [ICS security list curated by industry professionals](https://github.com/Ka0sKl0wN/ICS-Security-Study-Resources/blob/master/Videos.csv). 

## Electrical Sector
- NERC CIP - Considering the core importance of the energy sector within societal infrastructure, reading up on the related U.S regulatory standards is probably helpful. Under the "[(CIP) Critical Infrastructure Protection](https://www.nerc.com/pa/Stand/Pages/ReliabilityStandards.aspx)" tab, the cybersecurity reliability standards can be found. For an overview of each standards domain, see for example [this link](https://www.industrialdefender.com/blog/what-is-nerc-cip).
- [The Five Critical ICS CyberSec Controls and the Electrical Sector.](https://www.sans.org/white-papers/five-ics-cybersecurity-critical-controls-electric-sector)
- [IR 7628 - Guidelines for Smart Grid CyberSec](https://csrc.nist.gov/pubs/ir/7628/r1/final).
- [Substation Automation insights](https://www.kth.se/social/files/543bacc7f2765447b28bcce2/IEC%2061850%20for%20Substation%20Automation%20-%20AndreaBonetti.pdf). 

## MITRE ICS ATT&CK Framework
"_The major architectural focus of ATT&CK for ICS are the systems and functions associated with functional levels 0 – 2 of the Purdue architecture_" - MITRE ATT&CK ® for Industrial Control Systems: Design and Philosophy(Alexander, Otis. Et al. 2020).  
  
The above document is a very good reference for understanding the structure and motivation of the Mitre ICS ATT&CK framework, but is not that relevant for the GICSP exam. To learn about topics more directly related to the exam objectives, the actual techniques can be referred to; they are listed in the [ICS ATT&CK matrix](https://attack.mitre.org/matrices/ics/). This is a very good resource for reading up on the types of attacks most commonly employed when targeting ICS systems.

## Notable Resources
- For getting started in ICS security, the founder of Dragos - Robert M. Lee - provides an extensive [library of ICS security resources](https://www.robertmlee.org/a-collection-of-resources-for-getting-started-in-icsscada-cybersecurity/) via his webpage.
- Additional ICS security related repos, can be found [here](https://github.com/Ka0sKl0wN/ICS-Security-Study-Resources/blob/master/Git%20Repos.csv).
- The Center for Internet Security has a list of [20 critical security controls](https://www.cisecurity.org/controls/v8), and also a guide for how to [apply these to ICS environments](https://www.cisecurity.org/insights/white-papers/cis-critical-security-controls-v8-1-industrial-control-systems-ics-guide).
- [SANS Cheat Sheet PDFs.](https://www.sans.org/blog/the-ultimate-list-of-sans-cheat-sheets). One frequent GIAC test taker(Hacks4Pancakes) noted: "_Keep those handy SANS cheat sheets for tools, commands, and operating systems they give you in the class, and bring them to the test_".  

# Additional Material
This section is aimed at providing references to material related to ICS that is not vital for the exam preparation, but that I want to look into in the future.

## Various ICS Security Resources 
- [SANS ICS Podcasts, White Papers, Blogs, etc.](https://www.sans.org/security-resources)   
- [The Dragos blog](https://www.dragos.com/blog) - for example the ICS/OT Security year in review. 
- [Via scadahacker](https://scadahacker.com/library/), it is possible to find huge amounts of additional resources.
- The rest of the ISA/IEC 62443 standards.
- [Adjusting CV](https://supratikpathak.com/blog/ot-cybersecurity-resume-guide/) to focus on topics valued by OT hiring managers.
- [ISA-95](https://www.isa.org/standards-and-publications/isa-standards/isa-95-standard), focuses on the integration between L3 and L4 in the Purdue model. These two layers, and the DMZ between them, constitutes the IT/OT boundary.
- [SANS ICS KillChain](https://www.sans.org/white-papers/webs-deception-using-sans-ics-kill-chain-flip-advantage-defender).
- [SCADA papers from Australian Control Engineering(ACE)](https://www.acectrl.com/white-papers/).

## BOOKS:  
- "Industrial Network Security", Eric D. Knapp.    
- "Implementing IEC 62433, a Pragmatic Approach to Cybersecurity", David Gunter.
- "Industrial Cyber Security Case Studies and Best Practices", Steve Mustard.
- "Firewall Deployment for SCADA and Process Control Networks: Good Practice Guide".

## PODCASTS:  
- Control Loop Dragos.  
- Unsolicited Response.  
- The protect OT Cybersecurity Podcast.  
- Industrial Security Podcast.  

## Youtube Channels:
- [Dragos Channel.](https://www.youtube.com/@DragosInc/videos) For example good for NERC CIP basics.  
- [Siemens Webinars.](https://www.youtube.com/playlist?list=PLewnA6R5Js9JRCB2v_HULi5lfuhsOWRFf)  
- [Schneider Electric Channel.](https://www.youtube.com/SchneiderElectric)    
- [Industrial Control System (ICS) Cyber Security Training Course](https://www.youtube.com/playlist?list=PLI78ZBihrkE1EpPaG79hQFuEIN9_35EbA).  
- [ControlThings](https://www.youtube.com/@ControlThings). 

## Potential additional OT related certifications:
- [CAP associate certificate program](https://www.isa.org/certification/certificate-programs/cap-associate-certificate-program) - Overview program of OT environments/processes etc.
- [SANS ICS515(GRID)](https://www.sans.org/cyber-security-courses/ics-visibility-detection-response) - More technically oriented than the GICSP. 

***Note: Anna's Archive is very good for finding text-based resources.***
