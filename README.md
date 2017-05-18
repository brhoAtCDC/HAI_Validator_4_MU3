HAI_Validator_4_MU3
=======

For 2018, Antimicrobial Resistance and Antimicrobial Use reporting to the National Healthcare Safety Network (NHSN) 
has been identified as a new option for public health registry reporting under Meaningful Use Stage 3.  
See https://www.federalregister.gov/articles/2015/03/30/2015-06612/2015-edition-health-information-technology-health-it-certification-criteria-2015-edition-base.  
See certification criterion ( 170.315(f)(6)).    

In order to qualify as certified technology an EHR or EHR Module must be capable of 
creating  Clinical Document Architecture (CDA) documents for 
Antimicrobial Use and Resistance conformant to the HL7 Implementation Guide for 
CDA ? Release 2—Level 3: Healthcare Associated Infection Reports, Release 1—US Realm—August 2013.  
See http://www.hl7.org/implement/standards/product_brief.cfm?product_id=20.   
The following CDAs must all be successfully generated.
•	Antimicrobial Resistance Option (ARO) Report (Numerator) specific document template in Section 2.1.2.1 (pages 69-72);
•	Antimicrobial Resistance Option (ARO) Summary Report (Denominator) specific document template in Section 2.1.1.1 (pages 54-56);
•	Antimicrobial Use (AUP) Summary Report (Numerator and Denominator) specific document template in Section 2.1.1.2 (pages 56-58)
The validator checks the aforementioned CDAs for three levels of conformance. 

•	Check for valid XML
•	Check that the file validates against the cda.xsl schema
•	Check that the file validates against the hai.sch Schematron

The schema and schematron files were all developed by Lantana Consulting Group 
(see http://www.lantanagroup.com/ )under contract to the Centers for Disease Control and Preventions (CDC).

This validator uses an open source tool called Probatron (see https://code.google.com/archive/p/probatron4j/)
as well as custom scripting.  Probatron.jar is included in the installation zip file.  


Contributing

Anyone is encouraged to contribute to the project by forking and submitting a pull request. (If you are new to GitHub, 
you might start with a basic tutorial.) By contributing to this project, you grant a world-wide, royalty-free, perpetual, 
irrevocable, non-exclusive, transferable license to all users under the terms of the Apache Software License v2 or later.
All comments, messages, pull requests, and other submissions received through CDC and PHIResearchLab.org pages including 
this GitHub page are subject to the Presidential Records Act and may be archived. Learn more http://cdc.gov/privacy

License

This project constitutes a work of the United States Government and is not subject to domestic copyright protection under 17 
USC Â§ 105. The project utilizes code licensed under the terms of the Apache Software License and therefore is licensed 
under ASL v2 or later. This program is free software: you can redistribute it and/or modify it under the terms of the 
Apache Software License version 2, or (at your option) any later version.
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty 
of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the Apache Software License for more details.You should have 
received a copy of the Apache Software License along with this program. If not, see http://www.apache.org/licenses/LICENSE-2.0.html

Privacy

This project contains only non-sensitive, publicly available data and information. All material and community participation 
is covered by the PHIResearchLab.org Disclaimer and Code of Conduct. For more information about CDC's privacy policy, 
please visit http://www.cdc.gov/privacy.html


