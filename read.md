![alt text](image.png)
(img1)

![alt text](image-1.png)
(img2)


![alt text](image-2.png)


# 23-01-2025



## SAP BTP Overview
reports means business warehouse 

![alt text](image-3.png)

forms ,workflows ,configurations are within technologies.

- BTP(Business technology platform) is a unified cloud based platform.

- cloud version of pipo is BTP integration suite.

Set of foundational services:
1. Development (ide enironment) we need a host an application
2. Automation
3. Integration 

- SAP BTP is HYbrid i.e it can connect with cloud systems and also integrate with on-premise systems.

![alt text](image-4.png)

### App Dev :

- low-code / no code : Achiving our business functionallity with low coding or no coding.

- Pro-code tooling: SAP build code , using this we can create new apps using python, java, node.js


### Automation :
- Workflow :  we can create custom workflows in btp 

- Robotic process Automation : when we what to do automation using UI screen then it is called robotic process automation. we need to write some technical codes to work on iyt 

- automation document processing :

### Integration :

PIPO + cloud --> hybrid integration

business to business integration ---> BCB integration

### DAta Analytics :
- sap btp works to derive insights from their data.
Managing the data.

### AI :

Zole(for SAP) is like a copilot for microsoft.
where we can create chatbot agents , prepare trained models.



# SAP BTP commercial Models :

Explained about BTP ...
we have free tier and subscription models. 

## aspects :

- flexibility 
- cost control 
- best for
 
![alt text](image-5.png)
![alt text](image-6.png)

1. Pay AS You Go : we will use as much as we want and at the end of the moth we get a invoice  and we need to pay.

2. Cloud platform Enterprsie Agreement(CPEA):
- Middle to large org with predictable usage patterns. 

- pre commited spending model 
- It is good for large business 
- it contains few agrement terms.
- Discounts are available for large commitments


# 24-01-2025

## SAP BTP COOKPIT

Services 

- All this information is mentioned as a one stop shop. where we can find all the related info

- there r 89 services in BTP

- trial version is different from free tier .. the free tier is only  available when we choose a commercial model pay as u go or subscription model.


service - SAP BTP ABAP environment.
(it is a service )
we check wheather free tier is available or not. 
overview , pricing, related 


service - develop a full time application using RAP
overview, project board, related missions .

SAP integration suite
![alt text](image-7.png)
pricing - subscription amount per month.
can make hybrid integration


![alt text](image-8.png)
(This is called a cockpit)
- BTP provides various like handling integration suite , data analysis, working on workflows, CAP dev , RAP dev 


## About the BTP cockpit 

- Global account is only provided to few people in the org.

SAP Build Code helps in getting started with CAp , RAP applications.

gone through the left side pallete
- resource providers 
- boosters 
- System landscapes 
- we get entitlements based on the credits available in CAP 

--

creating a subaccount in global account .

- in real time we need to follow few naming standards .


## In the subaccount 

- we created an another subaccount  other than trial ... so the integration is not enabled in the new dev subaccount. so to get integration suite we need to get more credits ....(credits?)

- We create a Integration suite. 

created dev and added entitlements for that sub acount .


## 27-01-2025
 
### SAP BTP Cockpit 
- we will either use a subscription model or a free trial or an trail account

![alt text](image-9.png)
- How to handle multiple global accounts. 

![alt text](image-10.png)

sub accounts are to logically separate and provide isolation . 

### Directory 

- it organizes the subaccounts into hierarchy(upto 7 levels)

- subaccounts can also directly come under global account.

### Entitlements 

- service plans that u entitled to use .

- this shows the booked service plans available in your BTP global account.


### Subaccount 

- region assignment doesnt have to depend on u r location. like if u r location is india subaccount can be US. 

![alt text](image-11.png)




![alt text](image-13.png)


![alt text](image-12.png)
- creating a subaccount --> since it is a trail account we got only 2 cloud providers.

- in the subaccount as a region we choose singapore and set the environment as cloud fountary. 

- we created two different sub accounts (for pankaj and micheal)

- We moved the integration Suite frm one directory to another.(we will select a new parent while moving)

- We arrange the directories for better visual understanding .


# Environment 

![alt text](image-14.png)

runtime - cloud fountary(open source  application ), kyma,ABAP environments.

