# Business Context
	- Illustrate what is the business outcome that this project is going to deliver
- # Requirements
	- ## Functional
		- Summary functional requirements or link to a page containing them
		- What is this service going to deliver?
		- Is the service bound to compliance requirements?
	- ## Non-Functional
		- Summary non-functional requirements or link to a page containing them
			- Volumes, etc.
- # Design
	- ## Architecturally significant use cases
		- What are the use cases that have shaped the proposed design?
		- What are the specific challenges that these use cases present?
		- Briefly explain
	- ## (Optional) Current Design Gaps
		- If the service already exists, what does the system look like? No need to include the whole design document, just a link to it.
		- What are the requirements that the current design cannot meet, in terms of use cases?
	- ## Use cases realization
		- ### Data flows
			- Rather than starting with a static architecture, we start by describing the data flows for each use case. The static architecture is just a by-product of the data flows.
		- ### Resulting target state architecture
			- The static component architecture is a result of the data flows, hence it goes after
		- ### (Optional) Interim architectural states
			- If the transformation consists of different steps, each one enabling specific value, describe them here
	- ## Infrastructure
		- What does the infrastructure look like
	- ## Security model
		- Threat model, detection and response
	- ## Drifts from technology strategy
		- Is this design introducing drifts from the technology strategy?
		- Which ones?
		- Why?
- # IT Service model
	- ## Service organization
		- Organization chart
		- Stakeholders and collaborations
		- RACI
	- ## Service Reliability
		- What are we sampling
		- How are we sampling
		- What alert conditions are we going to setup
		- See [What is FMEA? Failure Mode & Effects Analysis | ASQ](https://asq.org/quality-resources/fmea) for more information
		- Which recovery scenarios are going to be manual, which automated
		- Who is going to support the business service, what are the requirements in terms of FTEs etc.
	- ## Compliance
		- Auditing
		- GDPR compliance
		- PCI-DSS compliance
	- ## Financial model
		- Cost of run year 1
		- Cost of run year N, based on growth assumptions
- # Implementation
	- ## Circuit board
		- High level implementation milestones
		- Cost of build