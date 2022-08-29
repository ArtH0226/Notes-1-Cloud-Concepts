# Notes-1-Cloud-Concepts
## A Brief History
- Computing in the "cloud" traces back to the Origins of utility computing
- Computer Scientist John McCarthy Proposed this in 1961
  - > ***computing may someday be organized as a public utility just as the telphone system is a public utility -John McCarthy*** 
   - `John McCarthy had the foresight to see what computers were gonna be able to do years ahead of his time`
- In 1969 Leonard Kleinrock, a chief scientist of the Advanced Research Projects Agency Network or ARPANET project that seeded the Internet, stated:
  -  > ***As of now, computer networks are still in their infancy, but as they grow up and become sophisticated, we will probably see the spread of 'computer utilities***
  - `Kleinrock also predicted that computer utilities would be the normalcy in the future`
 - In the Mid 1990's the general Public have been using internet-based utilities computer utilities through various incarnations of search engines / e-mail services / open publishing platforms
- SalesForce.com pioneered the notion of bringing remotely provisioned services into the enterprise
- Amazon.com launched the Amazon Web Services (AWS) platform, a suite of enterprise-oriented services. Provided remotely privionsed storage, computing resources, and business functionality 
- Cloud computing emerged in the commerical arena in 2006, when amazon launched its Elastic Compute Cloud (EC2) services that enabled organizations to "lease" computing capacity and processing power to run their enterprise applications. Google Apps also began providing browser-based enterprise applications in the same year, and three years later, the Google App Engine became another historic milestone.

## Definitions 
- > " **Scalable** and **Elastic** - Gartner "
- " Standardized IT capability (services, software, or infrastructure) delievered via internet technologies in a pay-per-use, self-service way. - Forrester Research "
- Convineniet on-demand network access to a shared pool of configurable computing resources ( netowrks,servers,storage,applications, and services)
- ***Cloud computing is a specialized form of distributed computing that introduces utilization models for remotely provisioning scalable and measured resources.*** - Forrestor Research

## Business Drivers 
- Business Drivers  motivated organizations to adopt cloud computing in support of their business automation requirements.
- Correspondingly motivated otehr oganizations to become provides of cloud enviornments and cloud technology vendors in order to create and emet eh demand to fulfill consumer needs

## Capacity Planning
- capacity planning is the process of determining and fulfilling fuutre demands of an organization's IT resources, products, and services, Within this context, capacity represents the maxiumum amount of work that an IT resource is capable of delivering in a given period of time. 
- Capacity planning is focused on minimizing this discrepancy to achieve predictable efficiency and performance.
  -Different capicity planning strategies exist: 
    - ***Lead Strategy*** - adding capacity to an IT resource in anticipation of demand
    - ***Lag Strategy*** - adding capacity when the IT resource reaches its full capacity
    - ***Match Strategy*** - adding IT resource capacity in small increments, as demand increases
    
## Cost Reduction
- Direct alignment between IT costs and business performance can be difficult to maintain. Growth of IT enviornemnts often corresponds to the assessment of their maximum usage requirements. Its An ever-increasing investment.
- Two costs need to be accounted for:
  1. The cost of acquiring new infrastructure
  2. The cost of its ongoing Ownership
- Operational overhead represents a condsiderable share of IT budgets, often exceeding upfront investment costs.

- Common Forms of infrastructure-related overhead inlcude the following: 
  - technical personall required to keep the envionment operational
  - upgrades, and patches that introduce additional testing and deployment cycles
  - utility bills (AC, Electricity)
  - security / access control measures that need to be maintined and enforced
  - administrative and accounts staff that may be required to keep track of licenses and support arrangements
- On going battle in IT when it comes to cost reduction

## Organizational Agility
- Business need the ability to adapat, evolve due to both internal and external factors
- organizational agility is the ***measure of an organization's responsiveness to change***

## Cloud
- A cloud refers to a distinct IT environment that is designed for the purpose of remotely provisioning scalable and measured IT resources.
- a network of networks providing remote access to a set of decentralized IT resources.

## IT Resource
- An IT resource is a physical or virtual IT-related artifact that can be either software based, such as a virtual server or a custom software program, or hardware-based, such as a physical server or a network device

## On-Premise
- As a distinct and remotely accessible environment, a cloud represents an option for the deployment of IT resources.
- An IT resource that is on-premise cannot be cloud-based, and vice-versa.
- In other words, the term "on-premise" is another way of stating "on the premises of a controlled IT environment that is ***not cloud-based***."

## Scaling
- Scaling, from an IT resource perspective, represents the ability of the IT resource to handle increased or decreased usage demands.
- The following are types of scaling:
  - ***Horizontal Scaling*** - scaling out and scaling in
  -  ***Vertical Scaling*** - scaling up and scaling down
- Horizontal Scaling
  - The allocating or releasing of IT resources that are of the same type is referred to as ***horizontal scaling
  - horizontal allocation of resources is referred to as ***scaling out*** and the horizontal releasing of resources is referred to as ***scaling in***
  - common form of scaling within cloud environments
- Vertical Scaling
  - When an existing IT resource is replaced by another with higher or lower capacity, vertical scaling is considered to have occurred
  - replacing of an IT resource with another that has a higher capacity is referred to as ***scaling up*** and the replacing an IT resource with another that has a lower capacity is considered ***scaling down***
  - Less common in cloud enviornments due to the downtime required while the replacement is taking place

