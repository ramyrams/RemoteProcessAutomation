

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
 
 
