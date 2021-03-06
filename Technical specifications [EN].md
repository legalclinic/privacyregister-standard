# Technical specifications

This document holds the technical specifications of the open standard and is based on the Privacy Register White Paper [EN]. It contains the following:

1. Specifications of the structure of the register
2. Specifications of the user interface
3. User stories
4. Points which are still to be discussed

## 1. Specifications of the structure of the register

#### Which information should the record contain?

##### 1. Information about the Organisation

| Organisation:                            | Mandatory: | Sort:      |
| ---------------------------------------- | ---------- | ---------- |
| **Name:**                                | Yes        | Text field |
| **Point of contact:**                    | Yes        | Text field |
| **Chamber of Commerce-Number:**          | Dependent  | Number     |
| **Address:**                             | Yes        | Text field |
| **Phone Number:**                        | Dependent  | Number     |
| **E-mail address:**                      | Dependent  | Text field |
| **Data Protection Officer name**         | Dependent  | Text field |
| **Data Protection Officer e-mail address** | Dependent  | Text field |
| **Data Protection Officer phone number** | Dependent  | Text field |
| **Representative name**                  | Dependent  | Text field |
| **Representative e-mail address**        | Dependent  | Text field |
| **Representative phone number**          | Dependent  | Number     |

##### 2. Processing activity as a controller

| Name data processing activity: |                                          |
| ------------------------------ | ---------------------------------------- |
| Mandatory:                     | Yes                                      |
| Question:                      | What is the name of the processing activity you want to add to the register? |
| Description:                   | Article 4(2) GDPR defines 'processing' as: *Any operation or set of operations which is performed on personal data [..]* |
| Sort:                          | Text Field                               |

| Department:  |                                          |
| ------------ | ---------------------------------------- |
| Mandatory:   | No                                       |
| Question:    |                                          |
| Description: | This field enables users to apply a departmental categorization to the processing activities |
| Sort:        | List generated by user                   |

| Purpose(s) of the processing activity: |                                          |
| -------------------------------------- | ---------------------------------------- |
| Mandatory:                             | Yes                                      |
| Question:                              | What is the legitimate purpose of this processing activity? |
| Description:                           | The purpose of the processing activity has to be specified and explicit. |
| Sort:                                  | Text field                               |

| Categories of data subjects: |                                          |
| ---------------------------- | ---------------------------------------- |
| Mandatory:                   | Yes                                      |
| Question:                    | From what types of individuals are personal data collected? |
| Description:                 |                                          |
| Sort:                        | Text field / multiple entries            |

| Categories of personal data: |                                          |
| ---------------------------- | ---------------------------------------- |
| Mandatory:                   | Yes                                      |
| Question 1:                  | What categories of personal data are being collected for this processing activity? |
| Description:                 | Personal data: *Any information relating to an identified or identifiable natural person ('data subject'); an identifiable natural person is one who can be identified, directly or indirectly, in particular by reference to an identifier such as a name, an identification number, location data, an online identifier or to one or more factors specific to the physical, physiological, genetic, mental, economic, cultural or social identity of that natural person.* |
| Sort:                        | Text field / multiple entries            |
| Question 2:                  | Specify per category whether those personal data can be qualified as special. |
| Description:                 | Special personal data: *Data revealing racial or ethnic origin, political opinions, religious or philosophical beliefs, or trade union membership, and the processing of genetic data, biometric data for the purpose of uniquely identifying a natural person, data concerning health or data concerning a natural person's sex life or sexual orientation.* |
| Sort:                        | Boolean                                  |

