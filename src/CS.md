# EU Common Services APIs
Online procedures are made up of requirements. For a procedure to be completed, all of its corresponding requirements are to be fulfilled. It is the case therefore that Citizens are, via the ER, able to fulfil one or more requirements using OOTS. To fulfil a requirement, evidence is required to prove (or disprove) the said requirement. To locate the required evidence, the Citizen is to select the evidence type which is presented by OOTS and is derived from the selected requirements. It is therefore the case that Procedures are made up of Requirements, which in turn are made up of Evidence Types.  

As per the OOTS Technical Design, during each Evidence Exchange, ERs are to consult two services known as 1) the **Evidence Broker (EB)** and 2) the **Data Services Directory (DSD)** to gather all the necessary information needed to request Evidence on behalf of a Citizen. 

The Common Services APIs responsible for providing the following information:  
1. _Evidence Broker_: Return a list of requirements, given a procedure ID.
2. _Evidence Broker_: Return a list of evidence types, given a requirement ID.
3. _Data Services Directory_: uses the Evidence Types obtained from the EB to retrieve a list of possible EPs and their respective Data Services. 

The above three steps are instrumental for obtaining the required details to be able to issue an Evidence Request, which is essentially an XML metadata file containing information such as EP location and evidence file metadata. This Evidence Request file is then packaged as an eDelivery message and transferred to the national eDelivery Access Point for processing.

While the existence of eDelivery is worth mentioning, all of its functionality is abstracted by the SDG OOTS Integration API into simple REST calls and is therefore outside the scope of this Integration Document.