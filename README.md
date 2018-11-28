# SFDX  App

## Dev, Build and Test


## Resources


## Description of Files and Directories


## Issues

## Post Install Instructions
### Set Page Layout Assignment
* In the Setup object, go to the Object Manager tab, select Certification. Assign the page layouts
    * Achieved record type: Certification Layout
    * Planned record type: Planned Layout
* In the Exam object, assign the page layouts
    * Certification rt: Exam Layout
    * Maintenance rt:  Maintenance Layout
### Assign Custom Label variable
* In the Setup object, go to the Object Manager tab, select Certification.
* Go to Record Types and open Achieved.
* Copy the Record Type Id (second id) from the Browser's address.
* Click on the Home tab and enter in Custom Labels in Quick Find
* Click Edit next to "CertAchvdRtid"
* Paste the Id into the value field (delete the existing variable), and click Save.