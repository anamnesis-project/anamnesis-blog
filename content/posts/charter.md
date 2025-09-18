---
title: "Project Charter"
date: 2025-09-18
# weight: 1
# aliases: ["/first"]
tags: ["ideas", "test"]
# author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Full project description and specification"
# canonicalURL: "https://canonical.url/to/page"
disableHLJS: true
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "images/week-4-banner.png"
    alt: "week 4 cover" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: false
---

# Functional Requirements
## Hardware
- FR1 - The system must measure the patient’s body temperature.
- FR2 - The system must measure the patient’s heart rate.
- FR3 - The system must measure the patient’s oxygen saturation.
- FR4 - The system must measure the patient’s blood pressure.
- FR5 - The system must have audio output.
- FR6 - The system must have audio input.
- FR7 - The system must control if the doors should open or close.
- FR8 - The system must have a screen.
- FR9 - The system must have WiFi connection.
- FR10 - The system must indicate visually when the patient should speak.
- FR11 - The system must be plugged into the outlet.

## Mechanical
- FR12 - The system must have space to contain an oximeter and cardiac frequency sensor.
- FR13 - The system must have space to contain blood pressure equipment.
- FR14 - The system must have space to contain a temperature sensor.
- FR15 - The system must have space to contain a microphone. 
- FR16 - The system must have space to contain a sound box. 
- FR17 - The system must have at least 2 spaces to contain a speaker.
- FR18 - The system must have space to contain a camera.
- FR19 - The space that contains the blood pressure equipment should have a little door.
- FR20 - The space that contains the oximeter and cardiac frequency sensor should have a little door.
- FR21 - Both doors must lock when closed.
- FR22 - The system must have a space for a screen.
- FR23 - The drawer opening will be controlled by a servo motor.
FR24 - The door opening will be controlled by a servo motor.

## Software
- FR25 - The system must contain a website where healthcare professionals can access patients' information.
- FR26 - The website must have a login page.
- FR27 - The website must allow users to authenticate to get access.
- FR28 - The website must allow users to search for patient’s medical screenings.
- FR29 - The website must allow users to see all collected data in a patient’s medical screening.
- FR30 - The website must allow users to see a patient’s medical screening history.
- FR31 - The website must allow users to export a patient’s medical record as a PDF.
- FR32 - The website must manage sessions and keep users logged in.
- FR33 - The website must have admin users who can manage less privileged users.
- FR34  - The website must allow new authorized users to register.
 
## General 
- FR35 - The system must identify patients via name and CPF.
- FR36 - The system must communicate via audio with the patient.
- FR37 - The system must be voice-controlled.
- FR38 - The system must show the questions in text form on the screen.
- FR39 - The system must start the medical screening after a specific voice command.
- FR40 - The communication between the system and the patient should be in English.
- FR41 - The system must ask pre-defined questions at the beginning of the medical screening.
- FR42 - The system must elaborate questions intelligently based on the patient’s complaints.
- FR43 - The system must give the patient instructions about how to get vital signs monitored.
- FR44 - The system must show heart rate being measured in real time.
- FR45 - The system must show oxygen levels being measured in real time.
- FR46 - The system must show temperature being measured in real time.
- FR47 - The system must end the medical screening by timeout or user’s command.
- FR48 - The system must keep a history of a patient’s medical screenings.
- FR49 - The system must detect the presence of a patient via camera.
- FR50 - The system must perform person recognition via camera.
  
# Non Functional Requirements
- NFR1 - All hinges and locks must be made from non-brittle materials to avoid cracking under stress.
- NFR2 - All compartments must be accessible for maintenance without requiring specialized tools.
- NFR3 - The total system dimensions must not exceed 60 × 80 × 20 cm (to ensure portability).
- NFR4 - The total weight of the system must not exceed 12 kg.
- NFR5 – Access to sensors must allow easy patient placement without excessive effort.
- NFR6 – The system must include handles or grips to facilitate safe carrying
- NFR7 –Doors and panels must have stops or soft-close mechanisms to prevent sudden slamming.
- NFR8 – Internal components must be clearly identifiable to facilitate replacement or maintenance.
- NFR9 – The system must handle authentication using JWTs (JSON Web Tokens.)
- NFR10 – The web application must be in English.
- NFR11 – The web application must be written in PHP using the Laravel framework.
- NFR12 – The server backend must be written in Python 3.
- NFR13 – The Raspberry Pi application must be written in Python 3.
- NFR13 – The temperature must be measured in Celsius.

- NFR14 - The system must measure temperature using an infrared sensor (MLX90614). 
- NFR15 - The system must measure blood pressure using a HEM-7142 monitor.
- NFR16 - The system must measure heart rate and blood oxygen level using a MAX30100 sensor.
- NFR17 - The speaker must output at least 5 Watts.
- NFR18 - The microphone must capture audio from a minimum distance of 40 cm.
- NFR19 - The user shall remain at a minimum distance of 10–20 cm from the temperature sensor when measuring the temperature.
- NFR20 - The system must use PostgreSQL as the database.
- NFR21 - The website pages must have at least 4.5:1 contrast ratio for normal text.
- NFR22 - The website pages must have at least 3:1 contrast ratio for large text.
- NFR23 - The website must have its text with minimum 16px.

# Budget

| Item | Quantity | Price per unit | Total |
|---|---|---|---|
| Microphone | 1 | 25 | 25 |
| Speaker | 1 | 20 | 20 |
| Temperature sensor | 1 | 70 | 70 |
| Blood pressure monitor | 1 | 150 | 150 |
| Oximeter/heart rate monitor | 1 | 30 | 30 |
| Raspberry Pi 4 | 1 | 300 | 300 |
| MDF | 4 | 12,50 | 50 |
| Servomotors | 2 | 20 | 40 |
| Raspberry pi power source | 1 | 30 | 30 |
| Screen | 1 | 80 | 80 |
| Total | | | 795 |


# Schedule
[Time Management Spreadsheet](https://docs.google.com/spreadsheets/d/1vU3akLX5LN2Nhp2A6Dwx2Q3G0gA66hAT/edit?usp=sharing&rtpof=true&sd=true)

# Risk Management Analysis
[Risk Analysis Spreadsheet](https://docs.google.com/spreadsheets/d/1rO8OjuWplk_SSPupGUrg3xvEz_gmYyeS/edit?usp=sharing&ouid=102292798235720013692&rtpof=true&sd=true)
