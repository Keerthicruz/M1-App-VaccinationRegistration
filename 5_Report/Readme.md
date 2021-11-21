# Requirements
## Introduction
The long-term solution to the coronavirus disease 2019 (COVID-19) pandemic, hopefully, will be a globally implemented, safe vaccination program that has broad clinical and socioeconomic benefits. Dozens of vaccines are in development, with 8 currently in phase 1 trials. Some scenarios predict the earliest, widespread availability of a COVID-19 vaccine to be in 2021.1 As launches of prior mass vaccination programs have demonstrated, careful planning to ensure readiness of both the general public and the health community for a COVID-19 vaccine should begin now.

To substantially reduce morbidity and mortality from COVID-19, an efficacious and safe vaccine must be delivered swiftly and broadly to the public as soon as it is available. However, the mere availability of a vaccine is insufficient to guarantee broad immunological protection; the vaccine must also be acceptable to both the health community and general public. Vaccine hesitancy is a major barrier to vaccine uptake and the achievement of herd immunity, which is required to protect the most vulnerable populations. Depending on varying biological, environmental, and sociobehavioral factors, the threshold for COVID-19 herd immunity may be between 55% and 82% of the population.2

Given that certain individuals will be ineligible for COVID-19 vaccination due to age, immunocompromise, and other preexisting medical conditions, a vaccine refusal rate greater than 10% could significantly impede attainment of this goal. Recent surveys, that included 493 and 2200 individuals, suggest only 3 in 4 people would get vaccinated if a COVID-19 vaccine were available, and only 30% would want to receive the vaccine soon after it becomes available.3,4 Confidence in vaccines lies along a spectrum, and individuals who have hesitation about routine childhood vaccines have expressed various concerns.5 In their report on vaccine hesitancy, Edwards and Hackell5 identified 3 broad categories of parents’ concerns regarding childhood vaccines: (1) the necessity of vaccines, (2) vaccine safety, and (3) freedom of choice.5 This Viewpoint describes these categories of concerns with regard to a future COVID-19 vaccine and presents suggestions to enhance the likelihood of rapid, widespread vaccine uptake in the United States.



Each vaccine centre will operate locally to register and allot vaccines. 
The basic registration can be done online and schedules are set as desired by the patient. Assuming a vaccination centre can vaccinate around 100 people in a day. 
The data handling for online basic registration will be mostly done in the day time and the data acquired by the local centres of vaccinated people can be handled in the night.

The local server must store the data of around 100 people where the allocated online registration data will be loaded onto the local server of that local centre. 
Verification of the data is done based on the details provided by the patient. Once completed, the data of the vaccinated will be sent back for future use and reference.
### Advantages
* Comfortable data handling.
* Pre data readily available for verification.
### Disadvantages
* Cannot add large number of new registrations due to local server limitations.
* Encryption is not enabled to protect the data.
* OTP verification is not activated for new registrations.
# SWOT Analysis
## Strengths
* Creating a database to vaccinate people based on aadhar.
* Local vaccination centre enable easier operation.
## Weaknesses
* OTP verification is not available.
* Aadhar Linked phone number database not available.
## Opportunities
* Tracking the vaccination deployments.
## Threats
* Encryption of the data is not present.
## 4 W's and 1 H
### Who
* Patient who needs to be vaccinated.
### What
* Verify the details of the patient using the alloted data.
### When
* During the time alloted for vaccination.
### Where
* Local vaccination centre.
### How
* Online registration and on field verification using local server.
## High Level Requirements
* System should be able to access pre loaded registration data for verification 
* User should be able to add new registrations 
* System should recognize vaccinated patients 
* OTP generated verification for secure registration  
* System should recognize invalid credentials 
* System should be updated with the time interval between two doses 

## Low Level Requirement
* Only new user must be given an option to select vaccine type 
* Total quantity of vaccines used must be shown by EOD 
* Full list of patients vaccinated must be set as output 
* Remaining and present stock of vaccines must be tracked 
* Vaccine vials must be tracked for its use within a day 
# Architecture
## Flow chart
![Flowchart1 (1)](https://github.com/MukeshkumarK/M1-App-VaccinationRegistration/blob/ef9dd5a28d19d1f2db96a102d4dc50edc8112ca8/2_Architecture/Flowchart.png)
## UML Use case
![Untitled Workspace (5)](https://github.com/MukeshkumarK/M1-App-VaccinationRegistration/blob/0a48f58692939a072afb7c875d7b99bfc7ec3026/2_Architecture/UML%20m1.png)

