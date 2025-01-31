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
  - FRCP (Federal Rules of Civil Procedure)
  - FRCrP (Federal Rules of Criminal Procedure)
  - FRE (Federal Rules of Evidence)

- State interpretation of rules


### Federal Rules of Civil Procedure (FRCP)

Reference: [US Courts Forms and Rules](https://www.uscourts.gov/forms-rules/current-rules-practice-procedure/federal-rules-civil-procedure)

Established by US Supreme Court in 1938

---

#### FRCP Rule 1. Scope and Purpose

"...to secure the just, speedy, and inexpensive determination of every action and proceeding."

---

#### FRCP Rule 16. Pretrial Conferences; Scheduling; Management

- "The scheduling order... the judge must issue it within the earlier of 90 days after any defendant has been served with the complaint or 60 days after any defendant has appeared."
- "The scheduling order must... complete discovery..."
- "The scheduling order may... modify the extent of discovery..."
- "provide for disclosure, discovery, or preservation of electronically stored information."
- "Matters for Consideration at a pretrial conference... "
  - "formulating and simplifying the issues, and eliminating frivolous claims or defenses"
  - "avoid unnecessary proof and cumulative evidence..."
  - "controlling and scheduling discovery, including orders affecting disclosures and discovery under Rule 26..."
  - "identifying...documents"
  - "establishing a reasonable limit on the time allowed to present evidence..."
  - "facilitating in other ways the just, speedy, and inexpensive disposition of the action"


---

#### FRCP Rule 26. Duty to Disclose; General Provisions Governing Discovery

- **"Initial Disclosure...** a party must, without awaiting a discovery request, provide to the other party..."
  - "a copy - or a description by category and location - of all documents, electronically stored information, and tangible things that disclosing party has in its possession, custody, or control and may use to support its claims or defenses, unless the use would be solely for impeachment..."
  - "a computation of each category of damages claimed by the disclosing party - who must also make available for inspection and copying as under Rule 34 the documents or other evidentiary material, unless privileged or protected from disclosure, on which each computation is based, including materials bearing on the nature and extent of injuries suffered..."
  - "for inspection and copying as under Rule 34, any insurance agreement under which an insurance business may be liable to satisfy all or part..."
- "Time for Initial Disclosure - In General"
  - "A party must make the initial disclosure at or within 14 days after the parties' Rule 26 conference unless a different time is set..."
- "Time for Initial Disclosures - For Parties Served or Joined Later"
  - "must make the initial disclosures within 30 days after being served or joined, unless a different time is set..."
- "Basis for Initial Disclosure; Unacceptable Excuses"
  - "A party is not excused from making its disclosures because it has not fully investigated the case"
  - "or because it challenges the sufficiency of another party's disclosures"
  - "or because another party has not made its disclosures"
- **"Disclosures of Expert Testimony"**
  - "a party must disclose to the other parties the identity of any witness it may use at trial to present evidence under Federal Rules of Evidence 702, 703, or 705"
  - "must be accompanied by a written report - prepared and signed by the witness... report must contain..."
    - "a complete statement of all opinions the witness will express and the basis and reasons for them"
    - "the facts or data considered by the witness in forming them"
    - "any exhibits that will be used to summarize or support them"
    - "the witness's qualifications, including a list of all publications authored in the previous 10 years"
    - "a list of all other cases in which, during the previous 4 years, the witness testified as an expert at trial or by deposition..."
    - "a statement of the compensation to be paid for the study and testimony in the case"
  - "If the witness is not required to provide a written report, this disclosure must state..."
    - "the subject matter on which the witness is expected to present evidence under Federal Rule of Evidence 702, 703, or 705"
    - "a summary of the facts and opinions to which the witness is expected to testify"
  - "Time to disclose expert testimony"
    - "at least 90 days befire the date set for trial or for the case to be ready for trial"
    - if the evidence is intended solely to contradict or rebut evidence on the same subject matter identified by another party... within 30 days after the other party's disclosure"
- **"Pretrial Disclosures"**
  - "In General...an identification of each document or other exhibit, including summaries of other evidence - separately identifying those items the party expects to offer and tose it may offer if the need arises."
  - "Time for Pretrial Disclosures; Objections."
    - "At least 30 days before trial. Within 14 days after they are made,...a party may serve and promptly file a list of the following objections..."
  - "All disclosures under Rule 26(a) must be in writing, signed, and served"
- **"Discovery Scope and Limits"**
  - "Scope in General... Unless otherwise limited... Parties may obtain discovery regarding..."
    - "Information within this scope of discovery need not be admissible in evidence to be discoverable"
      - "nonprivileged matter that is relevant to any party's claim or defense"
      - "proportional to the needs of the case"
      - "considerin the importance of the issues at stake in the action"
      - "the amount in controversy"
      - "parties' relative access to relevant information"
      - "parties' resources"
      - "importance of the discovery in resolving the issues"
      - "whether the burden or expense of the proposed discovery outweighs its likely benefit"
    - **"Specific Limitations on Electronically Stored Information"**
      - "A party need not provide discovery or electronically stored information from sources that the party identifies as not reasonably accessible because of undue burden or cost."
      - "...the part from whom discovery is sought must show that the information is not reasonably accessible because of undue burden or cost"
      - "The court may nonetheless order discovery from such sources if the requesting party shows good cause... The court may specify conditions for the discovery"
    - "...the court must limit the frequency or extent of discovery... if it determines that..."
      - "the discovery sought is unreasonably cumulative or duplicative, or can be obtained from some other source that is more convenient, less burdensome, or less expensive"
      - "the party seeking discovery has had ample opportunity to obtain the information by discovery in the action"
      - "the proposed discovery is outside the scope permitted by Rule 26(b)(1)"
- "Trial Preparation: Materials"
  - "Documents and Tangible Things... may be discovered if..."
    - "they are otherwise discoverable under Rule 26(b)(1)"
    - "the party shows that it has substantial need for the materials to prepare its case and cannot, without undue hardship, obtain their substantial equivalent by other means"
  - "If the court orders discovery of those materials, it must protect against disclosure of the mental impressions, conclusions, opinions, or legal theories of a party's attorney or other representative concerning the litigation"
  - "Any party ... may... obtain the person's own previous statement about the action or its subject matter."
- "Trial Preparation: Experts"
- "Claiming Privilege or Protecting Trial-Preparation Materials"
  - "Information Withheld...When a party withholds information otherwise discoverable by claiming that the information is privileged or subject to protection... the part must"
    - "expressly make the claim"
    - "describe the nature of the documents, communications, or tangible things not produced or disclosed- and do so in a matter that... will enable other parties to assess the claim"
  - "Information Produced... If information produced in discovery is subject to...protection... the party making the claim may notify any party that received the information..."
    - "After being notified, a party must promptly return, sequester, or destroy the specified information and any copies it has; must not use or disclose the information until the claim is resolved; must take reasonable steps to retrive the information if the party disclosed it before being notified..."
    - "The producing party must preserve the information until the claim is resolved"
  - "Protective Orders... In general... A party or any person from whom discovery is sought may move for a protective order in the court where the action is pending..."
    - "The motion must include a certification that the movant has in good faith conferred or attempted to confer with other affected parties in an effort to resolve the dispute without court action."
    - "The court may, for good cause, issue an order to protect a party...including one or more of the following"
      - "forbidding the disclosure or discovery"
      - "specifying terms, including time and place or the allocation of expenses, for the disclosure or discovery"
      - "prescribing a discovery method other than the one selected by the party seeking discovery"
      - "forbidding inquiry into certain matters, or limiting the scope of disclosure or discovery to certain matters"
      - "designating the persons who may be present while the discovery is conducted"
      - "requiring that a desposition be sealed and opened only on court order"
      - "requiring that a trade secret or other confidential research, development, or commercial information not be revealed or be revealed only in a specific way"
  - "Timing and Sequence of Discovery"
    - "A party may not seek discovery from any source before the parties have conferred as required by Rule26(f), except in a proceeding excepted from initial disclosure..."
  - "Supplementing disclosures and responses"
    - "In General... A party who has made a disclosure under Rule26(a)...request for production... must supplement or correct its disclosure or response"
      - "in a timely manner if the party learns that...the disclosure or response is incomplete or incorrect...and...had not otherwise been made known to the other parties during the discovery process or in writing"
      - "or as ordered by court"
  - "Conferences of the parties; Planning for discovery"
    - "discuss any issues about preserving discoverable information"
    - "develop a proposed discovery plan"
    - "attempt in good faith to agree on the proposed discovery plan"
    - "submitting to the court within 14 days after the conference a written report outlining the plan"
    - "A discovery plan must state the parties' views and proposas on"
      - "what changes should be made...for disclosure under Rule26(a)...including...when initial disclosure were made or will be made"
      - "the subjects on which discovery may be needed, when discovery should be completed, and whether discovery should be conducted in phases or be limited to or focused on particular issues"
      - "any issues about disclosure, discovery, or preservation of electronically stored information, including the form or forms in which it should be produced"
      - "any issues about claims of privilege or of protection as trial-preparation materials..."
      - "what changes should be made in the limitations on discovery imposed under these rules or by local rule, and what other limitations should be imposed"
      - "any other orders that the court should issue under Rule26(c)"
    - "Expedited Schedule...court may by local rule..."
      - "require the parties' conference to occur less than 21 days before the scheduling conference is held"
      - "require written report outlining the discovery plan to be filed less than 14 days after the parties' conferece..."
  - "Signing Disclosures and Discovery Requests, Responses, and Objections"


---

#### FRCP Rule 33. Interrogatories to Parties

- "Number. Unless otherwise... a party may serve on any other party no more than 25 written interrogatories, including all discrete subparts."
- "Scope. An interrogatory may relate to any matter than may be inquired into under Rule26(b). ... not objectionable merely because it asks for an opinion or contention that relates to fact or the application of law to fact, but the court may order that the interrogatory need not be answered until designated discovery is complete, or until a pretrial conference or some other time."
- "Answers and Objections"
  - "Responding Party. The interrogatories must be answered... by the party to whom they are directed; or... if that party is a public or private corp... a partnership, an association, or a governmental agency, by an officer or agent, who must furnish the information available to the party."
  - "Time to Respond. ...must serve its answers and any objections within 30 days after being served with the interrogatories."
  - "Each... must... be answered separately and fully in writing under oath."
  - "The grounds for objecting to an interrogatory must be stated with specificity."
  - "The person who makes the answers must sign them, and the attorney who objects must sign any objections."
- "Answer to an interrogatory may be used to the extent allowed by the Federal Rules of Evidence."
- "Option to produce business records.... if the burden of deriving or scertaining the answer will be substantially the same for ither party, the responding party may answer by..."
  - "specifying the records that must be reviewed, in sufficient detail..."
  - "a reasonable opportunity to examine and audit the records and to make copies, compilations, abstracts, or summaries."


---

#### FRCP Rule 34. Producing Documents, Electronically Stored Information, and Tangible things, or Entering onto Land, for Inspection and Other Purposes

- "In general. A party may serve on any other party a request within the scope of Rule 26(b)"
  - "to produce and permit the requesting party or its representative to inspect, copy, test, or sample the following items in the responding party's possession, custody, or control"
    - "any designated documents or electronically stored information...stored in any medium from which information can be obtained either directly or, in necessary, after translation by the responding party into a reasonably usable form"
    - "any designated tangible things"
  - "to permit entry onto designated land or other property possessed or controlled by the responding party, so that the requesting party may inspect, measure, survey, photograph, test, or sample the property or any designated object or operation on it."
- "Prodecure"
  - "Contents of the Request"
    - "must describe with reasonable particularity each item or category of items to be inspected"
    - "must specify a reasonable time, place, and manner for the inspection and for performing the related acts"
    - "may specify the form or forms in which electronically stored information is to be produced"
  - "Response and Objections"
    - "Time to Respond... must respond in writing within 30 days after being served or - if request was delivered under Rule26(d)(2)- within 30 days after the parties' first Rule26(f) conference."
    - "Responding to Each Item"
      - "the response must either state that inspection and related activities will be permitted as requested or state with specificity the grounds for objecting to the request, including the reasons."
      - "... may state that it will produce copies of documents or of {ESI} instead of permitting inspection. The production must then be completed no later than the time for inspection specified in the request or another reasonable time specified in the response."


---

#### FRCP Rule 37. Failure to Make or to Cooperate in Discovery; Sanctions

- "Motion for an order compelling disclosure or discovery."
  - "On notice to other parties and all affected persons..."
  - "motion must include a certification that the movant has in good faith conferred or attempted to confer with the person or party failing to make disclosure or discovery in an effort to obtain it without court action."
  - "must be made in the court where the action is pending"
  - "A motion for an order to a nonparty must be made in the court where the discovery is or will be taken."
  - "Specific Motions."
    - "If a party fails to make a disclosure required by Rule 26(a), any other party may move to compel disclosure and for appropriate sanctions."
    - "A party seeking discovery may move for an order compelling an answer, designation, production, or inspection...if:"
      - "a deponent fails to answer a question asked under Rule 30 or 31"
      - "a corporation or other entity fails to make a designation undr Rule 30(b)(6) or 31(a)(4)"
      - "a party fails to answer an interrogatory submitted under Rule 33"
      - "a party fails to produce documents or fails to respond that inspection will be permitted-or fails to permit inspection-as requested under Rule 34."
    - "oral deposition...party asking a question may complete or adjourn the examination before moving for an order"
  - "An evasive or incomplete disclosure, answer, or response must be treated as a failure to disclose, answer, or respond"
  - "Payment of Expenses; Protective Orders"
    - "If the Motion is granted...after giving an opportunity to be heard, require the party or deponent whose conduct necessitated the motion, the party or attorney advising that conduct, or both to pay the movant's reasonable expenses incurred in making the motion, including attorney's fees."
    - "The court must not order this payment if:"
      - "the movant filed the motion before attempting in good faith to obtain the disclosure or discovery without court action"
      - "the opposing party's nondisclosure, response, or objection was substantially justified..."
      - "other circumstances make an award or expenses unjust"
    - "If the Motion is Denied..."
      - "the court may issue any protective order authorized under Rule26(c) and must, after giving an opportunity to be heard, require the movant, the attorney filing the motion, or both to pay the part or deponent who opposed the motion its reasonable expenses incurred in opposing the motion, including attorney's fees."
      - "But the court must not order this payment if the motion was substantially justified or other circumstances make an award or expenses unjust."
    - "If the Motion is Granted in Part and Denied in Part"
      - "the court may issue any protective order authorized under Rule 26(c) and may, after giving an opportunity to be heard, apportion the reasonable expenses for the motion."
- "FAILURE TO COMPLY WITH A COURT ORDER"
  - "Sanctions Sought in the District Where the Deposition Is Taken"
    - "If the court orders a deponent to be sworn or to answer a question and the deponent fails to obey, the failure may be treated as contempt of court."
    - "If a deposition-related motion is transferred and the deponent fails to obey, the failure may be treated as contempt of either court."
  - "Sanctions Sought in the District Where the Action Is Pending"
    - "For Not Obeying a Discovery Order"
      - "If a party or a party’s officer, director, or managing agent—or a witness designated under Rule 30(b)(6) or 31(a)(4)—fails to obey an order to provide or permit discovery, the court may issue further just orders."
      - "directing that the matters embraced in the order or other designated facts be taken as established"
      - "prohibiting the disobedient party from supporting or opposing designated claims or defenses, or from introducing designated matters in evidence"
      - "striking pleadings in whole or in part"
      - "staying further proceedings until the order is obeyed"
      - "dismissing the action or proceeding in whole or in part"
      - "rendering a default judgment against the disobedient party"
      - "treating as contempt of court the failure to obey any order except an order to submit to a physical or mental examination"
    - "For Not Producing a Person for Examination"
      - "If a party fails to comply with an order requiring it to produce another person for examination, the court may issue any of the orders listed unless the disobedient party shows that it cannot produce the other person."
    - "Payment of Expenses"
      - "The court must order the disobedient party, the attorney advising that party, or both to pay the reasonable expenses, including attorney’s fees, caused by the failure"
      - "unless the failure was substantially justified or other circumstances make an award of expenses unjust"

- "FAILURE TO DISCLOSE, TO SUPPLEMENT AN EARLIER RESPONSE, OR TO ADMIT"
  - "Failure to Disclose or Supplement"
    - "If a party fails to provide information or identify a witness as required, the party is not allowed to use that information or witness as evidence unless the failure was substantially justified or is harmless."
    - "The court may order payment of reasonable expenses, including attorney’s fees"
    - "The court may inform the jury of the party’s failure"
    - "The court may impose other appropriate sanctions"
  - "Failure to Admit"
    - "If a party fails to admit what is requested and the requesting party later proves the matter true, the requesting party may move that the failing party pay reasonable expenses, including attorney’s fees."
    - "The court must so order unless:"
      - "the request was held objectionable"
      - "the admission sought was of no substantial importance"
      - "the party had a reasonable ground to believe that it might prevail"
      - "there was other good reason for the failure to admit"

- "PARTY’S FAILURE TO ATTEND ITS OWN DEPOSITION, SERVE ANSWERS TO INTERROGATORIES, OR RESPOND TO A REQUEST FOR INSPECTION"
  - "Motion; Grounds for Sanctions"
    - "The court may order sanctions if:"
      - "a party fails, after being served with proper notice, to appear for deposition"
      - "a party fails to serve answers, objections, or written responses to interrogatories or requests for inspection"
  - "Certification"
    - "A motion for sanctions must include a certification that the movant has in good faith conferred or attempted to confer with the party failing to act."
  - "Unacceptable Excuse for Failing to Act"
    - "A failure is not excused on the ground that the discovery sought was objectionable unless the party has a pending motion for a protective order."
  - "Types of Sanctions"
    - "Sanctions may include any of the listed orders."
    - "The court must require the failing party, the advising attorney, or both to pay reasonable expenses unless the failure was substantially justified or other circumstances make an award of expenses unjust."

- "FAILURE TO PRESERVE ELECTRONICALLY STORED INFORMATION"
  - "If electronically stored information that should have been preserved is lost due to failure to take reasonable steps, and it cannot be restored or replaced, the court:"
    - "upon finding prejudice, may order measures no greater than necessary to cure the prejudice"
    - "only upon finding intent to deprive another party of the information’s use may:"
      - "presume that the lost information was unfavorable to the party"
      - "instruct the jury that it may or must presume the information was unfavorable"
      - "dismiss the action or enter a default judgment"

- "FAILURE TO PARTICIPATE IN FRAMING A DISCOVERY PLAN"
  - "If a party or its attorney fails to participate in good faith in developing a proposed discovery plan, the court may require that party or attorney to pay reasonable expenses to another party."

























