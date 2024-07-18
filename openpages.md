# IBM OpenPages

## IBM OpenPages use

IBM OpenPages® is an AI-driven, highly scalable governance, risk, and compliance (GRC) solution. OpenPages enables organizations to centralize siloed risk management functions within a single environment to identify, manage, monitor, and report on risk and regulatory compliance

## Solution areas that IBM OpenPages with Watson offers

OpenPages with Watson provides core services and components that span risk and compliance domains. These components include operational risk, policy management, financial controls management, IT governance, internal audit, regulatory compliance management, and model risk governance

## Search file attachments in OpenPages

 IBM® OpenPages® global search can be configured so that you can search not only on objects content, but also on the contents of any file attachments for which you have permission

## Third Party Risk Management In previous releases of IBM OpenPages

Name of Third Party Risk Management In previous releases of IBM OpenPages was Vendor Risk Management

## Use of IBM OpenPages® Business Continuity Management

IBM OpenPages® Business Continuity Management (BCM) is used by an organization, or group, to maintain or resume a predetermined level of operations during or after a disruptive event

## About OpenPages

IBM OpenPages is an integrated governance, risk, and compliance (GRC) platform that enables companies to manage risk and regulatory challenges across the enterprise. The software was developed by American Computer Innovators in 1996.

## History

In 1996, Amherst, Massachusetts-based American Computer Innovators (ACI, a company founded May 1990) began developing an electronic publishing system for news publishers and other media companies. The software was eventually marketed as an enterprise content management system under the brand/product name OpenPages Composer. Customers at the time included dozens of news publishers around the U.S. such as The Day Publishing Company, Daily Press, Chicago Tribune, Miami Herald and many more. In August, 2000, American Computer Innovators was officially renamed Openpages, and the computer hardware sales and repair portion of the business was spun off as Amherst Computerworks in June 2001. The company was significantly restructured during 2000-2001, and under new management its offerings were marketed as Governance, Risk, and Compliance software and services sold to enterprise customers. Over the decade that followed OpenPages attracted more than 200 customers including Barclays, Duke Energy, and TIAA-CREF.

## Acquisition

On October 21, 2010, OpenPages was officially acquired by IBM. OpenPages joins software brands Cognos and SPSS to form the Business Analytics division of the IBM Software Group. The OpenPages name continues to be applied to IBM's line of governance, risk management, and compliance products.

## Cloud Pak for Data Integration

On November 17, 2020, IBM announced OpenPages would be included in their Cloud Pak for Data solution. IBM Cloud Pak for Data 4.0 provides an intelligent data fabric that combines and automates data and AI lifecycles, simplifying data management to accelerate digital transformation.

## Core services and functional components of OpenPages

Operational Risk, Policy Management, Financial Controls Management, IT Governance, Internal Audit, Model Risk Governance, Regulatory Compliance Management, Third-party Risk Management, Business Continuity Management, Data Privacy Management

## Company type

Brand (of IBM)

## Industry

Governance, Risk, and Compliance Risk Management Compliance Management Operational Risk Management IT Governance SOX Compliance Internal Audit Management

## Founded

1990

## Founders

Scott Killoh, Warren Ondras

## Headquarters

Waltham , United States

## Website

http://www.ibm.com/openpages



## Main Components of IBM OpenPages On-Premises

IBM OpenPages consists of the following components:

- **Installation Server**: Used to install IBM OpenPages.
- **Database Server**: Hosts the OpenPages repository.
- **Application Servers**: Host the OpenPages application.
- **Reporting Servers**: Host IBM Cognos Analytics and OpenPages CommandCenter.
- **Search Server (optional)**: Hosts the OpenPages global search component.

## Utilizing IBM Cognos for Managing Reports

IBM OpenPages uses IBM Cognos Analytics to create, customize, and manage reports and dashboards for governance, risk, and compliance insights.

## Deployment Types for IBM OpenPages

IBM OpenPages can be deployed as:

- **OpenPages As a Service**
- **Cloud Pak for Data**
- **IBM OpenPages on cloud (hosted SaaS)**

## Supported Databases for On-Premise Deployment

IBM OpenPages supports the following databases for on-premise deployment:

- **IBM DB2**
- **Oracle**

## Purpose of the IBM OpenPages Policy Management Module

