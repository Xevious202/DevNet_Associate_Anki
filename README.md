#### _This is a Work in Progress a/o June 2021_

This is an Anki deck made to help anyone study for the Cisco DevNet Associate Exam.

## Prerequisites
- Install Anki Desktop
  - https://apps.ankiweb.net
- Install the CrowdAnki add-on
  - https://ankiweb.net/shared/info/1788670778

## Directions
- Import this deck using "CrowdAnki: Import from Git Repository" using this URL
  - https://github.com/Xevious202/DevNet_Associate_Anki
- If you'd like to add cards to this deck, please contribute them!
## Blueprint Verbs are important! (SRC: [Bloom's Taxonomy])
Indicate level of knowledge needed on each topic. Associate level is (on average) just above "Describe"
| Verb | Difficulty |
| ------ | ------ |
| Design | Expert level; No instances found on this Blueprint |
| Troubleshoot | Professional level; Understand show commands and how to spot/fix misconfigured values |
| Construct | Associate level; You may be asked how to configure this |
| Describe | Conceptual, likely not covered in simulated environment questions |

# Exam Blueprint | 185 Cards Total
## 1.0 Software Development & Design 15% | 40 Cards Created
- 1.1 Compare data formats (XML, JSON, and YAML) | 3 "data-serialization"
- 1.2 Describe parsing of common data format (XML, JSON, and YAML) to Python data structures | 3 "data-serialization", "python"
- 1.3 Describe the concepts of test-driven development | 2 "development"
- 1.4 Compare software development methods (agile, lean, and waterfall) | 3 "development"
- 1.5 Explain the benefits of organizing code into methods / functions, classes, and modules | 4 "design"
- 1.6 Identify the advantages of common design patterns (MVC and Observer) | 2 "design"
- 1.7 Explain the advantages of version control | 5 "version-control"
- 1.8 Utilize common version control operations with Git | 19 "version-control"
  - 1.8.a Clone
  - 1.8.b Add/remove
  - 1.8.c Commit
  - 1.8.d Push / pull
  - 1.8.e Branch
  - 1.8.f Merge and handling conflicts
  - 1.8.g diff

## 2.0 Understanding and Using APIs 20% | 19 Cards Created
- 2.1 Construct a REST API request to accomplish a task given API documentation | 1 "API"
- 2.2 Describe common usage patterns related to webhooks
- 2.3 Identify the constraints when consuming APIs
- 2.4 Explain common HTTP response codes associated with REST APIs | 17 "API", "HTML"
- 2.5 Troubleshoot a problem given the HTTP response code, request and API documentation
- 2.6 Identify the parts of an HTTP response (response code, headers, body)
- 2.7 Utilize common API authentication mechanisms: basic, custom token, and API keys
- 2.8 Compare common API styles (REST, RPC, synchronous, and asynchronous)
- 2.9 Construct a Python script that calls a REST API using the requests library | 1 "Construct"

## 3.0 Cisco Platforms & Development 15% | 34 Cards Created
- 3.1 Construct a Python script that uses a Cisco SDK given SDK documentation
- 3.2 Describe the capabilities of Cisco network management platforms and APIs (Meraki, Cisco DNA Center, ACI, Cisco SD-WAN, and NSO) | 10 "Platforms", "API"
- 3.3 Describe the capabilities of Cisco compute management platforms and APIs (UCS Manager, UCS Director, and Intersight) | 6 "Platforms", "API"
- 3.4 Describe the capabilities of Cisco collaboration platforms and APIs (Webex Teams, Webex devices, Cisco Unified Communication Manager including AXL and UDS interfaces, and Finesse) | 6 "Platforms, "API"
- 3.5 Describe the capabilities of Cisco security platforms and APIs (Firepower, Umbrella, AMP, ISE, and ThreatGrid) | 10 "Platforms", "API"
- 3.6 Describe the device level APIs and dynamic interfaces for IOS XE and NX-OS | 2 "API"
- 3.7 Identify the appropriate DevNet resource for a given scenario (Sandbox, Code Exchange, support, forums, Learning Labs, and API documentation)
- 3.8 Apply concepts of model driven programmability (YANG, RESTCONF, and NETCONF) in a Cisco environment
- 3.9 Construct code to perform a specific operation based on a set of requirements and given API reference documentation such as these:
  - 3.9.a Obtain a list of network devices by using Meraki, Cisco DNA Center, ACI, Cisco SD-WAN, or NSO
  - 3.9.b Manage spaces, participants, and messages in Webex Teams
  - 3.9.c Obtain a list of clients / hosts seen on a network using Meraki or Cisco DNA Center