| Legal bases for processing: |                                          |
| --------------------------- | ---------------------------------------- |
| Mandatory:                  | Yes                                      |
| Question:                   | What is the legal basis for processing these personal data? |
| Description:                | Processing personal data requires at least one of the six lawful bases. A lawful basis is the reason why you are permitted to process personal data. |
| Sort:                       | Dropdown, multiple selection. Dependent on why personal data is processsed (per processing activity) |
| **Normal**                  |                                          |
| Option 1:                   | Consent data subject (art. 6.1 (a) GDPR) |
| Option 2:                   | Necessary for the performance of a contract(art. 6.1 (b) GDPR) |
| Option 3:                   | Necessary for compliance with a legal obligation(art. 6.1 (c) GDPR) |
| Option 4:                   | Necessary in order to protect the vital interests of the individual (art. 6.1 (d) GDPR) |
| Option 5:                   | Necessary for the performance of a task carried out in the public interest or in the excercise of official authority vested in the controller. (art. 6.1 (e) GDPR) |
| Option 6:                   | Necessary for the purposes of the legitimate interests pursued by the controller or by a third party (art. 6.1 (f) GDPR) |
| **Special**                 |                                          |
| Option 1:                   | Explicit consent data subject (art. 9.2 (a) GDPR) |
| Option 2:                   | necessary for the purposes of carrying out the obligations and exercising specific rights of the controller or of the data subject in the field of employment and social security and social protection law (art. 9.2 (b) GDPR) |
| Option 3:                   | necessary to protect the vital interests of the data subject or of another natural person where the data subject is physically or legally incapable of giving consent (art. 9.2 (c) GDPR) |
| Option 4:                   | carried out in the course of its legitimate activities with appropriate safeguards by a foundation, association or any other not-for-profit body with a political, philosophical, religious or trade union aim and on condition that the processing relates solely to the members or to former members of the body or to persons who have regular contact with it in connection with its purposes and that the personal data are not disclosed outside that body without the consent of the data subjects (art. 9.2 (d) GDPR) |
| Option 5:                   | Processing relates to personal data which are manifestly made public by the data subject (art. 9.2 (e) GDPR) |
| Option 6:                   | necessary for the establishment, exercise or defence of legal claims or whenever courts are acting in their judicial capacity (art. 9.2 (f) GDPR) |
| Option 7:                   | Necessary for reasons of substantial public interest (art. 9.2. (g) GDPR) |
| Option 8:                   | Necessary for the purposes of preventive or occupational medicine, for the assessment of the working capacity of the employee, medical diagnosis, the provision of health or social care or treatment or the management of health or social care systems and services on the basis of Union or Member State law or pursuant to contract with a health professional and subject to the conditions and safeguards referred to in paragraph 3 (art. 9.2. (h) GDPR) |
| Option 9:                   | Necessary for reasons of public interest in the area of public health (art. 9.2 (i) GDPR) |
| Option 10:                  | Necessary for archiving purposes in the public interest, scientific or historical research purposes or statistical purposes in accordance with Article 89(1) based on Union or Member State law which shall be proportionate to the aim pursued, respect the essence of the right to data protection and provide for suitable and specific measures to safeguard the fundamental rights and the interests of the data subject. (art. 9.2. (j) GDPR) |

| Categories of internal recipients: |                                          |
| ---------------------------------- | ---------------------------------------- |
| Mandatory:                         | Yes                                      |
| Question:                          | To whom will the data be disclosed / which recipients have access to the data? |
| Description:                       | Define which internal positions are entitled to access the personal data. |
| Sort:                              | Text field / multiple entries            |

| Categories of external recipients: |                                          |
| ---------------------------------- | ---------------------------------------- |
| Mandatory:                         | Yes                                      |
| Question:                          | To whom will the data be disclosed / which recipients have access to the data? |
| Description:                       | Define which external parties are entitled to access the personal data. |
| Sort:                              | Text field / multiple entries            |

| Transfers of personal data to a third country or an international organisation: |                                          |
| ---------------------------------------- | ---------------------------------------- |
| Mandatory:                               | Yes                                      |
| Question:                                | Are the data transferred to international organisations or countries outside of the European Economic Area (EU countries plus Norway, Iceland and Liechtenstein)? |
| Description:                             | Transfers applicable to the processing activity |
| Sort:                                    | Boolean                                  |
| Mandatory:                               | Dependent                                |
| Question 2:                              | To which countries are the data transferred outside of the European Economic Area (EU countries plus Norway, Iceland and Liechtenstein)? |
| Description:                             | Identify which countries and/or international organisations |
| Sort:                                    | Text field / multiple entries            |