- Cloud fountry is for CAP sevices

- when we r trying to build any microservices we use kyma.

- ABAP env 

- it have restrictions
- it is mostly recommended when we r using RAP as a backend. 

# Services


![alt text](image-15.png)

we created an instance and we created a service key.

![alt text](image-16.png)
- it contains the imp capabilities. 


- Since it is a trail account we have only limited quota.  

So we can only use 1 Integration suite  for a suvb account.

![alt text](image-17.png)

## 28-01-2025

- API Management 
Normally, when we have 10 api fetches in that 4 fetches are from one API , and other4 are from 1 API remaing 2 from other there are 3 different API's .


But here in API management, we will write 1 api( This is the main API) that internally connect with other three API's.

- Trading partner Management.

- OData Provisioning 

- Open Connectors: There will be lot of connectors in integration Suite. 

- Integration Assessment: 

- Migration Assessment :PIPO, Feasability Analysis

## TO work on CAP or RAP we need to subscribe for SAP build Code. 

we tried to add  build code Application  into our tenent. 
- checked the sap Build code in the entitlements.

![alt text](image-18.png)

![alt text](image-19.png)

- we have seen the lobby for build code where we can create codes

---

development configuration :

- SAP Fiori Application
- Full- Stack Application 
- Mobile Application 


# SAP Build 

## Lobby :

This is Like a Dashboard and can  get overview of applications where the developer can manage and see the applications.

This Lobby canalso provide notifications, team collaborations.

## Store :

This is  Similar to a repositary


## About SAP Build Code

- SAP BUild Code is a low code development platform . That allows us to develop custom applications quickly and easily.

Using SAP we can drag and drop pre-build components, connect data sources and create workflows to build Applications.

![alt text](image-20.png)


## 29-01-2025

- created a buil nd created a project in it. 
![alt text](image-21.png)
it is get started with business studio 

![alt text](image-22.png)

build code is started  in the recent times.

- Gen AI in integration Suite helps us in developing integration flows more on groovy scripts. 

- before build code .. to create a fiori app we need to get the entitlements. 

- cloud version of vs code -> SAP Business application Studio. 

- firstly Build code is for CAP letter it is suitable for RAP too.

## SAP HANA Cloud 

![alt text](image-23.png)
- can use for anytype of data.(structured, un structured, semi structured)

cosmos DB Can hold any kind of Data.

![alt text](image-24.png)


## 30-01-2025

# Interfaces 

recap of fit to standard gap Analysis 

![alt text](image-25.png)

interfaces - coz the source and target are different and we need a middleware.

ex : source is SAP 
target is ICICI Bank 

![alt text](image-26.png)

### life cycle of interface 

- functional consaltant explains the process of the project .

## Design : 
once we are clear abt the requirement , we will make a technical design. 

we will be asking the target for all the info regarding the integration. 

like ,
do we need to upload the payload to azure, Does API's Available. 

## Build: 
here we develop the SAP programs , configuring the middleware .

## Error HAndling:

perform validations , find errors and think wheather the errors can be handled or not. 

## Testing :

security checks are done and will perform few checkings.


- this is almost similar to sdlc life cycle ins/w development.


![alt text](image-27.png)

real-time : the data should flow simultaneously when shen sending from source to target. 

- Data format & protocol : IDoc is only used when Source and target is sap only. 


- Security is provided by using pgp keys.


## About integration pattern 

![alt text](image-28.png)

- API based integration is like dealing with real time , it also provides security

- Event driven architecture is more popular , it is similar to real-time plug-in and plug out and is also reusable . 

But event driven is complex 

- Filebased integration: data exchanged in a structured format . 

But error handling is difficult 

## Build 

![alt text](image-29.png)

in the design we have set all the requirements ,like what api we willuse and about the integration suite. 


At the end of a process we will raise a TR to deploy the work to QA

- sap btp admin imports the TR to QA

![alt text](image-30.png)

![alt text](image-31.png)
(the functional team takes care of testing)

![alt text](image-32.png)

## Integration Suite 

SAP Integration Suite is used to connect applications, processes, and data across different systems

![alt text](image-33.png)

it can connect with SAP to SAP and SAP to Non-SAP

1. Multiple Integration Styles

