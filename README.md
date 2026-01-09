# Foundations of Cybersecurity

This is the repository for the "Foundations of Cybersecurity" course held at University of Pavia - Department of Electrical, Computer and Biomedical Engineering. The duration of the course is of 45 hours.

----

🏴󠁧󠁢󠁥󠁮󠁧󠁿 The **goal** of the course is to provide a high-level view of the main cybersecurity aspects at the basis of modern software and network ecosystems. The course will allow to understand vulnerabilities and weaknesses plaguing the software, recognize bad security practices and major attack models, as well as to autonomously retrieve information on malware and network threats. 

The **prerequisites** for the course are: basic understanding of operating systems and hardware architectures, basic knowledge of programming and of the most popular network protocols. 

The course is **organized** in indpenendet **modules**, each one investigating a major topic in cybersecurity related to the role of a professional engineer.

---

🇮🇹 L'**obiettivo** del corso è fornire una panoramica dei principali aspetti di cybersecurity alla base dei moderni ecosistemi software e infrastrutture di rete. Il corso consentirà di comprendere le vulnerabilità e le debolezze del software, riconoscere le cattive pratiche di sicurezza, i principali modelli di attacco, e di reperire autonomamente informazioni su malware e minacce informatiche.

I **prerequisiti** del corso sono: conoscenza di base dei sistemi operativi e delle architetture hardware, nozioni di base di programmazione e dei protocolli di rete più diffusi.

Il corso è **organizzato** in moduli che trattano un tema base della sicurezza informatica di particolare rilevanza per la figura dell'ingegnere.

---

**Important**: this repository will be udpadted during the year according to the **actual pace** of the course. The language for the classes as well as for all the materials is **english**. 

## Organization of the Repository

Each module has its own set of material, which may vary according to the topic. The general organization of the repository is based on the following folders:

- Slides: the .pdf version of the slides;
- Examples: various examples shown during the course, e.g., code, scripts, and outputs;
- References: reference research papers that can provide details for studying the topic or useful directions for further investigations;
- Misc: videos, reports, and simple PoC tools to make a topic clearer (and more enjoayble).

## Module 0 - Foreword

This module discusses some bureaucracy and rules (e.g., what is needed to pass the course) just to crack the ice. 

## Module 1 - Introduction and Basics

This module addresses some introductory information (e.g., the relevance of cybersecurity aspects), the Cyber Kill Chain, concepts related to the attack surface and attack surface reduction practices, and a brief discussion on the importance of considering human aspects. The related material contains some reference papers and official reports. 

## Module 2 - Security Analysis and Modeling

This module covers how some security aspects can be analyzed and modeled. Specifically, it deals with the Common Weaknesses Enumeration (CWE), the Common Vulnerability Enumeration (CVE), the Common Vulnerability Scoring System (CVSS), as well as a basic discussion on testing approaches (static and fuzzing). The related material contains some reference papers and a tutorial/challenge for fuzz-testing the xpdf package via the AFL fuzzer. 

## Module 3 - Software Supply Chain Security

This module deals with major attack entry points and security implications of modern software supply chains. In more detail, it covers threats against source code and dependencies, *-squatting techniques, and Software Bill of Materials (SBOMs). The module also presents some mitigation techniques, i.e., debloating and reproducible builds. The related material containes some reference papers, SBOMs in .json/Cyclone-DX format, and small examples to be used against Grype and diffoscope. A simple "SquatScanner" tool is also provided, which can be used as a challenge and to understand how to build your own testing tools. 

## Module 4 - Malware 

This module discusses major aspects of malware. In more detail, it showcases major malware types, e.g., virus, worms, droppers, RATs, trojans, cryptolockers, and cryptominers, and it introduces the basic architectural blueprint of malicious software. The module also presents some concepts of malware analysis, mainly focusing on static approaches and how to "distil" basic YARA rules. The last part of the module briefly shows advanced offensive techniques, like obfuscation and minification (the latter is not an offensive technique in a strict sense). The related material contains basic reference papers, the main outputs of static approaches, and example YARA rules. 

**WARNING:** the supplemental material includes two archives with real malicious software. To avoid unintended usages, archives are protected by a password, which will be disclosed during lectures. In any case, pay a lot of attention, do not wipe out yourself or your neighborhood. 

## Module 5 - Network Security

This module reviews the major aspect of network security. Specifically, it covers spoofing attacks, DoS/DDoS templates, and packet filters (firewalls). The module also introduces vulnerability/network scanning and related strategies, as well as prime countermeasures to reduce the network attack surface such as, hardening, network segmentation and honeypots. The related material containes some reference papers and a very basic port scanner written in Python. 

## Module 6 - Information Hiding

This module introduces how information hiding techniques can be used both as offensive and defensive mechanisms. In more detail, it first discusses covert channels, with many examples related to emerging real attack campaigns. Then it presents stegomalware, i.e., malicious software that takes advantage of steganography to remain undetected. The module also discusses watermarking techniques that can be used to track and protect different types of contents, mainly software and AI. The related matieral contains introductive papers on the topic, some videos on covert communications, and examples on how to mark AI models and network traffic.

**DISCLAIMER:** concepts belonging to this module are at the intersection between industry and research. The idea here is to present advanced techniques that require a "nice thinking" to be faced and to underline that *ambiguities* and *imperfect isolation* may be exploited by an attacker.

## Module 7 - Conclusions

This module concludes the course and provides a recap. Just to say goodbye... 

## Seminar - Vulnerability Discovery: SAST and Fuzz Testing

This seminar showcases basic information on sofware testing, mainly static analysis security testing and fuzz testing. The related material contains slides of the seminar as well as some referene literature. The files used in the seminar (e.g., AFL++ configuration and the tested xpdf packages) are already present in **Module 2 - Security Analysis and Modeling**. Even if the "hands on" labs done during the seminar are not strictly part of the course, the basic concepts should be known as they complete the knowledge needed to spot possible security issues and exploitable behaviors of software. 

## Presentations - Assignments 

This folder contains the .pdf version of the assignments needed to skip part of the final exam. Each team prepared and presented a small monograph on a well-defined topic (e.g., a defensive technique, threat, attack campaign, or emerging hazard) that has been introduced during the lectures. Presentations are part of the course material since they offer alternative viewpoints or an in-depth analysis of major cybersecurity aspects. 

Covered topics are: 

- The CryptoLocker Ransomware
- Static Analysis and Software Supply Chain Security
- Analysis of Sunburst 
- Technical and Economical Analysis of Carbanak
- The WannaCry Ransomware
- Software Supply Chain attacks and SolarWinds
- ARP Spoofing and Man-in-the-Middle Attacks
- Security Risks of AI-assisted Software Development


## Acknowledgments 

The material used during the course and collected in this repository has been prepared with the help of many colleagues. Angelica Liguori is the owner of the code for watermarking AI models, while Marco Zuppelli prepared the digital media and network traffic examples. Giacomo Benedetti provided several examples, code, and ideas on the security of the software supply chain. Luca Veltri and Matteo Repetto shared the slides used in their network security courses. 

## Contacts

Please, report any issue or mistake. And feel free to contact me at luca.caviglione(AT)cnr.it



