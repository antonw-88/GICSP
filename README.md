# GICSP Exam-Preparation Reference Manual

**NOTE: The first iteration of the project is currently under development. Some sections are still in an initial planning phase.**  

**This repo is a self-studies reference manual for the GICSP**(_Global Industrial Cyber Security Professional Certification_), where the information has been gathered from a large number of other individuals/guides. Being a reference manual, it points towards various material that I found relevant when studying for the GICSP. It is not an attempt at being an actual course; the aim is to provide a concise overview of study material that multiple credible professionals mention to be of a high relevance. The repo also includes notes regarding topics that I found particularly interesting, and additional ICS/OT related sections that I will continue updating after having achieved the certification.
  
*NOTE: This guide is written from the point-of-view of someone with a SysAdmin/InfoSec/Networking background. This may affect its relevance for individuals with other backgrounds.*  

## Reference Manual Overview

0. [Overview of the guide's main resources.](https://github.com/antonw-88/GICSP/blob/main/study-topics.md)

1. [Initial Overview of ICS](https://github.com/antonw-88/GICSP/tree/main/intro-stage), via CISA training resources. Goal being to understand what OT+IT systems are, major related components/concepts, and how OT and IT differ from each other.

2. [ICS Components & Architecture](https://github.com/antonw-88/GICSP/tree/main/ICS%20Components%20%26%20Architecture) - Categorize assets that comprise Purdue Reference Architecture levels zero through three and describe how they can be implemented in a securable architecture. Additionally, summarize the use of levels and zones in defining a secure ICS architecture, as well as the devices deployed at each level and zone.  

3. [ICS Overview & Concepts](https://github.com/antonw-88/GICSP/tree/main/ICS%20Overview%20%26%20Concepts) - Summarize the function of high-level ICS processes as well as ICS roles and responsibilities. Additionally, compare and contrast high-level differences between ICS and IT, including physical security considerations.  

4. [Protocols, Communications, & Compromises](https://github.com/antonw-88/GICSP/tree/main/industrial-protocols) - Describe the basic structures, protocols, and defense of communications within an ICS and summarize how they can be compromised. This includes TCP/IP as well as ICS specific protocols. Additionally, at a basic level, describe the cryptography used to protect communications.  

5. [PERA Level 0 & 1 Technology Overview and Compromise](https://github.com/antonw-88/GICSP/tree/main/Purdue-Model-Level-0+1) - Describe level 0 and level 1 devices and technologies and summarize how those devices and technologies are targeted and attacked.  

6. [PERA Level 2 & 3 Technology Overview and Compromise](https://github.com/antonw-88/GICSP/tree/main/Purdue-Model-Level-2%2B3) - Describe level 2 and level 3 devices and technologies and summarize how those devices and technologies are targeted and attacked.  

7. [ICS Program & Policy Development](https://github.com/antonw-88/GICSP/tree/main/ICS%20Program%20%26%20Policy%20Development) - Summarize the steps and best practices used in building a security program and creating enforceable security policies for an ICS.  

8. [Intelligence Gathering & Threat Modeling](https://github.com/antonw-88/GICSP/tree/main/Intelligence%20Gathering%20%26%20Threat%20Modeling) - Determine the threat landscape of an ICS and high-level concepts of threat modeling.  

9. [Risk Based Disaster Recovery & Incident Response](https://github.com/antonw-88/GICSP/tree/main/Risk%20Based%20Disaster%20Recovery%20%26%20Incident%20Response) - Describe how risk is measured and how it can be used to inform disaster recovery and incident response.  

10. [Wireless Technologies & Compromises](https://github.com/antonw-88/GICSP/tree/main/Wireless%20Technologies%20%26%20Compromises) - Summarize the different wireless communication technologies used in an ICS, how they are targeted, and how they can be defended.  

11. [Hardening & Protecting Endpoints](https://github.com/antonw-88/GICSP/tree/main/Hardening%20%26%20Protecting%20Endpoints) - Describe how to implement endpoint security software along with hardening and patching, to secure the Windows and Unix style operating systems commonly found in an ICS environment.

12. [Safety Instrumented Systems and Functions](https://github.com/antonw-88/GICSP/tree/main/Safety-Instrumented-Systems-and-Functions) - Identify various forms of SIS systems and what they consist of.

13. [Logical Access Control Management](https://github.com/antonw-88/GICSP/tree/main/access-control-management) - Not explicitly mentioned on the GIAC syllabus page, but of vital concern for IT and OT security efforts. 

## Other Resources

- [ICS Project](https://github.com/antonw-88/GICSP/tree/main/ICS-project) - Based on a case study of the _to-be-decided_ incident.
- [Labs](https://github.com/antonw-88/GICSP/tree/main/labs) - Links to various lab environments that I found when researching this project.
- [Indexing](https://github.com/antonw-88/GICSP/tree/main/indexing-methodology) - Various resources for reference indexing.
- [Webinars](https://github.com/antonw-88/GICSP/tree/main/webinars-etc) - Summaries of webinars that I've joined.

## Information about the Repo

**The motivation for the repo** was that I couldn't find what seemed to me a comprehensive and well structured text-based self-study reference manual for the GICSP. While a well reputed SANS course exists, it is very expensive. Since I find both OT, the intersection of IT/OT, and security very interesting, I decided to create a guide myself to organize my studies. Manjunath Hiregange's Youtube video "[_How to Prepare for GICSP Certification Without SANS Training_](https://www.youtube.com/watch?v=U5ttY--AOvw)" provided a very good initial overview of where to find relevant resources and how to think about the process. Usman Shahzad's [Linkedin post](https://www.linkedin.com/pulse/my-journey-achieving-gicsp-certification-through-usman-das9f) regarding his self studies, was also very helpful. Additionally, Mike Holcomb's introductory [ICS IT/OT CyberSecurity course](https://www.youtube.com/watch?v=U5ttY--AOvw) is a great way to both gain valuable insights and get a break from just reading NIST and ISA/IEC documents.  

**The informational base for this guide**, consists of mainly ISA/IEC and NIST resources. A note in relation to this, is that the official books for the exam, that are provided with the [SANS course](https://www.sans.org/cyber-security-courses/ics-scada-cyber-security-essentials), seemingly contain the exact same sentences that can be found on the actual exam. One Reddit user wrote: "_I couldn't imagine a SANS test without the associated books. Literally the questions are taken from the books_". This may first seem demotivating - almost like the certification is rigged in favour of those paying for the course([further highlighted here](https://www.reddit.com/r/GIAC/comments/1e9ghi1/gicsp_exam_booking/)) - but it made it even more clear to me that a well-structured and comprehensive reference manual should exist. The GICSP is frequently referenced in job adverts, and OT/IT security is clearly becoming more and more important. Additionally, by not having the SANS books, it may also require a both deeper and broader understanding of the topics. In the end, the true goal is the learning aspect itself, and then bringing that knowledge into the external world. The paper has no particular worth in and of itself. Finally, the SANS ICS410 course - the GICSP course - is, from what I've found, built on the ISA/IEC 62443 standards and the NIST 800-82 publication as its core foundation. Truly understanding this material in-depth, should alleviate the risk associated with not taking the official course.  

**The structure of the repo** is based on the [official GIAC syllabus](https://www.giac.org/certifications/global-industrial-cyber-security-professional-gicsp/). For each of the exam topics, I've referenced sections in books; videos; labs; etc. During the initial research for this project, multiple individuals identified that an in-depth indexing of information is very important since the exam is open-book. [A guide for indexing](https://tisiphone.net/2015/08/18/giac-testing/) created by Lesley(Hacks4Pancakes), is apparently very popular. However, that guide is to some extent based on having access to the SANS material, so you will need to adjust the process a bit(_note: at the end of the post Lesley also links to other indexing methods_). The overall study index I created is basically this repo, and the file indexing.xlsx is the exam oriented overview of concept references. I based this exam oriented index on the Practical Industrial Cybersecurity book, to keep things clean and with a focus on deep understanding of the various materials' technical aspects, instead of a focus on memorizing where to find the information.  

**Finally, I found [this blogpost](https://baston.uk/gicsp-how-to-pass-first-time/) to be a good introduction** to the certification process. It also references the importance of indexing: "_I knew exactly what questions I got wrong. The ones I couldn’t look up in my index, the ones I was overthinking_".