Supports different integration patterns, including:

- Cloud Integration (Process Integration): For A2A and B2B integrations.
- API Management: To create, expose, and monitor APIs securely.
- Event Mesh: For real-time event-driven architecture.
- Open Connectors: Simplifies connectivity with third-party applications

2. Seamless Integration Between Systems

Connects SAP and non-SAP applications, both on-premise and in the cloud.
Supports APIs, events, and batch processes for different integration scenarios.

![alt text](image-34.png)

- b/w two non sap products we r not recommended to use sap btp .

Hybrid integration cap : we can work with PIPO additional pipe lines.

![alt text](image-35.png)

![alt text](image-36.png)

![alt text](image-37.png)

- we dont need to  write much code ... we will mention codes in groovy. 

### SAP Graph : it itself is a capability and a topic

Odata provisioning : it replaces  net waver gateway

Connecting Suppliers & Vendors
📌 Scenario: A manufacturing company orders raw materials from multiple vendors.
🔹 Use Case: Integration Suite helps:

Automatically exchange purchase orders, invoices, and shipment updates with suppliers.
Ensure smooth supply chain management with real-time updates.


## 04-02-2025

![alt text](image-37.png)

- CI we will use extensively in our development.
- Event Mesh (It is a event driven architecture)

- Integration Assesment is used to assesst our strategy. 

![alt text](image-38.png)

- btp integration suite can work with ECC, It ca talk to SAP , non -SAP and SaaS products. 
- integration suite is mostly pattern related.
- security & Compilance : OAuth or BAsic in the Authentication. 

![alt text](image-39.png)
(one of the above models should be there to use intrgration Suite)

![alt text](<Screenshot 2025-02-04 at 11.47.49.png>)

![alt text](image-40.png)
(the below artifacts are workflows which are accessible but are immutable)

- We created a package in integration Suite. 
and inside the integration suite we create artifacts.


![alt text](image-41.png)
value Mapping : source one name is mapped to other name in the destination.
API 
data types and msg types are used in message mapping . 



## Graph

- Graph is a place where we can explore more about our data graph.
- B2B Scenarios : trading partner management.


Custom type systems : we will use custom type msgs for the SOAP req kind of work 

configure is where we configure our API's .

MIG : describes the structure  of a customized interface
MAG: specifies mapping  b/w source and target

![alt text](image-42.png)

![alt text](image-43.png)
(Key store , the OAuth2 Authentication code is used more)

- Analyze : it checks the health of the instances and other processing functionality.

![alt text](image-44.png)
the integration leader or the integration architect looks into the designs. 

Maintaining the access policies - restricting the unauthorized users. 

- custom roles : it is more important becoz the person who is eligible to use this can only use the application. 

- Overview and test connectivity we have gone through at end.




### Tmrw : cloud integration , workflow.

## 05-02-2025 

- ABout the downloading the artifacts and packages. 
- TMS service is responsible for import and exports of the integration flows.

![alt text](image-45.png)

About the artifacts : it defines integration logic

- iflow : graphical rep of integration process 

- message Mapping : converts data from one format to another format  using predefined functions .

- value Mapping : replaces values dynamically b/w source and target .

- Adapters : prebuilt connectors. 

- API : Supports API exposure  through REST and SOAP protocols.

- data type : defined structured data format .

- Message type : describes the structure of message . 

### Question :
(Can we modify the artifacts. There will be 2 types They are editable andconfigure-only.)

![alt text](image-46.png)

![alt text](image-47.png)
(iflow example)

- IDOC or SOAP is the real time considering part. 


# 10-02-2025



(Cloud integration and API management)

## Cloud Integration 

- Different types of Adapters.

Non -SAP Application -> we can publish using HTTPS, SOAP 

![alt text](image-49.png)
(about the assignmennt of the roles)

![alt text](image-50.png)
(we check in the instance 2 diff segments of micheal and affrudin) from this we will create the service keys and takes the authorization.

![alt text](image-51.png)

![alt text](image-52.png)

# 11-02-2025 

Solved the problems faced on 10th 
(written in note )


# 12-05-2025 

## PGP Encryptor

![alt text](image-53.png)

![alt text](image-54.png)

![alt text](image-55.png)

# 13-02-2025

