# ch1 Security Governance Through Principles and Policies

```
CH1-1.1 Integrity、 Availability、 Confidentiality
CH1-1.1.1 Confidentiality
CH1-1.1.2 Integrity
CH1-1.1.3 Availability
CH1-1.2 Other Security Concepts
CH1-1.6 Protection Mechanisms
CH1-1.7 Layering
CH1-1.8 Abstraction
CH1-1.9 Data Hiding
CH1-1.10 Encryption
```
```
CH1-2.1 Apply Security Governance Principles
CH1-2.1.1 Alignment of Security Function to Strategy, Goals,
CH1-2.1.2 Mission, and Objectives
CH1-2.1.3 Organizational Processes
CH1-2.2 Security Roles and Responsibilities
CH1-2.3 Control Frameworks
CH1-2.4 Due Care and Due Diligence
```
```
CH1-3-1 Develop and Implement Documented Security Policy,
CH1-3-2 Standards, Procedures, and Guidelines
CH1-3-2.1 Security Policies
CH1-3-2.2 Security Standards, Baselines, and Guidelines
CH1-3-2.3 Security Procedures
```
```
CH1-4-1 Understand and Apply Threat Modeling
CH1-4-2 Identifying Threats
CH1-4-3 Determining and Diagramming Potential Attacks
CH1-4-4 Performing Reduction Analysis
CH1-4-5 Prioritization and Response
```
```
CH1-5-1 Integrate Security Risk Considerations into Acquisition
CH1-5-2 Strategy and Practice
```
```
partA.Summary
partB.Exam Essentials
partC.Written Lab
partD.Review Questions
```

## CH1-1 Integrity Availability Confidentiality
#### CH1-1.1 Confidentiality
```
Confidentiality(機密性)

1.Concealment 
Concealment is the act of hiding or preventing disclosure. 
Often conceal-ment is viewed as a means of cover, obfuscation, or distraction.

2.Secrecy 
Secrecy is the act of keeping something a secret or preventing the disclosure of information.

3.Privacy 
Privacy refers to keeping information confidential that is personally identifiable or that might cause harm, 
embarrassment, or disgrace to someone if revealed.

4.Seclusion 
Seclusion involves storing something in an out-of-the-way location.
This loca-tion can also provide strict access controls. Seclusion can help enforcement confidentiality protections.

5.Isolation 
Isolation is the act of keeping something separated from others. 
Isolation can beused to prevent commingling of information or disclosure of information.


The fi rst principle of the CIA Triad is confidentiality. 

If a threat exists against confidentiality, 
unauthorized disclo-sure could take place.

In general, for confidentiality to be maintained on a network, 
data must be protected from unauthorized access, use, 
or disclosure while in storage, in process, and in transit.

Numerous attacks focus on the violation of confidentiality.
These include capturing net-work traffic and stealing password fi les as well as social engineering,
port scanning, shoul-der surfi ng, eavesdropping, sniffi ng, and so on.
```
#### CH1-1.2 Integrity
```
Integrity(完整性)

For integrity to be maintained, 
objects must retain their veracity and be intentionally modified by only authorized subjects.

If a security mechanism offers integrity,
it offers a high level of assurance that the data, 
objects,and resources are unaltered from their original protected state. 

Alterations should not occur while the object is in storage, 
in transit, or in process. 

1.Preventing unauthorized subjects from making modifications

2.Preventing authorized subjects from making unauthorized modifications, such as mistakes

3.Maintaining the internal and external consistency of objects so that their data is a cor-rect and
true reflection of the real world and any relationship with any child,
peer, or parent object is valid, consistent, and verifiable

Numerous attacks focus on the violation of integrity.
These include viruses, logic bombs,unauthorized access,
errors in coding and applications, malicious modification, 
intentional replacement, and system back doors.

Other concepts, conditions, and aspects of integrity include accuracy,
truthful-ness, authenticity, validity, nonrepudiation, accountability,
responsibility, completeness,and comprehensiveness.
```
#### CH1-1.3 Availability
```
Availability(可用性)

If a security mechanism offers availability,
it offers a high level of assurance that the data, objects, 
and resources are accessible to authorized subjects. 

Availability includes efficient uninterrupted access to objects and prevention of denial-of-service (DoS) attacks.
Availability also implies that the supporting infrastructure—including network services, 
communications, and access control mechanisms—is functional and allows authorized users to gain authorized access.

There are numerous threats to availability. These include device failure, 
software errors,and environmental issues (heat, static, flooding, power loss, and so on).

There are also some forms of attacks that focus on the violation of availability, 
including DoS attacks,object destruction, and communication interruptions.

Availability depends on both integrity and confidentiality. Without integrity and con-fidentiality, 
availability cannot be maintained. 

Other concepts,conditions, and aspects of availability include usability, accessibility, and timeliness.
```

## CH1-1.2 Other Security Concepts
## CH1-1.6 Protection Mechanisms
## CH1-1.7 Layering
## CH1-1.8 Abstraction
## CH1-1.9 Data Hiding
## CH1-1.10 Encryption