The Policy Management module in IBM OpenPages helps organizations create, manage, and enforce policies and procedures to ensure compliance and mitigate risks.



# OpenPages Internal IT Governance objects

## Sub-Mandates
Sub-Mandates represent external (or internal) sub-items with which the organization needs to comply. Content can be pulled from third-party providers, including UCF, Ascent Reg Tech, Thomson Reuters, and Wolters Kluwer. Typically, Sub-Mandates are represented in a Library Business Entity structure, and are not replicated throughout the system. Sub-Mandate is recursive, but Deloitte, UCF, Ascent Reg Tech, Thomson Reuters, and Wolters Kluwer content use exactly one level of Sub-Mandate. Sub-Mandates also support content for regulatory compliance. Sub-Mandates can be used to represent paragraphs that are derived from regulatory papers.
## Requirements
The Requirement object details specific requirements, found in the related Mandate or Sub-Mandate object, that the organization needs to adhere to in order to be in compliance.
## Control plans
Control Plan is a self-contained object type, which means that folders are created for each Control Plan. It groups multiple Baselines to represent elements in the operating environment that can be assessed for risk. It acts as a container for a collection of Baseline objects that together perform a function or comprise an IT service. For example, a Control Plan object might represent the servers, operating systems, applications, databases, support personnel, and facilities that provide the corporate email.
## Baselines
A Baseline object type represents a template of library requirements. It is self-contained, which means folders are created for each Baseline. Baselines in the Library represent elements of the IT operating environment. They are linked to Requirements for that type of element. The Baseline object is copied from the library to the business hierarchy, an association is made to a Requirement in the library, and Risk, Control, and Test object types are created as child objects. The Risk, Control, and Test objects are populated with data from the Requirement.
## Resources and Resource Links
The Resource object type is used to represent categories of personnel, applications, infrastructure, processes, facilities, and functions. Resource objects of the same type often need to be related to each other. You can use a Resource Link object type to link two Resource objects.
## Incidents
An incident is an occurrence that has a potentially adverse effect on your enterprise. Create an Incident object to record information, such as the person responsible for investigating the incident and other related data. The Incident object is used by a workflow to facilitate incident analysis. Categories that apply to incidents include Regulatory Compliance, Legal Compliance, Information Security, and IT. Incidents are stored under the Business Entity or IT Resource where the event occurred and associated secondarily to an impacted Mandate or Policy.
## KRIs and KRI values
KRIs (Key Risk Indicators) are components of the risk monitoring process and are used to provide leading or lagging indicators for potential risk conditions. Each instance of a KRI within the organization can have unique target and threshold limits. KRI values are used to record the actual value of an indicator at a specific point in time.
## KPIs and KPI values
KPIs (Key Performance Indicators) are components of the risk monitoring process and are used to provide leading or lagging indicators for potential risk conditions. Each instance of a KPI within the organization can have unique target and threshold limits. The KPI Value object type records the value of a KPI object at a specific point. Create a KPI object, and then periodically (daily, weekly, monthly) create a KPI Value object so you can detect trends.
## Waivers
Waivers give you the ability to document, process and manage the lifecycle of exceptions to Corporate Policies, InfoSec Policies, IT Policies, or Regulatory Compliance Requirements. Waivers can be associated to Business Entities, Policies, Procedures, Requirements, Risks, Controls, Baselines, and Resources.
## Policies
Policies represent internal guidelines that are adopted by the Board of Directors or senior governance body within an organization. The text of a Policy can either be stored in standardized fields on the object or as an attachment to the object. Policies typically have a distinct lifecycle from Draft to Published to Expired, as well as a review and approval process. Draft policies typically reside in the Organizational Business Hierarchy, while Published and Expired Policies typically reside in reference Library entities. Policies are also often mapped to applicable Mandates in the Library to which they relate.
## Procedures
Procedures represent the what, where, when, and how of how policies are implemented in an organization. The text of Procedures is typically stored in the fields on the object. Typically, Procedures are represented as children of a Policy and reside in the same entity structure as its parent Policy.
## Vulnerabilities
Vulnerabilities give you the ability to track and assess security weaknesses. You assign scores to Vulnerabilities using the Vulnerabilities Common Vulnerability Scoring System (CVSS v2). The parent object for a Vulnerability can be a Control Plan, Incident, Resource, or Risk. Typically, you import Vulnerabilities from an IT security solution.
## Workpapers
A Workpaper is any artifact or deliverable you want to track in the scope of an audit. It can represent an engagement letter, a testing matrix, interview notes, or anything else appropriate to the audit in question. The workpaper itself can be attributes that are stored on the Workpaper object, or it can be a Microsoft Word, Microsoft Excel, or other type of file that is attached to a Workpaper object. When Workpaper is used for test evidence, it documents both the test planning and the test results.
## Defining a workflow
Click Administration menu > Solution Configuration > Workflows.
Click New Workflow.
Complete the following workflow properties and click Create.
Leave Enabled selected. It can be changed later.
Enter an internal Name for the workflow. It cannot be changed later.
Allowed characters are A-Z, a-z, 0-9, underscore, hyphen, and spaces. Special characters are not allowed.

