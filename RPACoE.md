

![](https://labs.sogeti.com/wp-content/uploads/2019/02/Core-Capabilities-of-an-RPA-COE-1024x587.jpg)



 
* **Governance:** establish the policies, procedures, and standards for bot qualification, development and deployment to meet audit, regulatory, information security, and compliance requirements;
* **Technology:** select the right automation tools and then organize the maintenance and support of these tools. Drive the integration of RPA into the fabric of IT Service Management (ITSM), including change management and the configuration management database (CMDB);
* **Processes:** execute and monitor the complete lifecycle of RPA in the enterprise, from evaluating automation opportunities to deploying bots into production environments with a scalable support structure;
* **People and Culture:** analyze and effect the changes to human roles by RPA, from organizational change management (OCM) to redefined job descriptions and even altered org structures;
* **Organization:** define the organizational structure of the COE itself, including the definition of a RACI chart to define the roles and responsibilities for all aspects of RPA;


![](https://labs.sogeti.com/wp-content/uploads/2019/02/2-1-1024x576.jpg)



The COE as a support function for the business: this model provides a loosely governed operating model, most suitable for less regulated industries (e.g., consumer packaged goods, industrial manufacturing, etc.). In this scenario, the lines of business establish their own COE guidelines and structures, which can aid speed and flexibility but may hamper scalability.
The COE as a central RPA provider: this model provides a shared service comprised of business and IT members who manage all aspects of RPA intake, delivery and support. This option supports high scalability but can require more significant discussions with business and IT stakeholders to establish the framework for a true shared service.
The COE in IT as enabler for business: on the opposite side of the spectrum from the first option is a COE closely managed by IT. While it’s usually easier to get executive support for this model, it can hamper enterprise scalability in some cases.


* **Automation Strategy** – What are the vision, charter, roadmap and measures of success for automation? How to identify attractive automation candidates?  How to prioritize and justify automation investments with a compelling business case?
* **Technology Strategy** – What is the right automation technology solution?  How and when to embrace more advanced automation technologies (assisted automation, chat-bots, OCR, artificial intelligence/machine learning)?  How to build a scalable automation architecture?
* **Governance** – What types of governance bodies are required? How should automation investments be funded and who should have what decision rights?  What are the new roles and responsibilities?
* **People Enablement** – What kinds of skill sets need to be built in order to support automation?  What should be the Change Management strategy?  How do I manage the people impacts of automation / reskill people for new ways of work?
* **Operating Model** – How to organize around RPA?  Should RPA be a business or IT solution?  What kinds of controls need to be put in place around the technology?
* **BOT Development & Support** – What are the right development methodology, tools and standards for automation?  What do we design for reusability and manage robots as an asset?  How to manage and monitor an RPA environment?


![](https://www.infosysconsultinginsights.com/wp-content/uploads/2017/12/Automation_Center_Of_Excellence2.png)

![](https://www.acronotics.com/images/consulting/coe-framework.png)

## Governance Committee
The RPA GC should comprise of the leaders from those business units and functional areas (F&A, HR, Ops & Tech etc.) that are participating in the program. Irrespective of the participating areas, the GC should include exec(s) representing the CFO & the IT organisation, the former for budgetary decisions, and the latter for infrastructure, security & deployment considerations. An overall CoE Head with the mandate to deliver the automation program across the organisation is recommended and should be part of this committee.

The GC is essentially a governance entity and its main role is to:
* Set objectives
* Track progress
* Give direction
* Resolve conflict

## Business Analysis Team
These are the designated RPA champions, process experts & business analysts from each business unit/ functional area. This should be a federated team, sitting within their respective units and driving the automation program within that unit.

The BA team in each unit is responsible for:
* RPA Evangelization
* Process Identification
* Feasibility Analysis
* Complexity Analysis
* Process Prioritization
Process expertise tends to be specific to a business/ function, hence having a central BA pool does not serve a meaningful purpose.

## Core Resource Pool
These are the people who actually design, build and deploy the bots. The key roles are:
* Delivery Managers
* Project Managers
* Solution Architects
* Tech Architects
* Bot Developers
 
The core resource pool should be centralized, with resources being allocated to business units for specific projects, and returning to the pool after each project is completed (for reallocation to a new project).

The skills required for bot development are not (necessarily) linked to knowledge of a particular process area. Although a developer who works on multiple projects in the same process area will undoubtedly become more productive over time, optimal resource allocation is on balance the bigger consideration here. If each process area has its own captive team of automation engineers, it simply leads to isolated pockets of underutilized resources. And these distributed resource typically fail to share knowledge and learn from each other.

A centralized pool of development resources leads to:

* Optimal resource allocation & utilization
* Knowledge sharing & expertise transfer between units
* Efficient gap-identification, training & re-skilling of the resource pool

## Common Standards (Team)

A well-organized automation program should have a centralized, shared repository of:

* RPA Standards
* Design Principles
* Best Practices
* Frameworks, Methodologies & Tools (FMT)
The need for maintaining such a shared library is self-evident. The standards team itself can be quite small, but it must be mandatory for each project team to utilize the common standards, as well as contribute to the repository by adding new elements and enhancing the existing ones.

## Bot Factory

Bots should be designed and built in a modular fashion, since every process is just a sequence of sub-processes, and many of the sub-processes are common across many processes. The most obvious sub-process in this respect is logging into (or logging out of) a particular application. If a mini-bot is built that simply logs into an application, this component can then be reused across multiple process bots.

As the automation program scales up, having a centralized bot factory with such components can significantly improve the productivity of the automation team.

## Quality Assurance

We recommend having a small, centralized team of QA leads whose job is to:

* Enforce Standards
* Perform Quality Control
* Set Acceptance Criteria
* Collect & report metrics to GC
The central QA team functions as an independent third-eye mechanism, and ensures that standards are being enforced, quality is being maintained, and metrics are being reported.

## Bot Maintenance

Once bots have been put into production, there is a need for a techno-functional maintenance team in order to:

 Provide production support for the live bots (to ensure that they run smoothly)
 Carry out minor enhancements to the bots (for example, if some underlying application is changed)
 Ensure that BCP & DR plans are in place and can be executed if needed
The Bot Maintenance team can be either centralized or decentralized depending on the company’s context and needs.

## Summary

Acronotics has developed a comprehensive CoE framework based on extensive hands-on experience of what works and what doesn’t. We recommend the following:

* Decentralized (federated) BA team in each business unit/ process area
* Centralized Standards, QA team and Bot Factory
* Centralized Core Resource Pool with allocation to business units
* Centralized or federated Bot Maintenance team as appropriate
 

* **Set up an RPA team with well-defined roles and responsibilities.**
	Identify an RPA sponsor, change manager, solution architects, developers, infrastructure and service support to take on key roles in the RPA CoE. The team needs to understand how to work well together – and with stakeholders – to deploy automation technology, adhere to standard processes and procedures, and measure business metrics and performance goals, including return on investment and customer satisfaction.
* **Establish an RPA CoE Council.**
	The RPA CoE Council is essentially a steering committee that provides overall governance and direction. It should meet regularly and include key representatives from the business, IT, Finance, audit, RPA CoE and others who will ensure the outcomes of RPA initiatives are in line with the objectives and expectations of executive management. The CoE Council should focus on driving RPA adoption across business units to create economies of scale and into the design and performance of the organization.
* **Establish an effective governance model.**
	As RPA deployment expands across an enterprise, the RPA CoE likely will face challenges related to cross-departmental collaboration. This requires a governance framework that determines participation and interaction among different departments and establishes protocols and prioritization for managing and sharing knowledge. The governance structure also should create a framework for developing and applying best practices to each stage of an RPA implementation.
* **Proactively manage organizational change.**
	Effective change management lays the groundwork for the successful transfer of work from humans to robots and is an essential but often overlooked part of the implementation process. The main challenge with RPA is that the change comes much faster than with traditional automation deployment – so the CoE needs to help drive operational planning, organizational redesign and before/after work process disposition.
* **Collaborate with IT.**
	As the RPA footprint expands across business units, IT support becomes increasingly important. The CoE should engage IT functions, including infrastructure, service/support, security and compliance. Many CoEs name an “IT liaison” to work directly with the CoE team to coordinate automation development so IT is in synch with security and compliance needs and to help resolve IT issues that may arise.


* Where is RPA best anchored in the enterprise structure?
* Who owns it?
* Who leads it?
* What is involved?
* How many people are needed?
* What expertise is required?
* How long will this take?
* What is an ideal budget?


# 6 Steps to Creating an RPA Center of Excellence
It's important to follow these six steps to help ensure the success of your CoE:
* **Build some robots first:**
	Before you even establish your CoE, it’s important to learn the technology first. Your organization probably doesn’t have much RPA experience and may be confused by unrealistic claims made by some solutions out there. Gaining the right experience will enable more informed choices and set up your CoE for success.
* **Focus your CoE on business outcomes:**
	Automation must support your overall strategy, and intelligent process automation involves leveraging a variety of technologies, such as BPM, robotics, analytics, artificial intelligence, and machine learning. Instead of focusing on a specific technology, organize your CoE around important organizational objectives or business outcomes.
* **Build business and end user support:**
	Getting stakeholder support is fundamental. Connect your CoE to business needs, executives who support it, and the operational teams critical to its success. Remember to evangelize early and often with key stakeholders.
* **Define your operation model:**
	Will your CoE take a centralized or decentralized, federated approach? While both have their pros and cons, many organizations are leaning toward a federated approach. In this setting, it’s important to have a simplified design environment to support robots built by business analysts instead of programmers. However you define your CoE model, it is critical to standardize testing and deployment across multiple business units.
* **Identify quick wins:** An advantage of RPA is its potential to improve process performance quickly. The ability to apply RPA surgically can accelerate time to value and provide great return on investment in a specific department versus a corporate-wide project that may require buy-in across many departments in the organization.
* **Establish governance:**
	Creating a governance process is its own unique challenge within the CoE. Remain agile, build robots quickly, and repeat based on lessons learned


# Where to Go From Here
* Build the essential skills and capacity for RPA
* Establish an effective governance model
* Best practices
* Tools and standards
* Train, prepare and scale up
 
 RPA USE CASES BY FUNCTIONAL AREAS
# HR
HR processes typically involve lots of manual processes such as form filling, data gathering & updating, request processing and so on, providing a fertile ground for productivity improvement through robotic automation. Processes that can be automated in part or whole include:
* Recruitment
* Employee On-boarding
* Payroll Processing
* Tax Withholding (W4 Management)
* Education & Training
* Time & Attendance Management
* Benefits Administration
* Stock Administration
* Personnel Administration
* Compliance & Reporting

# Financial & Accounting
F&A processes are full of automation opportunities. As an example, RPA can cut the cost of invoice processing by as much as 60%. Typical F&A process areas that are ripe for automation are:
* Procure-to-Pay
* Employee On-boarding
* Order to Cash
* Customer Master Data Management
* Credit Management
* Order Management/ Fulfilment
* Billing & Invoicing
* Collections
* Record-to-Report
* Account Closing
* Statutory Reporting
* Tax Compliance
* Treasury Management
* Cost Accounting

# IT Services
Modern companies are heavily dependent on IT. While many aspects of IT are complex and require human intelligence, it is estimated that nearly a third of IT Services comprises of low-level system admin tasks that can be automated away, such as:
* Software Installation
* Server & Application Monitoring
* Running diagnostics & system checks
* Taking Backups
* Email processing & distribution
* File Management
* Batch Processing
* FTP Management
* QA & Testing

# Supply Chain Management
The complex coordination between suppliers, warehouses, manufacturing facilities, transporters and customers is typically rife with inefficient, manual, and un-coordinated processes. Supply chain issues can be responsible for a 20% erosion in value in many companies. RPA can be applied to supply chain processes such as:

* Demand & Supply Planning
* Inventory Management
* Quote, Invoice & Contract Management
* Work Order Management
* Freight Management
* Returns Processing

# Customer Service
Customer service related processes offer a rich hunting ground for RPA use cases.

Most companies have call centres and service desks to deal with incoming customer calls. In today’s multi-channel environment, customers can get in touch with a company through many different channels – phone call, mobile app, online, email, chat applications etc. A customer might call to place an order, make a query, seek information, update personal details, track or cancel and order, raise a complaint and so on. Typically, call centres use a number of different systems and applications to service these requests. The agents carry out a high volume of low complexity repetitive tasks, involving accessing, translating & updating information across different channels & systems while executing the required actions. This process can be slow, inaccurate and irritating. RPA can be used to create Virtual Customer Service Agents and thus automate, speed-up and improve the quality of the entire customer experience.


# Integration of Silos & Data Management
As a result of multiple organic and inorganic growth factors, many companies are run in a non-integrated, siloed manner. RPA can fix these problems.

A typical business process might run across disparate systems with manual or semi-automated hand-offs. Data is siloed across multiple systems and applications that may or may not talk to each other. Ad-hoc end-user computing systems (typically spreadsheets) are used extensively. RPA is the ideal solution to eliminate organisational inefficiencies arising from such silos.

Today’s businesses collect data from multiple sources, such as web pages, invoicing systems, emails and excel spreadsheets. This requires individuals to log in and out of multiple systems, and copy & paste data between different sources and formats. RPA can be used to automate these high-volume, low complexity tasks.

Examples of use cases are:
* Application Integration
* ERP Integration/ Automation
* Data Aggregation/ Migration
* CSV file imports
* Excel automation
* Business Intelligence



# RPA USE CASES BY INDUSTRY

## Banking
* Account opening
* Client on-boarding & KYC compliance
* Account management
* Form filling/ order taking
* Fraud management
* Status monitoring and alerts
* Position matching and reconciliation
* Report creation
* Claims processing
* Credit limit changes
* Data aggregation/ migration across systems

## Insurance
* Policy administration
* Claims processing
* Recoveries
* Redemptions processing
* Customer data gathering & validation
* Amend customer data (address, direct debit etc.) across systems
* Data aggregation/ migration across systems

## Technology/Software
Hardware and software testing/ test automation, application integration.


## Telecommunications
Collecting and consolidating data from client phones, backing up information from client phones, uploading data, extracting data about competitor pricing, extracting phone manufacturing information.


## Manufacturing
ERP automation, automation of logistics data, data monitoring, product pricing comparisons.


## Government
Filling subcontractor forms, automating verification processes, integrating legacy systems, automating reports.


## Healthcare
Patient data migration and processing, reporting for doctors, medical bill processing, insurance data automation and claim processing, triggering emails from medical billing systems, claim status and eligibility automation, and patient record storage.


## Consumer Goods
Order processing, data entry, resolution consulting, claims processing, FTP automation, incentive claims processing.


## Hospitality
Competitor pricing analysis, guest data processing, data verification, payment processing, user account creation.


## Retail
Extract product data from manufacturers websites, automatically updating online inventory and product information, importing website and email sales.


![](https://www.acronotics.com/images/consulting/process-prioritization-model.png)
![](https://www.acronotics.com/images/consulting/rpa-criteria-shortlisting-use-cases.png)
![](https://www.acronotics.com/images/consulting/acronotics-intelligent-automation-framework.png)
![](https://www.acronotics.com/images/consulting/human-actions-automation-ai.png)


# Developing an Automation Roadmap



# PROCESS DISCOVERY WORKSHOPS
The first step in getting an automation program off the ground is to identify processes that are possible candidates for automation. Acronotics’ approach is to conduct a series of quick workshops with the process owners for the business areas that are being considered for automation. These workshops have the following characteristics:

* The Acronotics Business Analysts are armed with a repository of well-known use cases in each functional area, and they drive the discovery process towards these use cases in order to quickly come up with a practical roadmap.
* A pilot of 5-6 processes is identified which can be implemented quickly with a small investment in order to prove to management that the solution works.
* Acronotics’ templates for Feasibility, Complexity & Effort Analysis focus on the minimal data that is necessary to develop the plan, instead of getting into a long-drawn out theoretical analysis. We adopt a pragmatic, pareto-optimal approach to develop the business case for automation.
 
# PROCESS PRIORITIZATION MODEL
Once candidate processes have been identified through the process discovery workshops, the next step is to analyze and prioritize them. This involves assessing the following for each candidate process:
*  Feasibility for automation
*  Complexity to automate
*  Effort & cost to automate
*  Savings from automation
*  Return on Investment (ROI)
Most consulting firms use elaborate models to carry out this analysis, which takes a lot of time and involves a substantial upfront investment just to develop the business case for automation.

Acronotics is able to expedite this process by ensuring that the key data elements for this analysis are gathered during the process discovery workshop itself. Our approach focusses on delivering the following outcomes:
*  Getting the program off the ground as quickly as possible
*  Getting the first set of bots into production fast and with limited investment
*  Minimizing the Cost per Robot (CPR) and Time to Market (TTM) for the overall program
*  Finding the optimal intelligent automation solution for each process combining RPA with Machine Learning & other AI technologies

# Feasibility Analysis

Typical approaches to evaluating feasibility focus on what extant RPA software packages can or cannot handle.

These criteria are quite helpful in identifying quick wins that can be automated using a standard RPA tool. More complex processes with greater business impact get excluded in such analysis, in particular processes that:

*  Involve judgement calls or qualitative decision-making by a human operator
*  Involve scanned documents
 
![](https://www.acronotics.com/images/consulting/rpa-criteria-shortlisting-use-cases.png)

# ACRONOTICS INTELLIGENT AUTOMATION FRAMEWORK
The Acronotics Intelligent Automation Framework helps organizations design automation solutions for complex processes that RPA alone cannot handle. Feasibility is established not based on what RPA alone can automate, but what a combination of RPA & AI technologies can automate. This approach also enables us to develop a high level blueprint for automating the process right at the onset.

![](https://www.acronotics.com/images/consulting/acronotics-intelligent-automation-framework.png)
![](https://www.acronotics.com/images/consulting/human-actions-automation-ai.png)


## Complexity Analysis, Effort & Cost Estimation

Once feasibility (and high-level automation approach) have been determined, the next step is to estimate the complexity to automate the selected processes.

*  Acronotics has developed a data-driven model that enables us to estimate the complexity of automating each process.
*  Once the complexity level has been established, the model correlates it to the effort and cost of automation for each process.


## Savings & Benefits Assessment

For each process (or a group of related processes), we estimate expected FTE savings by:

*  Establishing the current FTE count that is allocated
*  Determining the % of automation that is possible
For example, if a process has 5 FTEs allocated to it, and it can be 80% automated, the expected FTE saving is 4 FTE (leaving 1 residual FTE to carry out exception processing).

Besides FTE savings that can be more visibly measured, automation can deliver several other benefits with substantial $ savings, but these savings can be harder to quantify. These include:

*  Error reduction (once correctly built, bots don’t make mistakes)
*  Business agility & enhanced CSAT (faster, straight-through-processing)
*  Employee productivity & ESAT improvement (elimination of boring, mundane work)
*  Better regulatory compliance (bot-based reporting, monitoring & analysis)
Since it is not easy to nail down these savings, Acronotics recommends building the ROI model for automation based on hard savings from FTE reduction/ reallocation only. Even with only FTE savings taken into consideration, most well-designed RPA programs deliver a payback period of less than 1 year and a very solid ROI over 3-5 years.



# ROI Calculation

To calculate the ROI for an automation program, we need to bring together the following data elements:

*  Current FTE headcount allocated, and the fully loaded cost thereof
*  Residual FTE headcount after the processes have been automated
*  One-time cost of developing the bots (derived from the complexity & effort analysis)
*  Recurring cost of running the bots (license cost plus bot maintenance cost)
Once this information has been assembled, it can be plugged into the Acronotics ROI Model to arrive at the business case.

Summary – Developing an Automation Roadmap

*  Process Discovery Workshops – Leverage Acronotics Use Case Repository to identify candidate processes and capture relevant data for subsequent analysis
*  Apply Acronotics Intelligent Automation Framework to establish feasibility of automating the candidate processes as well as determining a high-level solution approach
*  Estimate the one-time cost of automation by carrying out Complexity Analysis followed by Effort & Cost Estimation
*  Estimate the running cost of automation by sizing the infrastructure (licenses & hardware) and working out the support requirements for the automation solution
*  Estimate the expected FTE savings from the current FTE allocation & expected % of automation
*  Put it all together into the Acronotics ROI Model.


# Implementation Bot Development 
 
 ## APPROACH
Acronotics executes automation programs in the agile mode. The schedule is broken up into a series of sprints, with each sprint running over 8-10 weeks covering business analysis, bot design, bot development, unit testing and UAT.

Each sprint can have one or more automation pods. Each pod has 3 automation engineers working as a team on a set of logically related processes. One pod can automate 3-5 processes in one sprint. So if a sprint has 2 pods, it can automate 6-10 processes.

In addition to the pod(s), the sprint team typically includes the following resources (shared across the pods)

*  A Team lead (TL) with end-to-end responsibility for all the pods
*  A Solution Architect (SA) who helps the automation engineers to develop the optimal automation solution for each process
*  One or more Business Analysts (BAs) who help in creating the Process Description Documents (PDDs) & Solution Design Documents (SDDs)
*  Optionally, one or more Quality Assurance (QA) lead(s) who help the pod teams in testing the bots
*  Optionally, production support engineers who get added to the team after the completion of the first sprint for on-going support of the bots as they go into production


A typical project schedule with two sprints and two pods in each sprint looks like this:

![](https://www.acronotics.com/images/implementation/project-schedule.png)



This approach ensures that:

*  Sets of 3-5 bots are going into production every 8 weeks or so. The program can be scaled up to deliver more bots in each sprint by simply adding more pods.
*  Related processes can be grouped logically into a pod so that they can be analysed, designed and built together.
*  This minimizes the amount of time that process SMEs have to spend with the automation team for the business analysis (related processes can be covered in one workshop by the same SMEs).
*  It also ensures that bots are smartly designed with a layered/ componentized architecture (as common elements across related processes can be built as reusable components).


Each sprint comprises of the following sequence of activities:

![](https://www.acronotics.com/images/implementation/sprint-sequence.png)


Analysis & Design

The Business Analysis Phase is usually the first two weeks of each sprint, during which the Acronotics team gets a detailed understanding of the as-is processes from the client’s process SMEs. The following is a list of activities involved (for each process):

Task	- Owner
Document as-is process in Process InVision	-> Process SME
Process Walkthrough (meeting)	->  Process SME + Acronotics
Prepare draft Process Description Document (PDD)	->  Acronotics
Process Review and Clarification (meeting)	->  Process SME + Acronotics
Signoff PDD	->  Process SME
Develop Solution Design Document (SDD)	->  Acronotics
Prepare Test Cases	-> Acronotics
Review Test Cases	-> Process SME




## Process Walkthrough

A Process Walkthrough is a discussion between the process SME(s) and the Acronotics BA(a) to understand the as-is process in detail.  Process walkthroughs need to be scheduled with the relevant SME(s) for each process.  

The SME(s) should document the step by step flow of the process in a process mapping tool (such as Process InVision) and share it with the Acronotics team before the walkthrough.

During the walkthrough session:

*  The SME(s) give the Acronotics team a live demo of how the process is carried out as of today.
*  The SME(s) walk through all the different scenarios/ variations to the “happy path”.
*  The SME(s) walk through the various errors/ exceptions that are known to occur during the process and how they are to be handled.
*  The SME(s) identify all the applications/ technologies used in the process.

After the walkthrough session Acronotics prepares the Process Description Document (PDD) and shares it with the SME(s) for their review to ensure all the steps, variations, exceptions etc. are fully captured. Once the SME(s) sign off on the PDD document, and Acronotics starts developing the automation solution (SDD) for the process based on the same.  






## Bot Design

Bot design process involves Solution Architects (SAs) analyzing the as-is process flow and designing the to-be (automated) process and high-level bot structure in an SDD document. This phase will also involve some discussion with SME(s) if there are parts of the process that have feasibility challenges like usage of dynamically generated one-time-passwords (OTPs).

Below are some of the best practices for bot design:

*  Utilize the standard structure of one master bot with several sub-bots to ensure modularization of bots
*  Use Single Responsibility Principle i.e. each logically separate functionality of the process or bot should be encapsulated in one sub-bot
*  Ensure usage of standard re-usable components from Acronotics common repository like for error-handling, login to a common application like Service-Now etc.
*  Ensure the bots take care of not just the happy path or automated part of process but also the exception scenarios i.e. inform and enable the process SMEs to handle exception scenarios in case those need to be addressed manually
*  Ensure the bots are designed to handle the volume of transactions in the given SLA window i.e. if the volume of transactions is high the bot might need to be logically broken up for load balancing and parallel execution from multiple runners
*  Collaborate with process SMEs to design the to-be process if changes are expected in up-stream or down-stream parts of the business process/ underlying applications

## Bot Development

Automation Pods (teams of 3 automation engineers) work with SAs and BAs to understand the process & bot design and develop bots as per the requirements. Deliverables that are created as part of the bot development are:

*  Technical design document (TDD): Detailed document about the bot code including the pseudo code
*  Peer-review sign-off: Every bot is peer reviewed by another automation engineer to ensure that coding guidelines are being followed
*  QA sign-off: Internal testing by QA team ensures that bot meets functional and technical requirements

Below are some of the coding best practices for development of bots:

*  Use configuration file for all the environment level settings to ensure no changes are required in bot code for migration of bot from dev to UAT & from UAT to prod
*  No hard coding of paths, file names, URLs, etc.
*  Ensure usage of comments to explain the code as much as possible
*  Two types of logs need to be created for different audiences: 
*  Process log: For the process SMEs to know the functional progress of the bot and exceptions that might need to be handled.
*  Technical log: For the support team to troubleshoot in case of failure.
*  Ensure standard naming convention for variables, folder structure, config files, input and output files
*  Ensure error handling at two levels 1) enclose the whole code in an error handling block and 2) every critical part of the bot in its individual error handling block
*  Use credential vault or encrypted store for credentials or other information that needs to be secure

## User Acceptance Testing (UAT)

Business Analysts (BAs) co-ordinate with Process SMEs to conduct UAT sessions of the bots. The process involves running the bot as a demo to the SMEs for them to visually see the bot in action and then review the results of the bot execution in form of processed transactions and process logs generated as part of the execution.

Below are some of the best practices for UAT:

*  Ensure the test of exception scenarios in addition to the happy path scenarios.
*  Conduct the UAT execution of the bot from control room instead of developer’s workstation/VDI.
*  Plan ahead to make sure SMEs have time and bandwidth to create the test data for all the test scenarios.
*  Ensure access to UAT systems is gained well before the bots are ready to go into UAT to avoid delays.
*  Document any changes/ defects discovered during the UAT session and if possible, communicate the timeline for the fix to ensure availability of test data and SMEs for next UAT session.



Bot Deployment

Bot deployment is one of the topics that is often ignored till the last minute and should be considered early in the process to avoid implementation delays and improve reliability of bots as they move to production. It is important make sure that bots follow well defined bot promotion process as they move from Dev to UAT and to Production environments. We work with our clients to finalize the bot deployment process in early stages of project. Below is an example of bot promotion process that we follow as the bots get ready for production.

![](https://www.acronotics.com/images/implementation/bot-deployment.png)

Before we move the bots into production, the following points need to be taken into account:

*  Make sure that bots have been properly tested in UAT environment and have received a UAT sign off
*  The underlying application environments that the bots access in UAT need to be different from the environment used during the development. This confirms that bots are configurable as they move from one environment to another and don’t have hard coded URLs, * application paths etc.
*  Code review is conducted to make sure development best practices like DRY (don’t repeat yourself etc) have been followed
*  Any pop-ups, message boxes that were added as part of the development process are removed
*  Any application paths, input and output file locations required by the bots have been created and access to these locations has been tested
*  Access to applications and systems that bots are going to access has been received
*  The runner machines have been tested to confirm the applications are accessible from the runner machines
*  Any installed application that bots use for processing need to be installed on production runner machines before the first production run is scheduled.
*  Run-book for production support of the bots is reviewed and a production handover meeting is scheduled.
*  Bot execution schedule is reviewed and finalized with process SMEs


As part of the production cut over, the following points need to be taken care of:

*  All bot dependencies are mapped and migrated as part of the cut-over process
*  Hand over meeting with production support team is conducted
*  Production support team is part of the first execution (HyperCare) of the bots in production
*  Bots are scheduled and executed by designated bot promoter/ production support team only to maintain delineation of duty






# Implementation Bot Maintenance


## Introduction

Bot maintenance is primarily geared towards scheduling and monitoring the bots to ensure that bots continue to execute as scheduled. The focus of the maintenance team is to proactively identify any adverse scenarios and provide a quick fix to any issues that come up. There are three main stages of bot maintenance as they move to production:

*  HyperCare
*  Production Support
*  Minor enhancements

##HyperCare

This is the first stage of production migration of bots. First few runs of bots are executed under close watch in collaboration with process SMEs. Below are some of the key points about the approach to HyperCare:

*  Duration of HyperCare phase is decided in collaboration with process SMEs during the project planning phase. At minimum first 5 runs of the bots are run under HyperCare mode
*  Schedule of HyperCare sessions is planned with process SMEs to ensure their availability in case of any issues during or after the bot execution
*  Bots are manually executed from production control room with process SMEs actively involved during the execution of the bots
*  Any changes or fixes that are required during the HyperCare phase are taken care by the development team
*  Explicit review & signoff is required from process SMEs after every bot execution

##Support

Production Support team has the explicit responsibility to make sure that bots are scheduled and monitored in accordance with plan agreed with process SMEs. This ensures proper controls are in place to avoid any unauthorized bots running in production. Production support team is responsible for:

*  Scheduling and monitoring bots in production
*  Co-ordinating with IT infrastructure teams to ensure availability of automated business processes and resolution of any issues that affect execution of bots
*  Publish a dashboard with bot execution results
*  Co-ordination with business SMEs for process exceptions or failures of bots
*  Maximize the utilization of runners (licenses) by scheduling the processes effectively

## Minor Enhancements

It is inevitable that processes or underlying systems that bots access will go through some change and the bots will need to be updated to make sure that they continue to deliver the business value that they were programmed for. Production support team is equipped to handle these enhancements on a pro-active basis through detailed documentation and hand over meetings.

*  RPA production support team needs to stay in touch with process owners and application owners to know ahead of time when these systems change
*  Any upcoming changes to the process or underlying application interface are discussed with process SMEs and planned for proactively.
*  It is important to realize that bots are sensitive to certain changes that in normal IT application are considered low impact. As part of communication plan for RPA program it is made sure that application owners and process owners are aware of the type of changes that bots are sensitive to. For example, a change in login page of an application might not be a big change in general because users intuitively know to enter credentials when a login window appears but for a bot it is a change and this minor change needs to be planned for when the underlying system is expected to change.
*  Production support team works with IT support or process SMEs to assess the change and creates an effort estimate to decide whether a given change is a simple fix, a minor enhancement or a fundamental change in the process that needs to be treated as a major * enhancement.
*  Changes deemed as minor enhancements are assessed and prioritized based on their criticality in collaboration with SMEs.
*  Production support team takes up the development of these changes based on the prioritization.
*  Bot enhancement process to develop and test the bots is followed before the updated bots are moved to production.

![](https://www.yash.com/wp-content/uploads/2018/11/robotic-process-automation-from-yash21.png)
![](https://www.yash.com/wp-content/uploads/2018/11/robotic-process-automation-from-yash11.png)



