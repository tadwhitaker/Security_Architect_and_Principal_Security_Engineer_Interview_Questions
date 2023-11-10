Back in 2016, I wrote the Security_Engineer_Interview_Questions list and that thing took off. I\'92ve even been on job interviews where the hiring manager told me they used that list for finding interview questions. Neat.

That list of questions is pretty broad and doesn't distinguish between the L1-5 levels (Associate Security Engineer, Security Engineer, Senior Security Engineer, Staff Security Engineer and Senior Staff Security Engineer) that I associate with a career ladder like the CircleCI Engineering Competency Matrix or others like it. Non-manager career advancement tends to start with the L4 Staff Security Engineer level, which is on par with an M1 Security Manager. At the upper end of this non-manager track are L6 Principal Security Engineer and Security Architects.

What does someone get asked if they're interviewing for one of those positions? I was curious, looked up the interview questions on Glassdoor.com and pasted them below.

What's most interesting is the ~1:8 ratio of questions submitted: For every Principal Security Engineer question, there were 7.8 Security Architect questions. Does that mean there are 8x as many security architects as principal security engineers? I have no idea. Still, that's such a large difference that it's worth calling out. The questions are from every company imaginable too: Netflix to Morgan Stanley 7Eleven to Airbus to Alcoa to Wiz. It's also worth noting that you're not going to see small startups among the companies because they simply won't have the need for these folks.

When you ask ChatGPT what the difference is between a Security Architect and a Principal Security Engineer, it rattles out: "A Principal Security Engineer is more hands-on, dealing with the technical implementation of security measures, while a Security Architect is more focused on designing the overall security strategy and framework for an organization." Despite that, I didn't see a clear difference between the two sets of questions submitted. Every one of them can be put into one of the three buckets:

1. Technical
2. Behavioral
3. Frameworks, Design and Threat Modeling

Here you go:

Technical
All about DNS, HTTP and OWASP top 10.
Logical coding program which included 2 arrays.
Interesting findings? SQL Injection? Do you know code review? How do you secure an application?
1. Cloud AWS - How you will secure many cloud accounts? 2. CVE - Please elaborate on some new CVE. 3. ZTNA - What is a ZTNA solution? Pros and Cons...
What is a static route? how to use nmap
What's the difference between TLS 1.2 & TLS 1.3
What are the services use for central monitoring in AWS
Session cookie questions, asymmetric vs symmetric, difference between hashing and salting, what to think about when building a login web app
How Windows local authentication happens?
Describe TLS handshake - Stateless vs Stateful firewalls vs WAF
Please explain the concept of DNS
How do you make an ec2 accessible to the public How would you update a docker image what is cloud security
Some questions included, explain application attacks, OWASP top 10 related, privileged access management, TLS and why is it better than SSL, asymmetric/symmetric encryption, how to protect an EC2 instance or server iWhat is OAuth 2.0 used for? Q: Name the different OAuth grant types and provide examples of usage Q: What is a "rainbow attack"? Q: presented a multi-tier architecture diagram and asked for possible vulnerabilities and issues in general
AWS presentation, general onion based security protocols regarding cloud and hybrid.
What is CDN? DNS resolution?
Difference between masking and encryption and the use cases for both
Do you know about glitch attack?
Describe how TLS works and what is PFS(Perfect forward secrecy)?
What do you think about WAF technology?
Explain cross-site scripting
Tell me an occasion where you made a mistake on a design/project and how you handled it
ARP Poisoning, DNS Poisoning, Setting up firewall using IP Tables and Linux system
What are the primary differences between encryption, hashing, and tokenization?
LDAP connection types.
How can you bypass CSRF protection?
When looking at PAN data, how would you separate data in the hypervisor?
Have you had to troubleshoot SSO and was it for external clients or internal issues?
How would you use knowledge of the key used to encrypt one column in a database to decrypt the other column.
Explain components of a CA infrastructure
What is the Linux command to look up for open ports?
Name two major forms of Cryptography?
What is the difference between static and dynamic application scanning?
Explain the difference between IDS/IPS and the firewall.
How do you stop screen / website scraping?
how you would separate data in the hypervisors?
What's your experience with memory leaks?
Sum binary digits with Go.

