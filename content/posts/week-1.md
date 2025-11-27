---
title: "Week 1 - Brainstorming of project ideas"
date: 2025-08-21
# weight: 1
# aliases: ["/first"]
tags: ["ideas", "kick-off"]
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
    image: "images/week-1-banner.png"
    alt: "week 1 cover" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: false
---

The first week of work was entirely focused on coming up with the three ideas that needed to be presented.

After extensive brainstorming, the team settled on the following three ideas:

---

## Automated Anamnesis System
This idea consists in building a totem that collects vitals and medically relevant personal information from the patient,
automatind the process of anamnesis and creating a medical report that can be classified by urgency.

### Vitals that would be collected
- Blood pressure
- Heart rate
- Oxygenation
- Temperature

The interaction with the user would be done either through speech recognition or text input.
The patient would interface with the machine with a screen, and hospital staff would be able to check patient records via a web interface. 

---

## Asset Tracking System
The asset tracking idea consists in adding BLE tags to valuable items in a company,
and through a LoRa mesh network in the premises, be able to approximately locate the items.
Furthermore, a system would be put in place to allow collaborators to retreive these items (given the required permissions),
registering such information to a server that can be accessed by management.

### Main technologies involved
- BLE tags
- Bluetooth sensors
- LoRa mesh network 

---

## Smart Store System
This idea consists in implementing a complete smart store system able to handle stock management and self checkout.
That would be done by adding RFID tags to the products. These tags would then be registered with an RFID recorder.
Customers would then choose the products they wish to buy and scan them on the self checkout station.
The station would be able to handle payment and send all information to a central server that would register the purchase and update stock levels.
Apart from that, the server may also use purchase data to provide a dashboard with data analytics,
showing product performance and customer purchase profiles.

### Main technologies involved
- RFID tags and sensors
- Handling of payments
- Robust backend system
