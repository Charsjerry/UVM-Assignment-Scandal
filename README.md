# UVM-Assignment-Scandal
Digital forensics Personal project


<h2>Incident and Case Overview </h2>
During the Spring 2026 semester at the University of UVM, Professor Jared Smith flagged students Kimberly McGee and Diane Quigley for suspected cheating. Initial suspicions indicated that one student was completing coursework for the other in exchange for monetary compensation.


<h2>DFIR Workflow stages</h2>
[1. Identification] → [2. Preservation] → [3. Acquisition] (Completed by Senior Examiner Lorraine Sheppard) [4. Examination] →  [5. Analysis] → [6. Documentation] → [7. Reporting] → [8. Presentation]  (Executed by Lead Investigator Charles Jeremiah Nosa) 

Initial Evidence Retrieval Senior Examiner: Lorraine Sheppard imaged Kimberly McGee's laptop (`Kimberleys.Computer.E01`). 
Secondary Evidence Retrieval: Investigators Melissa Thomas and Jessica Smith retrieved Instagram communication data and associated metadata.
Assigned Lead Examiner: Charles Jeremiah Nosa was assigned to complete stages 4 through 8 of the Digital Forensics and Incident Response (DFIR) lifecycle.

<h2>Digital Forensics Methodology</h2>
* Identification: Specifying media and digital evidence related to the incident.
* Preservation: Maintaining evidence integrity through cryptographic hashing. 
* Acquisition: Creating bit-stream forensic images (E01). 
* Examination: Forensic extraction of active, system, and deleted files 
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
Source file: Github repo <br/>
<img src="https://i.imgur.com/Y2fJZBG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


  
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