Behavioral
Describe a time when you had a disagreement with a coworker.
Tell me about a time you had an unpopular opinion in a project
HTTP headers and response codes
Are you used to working on multiple projects at the same time without guidance to defined expectations?
Give an example of a difficult client you dealt with – what was the issue, how was it handled, what was the outcome
Why do I want to leave my current role?
What kind of security initiatives would you take in the first six months?
How would you coordinate with non-technical teams to implement security strategies?
What are you currently reading?
One question they asked was how I would describe OAuth authentication to a client with limited to no technical background.
How do you modify the organization culture towards Secure Design practice in development teams?
Why have you moved around so much between jobs?
Tell me about a situation you had that was difficult and how did you handle it?
Describe a time when you found a configuration out of compliance, and what you did about it?
Describe how you would introduce a new security compliance policy.
What is your experience with Customer Audits?
Give me a presentation over the phone as if you are presenting to 100 people?
What security resources do you use to ensure your knowledge and skills remain up to date?
Asked who the individuals were who captured Kevin Mitnick.
What would you do if you found an infected host on your network and how would you stop its spread? (No details were given on what tools or equipment the customer may have)
How do you stay up to date with industry trends and modern research in one of the fastest evolving technical fields (cybersecurity) that exists?
Tell me about a time that you did something creative.
How fast can I become independent after taking up the job?
What do you use to debug your code?
Tell me about your most recent assignment.
What's the difference between a Principal and Sr Engineer?
Tell me about your experience as an application developer?
Are you capable of writing a policy?

Frameworks, Design and Threat Modeling
What have you done around ISO27001?
What is IAM?
What are the main points to be considered to build a Security Reference Architecture?
How would you tackle aging games as they do not provide revenues but require paying for backend services?
Can you propose a recommended architecture (on whiteboard) based on my requirements as a customer? Feel free to ask more questions to discover more.
What is your experience with security architecture in general and specifically Cloud architecture?
What security frameworks have you implemented?
Describe Your Threat Modeling Process Describe how you would influence Stakeholders
Explain Zero trust architecture please?
How would you design an Azure Sentinel detection engineering workflow?
What are ways you could secure an on-prem active directory within an Enhanced Security Administrative Environment?
Based on a technical problem of your choosing, how would you design it in AWS?
I was asked to describe a complex security project which I led. 1. What were the main objectives and KPIs? 2. Were there any difficulties and how did I manage to overcome them? 3. Was the project completed successfully, and how did I verify it?
Tell me how you would secure a multi-cloud environment at a large company.
How would you connect two AWS accounts together for two separate companies?
Describe Zero Trust
What is Threat Modeling and how that works in connected car scenario?
They asked about Well-architected framework
What are the most important considerations when developing secure infrastructure?
Encryption standards, Security standards, policy, and mechanisms.
What is your experience with identity management?
Questions about Secure software development practices, System design- design software for multilevel automated car parking station, OWASP Top 10, Software Security Standards like FIPS, NIST, etc., Threat Modeling
What is the STRIDE methodology?
Vulnerability Management, Security Architecture and Design, OS Hardening
Things to consider when allowing partner or acquired company to give access to Database. Network Security related.
What was the time when you used MITRE Framework with customer's requirements and how it helped the organization?
How would you perform a cyber attack against a mobile network?
Within an SDLC how would you ensure security in the CI/CD pipeline, not just from an overview but low-level script execution?
Describe how would you design a 3-tier architecture in AWS?
How do you implement Secure Design in Agile environment?
Given an event stream from the partner's node, how would you create an app to apply user security rules for access to a set of URLs to the NGFW?
Here's a whiteboard, show me a typical three-tier application architecture with a DMZ. What kind of security controls are at each of these points, etc.?
Explain your knowledge of the OSI model.
Who are our competitors and what weaknesses do they have?
How would you build a SOC and can you draw it on the board with the technologies that you would use?
What types of authentication products are you familiar with?
Design an example of an enterprise network with security on mind
Here is an application design diagram. How would you secure this application?
How would you ensure that information within a database is secure?
How would you go about securing a server?
What do you use a PodSecurityPolicy for?
How else do you secure your Kubernetes clusters?
How would you separate data in a Kubernetes hypervisor infrastructure for PCI?
How to secure multiple AWS accounts?
Look at the diagram and tell us any security observations.