| Retention Period: |                                          |
| ----------------- | ---------------------------------------- |
| Mandatory:        | Yes                                      |
| Question:         | What is the retention period of this personal data? |
| Description:      | Motivate the necessity of the retention period by quantitative means. If this is not possible, specify the qualitative criteria for determining the retention period. |
| Sort:             | Date or Text field                       |

| Security Measures: |                                          |
| ------------------ | ---------------------------------------- |
| Mandatory:         | Yes                                      |
| Question:          | Which technical and organizational security measures have been implemented for this processing activity? |
| Description:       | Art. 32: Taking into account the state of the art, the costs of implementation and the nature, scope, context and purposes of processing as well as the risk of varying likelihood and severity for the rights and freedoms of natural persons, the controller and the processor shall implement appropriate technical and organisational measures |
| Sort:              | Text field, multiple entries             |

| Source: |                                          |
| ------------------ | ---------------------------------------- |
| Mandatory:         | Dependent                                      |
| Question:          | Where does the personal data orginate from? |
| Description:       | Art. 14 and right of access require any available information to their source, where the personal data are not collected from the data subject  |
| Sort:              | Text field, multiple entries             |

##### 3. Processing activity as a processor

| Categories of processing: |                                          |
| ------------------------- | ---------------------------------------- |
| Mandatory:                | Yes                                      |
| Question:                 | What category of processing activities would you like to submit? |
| Description:              | Please describe the processing activity that is carried out on behalf of a controller |
| Sort:                     | Text field / multiple entries            |

| Name controller:                         |                                          |
| ---------------------------------------- | ---------------------------------------- |
| Mandatory:                               | Yes                                      |
| Question:                                | For which controller(s) are the personal data being processed? |
| Description:                             | Please enter the name of the controller and, if applicable, the name of its DPO and/or representative |
| Sort:                                    | multiple entries                         |
| **Name of the controller:**              | Text field                               |
| **Contact details of the controller:**   | Text field                               |
| **Data Protection Officer name**         | Text field                               |
| **Data Protection Officer e-mail address** | Text field                               |
| **Data Protection Officer phone number** | Number                                   |
| **Representative name**                  | Text field                               |
| **Representative e-mail address**        | Text field                               |
| **Representative phone number**          | Number                                   |

| Transfers of personal data to a third country or an international organisation: |                                          |
| ---------------------------------------- | ---------------------------------------- |
| Mandatory:                               | Yes                                      |
| Question:                                | Are the data transferred to international organisations or countries outside of the European Economic Area (EU countries plus Norway, Iceland and Liechtenstein)? |
| Description:                             | Identify which countries and/or international organisations |
| Sort:                                    | Text field / multiple entries            |

| Security Measures: |                                          |
| ------------------ | ---------------------------------------- |
| Mandatory:         | Yes                                      |
| Question:          | Which technical and organizational security measures have been implemented for these personal data? |
| Description:       | Article 32                               |
| Sort:              | Text field, multiple entries             |

#### Example JSON Schema Definition

