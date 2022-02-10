**Student Name:** KRANTHI KIRAN BINGI
#
**NetID:** AQ8192
#
# Homework #3 Solution
## Question 1
### 1(a)
## Types of IOC's
    1) MalDocs
    2) ImageFiles
    3) OBLIQUERAT PAYLOADS
    4) MALICIOUS DOMAINS
    5) OBLIQUERAT CNCS
    6) Url’s

### 1(b)
## File IoCs
Basically the above file type strings are generally seen in “ MALDOCS” so these kind of weird 64 character strings are generally found in the malicious files which holds the malware inside.
When we observe the above string it looks like the sha value of some MS word document file.
When I checked in VT ( Virus total ) found suspicious information on this string. The string value belong to the SHA256 value of Malicious MS word document file.
Please find the below reference screenshot.
![](Images/Img1.png)
![](Images/Img2.png)

## Question 2
### 2(a)
In the CyBOK reference AAA stands for Authentication, Authorization and Accountability.
The subjects and Objects in access control Model are as follows: 

1. The security Policies are collection of rules.
2. A rule grants or denies access rights to a principle.
[ The synonym for access right is Permission]
3. In the security policies on users, the principals are user identities.
4. When a user logs in to a system, a process is spawned that runs
under the user identity of that person.

5. The requests to protected resources are issued by this process.
6. In the terminology of access control, the process is the subject
 Subjects “speak for” principals.
7. The access control structures identify principals, it is
important that principal names be globally unique, human readable and memorable, easily and reliably associated with known people.
8. The principals in today’s web applications are domains.
9. The principals on today’s smartphones are the apps.
10. Deciding which resources an app may access is still a matter of access control.

### 2(b)
## Access Control Matrix
- ***Access Control Matrix*** is an abstract view of an information relevant to access control. 
- Rows of ACM corresponds to users/groups/subjects.
- Columns of ACM corresponds to resources that needs to be protected.
- ACM defines who can access what
   A[U,O] i.e. what access rights user U has on object O.
### 2 (C)
A *Reference monitor* manages all the authentications between objects and sources, the tasks performed by *reference monitor* is 
1. To authenticate access request to resource by any evidence provided by the subject.
2. To authenticate any request based on the set of policies defined.

2(d)
As per our discussion, the two meanings of authorization is
* Authorization is the process of determining which level of access each user is granted.
* It can also be used to define which object has access  on which resource. An object can access the resources only if they are authorized to particular resource.

### 2(e)
Three general types of information used to authenticate a person is
***Password Authentication***:  This is the most common way of authenticating a object. Information like passwords, captchas, otp’s e.t.c can be used to authenticate.

***Biometric Authentication***: Biometric Authentication is the process that relies on biological characteristics of an individual.  Information like fingerprints, facial recognition of an object can be used to authenticate.

***Token Based Authentication***: Token Authentication enables user to provide their credential once and then generate a unique token in exchange for a particular object.


## Question 3

### 3(a)
***RBAC System***
* In the context of access control, the acronym of RBAC is Resource Based Access Control.
* Resource Base Access Control is a security paradigm where users are granted access based upon their roles in their company.
* RBAC system can be used in IT industries, for example employees in a company cannot access the resources of an administrator. 
* To define access of an each resource to each object separately, RBAC system can be used.


### 3(b)

***ABAC System***
* Acronym of ABAC is Attribute Based Access Control.
* ABAC is a logical access control model that is distinguishable because it controls access to objects by evaluating rules against the attributes of the entities (subject and object) actions and the environment relevant to a request.
* Attributes may be considered characteristics of anything that may be defined and to which a value may be assigned.
* User attributes can include designation, usual responsibilities, security clearance, department, and/or seniority levels.

**How RBAC is different from ABAC**
 * RBAC grants access to users based upon their roles whereas ABAC determines access based on the user characteristics or attributes.
* ABAC has the most general access controls because the objects are defined with many attributes.


**Example of a situation covered by one but not the other**
* RBAC cannot restrict the access of an object to resource based on the time or date that it was created.
* For example, if there is a particular resource which should be accessed till particular time stamp. Since we cannot define attributes of a resource in RBAC, above situation cannot be covered.

