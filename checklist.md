#### Before You Start (Group Setup)
- [ ] Have a Group meeting and decide on how you will work (some form of Agile approach such as using a Kanban board for example)
- [ ] Agree on a communication channel (Teams, Discord etc)
Create a shared repository or folder structure - either in Teams or Gitlab /Bitbucket / Github etc
- [ ] Decide on report language (if English, remember the exam is in Danish)
- [ ] Read the project brief carefully

#### Week 1 — System Definition & Threat Modelling
- [ ] Clearly describe the system and its purpose
- [ ] Identify key data types (student, staff, research, audit data)
- [ ] Identify threat actors (internal, external, accidental, malicious)
- [ ] Create an initial threat model
- [ ] Note assumptions and system boundaries

Exam tip: Be able to explain why a specific threat matters more than others.

#### Week 2 — Authentication & Identity Management
- [ ] Identify all user and identity groups
- [ ] Decide how each group authenticates
- [ ] Consider MFA and usability trade-offs
- [ ] Identify identity-related risks (phishing, shared credentials)
- [ ] Justify authentication choices in writing

Exam tip: Think abour compromised accounts and usability vs security.

#### Week 3 — Authorisation & Role-Based Access Control
- [ ] Define system roles clearly
- [ ] Create an access control matrix
- [ ] Apply the principle of least privilege
- [ ] Identify risks of over-privileged roles
- [ ] Explain how credentials are stored (hashing vs encryption)

Exam tip: You may be asked: “What happens if this role is misused?”

#### Week 4 — Data Storage, Integrity & Cryptography
- [ ] Identify where data is stored (on-prem vs cloud)
Distinguish block, file, and object storage conceptually
- [ ] Decide which data is hashed and which is encrypted
- [ ] Explain how data integrity is verified
- [ ] Identify integrity threats (accidental or malicious)
- [ ] Reflect on SBOM or dependency-related risks
- [ ] Define a backup and restore strategy and explain the options for backing up data (short, long term, )

Exam tip: Be able to explain why encryption does not guarantee integrity. Also you will almost certainly be asked about backups and restore policy
(how often, different types of media, location of backups, restore policies etc)

#### Week 5 — Auditing, Logging & Accountability
- [ ] Explain the difference between logs and audit trails
- [ ] Identify which actions must be audited
- [ ] Design layered audit trails (application, database, storage)
- [ ] Decide who can access audit data
- [ ] Explain how an incident would be investigated

Exam tip: Think like an investigator: “How could you prove what happened?”

#### Week 6 — Encryption at Rest & in Transit
- [ ] Decide where encryption at rest is required
- [ ] Consider whole disk encryption and its limits
- [ ] Identify where TLS is required
- [ ] Explain symmetric vs asymmetric encryption conceptually
- [ ] Identify what encryption does not protect against

Exam tip: Be prepared to challenge statements like “The data is encrypted, so it’s safe.”

#### Week 7 — Data in Use & Data in Motion
- [ ] Identify when data is decrypted and actively used
- [ ] Trace data flows through the system
- [ ] Identify exposure risks (memory, UI, logs, tokens)
- [ ] Understand token-based access (e.g. JWT conceptually and with an example)
- [ ] Propose realistic mitigations beyond encryption

Exam tip: Expect questions about the limits of technical controls.

#### Week 8 — Governance, Classification & Lifecycle
- [ ] Classify all major data types
- [ ] Define retention and deletion policies
- [ ] Map security controls across the data lifecycle
- [ ] Identify ethical or organisational concerns
- [ ] Synthesize all decisions into a coherent narrative

Exam tip:
Be ready to discuss responsibility and accountability.

#### Technical Artefacts Checklist
- [ ] Small Python or Go scripts (hashing, encryption, integrity checks)
- [ ] Clear comments and explanations
- [ ] Evidence of tool usage (screenshots, logs, outputs)
- [ ] Artefacts referenced clearly in the report

Remember: 
The artefacts demonstrate understanding — they do not need to be completely working or finished just good enough to show how they could be used.

#### Report Quality Checklist
- [ ] Report is within 15–20 pages (a lot but it will really help in the future - your own guide to data security policies, concepts and technics 😀 )
- [ ] Clear structure matching project brief
- [ ] Consistent terminology
- [ ] Explicit justification of decisions
- [ ] Clear reflections on limitations and trade-offs

#### Exam Preparation Checklist
- [ ] Understand the entire project, not just things you worked on
- [ ] Be able to explain key decisions without notes
- [ ] Reflect on what you would improve with more time
- [ ] Be honest about limitations and assumptions

#### Final Self-Check
Before submission, ask yourself:
- [ ] Can I explain why we made each major security decision?
- [ ] Can I identify the biggest remaining risk?
- [ ] Can I defend our design under questioning?
If yes — you are ready!!