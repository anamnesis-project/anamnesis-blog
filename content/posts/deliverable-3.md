---
title: "Deliverable 3"
date: 2025-10-09
# weight: 1
# aliases: ["/first"]
tags: ["deliverable", "mechanics", "design", "hardware", "software", "electronics"]
# author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Mechanical and Electronic project and Software design"
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
    image: "images/deliverable-1-banner.png"
    alt: "deliverable 3 cover" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: false
---

For this deliverable, the team focused mainly on implementing the complete mechanical solution,
allowing the drawer and door to be opened automatically through the servomotors.

Apart from that, we started to work towards implementing the electronic and hardware project,
which involves collecting data from the sensors, implementing peripheral functionality, etc.

Last but not least, we finished the complete Software design,
including the User Interface and system architecture.

# Mechanics and Electronics
## Servomotors

### Servomotor functioning from the front
{{< rawhtml >}} 
<video width=80% controls>
    <source src="/videos/servos-preview-front.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
{{< /rawhtml >}}

### Servomotor functioning from the back
{{< rawhtml >}} 
<video width=80% controls>
    <source src="/videos/servos-preview-back.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
{{< /rawhtml >}}

# Software design
## Diagrams

### Totem Activity Diagram
!["Totem Activity Diagram"](/images/design/totem-activity.png)

### Totem Use Case Diagram
!["Totem Use Case Diagram"](/images/design/totem-use-case.png)

### New Deployment Diagram
The main changes here refer to the totem's implementation.

Instead of fisically connecting the Screen to the Raspberry Pi,
the new solution involves opening a webpage from a browser in the tablet.
The webpage will be served by the Raspberry Pi and will provide a long living connection between both devices.

Furthermore, due to computational constraints, we will use a STM Blackpill board to handle the firmware section of the totem.
The Blackpill will then communicate with the Raspberry Pi through commands over UART. 
!["New Deployment Diagram"](/images/design/deployment-new.png)

## UI design

### Color Palette
!["Color Palette"](/images/design/ui/color-palette.jpeg)

### Home Page
!["Home Page"](/images/design/ui/home-page.jpeg)

### Register Page
!["Register Page"](/images/design/ui/register-page.jpeg)

### Reports Page
!["Reports Page"](/images/design/ui/reports-page.jpeg)

### Patient Page
!["Patient Page"](/images/design/ui/patient-page.jpeg)

### Report Page
!["Report Page"](/images/design/ui/report-page.jpeg)

### Employee Authorization Page
!["Employee Authorization Page"](/images/design/ui/employee-authorization-page.jpeg)