### 3(c)
### RADIUS
* Remote Authentication Dial-In User Service (RADIUS) is a client-server networking protocol that runs in the application layer. The RADIUS protocol uses a RADIUS Server and RADIUS Clients.
* A RADIUS Client (or Network Access Server) is a networking device (like a VPN concentrator, router, switch) that is used to authenticate users.
* A RADIUS Server is a background process that runs on a UNIX or Windows server. It lets you maintain user profiles in a central database.

**Why/When to use RADIUS**
 * To prevent your organization's private information from being leaked to snooping outsiders.
* It also allows easy depreciation capabilities and enables individual users to be assigned with unique network permissions.
* If we want to integrate our existing system without any changes we can use RADIUS at that time.

**Why IEEE 802.1X**
* IEEE 802.1X typically used to control access to switch ports and wifi.
* Yes both the RADIUS and IEEE 802.1X can be used together.


### 3(d) 
**Why Red Team want to delete or modify logs**
Yes as a Red Team, deleting logs or modifying logs is mandatory to check if the traces of an bad actor activities are detected.

**Modification or deletion of the entire log, which is better?**
For a hacker finding the logs or entering into target system is difficult, once the target system is committed, deleting or modification of logs is easy.  So as a Red Team it’s their responsibility to find vulnerabilities if any, while a hacker tries to find logs.

**Attacked part of CIA triangle**
Confidentiality is the part of CIA triangle that is effected by deletion or modification of logs.


## Question 4
### 4(a)
**Two types of Laws**
1. Criminal Law
2. Civil Law

**Who instigates legal actions on laws?**
*Criminal law* is enforced by the agency of the state where as in Civil law legal action is taken by an attorney in court.



**Example of a type of case for each**

* Criminal law deals with the cases, where a bad activity is practiced on agency or an organization. For example stealing the company’s confidential data like design of an upcoming product even before company released it in market.
* Civil Law deals with the cases where an individual is effected in a activity.
    Eg: Road Accidents, Sexual Misconducts e.t.c.

### 4(b)
**Difference between rule by law and rule of law**
*Rule by law* is a concept where the government authority who is above the laws and has power to create and execute law where they find it to be convenient for them but not to the society where as Rule of Law is a political philosophy that is implied to follow by every individual in the society.

**Who sets the rules?**
 * Law makers sets the rules, this rules are implied to law makers as well.
 * Setting of syllabus is rule of law that is not supposed to be change in between the semester. If it is changed by professor as per his personal benefits then it would be a rule by law.


### 4(c)
* Yes, “Beyond a shadow of a doubt” is a legal standard of proof.
* The two examples of legal standards of proof is
  1. *Beyond a reasonable doubt*
  2. *Beyond a shadow of a doubt*
* *Beyond a reasonable doubt*  is used in the context where the conviction charge is true and there is no significant proof but there is a doubt where as *Beyond a shadow of a doubt* is assured proof of the bad activity made.


### 4(d)
**Bulletproof Host**
 Bulletproof host is a technical infrastructure service that is provided by the web hosters to intimate the illegal activities made by bad actor on the website.


## Question 5
### 5(a)
***Privacy***
* As per the CyBOK Law and Regulation Knowledge Area Issue 1.0 , privacy in terms of cybersecurity practitioner is to protect privacy of the system from any other activists to interfere in its personal data.
* Yes, privacy is considered an international human right.
* No, right to privacy is not absolute.

### 5(b)
**Personal data and PII**
Yes, both the definitions of PII and Personal data of CyBOK Law is similar. It is all about compromising any personal information of an individual to others.

### 5(c)
**GDPR’s principle of limitation of purpose**
 * *Principle of limitation of purpose* says that any information that is collected for one particular purpose cannot be revealed or use for any other purpose. Collected information should be restricted to the given purpose.




### 5(d)
**GDPR’s principle of data minimization**
* *Principle of data minimization* says that the data controller should collect the data whatever is required to accomplish the purpose that was collecting to. The personal data of individual should be as restricted as minimum and they should also retain the data only as long as they need it.

### 5(e)
**GDPR’s principle of storage limitation**
* *Principle of storage* limitation states that the data that was collected should be stored until needed and that data should be cleared once the given purpose was accomplished.
