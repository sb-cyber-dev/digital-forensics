# E-Discovery and Digital Evidence

---


## Glossary

- **E-discovery:** Process of applying traditional legal discovery process to electronic evidence
- **ESI:** Electronically Stored Information
- **MAC times:** Modified, Accessed, and Created dates and times
- **Digital Evidence:** data or files in digital format pertaining to a civil or criminal complaint

---


## Types of Digital Evidence
- Data
- Metadata
---

## Cloud Computing and Digital Evidence
**Reference:** [NIST (SP 800-145) Definition of Cloud Computing](https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-145.pdf)

### Essential Characteristics

- On-demand self-service
- Broad network access
- Resource pooling
- Rapid elasticity
- Measured service

### Service Models
- SaaS (Software as a Service)
- PaaS (Platform as a Service)
- IaaS (Infrastructure as a Service)


### Deployment Models
- Private cloud
- Community cloud
- Public cloud
- Hybrid cloud

---

## Factors Affecting Evidence Acquisition

- **Civil cases:** evidence acquired by issuing a request for production
    - Company responsibility to store and produce files, per the document retention order
- **Criminal cases:**
    - Requires strict adherence to Chain of Custody (ensure no tampering with evidence)
    - Use search warrants, subpoenas, etc.
- Civil cases can develop into criminal cases, and vice versa.


- **Digital Forensics cases:**
    - In a forensics lab, create forensic image (copies a device down to the smallest component) of device, and analyze image.
    - Can potentially find deleted files or file fragments (criminal cases only)


- Reduce Cost and Time
    - Narrow down scope (keywords, timeframe, specific files)

---

## Federal Rules in U.S. Courts

- 3 Sets of rules governing conduct of federal court cases
    - [FRCP (Federal Rules of Civil Procedure)](./FRCP-Rules.md)
    - FRCrP (Federal Rules of Criminal Procedure)
      - Rule 41. Search and Seizure
      - Department of Justice
        - [Searching and Seizing Computers and Obtaining Electronic Evidence in Criminal Investigations](https://www.justice.gov/d9/criminal-ccips/legacy/2015/01/14/ssmanual2009_002.pdf)
    - FRE (Federal Rules of Evidence)
      - U.S. Supreme Court
      - Article I, Rule 103. Rulings on Evidence
      - Article I, Rule 105. Limited Admissibility
      - Article I, Rule 106. Remainder of Related Writings or Recorded Statements
      - **Article IV. Relevancy and Its Limits**
      - **Article VII. Opinions and Expert Testimony**
      - **Article VIII. Hearsay**
      - **Article X. Contents of Writings, Recordings, and Photographs**


- State interpretation of rules

---

## Rules and Policies Governing Digital Evidence


### Location

- cloud load balancing leads to indeterminate locations
- Affected by country laws of where data resides and is stored


### Sedona Principle

- guides for handling electronic document
- 14 pinciples that link to the FRCP
- framework for what a company must do to prepare for possible litigation
- "best practices" for lawyers addressing electronic document production, in a defensible manner


### FRCP Amendments

- 2006, amended to address e-discovery, ESI
- require companies to protect data that might be subject to discovery in anticipated litigation
- maintain both searchability and metadata
  - scanned image/pdf copies make searchability more difficult or require further processing
  - metadata is lost when non-native files are produced
    - creation date
    - deletion date
    - originating IP address, etc.
- Rule37(f). Safe Harbor
  - the court cannot impose sanctions when a party destroys ESI as part of its "routine, good faith" operations
  - Destroying ESI in anticipation of litigation is not protected
    - Place a "litigation hold" on all potentially relevant ESI
      - Restricts a company from deleting, changing, or purging data or backups. 