Select an Object Type. It cannot be changed later.
Select Auto Start or Manual in Type. It can be changed later.
For more information, see Defining workflow properties.

The workflow canvas opens with one default stage, the start stage. The word Draft and the version number, v1, are displayed next to the workflow name. You can begin defining the workflow.
Leave the start stage. A workflow can have only one start stage. Click Edit next to Label to add labels to the start stage.
Define the standard stages.
For information, see Defining a standard stage
Define the end stages.
For information, see Defining an end stage.
Connect the stages with actions. For more information, see Defining a workflow action.
Note: You can define a stage and not connect it with an action to another stage. It is not considered an error in the workflow definition. However, the stage is not processed by the workflow. You can use this feature, for example, to define draft stages and workflow branches that you want to save for future use.
Optional: If you want to discard changes you made to a workflow, click Discard Draft. All changes since the last published version are discarded.
When you are ready to test the workflow, click Publish.
The v1 version of the workflow becomes the first published version of the workflow.
If the workflow is defined with a scheduled start, a job for the workflow is automatically added to the Scheduler as a job. The job name is a concatenated value of the workflow name, the object type, and - Scheduled Start. A schedule on a workflow cannot be changed in the Scheduler. But you can enable, disable, and start the job. On the linked detail page, you can change the description and view the schedule.

Test the workflow. If you need to make changes to the workflow, open it again in the GRC Workflow Designer. Since you are now opening a published workflow, the word Published appears, the version number is displayed next to the workflow name and the Publish button is grayed out. When you make a change to the workflow, Published changes to Draft, the version number is incremented by 1, and the Publish button becomes active.
To discard changes you make to a workflow, click Discard Draft. All changes since the last published version are discarded.

## Auditable Entity
An Auditable Entity object is a child of a Business Entity. An Internal Audit Business Entity hierarchy is established and all Auditable Entities are created as a child of the Internal Audit Business Entity object. Auditable Entities that are aligned with elements of the Business Entity Organizational Hierarchy are also associated to those Business Entities.

An Auditable Entity represents a single element of the Audit Universe; the collection of things in the business that might be audited. Most Auditable Entities represent business or legal entities, but they can also represent processes, long-running projects or initiatives, compliance programs, or shared IT Services.

Auditable Entities are risk ranked every year to determine the priority of performing an audit that year. A Weighted Risk Score is calculated but the score can be overridden.


## About OpenPages

IBM OpenPages® is an AI-driven, highly scalable governance, risk, and compliance (GRC) solution. OpenPages enables organizations to centralize siloed risk management functions within a single environment to identify, manage, monitor, and report on risk and regulatory compliance. 

### Reporting Fragments
A reporting fragment is typically either a chart, crosstab or list that can be placed on a page of the application so that the user can see a visual representation of data alongside the page data.

### Using Images in Reporting Fragments
 You can insert an image in a report that is used in Reporting Fragments.
The images that you insert must first be uploaded to both the IBM® Cognos® Analytics server and the IBM OpenPages® server. Images must be gif or jpg format.

After you upload the image, you must use a relative path to refer to the image. The relative path should be valid on both the IBM Cognos Analytics server and the IBM OpenPages server.
Follow these best practices:
- Copy the image to the following folders:
  - `<COGNOS_HOME>\webcontent\bi\images`
  - `<OP_HOME>/wlp-usr/shared/apps/op-apps.ear/sosa.war/images`
