# GICSP Exam-Preparation Reference Manual

**This repo is a self-study guide for the GICSP**(Global Industrial Cyber Security Professional Certification), where the information has been gathered from a large number of other individuals/guides. It is mainly a reference manual, pointing towards various material that I found relevant when studying for the GICSP. It also includes notes regarding topics that I found particularly interesting.  
*NOTE: This guide is written from the point-of-view of someone with a Linux/InfoSec/Networking background. This may affect its relevance for individuals with other backgrounds.*  

## Reference Manual Overview

0. [Overview of the guide's main resources.](https://github.com/antonw-88/GICSP/blob/main/study-topics.md)

1. [Step 1](https://github.com/antonw-88/GICSP/tree/main/intro-stage) - Initial Overview of ICS, via CISA training resources. Goal being to understand what OT+IT systems are, major related components/concepts, and how OT and IT differ from each other.

2. [Step 2](https://github.com/antonw-88/GICSP/blob/main/ICS%20Components%20%26%20Architecture/ICS-components-and-architecture.md) - ICS Components & Architecture - Categorize assets that comprise Purdue Reference Architecture levels zero through three and describe how they can be implemented in a securable architecture. Additionally, summarize the use of levels and zones in defining a secure ICS architecture, as well as the devices deployed at each level and zone.  

3. [Step 3](https://github.com/antonw-88/GICSP/tree/main/ICS%20Overview%20%26%20Concepts) - ICS Overview & Concepts - Summarize the function of high-level ICS processes as well as ICS roles and responsibilities. Additionally, compare and contrast high-level differences between ICS and IT, including physical security considerations.  

4. [Step 4](https://github.com/antonw-88/GICSP/tree/main/industrial-protocols) - Protocols, Communications, & Compromises - Describe the basic structures, protocols, and defense of communications within an ICS and summarize how they can be compromised. This includes TCP/IP as well as ICS specific protocols. Additionally, at a basic level, describe the cryptography used to protect communications.  

5. [Step 5](https://github.com/antonw-88/GICSP/tree/main/Purdue-Model-Level-0+1) - PERA Level 0 & 1 Technology Overview and Compromise - Describe level 0 and level 1 devices and technologies and summarize how those devices and technologies are targeted and attacked.  

6. [Step 6](https://github.com/antonw-88/GICSP/blob/main/Purdue-Model-Level-2%2B3/Purdue-Model-Level-2%2B3.md) - PERA Level 2 & 3 Technology Overview and Compromise - Describe level 2 and level 3 devices and technologies and summarize how those devices and technologies are targeted and attacked.  

7. [Step 7](https://github.com/antonw-88/GICSP/tree/main/ICS%20Program%20%26%20Policy%20Development) - ICS Program & Policy Development - Summarize the steps and best practices used in building a security program and creating enforceable security policies for an ICS.  

8. [Step 8](https://github.com/antonw-88/GICSP/tree/main/Intelligence%20Gathering%20%26%20Threat%20Modeling) - Intelligence Gathering & Threat Modeling - Determine the threat landscape of an ICS and high-level concepts of threat modeling.  

9. [Step 9](https://github.com/antonw-88/GICSP/tree/main/Risk%20Based%20Disaster%20Recovery%20%26%20Incident%20Response) - Risk Based Disaster Recovery & Incident Response - Describe how risk is measured and how it can be used to inform disaster recovery and incident response.  

10. [Step 10](https://github.com/antonw-88/GICSP/tree/main/Wireless%20Technologies%20%26%20Compromises) - Wireless Technologies & Compromises - Summarize the different wireless communication technologies used in an ICS, how they are targeted, and how they can be defended.  

11. [Step 11](https://github.com/antonw-88/GICSP/tree/main/Hardening%20%26%20Protecting%20Endpoints) - Hardening & Protecting Endpoints - Describe how to implement endpoint security software along with hardening and patching, to secure the Windows and Unix style operating systems commonly found in an ICS environment.  

## Other Resources

- [ICS Project](https://github.com/antonw-88/GICSP/tree/main/ICS-project) - A project that aims to simulate an OT+IT environment, based on Purdue Model.

- [ICS Case Studies](https://github.com/antonw-88/GICSP/tree/main/case-studies) - Some case studies I've done on ICS security related incidents.

- [Labs](https://github.com/antonw-88/GICSP/tree/main/labs) - Link to various lab environments that I found when researching this project.

- [Indexing](https://github.com/antonw-88/GICSP/tree/main/indexing-methodology) - Various resources for suggested indexing. During initial research, the indexing was repeatedly mentioned as being very important. 

- [Webinars](https://github.com/antonw-88/GICSP/tree/main/webinars-etc) - Summaries of webinars etc. that I've joined.

## Information about the Repo

**The motivation for the repo** was that I couldn't find what seemed to me a comprehensive and well structured self-study guide for the GICSP. While a well reputed SANS course exists, it is very expensive. Since I find both OT, the intersection of IT/OT, and security interesting, I decided to create a guide myself to organize my studies. I've also wanted to give back to the opensource community for a long time, and this feels like a hopefully good way to do so. Manjunath Hiregange's Youtube video "[How to Prepare for GICSP Certification Without SANS Training](https://www.youtube.com/watch?v=U5ttY--AOvw)" provided a very good initial overview of where to find relevant resources and how to think about the process. Usman Shahzad's [Linkedin post](https://www.linkedin.com/pulse/my-journey-achieving-gicsp-certification-through-usman-das9f) regarding his self studies, was also very helpful. Additionally, Mike Holcomb's introductory [ICS IT/OT CyberSecurity course](https://www.youtube.com/watch?v=U5ttY--AOvw) is a great way to both gain valuable insights and avoid just reading NIST and ISA documents.  

**The informational base for this guide**, consists of mainly SANS and NIST resources. A note in relation to this, is that the official books for the exam, that are provided with the SANS course, seemingly contain the exact same sentences that can be found on the actual exam. One Reddit user wrote: "I couldn't imagine a SANS test without the associated books. Literally the questions are taken from the books". This may first seem demotivating, but it made it even more clear to me that a well-structured and comprehensive self-study guide should exist. The GICSP is frequently referenced in job adverts, and OT/IT security is seemingly becoming more and more important. Additionally, by not having the SANS books, it may also require a both deeper and broader understanding of the topics. In the end, the true goal is the learning aspect itself, and then bringing that knowledge into the external world.

**The structure of the repo** is based on the [official GIAC syllabus](https://www.giac.org/certifications/global-industrial-cyber-security-professional-gicsp/). For each of the concepts/keywords/etc, sections in books; videos; labs; etc, are referenced. During the initial research for this project, it was identified that an in-depth indexing of information is very important since the exam is open-book. See the diagram below for an overview of the guide(ha rutor för varje sektion, med pilar till subsektioner, med pilar till specifika koncept/processer/enheter. Allt numrerat och leder vidare till specifika referenser.). The indexing will not be provided, since that would somewhat undermine the learning purpose. However, a guide created by lala can be found under the "Indexing Methodology" section.

**The repo will be continually updated**, for example with summaries of SANS webinars related to ICS and how they map to the IGCSP syllabus. 

**Finally, I found [this blogpost](https://baston.uk/gicsp-how-to-pass-first-time/) to be a good introduction** to the certification process. It also references the importance of indexing: "I knew exactly what questions I got wrong. The ones I couldn’t look up in my index, the ones I was overthinking".
