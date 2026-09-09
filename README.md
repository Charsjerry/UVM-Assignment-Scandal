# UVM-Assignment-Scandal
Digital forensics Personal project


<h2> INCIDENT AND CASE OVERVIEW </h2>
During the Spring 2026 semester at the University of UVM, Professor Jared Smith flagged students Kimberly McGee and Diane Quigley for suspected cheating. Initial suspicions indicated that one student was completing coursework for the other in exchange for monetary compensation.


### DIGITAL FORENSICS METHODOLOGY:
[1. Identification] → [2. Preservation] → [3. Acquisition] (Completed by Senior Examiner Lorraine Sheppard) [4. Examination] →  [5. Analysis] → [6. Documentation] → [7. Reporting] → [8. Presentation]  (Executed by Lead Investigator Charles Jeremiah Nosa) 

Initial Evidence Retrieval Senior Examiner: Lorraine Sheppard imaged Kimberly McGee's laptop (`Kimberleys.Computer.E01`). 
Secondary Evidence Retrieval: Investigators Melissa Thomas and Jessica Smith retrieved Instagram communication data and associated metadata.
Assigned Lead Examiner: Charles Jeremiah Nosa was assigned to complete stages 4 through 8 of the Digital Forensics and Incident Response (DFIR) lifecycle.


### DIGITAL FORENSICS METHODOLOGY :
* Identification: Specifying media and digital evidence related to the incident.
* Preservation: Maintaining evidence integrity through cryptographic hashing. 
* Acquisition: Creating bit-stream forensic images (E01). 
* Examination: Forensic extraction of active, system, and deleted files.
* Analysis: Translating raw technical artifacts into legally defensible findings. 
* Documentation: Continuous real-time record keeping of tools, paths, and procedures.
* Reporting: Synthesis of findings into a structured, technical report.
* Presentation: Expert presentation of evidence to decision-makers.
Primary Forensic Toolset : Autopsy 4.20.1 Forensic processing, ingest module parsing, artifact extraction, and deleted file recovery.


<h2>Incident walk-through:</h2>
<p align="center">
Overview of the incident writtern by the boss: <br/>
<img src="https://i.imgur.com/jvHKg61.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The process: Launching Autopsy <br/>
<img src="https://i.imgur.com/MuISiQY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Source file: Evidences Acquisition and Chain of custody <br/>
<img src="https://i.imgur.com/Y2fJZBG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Source file link:  https://github.com/AB-CW-DFIR/Forensic-Image-Download/releases/tag/Image_Download
Kimberleys computer SHA256 Value: sha256:e5fbd6832473b8199e82e4c0b10ff6f7aed887b714bbe29ce48d22e9005818cf

<img src="https://i.imgur.com/IqU8JgF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

sha256: e5fbd6832473b8199e82e4c0b10ff6f7aed887b714bbe29ce48d22e9005818cf
Kimberleys computer SHA256 Value After verification:
Integrity Statement: Verification of the SHA-256 hash confirms that `Kimberleys.Computer.E01` remained unaltered and bit-stream identical throughout the examination process.


<h2>EXAMINATION & TECHNICAL ANALYSIS:</h2>

<img src="https://i.imgur.com/76l1fWQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/lpvScff.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<img src="https://i.imgur.com/pvheRbE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/AC9WYdH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/6noKdSh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/ba5sjfH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/ZDMyEtF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/dmSat2o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/AxS5McJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/6thTcrd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/6ZgMwFV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/1JRzR3o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/GQ6YWv9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<img src="https://i.imgur.com/4ffr25l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/KAMbYHJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/1B4WpTs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/o6AuSkX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://i.imgur.com/cUhDeFc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2> KEY FINDINGS </h2>
As highlighted above, those were the information gotten from the operating system. Such as the name of the system, the windows installed, processor architecture, data source, date of acquired and device ID.

* Premeditated Collusion: Instagram chat metadata proves Kimberley McGee initiated a commercial offer to write coursework for Diane Quigley for $100, which Diane Quigley formally accepted on March 19, 2026..
* Direct Attribution: The document recovered from Kimberley McGee's laptop (Kimberleys.Computer.E01) contains an embedded author line identifying Diane Quigley. 
* Execution & Access History: Windows Shell LNK artifacts prove the file was actively downloaded and opened under Kimberley McGee's user profile on March 24, 2026. 
* Attempted Concealment: The primary target file was deleted from the active directory structure in an effort to destroy evidence but was recovered intact via forensic carving/parsing.

<h2> CONCLUSION AND RECOMMENDATION </h2>
Final Conclusion :
   The digital forensic evidence overwhelmingly validates the allegation of academic dishonesty and contract cheating between Kimberley McGee and Diane Quigley
Diane Quigley authored the paper "Veganism and the Ethical Considerations for Animals, The document was transferred to, opened on, and subsequently deleted from Kimberly McGee's computer.

Recommendation:
* Formal Interrogation: Call both Kimberly McGee (primary suspect/device owner) and Diane Quigley(document author) in for formal questioning regarding the method of file transfer (e.g., email, USB drive, or Instagram DMs).
* Cross-Examination of Communication Logs: Proceed with parsing the retrieved Instagram metadata (Instagram_CoC.pdf`) provided by investigators Melissa Thomas and Jessica Smith to establish the exact communication timeline and collusion motive
* Academic Sanction Review: Submit this technical report to the University of UVM Academic Disciplinary Board as physical evidence of shared academic coursework



🤳 Connect with me:</h2>
 www.linkedin.com/in/charles-jeremiah-n-8a9563190

Thank you for your time. 
I'd welcome the chance to connect! Feel free to reach out.



















