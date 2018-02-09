# Privacy Register White Paper

Article 30 of the General Data Protection Regulation (GDPR) brings into existence an obligation for controllers and processors to maintain a record of processing activities. The Privacy Register is an open standard that could be used to fulfil this obligation. 

This White Paper contains an assessment of the legal requirements that follow from article 30 GDPR. It serves as a basis for the specifications of the open standard and contains the following:

1. An explanation of the legal and theoretical framework and structure of article 30 GDPR, taking into account:
	- Recitals of the regulation
	- Literature
2. An elaboration of our own position with regard to the framework and the open standard.

### Legal and theoretical framework

1. General Data Protection Regulation (GDPR)	
	1. Background
		- The GDPR was adopted on 27 April 2016 and takes effect on 25 May 2018.
		- The GDPR replaces the data protection directive (Directive 95/46/EC) of 1995.
		- As a regulation it is directly applicable in all EU countries.
	2. Objective
		- The objective of the GDPR can be found in article 1 of the regulation:
			- **Article 1(1)**
			- *This Regulation lays down rules relating to the protection of natural persons with regard to the processing of personal data and rules relating to the free movement of personal data.*
		- An explanation in greater depth can be found in the recitals of the GDPR:
			- **Recital 7**
			- *Those developments (globalisation and rapid technological developments, ed.) require a strong and more coherent data protection framework in the Union, backed by strong enforcement, given the importance of creating the trust that will allow the digital economy to develop across the internal market*
		- The European legislator stresses in recitals 1 to 7 that the regulation also aims to provide a high level of protection in order to guarantee the fundamental right to the protection of personal data.

2. Article 30 GDPR
	1. Ratio
		- Article 30 must be read in the light of the principles relating to processing of personal data as summed up in article 5 GDPR.
		- The obligation to maintain a record of processing activities aims to:
			1. Increase transparancy regarding the processing of personal data; 
			2. Fill in the accountability of organisations; and
			3. Serve as a basis for other compliance requirements.
	2. Terminology
		- **Personal data**

			- Article 4(1) GDPR defines 'personal data' as:
			- *any information relating to an identified or identifiable natural person (‘data subject’); an identifiable natural person is one who can be identified, directly or indirectly, in particular by reference to an identifier such as a name, an identification number, location data, an online identifier or to one or more factors specific to the physical, physiological, genetic, mental, economic, cultural or social identity of that natural person;*

			- Recital 26 of the GDPR states that to determine whether a natural person is identifiable, account should be taken of all the means reasonably likely to be used, such as singling out, either by the controller or by another person to identify the natural person directly or indirectly.

		- **Processing (activity)**

			- Article 4(2) GDPR defines 'processing' as: 
			- *any operation or set of operations which is performed on personal data or on sets of personal data, whether or not by automated means, such as collection, recording, organisation, structuring, storage, adaptation or alteration, retrieval, consultation, use, disclosure by transmission, dissemination or otherwise making available, alignment or combination, restriction, erasure or destruction;*

		- **Controller**

			- Article 4(7) GDPR defines 'controller' as:
			- *the natural or legal person, public authority, agency or other body which, alone or jointly with others, determines the purposes and means of the processing of personal data;*

		- **Processor**

			- Article 4(8) GDPR defines 'processor' as:
			- *a natural or legal person, public authority, agency or other body which processes personal data on behalf of the controller;*

3. General remarks
	1. **Useful.** The record of processing activities must be useful. As a consequence each record of a processing activity should be sufficiently specified and contain the legal ground on which the processing activity is based.
	2. **Complete.** The record of processing activities must be complete. This does however not mean that the register should literally contain all information. By making use of categorizations (e.g. for data subjects and recipients) it is possible to equate a category with a number or other character whose meaning is documented elsewhere. This also applies to the security policy (technical and organizational measure) for which a reference to a location or document could suffice.

