### BAFIN
- [BAFIN Circular 10/2017 (BA) in the version of 16.08.2021](https://www.bafin.de/SharedDocs/Downloads/EN/Rundschreiben/dl_rs_1710_ba_BAIT_en.pdf%3F__blob%3DpublicationFile%26v%3D6)

To all credit institutions and financial services institutions in the Federal Republic of Germany
Supervisory Requirements for IT in Financial Institutions (BAIT)


#### 3. Information risk management

#### 3.1

The processing and sharing of information in business and service processes is supported by data processing IT systems and related IT processes.
The scope and quality thereof shall be based, in particular, on the institution’s internal operating needs, business activities and risk situation (see AT
7.2 number 1 of MaRisk). **The IT systems, the related IT processes and the other components of the information domain shall ensure the integrity,
availability, authenticity and confidentiality of the data (see AT 7.2 number 2 of MaRisk)**. The institution shall define and coordinate the tasks, competencies, responsibilities, controls and reporting channels required for the management of information risk (see AT 4.3.1 number 2 of MaRisk). To
this end, the institution shall set up appropriate monitoring and steering processes (see AT 7.2 number 4 of MaRisk) and define the related reporting requirements (see BT 3.2 number 1 of MaRisk).

### 4. Information security management

#### 4.4 

The management board shall establish an information security officer
function. This function is responsible for all information security issues within the institution and with regard to third parties. It ensures that information security objectives and measures defined in the institution’s IT strategy, information security policy and information security guidelines are transparent both within the institution 
and for third parties, and that compliance with them is reviewed and monitored regularly and on an event-driven basis.

The information security officer function has in particular the following tasks:
- supporting the management board when defining and changing the information security policy and advising on all issues of information security; this includes helping to resolve conflicting goals (e.g. economic aspects versus information security);
- preparing information security policies and, where appropriate, any other relevant regulations as well as checking compliance;
- managing and coordinating the institution’s information security process as well as monitoring the involvement of IT service providers and assisting in any related tasks;
- supporting the preparation and updating of the contingency plan with regard to information security issues;
- initiating and monitoring the implementation of information security measures;
- monitoring and working to ensure compliance with information security in projects and procurement;
- **acting as a contact for any questions relating to information security coming from within the institution or from third parties**;
- examining information security incidents and reporting these to the management board;
- initiating and coordinating measures to raise awareness of and training sessions on information security.
The information security officer may be supported by an information security management team.


#### 4.8

The institution shall introduce a **policy on testing and reviewing measures to protect information security** and shall review it regularly and on an event-driven basis and modify it if necessary. 

Among other things, the policy shall cover:
- the general threat level;
- the institution’s individual risk situation;
- categories of test and review subjects (e.g. the institution, IT systems, components);
- the nature, scope and frequency of tests and reviews;
- responsibilities and arrangements for avoiding conflicts of interest.

### 5. Operational information security

#### 5.3

**Threats to the information domain shall be identified as early as possible**. Potentially security-related information shall be evaluated suitably promptly, using a rule-based approach, and centrally. This information shall be protected during transport and storage and shall be
held available for an appropriate period for subsequent evaluation.
Examples of potentially security-related information include log data, reports and disruptions that could indicate breaches of protection objectives.
As a general principle, the rule-based evaluation (e.g. using parameters, correlation of information, deviations or patterns) of large data volumes requires the use of automated IT systems.
Subsequent evaluations include forensic analyses and internal improvement measures. The period of time should be appropriate to the threat level.

#### 5.6

**The security of the IT systems shall be reviewed regularly**, on an event-driven basis while avoiding any conflicts of interest. 
Results shall be analysed to establish any necessary improvements and risks shall be managed appropriately.
The frequency, nature and scope of the review should be based in particular on the protection requirements and the potential vulnerability of the IT system (e.g. extent to which it can be reached from the internet).
Examples of types of reviews include:
- variance analysis (gap analysis);
- vulnerability scans;
- penetration tests;
- simulated attacks


### 7. IT project and application development

#### 7.8 

**In the context of application development**, appropriate arrangements shall be made, depending on the protection requirement, such that **after each application goes live the confidentiality, integrity, availability and authenticity of the data to be processed are also comprehensibly assured**.
Suitable arrangements include:
- checking of input data;
- system access control;
- user authentication;
- transaction authorisation;
- logging of system activity;
- audit logs;
- tracking of security-related incidents;
- handling of exceptions.

#### 7.11 

**A methodology for testing applications prior to their first use and after material modifications shall be defined and introduced**. The scope of the tests shall include the functionality of the application, the measures implemented to protect information and, if relevant, system performance under various stress scenarios. The responsible organisational units shall be responsible for performing acceptance tests.
Performance of the tests requires relevant expertise on the part of the testers as well as appropriately structured independence from the application developers. The protection requirements of the data used for the test shall be taken into account.
Test environments for performing the acceptance tests shall correspond to the production environment in aspects material to the test. Test activities and test results shall be documented.
Test documentation contains the following points as a minimum:
test case description;
documentation of the parameterisation underlying the test case;
test data;
expected test result;
actual test result;
measures derived from the tests. In a risk-based approach, the measures to protection information also include penetration tests.

#### 7.12
**After the application goes live, any deviations from standard operations shall be monitored**, their causes shall be investigated and, where appropriate, measures for subsequent improvement shall be taken. Indications of serious shortcomings may include, for example, repeated incidences of deviations from standard operations.
