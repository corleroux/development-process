# Software development life cycle defined

**Based on the 3D SDLC Model**

#### Design <a id="design"></a>

1. [Planning](sdlc-components/planning-the-project.md)
2. Systems Analysis and Requirements
3. Systems Design

#### Develop

1. Development
2. Integration and Testing

#### Deploy

1. Implementation
2. Operations and Maintenance

## 1. The Plan \(Planning the project\) <a id="design"></a>

### Purpose

1. Bring together the main stakeholders of the system
2. Feasibility study to determine
   * Economical viability
   * Technical viability
   * Operational viability

### Deliverable

Estimation of

* Cost
* Schedule

_It's important to note that these two deliverable are only an estimate given the high level nature of the requirements. The final cost and schedule will be provided upon conclusion of phase 3 after which the stakeholders will re-evaluate the actual figures._

### Essential requirements

It's critical that ALL the stakeholders attend the planning session / phase in order to avoid costly renegotiation later on in the project. All parties should understand the viability, scope as well as priority at the conclusion of this phase to avoid confusion and miscommunication during the progress of the project.

1. Know the target audience and purpose of the Software
   1. Target Audience: Who is going to use this software?
      * Helps build the solution from the end user's perspective
   2. Purpose: Why is this software required?
2. Identify the problem
   1. Software are built to address a specific problem
   2. Explore and understand the problem completely before applying a technical solution to the problem

### RACI Matrix

| Responsible | Accountable | Consulted | Informed |
| :--- | :--- | :--- | :--- |
| Scrum Master | Head of Systems | Business stakeholders Head of Systems | Business stakeholders |

### Tooling

## 2. The Definition \(Systems analysis & requirements\)

### Purpose

The team explores both the functional and non-functional requirements of the project. Business analysis principles are used to liaise between business stakeholders and the technical experts who will be creating the system.

These principles include:

* Collating factual data
* Identifying software flaws
* Understanding the information architecture
* Developing solutions to overcome weaknesses in the project

### Deliverables

1. Draw the project timeline and scope
2. Detailed software requirement specification \(SRS\) which will be used to create the system design
   * End user requirements are captured in a technical format
   * Defines the functionalities that will be designed and developed during the project lifecycle

### Essential requirements

The availability of both the business process experts together with the technical experts are guaranteed during this phase. It's essential that both parties avail themselves for these sessions to ensure that any and all questions are answered in order to facilitate a smooth and timeous completion of this phase.

### RACI Matrix

| Responsible | Accountable | Consulted | Informed |
| :--- | :--- | :--- | :--- |
| Business Analyst | Head of Systems | Business process Expert Technical Expert | Business stakeholders |

### Tooling

## 3. The Design \(Systems Design\)

### Purpose

High level architectural design of the software, covering the overall system architecture and database design. Following the creation of the design document specification \(DDS\), the stakeholders review, discuss and approve the proposed architecture. _Although not necessary, more than one approach can be proposed and the best solution is picked during the stakeholder review session._

The selected approach, including the feedback from the review session, is signed off by the stakeholders.

The DDS serves as the roadmap for the development phase.

_**The reason the SDLC process requires the planning, definition and design phases before any development can begin, is to eliminate any confusion, inaccuracies and changes to requirements when the actual development work starts.**_

### Input

1. SRS documentation

### Deliverables

1. Signed off design document specification \(DDS\)
2. Project estimates
   * Time & Cost

### Essential requirements

1. Stakeholders review the design plans to re-evaluate the project in terms of:
   * Time
   * Cost
   * Feasibility 
2. Approval of the design specifications

**The time and cost figures presented in this phase should be the final estimates upon which the progress of the project will be measured against.**

### RACI Matrix

| Responsible | Accountable | Consulted | Informed |
| :--- | :--- | :--- | :--- |
| Technical Expert | Head of Systems | Business analyst Business process Expert Infrastructure Expert | Business stakeholders |

### Tooling

## 4. Building the solution \(Developing the system\)

### Purpose

Following the roadmap set out in the previous phases, the development team start to develop the system based on the requirements specification documentation.

### Deliverables

1. Working software ready to handed over to the testing team
2. Passing unit tests for specific features and or modules