## 4.0 Application Deployment & Security 15% | 52 Cards Created
- 4.1 Describe benefits of edge computing
- 4.2 Identify attributes of different application deployment models (private cloud, public cloud, hybrid cloud, and edge)
- 4.3 Identify the attributes of these application deployment types
  - 4.3.a Virtual machines
  - 4.3.b Bare metal
  - 4.3.c Containers
- 4.4 Describe components for a CI/CD pipeline in application deployments | 6 "Deployment"
- 4.5 Construct a Python unit test | 3 "Python", "Deployment"
- 4.6 Interpret contents of a Dockerfile | 8 "Containers"
- 4.7 Utilize Docker images in local developer environment | 14 "Containers"
- 4.8 Identify application security issues related to secret protection, encryption (storage and transport), and data handling
- 4.9 Explain how firewall, DNS, load balancers, and reverse proxy in application deployment | 5 "Security"
- 4.10 Describe top OWASP threats (such as XSS, SQL injections, and CSRF) | 5 "Security"
- 4.11 Utilize Bash commands (file management, directory navigation, and environmental variables) | 11 "Shell"
- 4.12 Identify the principles of DevOps practices

## 5.0 Infrastructure & Automation 20% | 22 Cards Created
- 5.1 Describe the value of model driven programmability for infrastructure automation
- 5.2 Compare controller-level to device-level management | 4 "Automation"
- 5.3 Describe the use and roles of network simulation and test tools (such as VIRL and pyATS) | 2 "Automation"
- 5.4 Describe the components and benefits of CI/CD pipeline in infrastructure automation
- 5.5 Describe principles of infrastructure as code | 1 "Automation"
- 5.6 Describe the capabilities of automation tools such as Ansible, Puppet, Chef, and Cisco NSO | 10 "Automation"
- 5.7 Identify the workflow being automated by a Python script that uses Cisco APIs including ACI, Meraki, Cisco DNA Center, or RESTCONF
- 5.8 Identify the workflow being automated by an Ansible playbook (management packages, user management related to services, basic service configuration, and start/stop) | 5 "Ansible"
- 5.9 Identify the workflow being automated by a bash script (such as file management, app install, user management, directory navigation)
- 5.10 Interpret the results of a RESTCONF or NETCONF query
- 5.11 Interpret basic YANG models
- 5.12 Interpret a unified diff
- 5.13 Describe the principles and benefits of a code review process
- 5.14 Interpret sequence diagram that includes API calls

## 6.0 Network Fundamentals 15% | No Cards Created
- 6.1 Describe the purpose and usage of MAC addresses and VLANs
- 6.2 Describe the purpose and usage of IP addresses, routes, subnet mask / prefix, and gateways
- 6.3 Describe the function of common networking components (such as switches, routers, firewalls, and load balancers)
- 6.4 Interpret a basic network topology diagram with elements such as switches, routers, firewalls, load balancers, and port values
- 6.5 Describe the function of management, data, and control planes in a network device
- 6.6 Describe the functionality of these IP Services: DHCP, DNS, NAT, SNMP, NTP
- 6.7 Recognize common protocol port values (such as, SSH, Telnet, HTTP, HTTPS, and NETCONF)
- 6.8 Identify cause of application connectivity issues (NAT problem, Transport Port blocked, proxy, and VPN)
- 6.9 Explain the impacts of network constraints on applications

## Uncategorized Fundamentals (NOT IN BLUEPRINT) | 19 Cards Created
- Python | 10 "python", "shell", "Basics"
  - Compare Sets
  - Data Types
  - Importing Modules
  - REPL
  - Decorators
- Programming Types | 5 "Basics"
  - Imperative Paradigm: Procedural, and Object-oriented Programming
  - Declarative Paradigm: Functional Programming
- Terminology | 4 "Basics"
  - Idempotency
  - CRUD
  - Semantic and Syntax errors

## License

GPL

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks Dillinger.io and SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

  [Bloom's Taxonomy]: <http://www.fresnostate.edu/academics/oie/documents/assesments/Blooms%20Level.pdf>
