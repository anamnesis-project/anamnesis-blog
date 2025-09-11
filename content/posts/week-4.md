---
title: "Week 4 - Preliminary Project Charter"
date: 2025-09-11
# weight: 1
# aliases: ["/first"]
tags: ["ideas"]
# author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "ANAmnesis - Requirements, Time Management and budget"
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
- FR1 - The system must have space to contain an oximeter and cardiac frequency sensor.
- FR2 - The system must have space to contain blood pressure equipment.
- FR3 - The system must have space to contain a temperature sensor.
- FR4 - The system must have space to contain a microphone. 
- FR5 - The system must have space to contain a sound box. 
- FR6 - The system must have at least 2 spaces to contain a speaker.
- FR7 - The space that contains the blood pressure equipment should have a little door.
 
- FR8 - The space that contains the oximeter and cardiac frequency sensor should have a little door.
- FR9 - Both doors must have a lock.
- FR10 - The system must have a space for a screen.
 
## Software
- FR1 - The system must contain a website where healthcare professionals can access patients' information.
- FR2 - The system must have a login page.
- FR3 - The website must allow users to authenticate to get access.
- FR4 - The website must allow users to search for patient’s medical screenings.

## General
- FR0 - The system must identify patients via name and CPF.
- FR1 - The system must convert text to audio to communicate with the patient.
- FR2 - The system must convert input audio to text.
- FR3 - The system must start the medical screening after a specific voice command.
- FR4 - The communication between the system and the patient should be in English.
- FR5 - The system must ask pre-defined questions at the beginning of the medical screening.
- FR6 - The system must process the patient’s answers and store them.
- FR7 - The system must elaborate questions intelligently based on the patient’s complaints.
- FR8 - The system must give the patient instructions about how to get vital signs monitored.
- FR9 - The system must end the medical screening by timeout or user’s command.
- FR10 - The system must record the patient’s information in a server.
- FR11 - The server must keep a history of a patient’s medical screenings.

# Non-Functional Requirements
- NFR1 - The website pages must have at least 4.5:1 contrast ratio for normal text.
- NFR2 - The website pages must have at least 3:1 contrast ratio for large text.
- NFR3 - The website must have its text with minimum 16px.
- NFR4 - All hinges and locks must be made from non-brittle materials to avoid cracking under stress.
- NFR5 - All compartments must be accessible for maintenance without requiring specialized tools.
- NFR6 - The total weight of the system must not exceed 5 kg.
- NFR7- The system must use The OMRON HEM-7113 pressure monitor.

# Budget
 
| Item | Quantity | Price per unit | Total |
|---|---|---|---|
| Microphone | 1 | 25 | 25 |
| Speaker | 1 | 45 | 45 |
| Temperature sensor | 1 | 70 | 70 |
| Blood pressure monitor | 1 | 150 | 150 |
| Oximeter/heart rate monitor | 1 | 30 | 30 |
| Raspberry Pi 4 | 1 | 300 | 300 |
| Chapa MDF | 4 | 12,50 | 50 |
| Servomotors | 2 | 20 | 40 |
| MicroSD card | 1 | 40 | 40 |
| Font raspberry pi | 1 | 30 | 30 |
| Screen | 1 | 80 | 80 |


### Total: R$860,00

# Time management
[Schedule Spread Sheet](https://docs.google.com/spreadsheets/d/1vU3akLX5LN2Nhp2A6Dwx2Q3G0gA66hAT/edit?gid=1820079268#gid=1820079268)
