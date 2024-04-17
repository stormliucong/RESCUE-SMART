# Introduction

#### Background
- This is lack of testable research fhir server for translating research oriented AI algorithms to applied application
- The barrier is the gap between research infrustracture and operational infrustructure. One of the biggest obstacle is the sandbox using different standard. 
- Sandbox based on FHIR is commonly used in operational IT infrustructure but usually closed sourced and specific to healthcare oganization.
- For reseach (particularly in specific domain), there is lack of sandbox with sythetic patient data with a good representation of real-world patients
- The barrier cause the trouble in translating algorithms developed into applications can be used in real-world clinics environement
- In addition, it is even tricky for patient facing applications, where no publical open sourced sandbox are available for rare genetic diagnosis support application development. 
#### Relevant Work
- There are a set of [publically testable servers](https://confluence.hl7.org/display/FHIR/Public+Test+Servers), 
- [FHIR python client](`https://github.com/smart-on-fhir/client-py`) is available.

#### Our Proposal
- We first analyzed all publically available sandboxes using $everything approach
- We summarized number of patients, entries and distribution of different resources for different endpoint sandboxes
- We performed a gap analysis to identify the need of extra resources/sythetic data for testing translating algorithm purposes.