### Essential requirements

If the previous phases were thorough and detailed, the development team will be able to create the software components with minimal difficulty.

Most of the problems encountered during the development phase are as a result of inaccuracies or changes to the project’s requirements, which cause developers to spend additional time researching and revising their source code.

### RACI Matrix

| Responsible | Accountable | Consulted | Informed |
| :--- | :--- | :--- | :--- |
| Technical Expert | Head of Systems | Business analyst Business process Expert | Testing Expert Infrastructure Expert |

### Tooling

## 5. Verifying the solution \(Integration & Testing\)

### Purpose

The testing team needs to ensure that the project has met the requirements that were determined in the planning and design phases. They identify as many defects as possible during the allocated time and prioritize them for correction by the development team.

Types of tests to be performed during the testing phase:

* Integration testing
* Acceptance testing
* System testing

### Deliverables

* Prioritized list of bugs to be fixed by the development team
* Stable increment of the product, ready to be deployed
* Automated test packs for specific features and or modules

### Essential requirements

Once the product satisfies the quality standards defined during the planning phase, the project can be deployed.

### RACI Matrix

| Responsible | Accountable | Consulted | Informed |
| :--- | :--- | :--- | :--- |
| Testing Expert | Head of Systems | Business analyst Business process Expert Technical Expert Infrastructure Expert | Technical Expert Infrastructure Expert Business process Expert |

### Tooling

## 6. Release to the wild \(Implementation & Deployment\)

### Purpose

The system is deployed to the production environment once it has passed the testing phase. Deployment consists of installing the software and any required hardware for the end users to begin using it.

### Deliverables

1. Detailed deployment plan \(especially if the system is replacing a system already in use\)
   * Including a smoke testing plan post deployment to ensure current functionality as well as any new features work as expected in the production environment.
   * Including a comprehensive rollback plan / strategy in case of catastrophic system failure.
2. Training plan / schedule
   * Including documentation to help end users learn to use the system and any new feature / s that's been deployed.
3. Support handover documentation
   * Including technical documentation detailing the implementation of the system and any feature / s deployed
     * Software perspective
     * Hardware perspective

### Essential requirements

It's essential that the development, testing and infrastructure teams work closely together in order to achieve the deliverables of this phase.

Change controls need to be in place to ensure that all relevant stakeholders are aware of all changes to the production system.

* Change control template
* Change control signoff process
* Change control communication strategy

### RACI Matrix

| Responsible | Accountable | Consulted | Informed |
| :--- | :--- | :--- | :--- |
| Deployment Expert | Head of Systems | Technical Expert Infrastructure Expert Testing Expert | Business stakeholders |

### Tooling

## 7. Eye on the Prize \(Operations & Maintenance\)

### Purpose

After deployment the system and new features will be maintained by the development and infrastructure support teams.

### Deliverables

1. Repairs to the system when failures occur
2. Patching any known or newly uncovered defects
3. Can include incremental features that do not require significant changes to the system or the design of the system

### Essential requirements

Clearly defined service level agreement detailing classification of defects and turn around times for resolving classified defects. All stakeholders needs to be aware of the definitions contained within the SLA as to eliminate confusion and manage expectations of both the end user as well as the support teams.

### RACI Matrix

| Responsible | Accountable | Consulted | Informed |
| :--- | :--- | :--- | :--- |
| Incident Manager | Head of Systems | Technical Expert Infrastructure Expert | Business stakeholders End users |

### Tooling

Support ticketing system

## Glossary

| Term | Description |
| :--- | :--- |
| Business stakeholders | All parties that has a stake in the system. Usually refers to all department heads and all business owners |
| Head of Systems | Manager responsible for systems |
| Business process Expert | Subject matter expert within a given business unit |
| Technical Expert | Subject matter expert within the given system |
| Testing Expert | Subject matter expert within the testing business unit |
| Infrastructure Expert | Subject matter expert within the infrastructure \(I.T.\) business unit |
| Deployment Expert | Subject matter expert within the DevOps business unit |
| Incident Manager | Manager responsible for support and maintenance of all systems |
| End users | Any individual that use the system to perform any part of their daily work |