doubts on encrypter and decrypter 

(About signatures and algorithms )


# 14-02-2025

Message mapping , script collection , routing 

![alt text](image-56.png)


exception handling

# 17-02-2025 

about the problems faced on exception handling , explaining the adapters and pallete functions

sevice now and splunk trail account

![alt text](image-57.png)

# 18-02-2025 

# SOAP UI

source and destination can either be sap or non sap

![alt text](image-58.png)

![alt text](image-59.png)


Ex: Journal API 

for this there are no REST API's there are few odata APIS but no authorization to post. In this scenario we use SOAP.

![alt text](image-60.png)

# 24 -02 - 2025 

![alt text](image-61.png)

![alt text](image-62.png)

(ODATA with  post operation)


![alt text](image-63.png)

3- Q/A
4- Interview (Mock)



##  SOAP 

![alt text](image-64.png)


Message mapping is used to deal with the custom mapping like XML to WSDL


![alt text](image-65.png)


URL are only created to HTTPS, SOAP, AS2


sandbox only allows apikey

## Sandbox only supports get operations



Post

![alt text](image-66.png)

![alt text](image-67.png)


# 27-02-2025

# Data Stores 

![alt text](image-68.png)

when creating 48 duplicates we can override the file. 


![alt text](image-69.png)

![alt text](image-70.png)


# 03-03-2025 

## Data Stores 

![alt text](image-72.png)

![alt text](image-73.png)

s4 hana public cloud-->source
get coupa oauth bearer token--> then get coupa suplier number-->get coupa supplier remittance--->post
supplier to Coupa--->iflow execution completed.
get coupa oauth bearer token--> no need of new token everytime


![alt text](image-88.png)
(Write)
 

 - Data stores are not recommended for high volume .
 ## Error Handling 

 error monitoring-->we get a chance to get in emails or IFlow monitoring
error notification---> in exception handling we have used mail adpter, to notify it.
or logging to service now, or
 
error handling---> what is the error, what is the route cause, how should i hold the msg for, im i moving to jms.

error reprocess--->a system designed to automatically retry processing data that previously failed due to an error

![alt text](image-74.png)

![alt text](image-75.png)

![alt text](image-76.png)
sender- s4 hana 
iflow1 - publisher/ dumps the data
JMS queue- look ups the msg  
iflow2- Subscriber 

![alt text](image-78.png)

### The JMS Queues 

![alt text](image-79.png)


![alt text](image-81.png)

![alt text](image-82.png)
(Where used)


How to determine no: of  Queues are requird?


![alt text](image-83.png)

### Variables which has visibility for particular IFlows

![alt text](image-80.png)

--- 

![alt text](image-84.png)

![alt text](image-85.png)

Both the Iflows are de-coupling . 
They doesnt depend on each other . 

![alt text](image-86.png)


![alt text](image-87.png)

## 04-03-2025 

- Data store is not good for heavy payloads, it is only good for small payloads. 

-- Write : 

Visibility is the usage scope .. global means all integration flows can use them 

write-->store the messages
get--->selecting the particular entry.
select--> we get all the entries.there is no entry id.
delete:
if it is global, directly it will delete.

![alt text](image-94.png)

![alt text](image-95.png)


cm-2 

![alt text](image-96.png)



2 dfferent iflows lo global declare chesi chesina kuda same data store gets effected



## 07-03-2025 

![alt text](image-97.png)
![alt text](image-100.png)
![alt text](image-99.png)
![alt text](image-98.png)

## 10-3-2025

Fiori, CAP, S4 HANA 




# 11 -03-2025

Stress testing----testing with double its capability







Exploring Business accelarator Hub, Certificate based Authentication,SOAP sender Adapter

Exception handling, Escalation End , SOAP Sender Adapter, Sandbox URL, API's


Routing, Exception Handling Process , mail triggering, 

![alt text](image-101.png)


# Task 

![alt text](image-102.png)

# 25-03-2025 

- To load 24 sales order data 
![alt text](image-103.png)


# 27-03-2025

## API Management

![alt text](image-104.png)

![alt text](image-105.png)

![alt text](image-106.png)

![alt text](image-107.png)
![alt text](image-108.png)



# 8-04-2025

Mulesoft 
Bhoomi

