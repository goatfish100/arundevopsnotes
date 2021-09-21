# arundevopsnotes
dev ops notes


##Microservices:
- Principles
- read/know 12 factor app https://12factor.net/
- Circuit breakers
- aws notes on microservices https://aws.amazon.com/microservices/

## Dev Ops
- Make sure you know principles - and are ready to answer questions in interview https://aws.amazon.com/devops/what-is-devops/  Culture and Philosphy.


## Resources
- AWS Well architected app  https://docs.aws.amazon.com/wellarchitected/

- AWS best practices for secrets .. https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html


## Dev Vs Ops ....
The exact roles and fuctions of dev ops varies a lot between companies.  Some are much more focused on
operations side while others are more about automation.  It's likely best to focus on Automation side
and get ops experience as needed.

- Continuas integration
- git
- build tools - maven/gradle.  
- jenkins/circleci - concepts are all same but players are different.  Some Jenkins - some CircleCi.  Jenkins is easy to play with and can be easily configured with drag drop - but should be noted it has significant customization/scripting with both Groovy and Kotlin DSL.  

Ops ...
- Be familiar with the landscape for monitoring - chef/puppet/cacti
- monitor/alertign (basically track all metrics on servers/containers) and set alerts when threshold reached (cpu > 90% type of thing)

Security (Dev-Sec-ops):
This is the new "hot" field and it's more about security then anything else.  
- Data Encryption when data is at rest
- isolate and lock down (close ports) anything and everything that can be.
- Secrets - options/strategies.
- AWS notes https://aws.amazon.com/architecture/security-identity-compliance/?cards-all.sort-by=item.additionalFields.sortDate&cards-all.sort-order=desc&awsf.content-type=*all&awsf.methodology=*all


## Software As a Server/Platform as a service
Be ready to discuss different aspects of SAS/PAAS systems...
Docker (a container system) - Docker Compose (an orchestration system) - and Docker Swarm (Kubernetes type management system)
Basically - Platform as a Service - have more functions / end to end management - like Pivotal's CloudFoundry
Kubernetes - is more SAS category - for complete functionality - you have more to manage yourself.
I view things like Openshift - as adding features to Kubernete's to make it a PAAS 
