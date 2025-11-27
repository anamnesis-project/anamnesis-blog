---
title: "Projects"
date: 2025-08-28
# weight: 1
# aliases: ["/first"]
tags: ["ideas", "kick-off"]
# author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: true
hidemeta: false
comments: false
description: "3 ideas developed for presentation"
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
    image: "images/project-banner.png"
    alt: "week 2 cover" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: false
---

---

## Automated Anamnesis System
This idea consists in building a totem that collects vitals and medically relevant personal information from the patient,
automating the process of anamnesis.

### Vitals that would be collected
- Blood pressure
- Heart rate
- Oxygenation
- Temperature

The interaction with the user would be done either through speech recognition or text input.
The patient would interface with the machine with a screen, and hospital staff would be able to check patient records via a web interface. 
There will be a motor controlled door to open and close the hole where the patient inserts their arm

### Diagram
!["diagram"](/images/anamnesis-diagram.jpeg)

---

## Asset Tracking System
The asset tracking idea consists in adding BLE tags to valuable items in a company,
and through devices connected to the local network in the premises, be able to approximately locate the items.
The items will be stored in a cabinet that opens with a motor.
Furthermore, collaborators will have an RFID badge that must be scanned to open the doors so that they can retreive the items,
registering such information to a server that can be accessed by management.

### Main technologies involved
- BLE tags
- RFID badges and sensors
- Bluetooth

### Diagram
!["diagram"](/images/asset-tracking-diagram.png)

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

### Diagram
!["diagram"](/images/smart-store-diagram.jpeg)
