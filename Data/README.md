# Data
Data is mainly formed by two files: German credit dataset and external data.
## German credit dataset
Data associated to a credit request and its corresponding Risk
* Number of instances: 1000.
* Number of attributes: 9 (4 numerical, 5 categorical).
### Attributes
* Age in years (numeric)
* Gender: male or female (categorical)
* Current job (categorical):
    * 0 : unemployed/ unskilled  - non-resident
    * 1 : unskilled - resident
    * 2 : skilled employee / official
    * 3 : management/self-employed/highly qualified employee/officer
* Housing: own, rent, or rent (categorical).
* Saving account (categorical):
    * null
    * little
    * moderate
    * rich
    * quite rich
* Checking account (categorical):
    * null
    * little
    * moderate
    * rich
* Credit amount (numerical)
* Credit duration (numerical)
* Purpose (categorical):
    * business
    * car
    * domestic appliances
    * education
    * furniture/equipment
    * radio/TV
    * repairs
    * vacation/others
### Label
* Risk (good/bad)
## External Data
Additional data related to credit frauds.
* Number of instances: 1063.
* Number of attributes: 6 (6 numerical).
### Attributes
* LegalCase: The applicant has been involved in a legal case involving unpaid credits.
* FraudSuspicion: The applicant has been registered in any external data source as fraudulent when paying subscription services like Telecomunications, mobiles, etc.
* PoliceReport: The applicant is registered in at least one Police Report related to fraud.
* ContactAudit: The applicant may be in a source of fraud audit data.
* UkvCheck: The applicant has not paid the income tax.
* AddressFraudCheck: The applicant has used false addresses fraudulently.