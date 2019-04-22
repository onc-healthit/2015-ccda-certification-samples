# 2015-C-CDA-Certification-Samples
This repository contains sample C-CDA files which have passed the ONC 2015 Edition using ONC 2015 Edition test procedures. The upload of these example files is optional, at the discretion of each ONC-Authorized Testing Labortory (ONC-ATL).

Of note: these C-CDAs are uploaded at the time they are tested; as such, they may not pass the most recent version of the C-CDA validator due to subsequent errata corrections.

Users of the Repository
-----------------------
This repository can be used (at their option) by ONC-Authorized Testing Labortories who are certifying vendor systems to the ONC 2015 Edition. The ONC-ATL can upload C-CDA samples that have been used in the certificaiton testing for the benefit of the health IT community.

Process for Uploading Files
--------------------------
The ability to add to the repository is restricted to one group of ATL administrators (one for each ATL). To be added to this exclusive group, the following process will be required: 

1) ATL sends an e-mail with the subject line: “Access to 2015 C-CDA Certification Samples” to: SITTeam@hhs.gov, along with the ATL admin's github credentials.
2) The SITE team will receive the email and create a JIRA ticket in the SITE JIRA project for tracking internally.
3) The SITE team will confirm the validity of the user access credentials with the Certification Team (via email or otherwise). 
4) On verification of access need and credentials, the SITE team will add the account to the GitHub ATL admin group.
5) The SITE team will notify the ATL submitter that access has been granted to upload into the repository. 

It will be up to the ATL’s and their administrators to ensure that only the test success C-CDA’s are uploaded. 

The public will be able to view-download the submitted files from this repository.  

If you have any additional questions, please contact SITTeam@hhs.gov.

Folder/File Structure and Naming Convention
-----------------------
ATL’s will create an organized folder structure to store the artifacts with the hierarchy of: 
 - vendor name 
   - product name. 
     - The C-CDA artifacts successfully tested shall be placed in the folder "product name"
     - Under the Product Name folder there should be four folders:
       a)  C-CDA 2.1 Document Template: Continuity of Care Document
       b)  C-CDA 2.1 Document Template: Referral Note
       c)  C-CDA 2.1 Document Template: Discharge Summary
       d)  C-CDA 2.1 Document Template: Care Plan

Then within these folders, File Name Structure:
ATL +Template Type+ Criterion+ Developer + ProductName+ Date) (ICSA_CCD_b1_Cerner_BestEHR_MMDDYYYY)

The files should be grouped in the folder by validator release tested against (ETT release) or some other chronological file folder order.