- Access the image in the report that is used for the reporting fragment by using the relative path ../images/<image file name>.

### Framework Models
OpenPages® includes a set of framework models. The following table lists the models and their namespaces.

|  Model |  Description | Namespaces |
|---|---|---|
| Assurance and Testing | For audit and assurance management use cases | AUD1, AUD2, DEFAULT |
| Model Risk and Data Privacy | For model risk and data privacy use cases | DEFAULT, DPM1, MRG1, MRG2  |
| Operational Risk and Control | For operational risk and financial control management use cases | DEFAULT, ORM1, ORM2, ORM3, RA1, RA2, SOX1 |
| Policy and Compliance | For regulatory and policy management use cases | DEFAULT, MAND1, MAND2, POL1, RCM1, RCM2, RCM3, REGAPP1 |
| Resilience and Continuity | For IT governance, business continuity, third party management, and operational resilience use cases | BCM1, BCM2, BCM3, BCM4, BCM5, BCM6, BCM7, BCM8, BCM9, DEFAULT, ITG1, ITG2, TPRM1 |
| Platform Reporting | The Level 0 framework model, which is used to run platform reports | DEFAULT |

### Object naming conventions
Use the following conventions to name objects:
- The maximum length of an object name is 252 characters.
- Only single spaces are allowed.
- If auto-naming is enabled, the name of the object is automatically created.
- Only the following special characters are allowed: ~@^()_+`[]{};',.!#%&*,'<>:"|?
    The forward slash / and backward slash \ are not allowed.
- The name must be unique within a folder.

If the Title field is enabled for an object type, use the following conventions:
- The object ID must meet the requirements for object names.
- The maximum length of an object Title is 4,000 characters.

### Optimize Report performance
  - Filtering Top Level Business Entities: To improve the performance of a report,
    all reports should either have a prompt that filters to a specific business entity
    or a filter that scopes the report by the top level business entity or entities.
    If reports are run without being scoped to a single entity, the query performs multiple
    searches through the hierarchy. This slows down the response time greatly and may introduce
    undesirable results for the entity prompt query page or report.
  - Filtering on Reporting Periods: All reports should include a filter on the reporting period.
    A reporting period is a snapshot of all of the data in your database as a function of time.
    This creates a very large data set each time this operation is performed.
  - Bypassing an Index: In the database tables, indexes are defined on all the enumerated string
    value IDs. If you use enumerated string value IDs as filters, you might want to bypass the specific
    index on the field for better performance overall.
  - Query Direction Performance: When you explore all the computation possibilities, there is one large
    distinction in what you can and should do
  - Adding New Indexes: If you find that a pattern in your reports involves joining two fields that are not indexed,
    it is worthwhile investigating whether adding the index will improve the report’s performance.
  - The Use for Parameter Info Setting: You can set the Use for Parameter Info property on all query subjects.
  

### Creating Graphs in a Report
1. To create a new chart report, complete the following steps.
  - Select the Pie, Donut Chart grouping.
  - Select the Pie chart type.
  - Click OK.
2. Drag and drop the following query items into the various chart sections:
   - Categories (pies)
        ```DEFAULT|[DEFAULT_REL]|GRC_OBJECTS|SOXBUSENTITY_FOLDER|
        [SOXBUSENTITY_GPC]|[SOXBUSENTITY_GPC]|[CEN_NAME00]
        ```
   - Default Measures
        ```
        DEFAULT|[DEFAULT_REL]|GRC_OBJECTS|[SOXCONTROL]|ID_FIELDS|
        [CN_CONTROL_ID]
        ```
   - Series (pie slices)
     ```
     DEFAULT|[DEFAULT_REL]|GRC_OBJECTS|[SOXCONTROL]|ENUMERATION_FIELDS|
     ```
3. From the Query Explorer, select the query.
4. In the Properties pane under Miscellaneous, set the name of the query to chartMain.
5. In the Data Items pane, select [CN_CONTROL_ID] and complete the following steps.
   - In the Properties pane under Data Item, change the value of the Aggregate Function property to Count Distinct.
   - In the Properties pane under Data Item, change the value of the Rollup Aggregate Function property to
    Automatic.
6. From the Page Explorer, create a Prompt Page and create a Business Entity prompt as shown in Adding a Business
  Entity Prompt.
1. Return to the main report page.
2. Double-click the title and set the value to Operating Effectiveness.
3. Run the report.




### Workpapers:
A Workpaper is any artifact or deliverable you want to track in the scope of an audit. It can represent an
engagement letter, a testing matrix, interview notes, or anything else appropriate to the audit in question.
The workpaper itself can be attributes that are stored on the Workpaper object, or it can be a Microsoft
Word, Microsoft Excel, or other type of file that is attached to a Workpaper object. When Workpaper is
used for test evidence, it documents both the test planning and the test results.
Create a Workpaper object from the task view of an Audit Section. Workpaper objects can also be copied
from a library, where they represent templates of different types of workpapers that are generated by an
internal audit department.

### Findings:
Findings can be used to represent observations that are reportable to the business, to the Audit
Committee, or both. Alternatively, Findings can be used to represent individual factual observations, while
Issues are used to represent consolidated themes and systemic problems, which are then reported to the
business, to the Audit Committee, or both.
A Finding represents anything that is uncovered in the course of an audit that needs to be accounted for
and addressed by management. You can use a finding to track management's progress in addressing the
underlying issue identified. The Issue object can be used in place of, or in conjunction with, the Finding
object.

### Auditors:
Resource planning and allocating requires key information about each individual who might perform audit
work. The Auditor object is used to create a pool of Auditors who can be assigned to Audits.
Each user who is assigned to audit work is represented as an Auditor instance. Auditors are then available
for resource allocation. The Auditor object includes attributes to use to evaluate and select Auditors for
audit engagements, such as specialties, languages, and certifications. Auditor objects are associated with
the relevant component of the Internal Audit organizational hierarchy. As a best practice, match the Name
on the Auditor object with the username.

### Audit review comments:
The Audit Review Comment object type is used to provide feedback during the review process for an Audit
and its components. It is associated as a child to the instance of the Audit, Section, Workpaper, or Finding
for which feedback is being provided.

### IBM OpenPages IT Governance:
IBM OpenPages IT Governance (ITG) is an enterprise IT Governance solution that aligns IT services, risks
and policies with corporate business initiatives, strategy, and operational standards.
IBM OpenPages IT Governance allows you to manage internal IT control and risk according to the
business processes they support. In addition, IBM OpenPages IT Governance unites multiple silos of
IT risk and compliance to deliver improved visibility, better decision support, and ultimately enhanced
corporate performance.
Key features include:
• IT Regulatory and Policy Compliance
• Risk and Control Assessments
• Control Testing and Issue Remediation
• IT Resource Management
• Incident tracking
• Vulnerability tracking and scoring
• Key Performance and Key Risk Indicators
• Reporting, monitoring and analytics

### IBM OpenPages Policy Management:
IBM OpenPages Policy Management (PCM) is an enterprise compliance management software solution
that reduces the cost, complexity, and cumbersome nature of compliance with multiple regulatory
mandates and corporate policies.
IBM OpenPages Policy Management allows companies to manage and monitor compliance activities
through a full set of integrated functionality including:
• Regulatory Libraries and Change Management
• Risk and Control Assessments
• Policy Management, including Policy Creation, Review & Approval and Policy Awareness
• Control Testing and Issue Remediation
• Regulator Interaction Management
• Incident Tracking
• Key Performance Indicators
• Reporting, monitoring, and analytics  
Management

### IBM OpenPages Regulatory Compliance Management:
IBM OpenPages Regulatory Compliance Management (RCM) supports organizations in breaking down
regulations into a catalog of requirements, evaluating its impact to the business, and creating actionable
tasks.
As a solution it allows firms to:
• Maintain a repository of regulations and requirements that they must comply with
• Identify and create a catalog of requirements that fulfill the regulations
• Map regulatory requirements to their internal control framework
• Create groupings of requirements into Compliance Themes
• Conduct assessments of regulatory requirements under Compliance Plans
• Ingest, direct, and respond to regulatory events supplied by third-party data providers
• Record, organize, and respond to regulator interactions, including regulatory inquiries and examinations

### IBM OpenPages Third Party Risk Management:
IBM OpenPages Third Party Risk Management supports organizations in organizing and centralizing
information about their vendors.
As a solution it provides a configurable and customizable platform, allowing firms to:
• Create, maintain, and document all vendors and engagements
• Classify or "tier" vendors as low, medium, or high criticality
• Use standard risk assessments to identify and mitigate risk in a specific way for individual vendors
• Leverage the questionnaire assessment capability to conduct vendor or engagement tiering using
information that you gather with risk or compliance questionnaire assessments
In previous releases, IBM OpenPages Third Party Risk Management was named Vendor Risk
Management. The original name and the acronym, VRM, still exist in internal names for profiles and
role templates.

### Databases in OpenPages:
IBM OpenPages supports both the IBM Db2® database and the Oracle database. (Oracle is not supported in IBM OpenPages for IBM Cloud Pak for Data).
 To run OpenPages SQL scripts, you must use CLPPlus with Db2, and SQL*Plus with Oracle database.
To run queries, you can use any SQL tool that is compatible with the database. For example, you could use CLPPlus or Optim™ Development Studio to run queries on the Db2 database.

### IBM OpenPages Business Continuity Management:
IBM OpenPages Business Continuity Management (BCM) is used by an organization, or group, to maintain
or resume a predetermined level of operations during or after a disruptive event. All risks that can
potentially impact the business during or following an event are identified.
Using BCM, organizations can build a framework for identifying critical assets and processes and creating
company-wide business continuity plans.
BCM helps organizations to:
• Centralize business continuity data
• Establish, monitor, and test impact tolerance thresholds for identified important businesses services
• Perform business impact analyses to determine criticality of people, processes, and assets
• Develop business continuity plans, including, but not limited to, preparedness for disaster recovery,
communication plans, equipment checklists, emergency readiness, employee logistics, and vendor
checklists
• Test the effectiveness of your business continuity plan and identify and mitigate key risks
• Run workflows on a scheduled basis to ensure reviews of business services, business impact analyses,
dependency mappings, and testing is conducted at regular intervals
• Visualize key management activities and monitor key performance and risk indicators with a userfriendly dashboard
BCM has built-in calculations to help organizations determine the criticality of processes to their business
and to ensure alignment of recovery time and point objectives across assets and vendors that support
critical business processes. Pre-built workflows allow organizations to draft, review, approve, and publish
plans with triggers for expiry and archival. These plans can be mapped to the client’s business impact
analyses, policies, procedures, processes, locations, events, issues, and tests.

### Problems addressed by Openpages GRE:
IBM OpenPages addresses three key problems of the global regulatory environment (low visibility, disparate GRC systems and limited reach) through the following ways
-Provides an accurate, timely view of all obligations and the associated end-to-end responsibilities 
-Breaks down silos and complex systems; provides a holistic view of risk and compliance across all units and risk types 
 -Uses the business intelligence capabilities of Cognos Analytics to uncover hidden insights 
 -Highlights obligations relevant to business units and maps them to internal controls 
 -Provides automated regulatory alerts through partnerships with leading third-party regulatory data sources 
 -Avoid potential compliance fines with IBM watsonx Assistant for Incident and Loss Event Reporting
 
### Open Pages support Natural language processing services:
Implementing and configuring a natural language processing service is an optional feature in
IBM OpenPages. If your administrator has implemented and configured a natural language
 processing service, you can use it to interpret and classify text that you enter in OpenPages.
A natural language processing service understands the intent behind text and returns corresponding
 suggested classifications, together with a confidence score
 
### Partnering with Thomson Reuters:
IBM OpenPages users can now subscribe to Thomson Reuters Regulatory Intelligence data feed (TRRI) to
 receive automated alerts from a large database of global regulators.
 This means
 -No time spent on sifting through vast amounts of irrelevant information
- Accurate track of important regulatory developments that impact the organization
-Quick access to thorough and reliable data for making informed decisions
-Faster implementation of relevant regulatory changes within the organization
  -Better management and mitigation of risks with no major regulatory change missed
 In addition to TRRI, IBM OpenPages incorporates the expertise of Promontory Financial Group that
 helps users to create a centralized library of regulatory requirements and map them to internal controls.
  This further simplifies the process of gathering, monitoring and analyzing regulatory data
in an efficient manner