```
Horizontal Scaling                                           | Vertical Scaling
less expensive (through commodity hardware components)       | more expensive (specialized servers)
IT resources instantly available                             | IT resources normally instantly available
resource replication and automated scaling                   | additional setup is normally needed
additional IT resources needed                               | no additional IT resources needed
not limited by hardware capacity                             | limited by maximum hardware capacity
```
## Cloud Service
- A cloud service is any IT resource that is made remotely accessible via a cloud. 
- A cloud service can exist as a simple Web-based software program with a technical interface invoked via the use of a messaging protocol, or as a remote access point for administrative tools or larger environments and other IT resources. 

## Cloud Service Consumer
- The ***cloud service consumer*** is a temporary runtime role assumed by a software program when it accesses a cloud service.
- Common types of cloud service consumers can include software programs and services capable of remotely accessing cloud services with published service contracts, as well as workstations, laptops and mobile devices running software capable of remotely accessing other IT resources positioned as cloud services.

## Goals and Benefits
- to Provide access to powerful infrastructures to organizations without having to purchase it themselves
- most common economic rationale for investing in cloud-based IT resources is in the reduction or eliminition of up-front IT investments (i.e Hardware and software purchases and ownership costs)
- Common measurable beneﬁts to cloud consumers include:
  - On-demand access to pay-as-you-go computing resources on a short-term basis (such as processors by the hour), and the ability to release these computing resources when they are no longer needed.
  - The perception of having unlimited computing resources that are available on demand
  - The ability to add or remove IT resources at a ﬁne-grained level, such as modifying available storage disk space by single gigabyte increments.
  - Abstraction of the infrastructure so applications are not locked into devices or locations and can be easily moved if needed.

## Six Properties of Cloud Computing
1. Cloud Computing is user-centric
  - Once a user is connected to the cloud, whatever is storerd there, becomes yours
2. Cloud computing is task-centric
  - when working with the cloud, your focus moves to what you need done and how that application can do it for you
3. Cloud Computing is powerful
  - Connecting hundreds or thousands of computers together in a cloud creates a wealth of computing power impossible with a single desktop PC.
4. Cloud computing is accessible
  - users can instantly retrieve more information from multiple places.
5. Cloud computing is intelligent
  - With all the data stored on the computers in the cloud, data mining and analysis are necessary to access this information in an intelligent manner.
6.  `Cloud computing is programmable`
  - automated to protect integrity of data, info, etc
 
 ## Six Advabtages if Cloud Computing
 1. Trade capital expense for variable expense
 2. Benefit from massive economies of scale
 3. Stop guessing capacity
 4. Increase speed and agility
 5. Stop spending money on running and maintaining data centers
 6. Go global in minutes

## Infrastructure as a Service (IaaS)
- An Instant computing infrasrtucture, provisioned and Managed over the Internet. Quickly scale up and down with demand, and pay only for what you use/
- commom scenarios: Test and development, website hosting, storage backup & recovery, web apps, high-performance, and big data analysis
- Advantages: 
  - Eliminates capital expense and reduces ongoing cost
  - imrpoves business continuity and disaster recovery
  - Allows for rapid innovations
  - allows for quicker repsonse to shifting business conditions.
  - focus on your core business
  - increased stability, reliability, and supoortability
  - better securrity
  - gets new apps to users faster.

 ## Platform as a Service (PaaS)
 - A complete development and deployment environment in the cloud with resources that enable you to deliver everytyhing from simple cloud-based apps to sophisticated, cloud-enabled enterprise applications.
 - 
 ## Software as a Service (SaaS)
 - software as a service (Saas) allows users to connect to and use cloud-based apps over the internet.
 - common scenarios: internet email (ie, yahoo, hotmail. gmail.)

 ## Comparing "as a Service" 
 - IaaS
  - user/enterpirse maintains application, data runtime, middleware, OS 
  - Iaas provider maintianas VM, netowrking, storage, and servers
 -PaaS
  - user/enterprise maintintans application & data
  - PaaS provider maintinas runtime , middleware, OS, VM, netowkring, storage, and servers
 -SaaS
  - user/enterprise maintains NOTHING
  -IaaS provider maintains apps, data, runtime, middleware, OS, VM, networking, storage, and servers
  
## Cloud Cloud Deployment Models
- Cloud > All parts of the application run in the cloud
- Hybrid > Connects on-premises and cloud-based resources
- On-Premises > "Private Cloud"

## AWS Management Console: Features
- Secure, web-based access
  - secure, login and asessions
  - browsers support
  - mobile app
- Tools for building and learning
  - Automated wizards and workflows
  - compatibility with CLI's SDKs, and other developer tools
  - AWS Marketplace
- Customize and Organize your console
  - Shorcuts and pins
  - Resource Groups
  - Tag Editor
- Manage and monitor your account
  - Billing and Cost mangagement dashboard
  - user roles and access management 
  - system health monitoring

######  ***Make sure to have a good Disaster Recovery Plan*** - Cassie Wright Jr.

I did not know that cloud computing was programmable, i thought the parameters were already set and cannot be changed
I learned that Cloud Computing is highly capable of fitting the needs of mostly any possible scenario, highly scalable and elastic 