![alt text](image-109.png)
1,2 kvm
3,4 basic AUTH


source - basic or oauth

target: client certificate based authentication


# SAP Graph 

![alt text](image-110.png)

![alt text](image-111.png)

Encapsulation of all the entities 

![alt text](image-112.png)



- For the content enricher we need to have a foreignkey value.



![alt text](image-113.png)

# 1/ 05 / 24 
## SAML Assertion bearer token policy (OAuth):

- SAML Assertion + bearer token 

![alt text](image-114.png)


# 05-05-25
First we started with what it causes without B2B scenarios . We need to create more IFlows .
Explored capabilities. 

![alt text](image-122.png)
![alt text](image-123.png)
![alt text](image-124.png)
pm is also know as b2b scenarios.
components involved are:
 
1. integration advsior
2. trading partner management(TPM)
3. sap cloud integration
4. b2b monitoring
 
# integration advsior
 
for example:
source is amazon or spencer
 
target is s4 hana public.  
this source will have one message implementation guideline
 
this target will have one message implementation guideline
 
we will have one mag to map this source and target.
 
generally sap message implementation is on odata or soap.
source is edi, edi factor x12.
 
when mag is ccreated, the integration advisor gives that acress diff companies, they are using this mapping---.like proposal.
 
for eg, some juice company are using the sap
 
# trading partner management(TPM)
 
repository to maintain .
for example:
 
like what is template, agreement, ast url,
what is my certificate with amazon,
 
UI to maintain all ur partners, all pertner specific agreements, sender, receiver configurations , profile certificates,encryption, decryption.--->configure for each specific partner,

# 06-05-25
## Trading partner Management

- Trading Partner Management (TPM) in SAP refers to the structured way of managing relationships, data exchange, and integration between a company and its external business partners (e.g., suppliers, customers, logistics providers). TPM is particularly critical in B2B integration, EDI (Electronic Data Interchange), and supply chain collaboration.

![alt text](image-115.png)

![alt text](image-116.png)
- Their purchase order is our sales order.
(Example of orange juice)
buying oranges from store i.e we r raising a purchase order to the shop owner i.e a sales order for him.
![alt text](image-117.png)

![alt text](image-118.png)
- (creating a profile for the company)

![alt text](image-119.png)

![alt text](image-120.png)

mag- mapping guide lines 
Using these 2 MIG's we create the MAG's.

- We will be having 1 Trading partner can have 1 or more Agrement templates. like for 850 - 1 template , 812 -1 Template

![alt text](image-121.png)

What Does "Multiple Trading Partners" Actually Mean?
In a business and integration context, "trading partners" are external organizations that your company exchanges business documents or data with, usually in an automated and structured way.

So, "multiple trading partners" means your organization is working with many such external entities, each potentially requiring unique configurations.

### Tmrw : trading partner implementation

- openconnectors the payload is only getting 750 lines

## 07-05-25

- Creating a profile 

![alt text](image-125.png)

When there are multiple trading partner . The above iflow shows the flow


Step1: AS2 with MDM 
1b
communication flow (Receiver)

--- 


MIG - they r placed at the source and target.
MAG - It acts as a mapping
The format of MIG's: 

![alt text](image-126.png)
![alt text](image-127.png)


The format of MAG's:

![alt text](image-128.png)

![alt text](image-129.png)


![alt text](image-130.png)


### Identifiers in TPM 

In TPM (Trading Partner Management) within SAP Cloud Integration (CPI), identifiers are key elements used to uniquely recognize and differentiate trading partners, agreements, and components during message processing.


# 09-05-25

## Integration Adivisor 

![alt text](image-131.png)


way1 : Converting the X12 into XML which is sent by walmart and sending it S4 HANA.

way2: We have an intermediate guy deals With EDI


## mig

(It is similar as source and target while posting the data)

![alt text](image-132.png)

- We will be having a specific file format.
- 1.1 means that is  mandatory.
- if we dont wanna consider we simply uncheck
- qualified duplicates - it is a duplicate but it is a valid transaction or record

![alt text](image-133.png)
![alt text](image-134.png)

We can import MIG's in our required format. 
(EX: our source could be s4hana or any other similar to target. we will be connecting through adapters like AS12 or SOAP)

![alt text](image-135.png)