4. Which information should a record of processing activities contain according to article 30 GDPR?
	1. Paragraph 1 of article 30 GDPR states that a record of processing activities maintained by a **controller** must contain the following information:
		- a) the name and contact details of the controller;
			- Controller name
			- Controller address
			- Contact details
				- Phone
				- Post
				- E-mail
				- Other
			- Where applicable, the contact details of a representative and the data protection officer

			*A controller should be easily reachable by the supervisory authority. It is therefore recommended for a user to submit multiple contact options*

		- b) the purposes of the processing activity;
			- The controller must describe the purpose(s) of each processing activity
			- The description must be specific and explicit

			*Responsibility as to what qualifies as a processing activity lies with the user. Due to its nature no suggestions or recommendations are included in the initial version of the open standard. It is up to the user to be as specific as possible per processing activity. Passive processing, depending on the organisation, can be of great importance and the user should therefore bear in mind that a processing activity could be both active as passive in nature.* 

		- c) a description of the categories of data subjects and of the categories of personal data;

			*It is crucial to include specific requirements that follow from the GDPR, such as the distinction between ordinary and special personal data and special regulations for minors. After all, the GDPR is an accountability instrument and the record of processing activities could be seen as a starting point for an organisation to comply with the GDPR.* 

		- d) the categories of recipients to whom the personal data have been or will be disclosed;

			*It must be kept in mind that a recipient could also be a part of an organisation (e.g. a certain department). The distinction has consequences with regards to the purpose limitation of the processing. The term 'recipient' must therefore be supplemented with 'persons entitled to access' (these are not designated by name, but can be determined uniquely by means of role or job description, for example).The distinction between internal and external recipients is therefore included in the register.*

		- e) where applicable, transfers of personal data to a third country or an international organisation, including the identification of that third country or international organisation;

			*No use can be made of categorization. Each country or international organisation must therefore be specifically described by the user. This can not be standardized and responsibility thus lies entirely with the user. However, including adequacy decisions can be considered for future versions of the Privacy Register. (Article 45(1) GDPR)*

		- f) where possible, the envisaged time limits for erasure of the different categories of data;

			*The retention period of the personal data must be motivated in connection with the necessity of that processing activity in order to achieve the purposes mentioned.*
			*A general reference to a retention period does not suffice. Precise information is required.*
			*The retention period can be specified by quantitative means as well as by qualitative criteria.*

		- g) where possible, a general description of the technical and organisational security 
		measures referred to in Article 32(1).
			- The following measures are mentioned in article 32(1) GDPR:
				- the pseudonymisation and encryption of personal data;
				- the ability to ensure the ongoing confidentiality, integrity, availability and resilience of processing systems and services;
				- the ability to restore the availability and access to personal data in a timely manner in the event of a physical or technical incident;
				- a process for regularly testing, assessing and evaluating the effectiveness of technical and organisational measures for ensuring the security of the processing.
			
			*Technical and organisational security measures must be described by the user, possibly supplemented with references in the register to existing security documents*
	2. Paragraph 2 of article 30 GDPR defines that a record of processing activities maintained by a **processor** must contain the following information:
		- a) name and contact details of the processor and of each controller on behalf of which the processor is acting;
			- If applicable, the contact details of the representative and the data protection officer of the controller

		- b) categories of processing carried out on behalf of each controller;

		- c) where applicable, transfers of personal data to a third country or an international organisation, including the identification of that third country or international organisation

		- d) where possible, a general description of the technical and organisational security measures referred to in Article 32(1).

5. Form of the register
	- According to article 30(3) GDPR the record of processing activities must be in writing, including in electronic form.

6. Applicability
	- In principle, all organisations are obliged to keep a register of processing operations pursuant to paragraph 1 or 2. The exemption clause in paragraph 5 states that this obligation does not exist when an organisation employs fewer than 250 persons. However, such organisations are still required to maintain a register under the following circumstances:
     - When the processing involves a risk to the rights and freedoms of the data subjects;
     - **When the processing is non-incidental**; or
     - When processing concerns special categories of personal data or personal data in connection with criminal convictions and criminal offenses.

7. Relation to other recording activities under the GDPR

### Position

1. Why?
	- Article 30 GDPR brings into existence an obligation for controllers and processors to maintain a record of processing activities. 
	- The record must contain information about the types of personal data they store and process and which security measures have been taken. 
	- Due to a number of reasons it can be a heavy burden for start-ups and small organisation to comply with this obligation.
	- This white paper çreates an open standard that could be used to fulfil the obligations that arise from article 30 GDPR. The aim is to make it easier to set up, maintain and share a record of processing activities.
2. Who are we?
	- This white paper was created by students of [Clinic Law Incubator](https://clinic.nl/), a law incubator specialised in IP/IT law and Privacy from Amsterdam, The Netherlands. 
	- We encourage everyone with an interest in privacy law to contribute to the project by forking the project and submitting a pull request.
3. What?
	- The open standard incorporates all information as required in article 30 GDPR and gives a base level for compliance with article 30 GDPR.
	- Compliance ultimately depends on the information the user submits and the ways in which the user makes use of the standard. 
4. For Whom?
	- The open standard as proposed in this white paper is designed as to be fit for use for most organisations.
	- Specific requirements should be determined on an organisational level.
5. How?
	- The technical specifications of the open standard can be found [here](https://github.com/legalclinic/privacyregister-standard/blob/master/Technical%20specifications%20%5BEN%5D.md)

### Resources

- [Regulation (EU) 2016/679 (*General Data Protection Regulation*)](http://eur-lex.europa.eu/legal-content/en/TXT/?uri=CELEX%3A32016R0679)
- [DPA Belgium, 'Aanbeveling betreffende het Register van de verwerkingsactiviteiten (artikel 30 van de AVG)
(CO-AR-2017-011)'](https://www.privacycommission.be/sites/privacycommission/files/documents/aanbeveling_06_2017_0.pdf)
- [DPA Saksen-Anhalt, 'Hinweise zum
Verzeichnis von Verarbeitungstätigkeiten, Art. 30 DS-GVO'](https://datenschutz.sachsen-anhalt.de/informationen/internationales/datenschutz-grundverordnung/)
- J. Berkvens & C. Jakimowicz, 'Tekstuitgave Privacyverordening', Den Haag : Boom Juridisch 2016
- B.W. Schermer, 'Van meldplicht naar registerplicht: de registratie van verwerkingen onder de AVG', *Computerrecht* 2017/151
- A. Engelfriet, L. Meij & P. Kager, 'De Algemene Verordening Gegevensbescherming. Artikelsgewijs commentaar', Amsterdam : Ius Mentis 2017
- M. Krzusztofek, 'Post-Reform Personal Data Protection in the European Union. General Data Protection Regulation', Alpen aan de Rijn : Kluwer Law International 2017