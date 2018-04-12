Swagger UI - Architecture Document Review
===

By Abhishek Arya V00848888

## Table of Contents

 1. [Purpose of the review](#1-purpose-of-the-review)
 2. [Subject of the review](#2-subject-of-the-review)
 3. [Question set for the review](#3-question-set-for-the-review)
 4. [Plan for the review](#4-plan-for-the-review)
 5. [Analysis and summary of review](#5-analysis-and-summary-of-review)
    + [Analysis of the result](#51-analysis-of-the-result)
    + [Summary and potential future roadmap](#52-summary-and-potential-future-roadmap)


## 1. Purpose of the review

This document provides a comprehensive assessment of architectural documentation of Swagger UI system by answering a specific set of questions. The purpose of this review is to convey worthiness of the documentation to the senior project developers/lead of the system. This will critique the good and bad artifacts of the AD with respect to answering the key quality attribute questions of the system and will suggest potential future roadmap.

## 2. Subject of the review

The subject of this review is the architecture documentation created by team for Swagger UI system. The architecture document must provide sufficient details to convey various aspects of the system and key quality attributes for review.

## 3. Question set for the review

<table align="left">

  <tr><td colspan=4><b>1. Question set name:</b> Evaluating system AD in regards to key quality attributes.</td></tr>
  <tr><td colspan=4><b>2. Purpose:</b> This question set could be utilized to check whether the architecture document is ready to be evaluated to answer key quality attribute questions. The questions helps to assess if the document contains sufficient information defining its quality and completeness and its suitability to be presented at an architecture review board.</td></tr>
  <tr><td colspan=4><b>3. Stakeholders and concerns:</b> The lead of the project is concerned with whether the document provides sufficient information for evaluation and usability of the AD. The project lead would like to utilize the AD to take design decision in terms if the system satisfies key quality attributes. 
An architecture evaluation is concerned with answering what, why and how to evaluate, and whether the AD supplies sufficient information for analysis.</td></tr>
  <tr><td><b>4. Questions</b></td><td><b>4a. Respondents</b></td><td><b>4b. Expected answers</b></td><td><b>4c. Criticality</b></td></tr>
  
  <tr>
  <td>
  1. Are the business goals of system clearly articulated and prioritized?</br></br>
  2. Have the stakeholders and their concerns been clearly defined? </br></br>
  3. Is there a clear understanding of the quality attributes that the architecture must satisfy? </br></br>
  4. Are the quality attributes measurable? </br></br>
  5. Are the quality attributes achievable? </br></br>
  6. Are any of the quality attributes unrealistic? </br></br>
  7. Are the ASRs that the system must satisfy clearly articulated and prioritized according to their impact on the architecture? </br></br>
  8. Can you determine the views necessary to analyze key quality attributes? Does the AD provide the views necessary to cover each QAS? </br></br>
  9. Are you able to identify key behavioral properties of the system? </br></br>
  10. Are any points of variation to the system captured in the AD? </br></br>
  11. Are the relationships between system and external components explicitly documented? </br></br>
  12. Does the AD contain the rationale for its architectural design decisions? </br></br>
  13. Can the AD support analysis of interfaces of other systems and their architectures? Does it define the relationship with other dependent architectures? </br></br>
  14. Are there any known inconsistencies to the system documented in AD? </br>
  </td>
  
  <td>Project Leads</td>
  
  <td>Positive answers are expected and the respondents must be able to identify places and elements in the AD which can justify their response to support results.</td>
  
  <td>Logical and</td>
  
  </tr>
  
  <tr><td colspan=4><b>Advice:</b> The same set of questions could be shared with new comer to the project for the person to have better understanding in speculating system architecture in regards to key quality attributes and also concerns such as does this AD meet all of the conformance points? Can this conformance be verified?</td></tr>
  
  
</table>



## 4. Plan for the review


## 5. Analysis and summary of review

### 5.1 Analysis of the result

**Q1. Are the business goals of system clearly articulated and prioritized?** </br>
Business goals of the system are very well categorized into three sections: Goal-object, Goal and Remarks/references. The goal-object puts the business goal into its most condensed category which makes the evaluation of business goals effective. 
Remarks/references section provide link to an artifact of system(such as Swagger UI's home page, Blog page, etc.) for each of the business goal which tries to provide evidence for each of the goal. However, it fails to deliver clear understanding on why the specific reference is related to the corresponding business goal.</br>

Total 11 business goals are articulated in the AD which depicts quite important business goal aspects of the system and so is very well prioritized among other secondary goals. </br></br>

**Q2. Have the stakeholders and their concerns been clearly defined?** </br>
Role of each stakeholder of a system is vital because actions of whom define the outcome of the business decisions. In the system AD, role and corresponding concern of the stakeholder is defined in a tabular form which provides better readable format. The role, as the name suggest, categorize the identity of a stakeholder and concern elaborates the role. However, this format on many occasion misses the specific names of key stakeholders to the system. Also, this format could be extended to where "instances" could be added in addition to role and concern which could clearly mention the current corresponding instance of a stakeholder such as the names of core management individuals. </br></br>


**Q3. Is there a clear understanding of the quality attributes that the architecture must satisfy?** </br>
Out of all the quality attributes relevant to the Swagger UI system, 7 prioritized ones are mentioned in the AD defined in correspondence to architecturally sgnificant requirements. Depicting quality attributes in correspondence to ASRs is the best way to analyse the systems key quality attributes. Out of these 7 prioritized attributes, 3 key quality attributes (performance, usability and reliability) were detailed into quality attribute scenario template format to calculate various aspects taking various scenario for the system. </br>
Using scenarios and the utility tree is very helpful and great way to enhance the quality of the architecture in the long run. These artifacts also clearly supply the needed understanding of the quality attributes of the system. </br></br>


**Q4. Are the quality attributes measurable?** </br>
Quality attributes in the AD is evaluated using the utlity tree and quality attribute scenarios for 3 key quality attributes to the system. The quality attribute scenaarios provides a scenario for each of 3 key quality atributes evaluated with factors such as stimulus, stimulus source, response and response measure. Both Utility tree and QAS are sufficient to justify that these quality attributes are measurable. </br></br>


**Q5. Are the quality attributes achievable?** </br>
Yes, the key quality attributes mentioned in the AD are achievable as depicted in QAS tables and utility tree in correspondence to the system. </br></br>


**Q6. Are any of the quality attributes unrealistic?** </br>
No, there isn't any quality attribute metioned unrealistic. The key quality attributes in AD could be broken down into scenarios and are measurable and achievable. </br></br>

**Q7. Are the ASRs that the system must satisfy clearly articulated and prioritized according to their impact on the architecture?** </br>
The ASRs to the system are mentioned in AD in correspondence to the quality attributes. Each of the ASRs are very clear to understand as these are mentioned with reference to the source. For example an ASR mentioned as "Assure that the stack trace is fully provided to aid in tracking down bugs." in the ASR table has source of a Swagger UI documentation. All the sources makes it very legit and easy to articulate.  </br>
Prioritization is done on the basis of corresponding quality attribute. The 7 quality attrbutes mentioned are the important ones to the system, hence the ASRs accordingly. </br> </br>

**Q8. Can you determine the views necessary to analyze key quality attributes? Does the AD provide the views necessary to cover each QAS?** </br>
There are two views articulated in the AD, module view and component & connector view. </br>
A module view is a module structure which provides a set of the system's modules and their organization. Module view of the system is presented as uses view type diagram in AD which is in correspondence to one of the key quality attribute scenario for performance QA. The diagram for module view describe each of the element of the system appropriately with keys mentioned.</br>
Another type of view used to answer important questions of QAS described in the AD is Component & Connector view. This type of view is mainly used to articulate execution components of the system. A Client-Server diagram is used here again to express QAS with performance QA. The diagram self describes the view in most appropriate manner. However, showing "system" component inside "Swagger-UI" container seems unnecessary as the system Swagger-UI is mentioned as container component to cover all the other internal run time components inside it.</br>

The AD does not provide views to cover each QAS. The views utilized in the AD covers only one QA i.e. performance which is the most appropriate QA to bond with these views.</br></br>

**Q9. Are you able to identify key behavioral properties of the system?**</br>
Yes, behavior of the system is clearly mentioned in the AD for the system using two views mentioned (module view and C&C view). A procedural sequence diagram to specify and construct react rendering mechanism in Swagger-UI for module view.
Another behavior diagram is mentioned to depict key brhavior activity of the system to present the dynamic aspects of the system. This is achieved in AD as presenting state based static state charts for C&C view.
The states and substates are mentioned appropriately in the AD in regards to C&C view to conform behavior of the system.</br></br>


**Q10. Are any points of variation to the system captured in the AD?**</br>
Yes, variability to the system is shown with regards to C&C view of the system. The three possible variation points to the system are captured as Add or Remove Validator, Add or Remove API Server and Add or Remove YAML Config Server.</br></br>

**Q11. Are the relationships between system and external components explicitly documented?**</br> 
Relationship of the system with external components are described in AD using context diagram in regards with module view and C&C view.
The context diagram for module view shows how Swagger-UI interacts with external tools and frameworks.
While, for C&C view, the context diagram shows various components, external tools, and frameworks that interact with Swagger-UI during runtime rendering.</br></br>

**Q12. Does the AD contain the rationale for its architectural design decisions?**</br>
Rationale is mentioned in AD to articulate why designers organized the system's modules and runtime components this way. The two rationale for module view and C&C view is well-reasoned with few assumptions mentioned. Both the rationale is in regards with QAS mentioned in for the views i.e. for Performance QA.</br></br>


**Q13. Can the AD support analysis of interfaces of other systems and their architectures? Does it define the relationship with other dependent architectures?**</br>

Interface is usually the point where two component communicate with each other. It could be internal or external to the system but independent from each other. AD's module view shows header and curl modules of the system to present interfaces to modules of the system. There are two interface descriptions mentioned in the AD for C&C view of the system. They are for SwaggerUI Requests OAS Specs, and SwaggerUi Starts/Updates React Structure.</br>
Performance and maintainability are the two key QA which are articulated here for interface diagrams.</br>
Hence, this AD supports the analysis of interfaces. However, It does not analyses the architecture of external components to the system which are communicated using interface.</br></br>



### 5.2 Summary and potential future roadmap

