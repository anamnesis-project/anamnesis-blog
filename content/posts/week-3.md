---
title: "Week 3 - Improving of proposals A and B"
date: 2025-09-04
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
description: ""
# canonicalURL: "https://canonical.url/to/page"
# disableHLJS: true
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
    image: "images/week-3-banner.png"
    alt: "week 3 cover" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: false
---
# Week 3 - Final proposal of projects A and B

On the previous week's class, the professors decided to veto our third idea - the Smart Store System.
From that point on, the team worked towards expanding the 2 remaining ideas, the anamnesis and the asset tracking systems.

Furthermore, we evaluated the viability of some implementation details on both projects,
and started to come up with functional requirements for the projects.

Here are main changes to the proposals made this week:

## Proposal A: ANAmnesis

### Main changes to the proposal
- We decided to go with voice recognition for all user interaction
- After evaluating our options, the team opted to use an LLM for generating the questions and parsing the user response

### Main functional requirements
- The system must measure body temperature.
- The system must measure oxygen saturation (SpO₂).
- The system must measure blood pressure
- The system must measure heart rate.
- The system must be totem-like
- The system must identify users via authentication (e.g. CPF).
- The system must allow users to input data through voice recognition.
- The system must communicate with the patient via audio. 
- The system must have an initial input to start a session (e.g. say its name)
- The system must be able to end a session by timeout or user’s input.
- The system must ask the patient basic medical information (e.g age, gender, occupation). 
- The system must ask the patient about possible symptoms.
- The system must ask investigative questions based on the symptoms and other given information. 
- The system must record all patients' data.
- The system must allow privileged users (e.g. doctors) to access patients information.
- The totem must have an autonomous compartment to store the blood pressure monitor.
- The totem must have an autonomous compartment to store the oxygen saturation sensor.

### Diagram of the system
!["ANAmnesis System Diagram"](/images/anamnesis-diagram.png)

## Proposal B: Asset Tracking System

### Main changes to the proposal
- We decided to give up on the idea of implementing a mesh network,
as the added complexity would not impact in any extra functional requirements or benefits.
- We evaluated the possibility of building our own BLE Tags, but that would turn out to be too expensive for our budget.
So we decided that buying them pre-made was the best option.
- We also opted for using the MQTT protocol for messaging between the server and the BLE Scanner Stations.

### Main functional requirements
- The system must have at least 4 BLE scanner stations;
    - The system must have BLE tags;
    - The scanner stations must report all detected BLE tags periodically;
    - The system must detect if an asset is not within the covered area;
    - The system must have a locker;
    - The locker's door must be opened using a stepper motor;
- The locker must have an RFID scanner;
    - The user must be able to automatically open the locker upon scanning their RFID badge;
    - The system must know when an asset is withdrawn from the locker;
    - The system must know if the user has withdrawn only the requested assets from the locker;
    - The system must not allow a user with no approved asset withdrawal request to open the locker;
- The system must have a web interface;
    - The web interface must show in which room each device is located;
    - The user must be able to generate an asset withdrawal request from the web interface;
    - The web interface must show whether an asset is currently taken or available for withdrawal;
    - The web interface must show all assets a user is currently using;
- The system must have custom user permissions;
- The permissions must define what assets the user is allowed to withdraw;

### Diagram of the system
!["Asset Tracking Diagram"](/images/asset-tracking-diagram.jpeg)