```JavaScript
// Basic

{
	Organisation : {
		processingActivitiesAsController = [{processingActivityAsController1}, {processingActivityAsController2}, etc..],
		processingActivitiesAsProcessor = [{processingActivityAsProcessor1}, {processingActivityAsProcessor2}, etc..]
	}

}

// Detailed

{
    "title": "Organisation",
    "description": "Information about the Organisation that fills in the Register",
    "type": "object",
    "properties": {
        "id": {
            "description": "The unique identifier for a Organisation",
            "type": "integer"
        },
        "name": {
            "description": "Name of the Organisation",
            "type": "string"
        },
        "contactPerson": {
            "type": "string"
        },
           "chamberOfCommerceNo": {
            "type": "integer"
        },
           "postalAddress": {
            "type": "object",
            "properties": {
            	"streetAddress" : {"type" : "string"},
            	"postalCode" : {"type" : "string"}
            }
        },
        "phoneNumber": {
            "type": "integer"
        },
        "emailAddress": {
            "type": "string"
        },
        "dpoName": {
            "type": "string"
        },
         "dpoEmailAddress": {
            "type": "string"
        },
         "dpoPhoneNumber": {
            "type": "string"
        },
         "representativeName": {
            "type": "string"
        },
         "representativeEmailAddress": {
            "type": "string"
        },
         "representativePhoneNumber": {
            "type": "string"
        },
        "processingActivitiesAsController" : {
        	"type": "array",
        	"processingActivityAsController" : {
        		"type": "object"
        	}
        },
        "processingActivitiesAsProcessor" : {
        	"type": "array",
        	"processingActivityAsProcessor" : {
        		"type": "object"
        	}
        },
    },
    "required": ["id", "name", "contactPerson", "address", "phoneNumber","emailAddress"]
}

{
	"title" : processingActivityAsController,
	"type" : "object",
	"properties": {
        "id": {
            "description": "The unique identifier for a processing activity",
            "type": "integer"
        },
        "namePA": {
            "type": "string"
        },
        "departmentPA": {
            "type" : "array"
            "items" : {
            	"type" : "string"
            }
        },
        "purposePA": {
            "type" : "array"
            "items" : {
            	"type" : "string"
            }
        },
         "categoriesOfDataSubjects": {
            "type" : "array"
            "items" : {
            	"type" : "string"
            }
        },
          "categoriesOfPersonalData": {
            "type" : "array"
            "items" : {
            	"type" : "object",
            	"properties" : {
            		"name" : {"type" : "string"},
            		"special" : {"type" : "boolean"},
            		"legalGround" : {"type" : "string"}
            	}
            }
        },
          "categoriesOfInternalRecipients": {
            "type" : "array"
            "items" : {
            	"type" : "string"
            }
        },
          "categoriesOfExternalRecipients": {
            "type" : "array"
            "items" : {
            	"type" : "string"
            }
        },
        "transfersToThirdCountriesInternationalOrganisations": {
            "type" : "array"
            "items" : {
            	"type" : "string"
            }
        },
		"retentionPeriod": {
            "type" : "array"
            "items" : {
            	"type" : "string"
            }
        },
		"securityMeasures": {
            "type" : "array"
            "items" : {
            	"type" : "string"
            }
        },

}

{
	"title" : processingActivityAsProcesor,
	"type" : "object",
	"properties": {
        "id": {
            "description": "The unique identifier for a processing activity",
            "type": "integer"
        },
        "categoryOfProcessing": {
            "type": "string"
        },
		"controller": {
            "type": "object",
            "properties": {
            	"" : {"type" : "string"},
            	"" : {"type" : "string"}
            }
        },
		"transfersToThirdCountriesInternationalOrganisations": {
            "type" : "array"
            "items" : {
            	"type" : "string"
            }
        },
		"securityMeasures": {
            "type" : "array"
            "items" : {
            	"type" : "string"
            }
        },
	}
}
```

## 2. Specifications of the web application

#### Which information / what functionalities should the web application contain?
1. Landing page
    - The landing page should contain **information** about:
        - The aim of the open standard / Privacy Register;
        - The creators and maintainers of the open standard.
    - The landing page should contain a link to the Github repository
    - The landing page should contain **examples** of records of processing activities
    - The landing page should contain **screenshots or an interactive demo** of the register
    - Footer
      - Privacy statement 
      - Disclaimer
2. Privacy register
- Register view (overview)
    - An overview of the records of processing activities as added by the user.
    - This overview should also include information about the user
- Guided entry
    - Method of adding a record to the Register by using a flowchart/questionnaire
- Manual entry
    - Method to manually add a record to the Register

#### Tech stack
- Handsontables
- HTML5 Local browser storage
    - https://laverna.cc/ 

## 3. User stories
- As a user I want to be able to
  - Be guided in the process of filling in a new entry in the register 
  - See a sorted and grouped overview of the processing activities in the record
  - Make manual adjustments to the register (without the guidance)
  - Export a version of the record in different formats (machine-readable and presentable)
  - Import a version of the record (machine-readable)
  - Store a version of the register in local storage

## 4. Discussion points
- What services are provided after the go-live of the project?
