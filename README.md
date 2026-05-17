# HTB-CDSA-Writeup-2026
HTB CDSA Writeup 2026 and tips

## Overall Impression
CDSA is a strong hands-on certification focused on blue team/defensive security. It is specifically geared towards those in the following fields:

Entry level Security Analysts / SOC Analysts / Incident Handlers / Forensic Analysts
Penetration Testers
IT Administrators / Security Personnel


## The Course
The SOC Analyst path provides you with everything you need to know for the exam, comprising 15 modules and unlocking exam eligibility once completed.

I’m not going to give a blow-by-blow review of each module, but here are some I found particularly interesting and/or useful for the exam:

Windows Event Logs & Finding Evil — Introduces Sysmon and Windows Event Logs, and how they can be used to uncover malicious activity.

Introduction to Threat Hunting & Hunting with Elastic — Covers foundational threat hunting with Elastic, which is used in the first incident in the exam.

Introduction to Malware Analysis — Covers static and dynamic analysis on both Linux and Windows.

Introduction to Digital Forensics — Explores both disk and memory forensics, as well as building timelines across diverse data sources.

Detecting Windows Attacks with Splunk — Focuses on analysing common Active Directory attacks such as reconnaissance, password spraying, and Kerberos abuse using Splunk.

Security Incident Reporting: Critical preparation for writing the final exam report.

## The Exam Experience
The CDSA exam is comprised of two core incidents which you are tasked with investigating over 7 days. For the first incident, you must answer 17 out of 20 questions by submitting the MD5 hash of the flag as the answer. In addition to this, you must submit a full commercial-grade report covering both incidents.
I started my exam on a Saturday to give myself the whole weekend to get through as much of the analysis as possible. I also built my report as I investigated each incident and took an excessive amount of screenshots for evidence. 
I managed to find 20/20 flags for the first incident, but unfortunately, due to a combination of life commitments, the day job, and VPN issues, I didn’t finish investigating both incidents until the Thursday evening.

Thankfully, I had already completed most of the technical analysis because I was documenting everything as I went, so I only needed to polish the report before submitting on Sunday. HackTheBox support also kindly granted a 1-day extension due to the VPN issues.



## Tips for Passing
Take good notes, capture screenshots, and write the report as you go.

Revisit and master the Splunk and Elastic modules — these are vital for the exam.If specific attacks are mentioned, refer back to the relevant modules that cover them.
If you can’t find an answer, move on and come back — sometimes later answers help you reverse engineer earlier ones.

Notes and Tips https://tr.ee/p195Pu 
