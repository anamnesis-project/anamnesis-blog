---
title: "Week 3"
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

## Proposal A: Anamnesis System

## Proposal B: Asset Tracking System
- We decided to give up on the idea of implementing a mesh network,
as the added complexity would not impact in any extra functional requirements or benefits.
- We evaluated the possibility of building our own BLE Tags, but that would turn out to be too expensive for our budget.
So we decided that buying them pre-made was the best option.
- We also opted for using the MQTT protocol for messaging between the server and the BLE Scanner Stations.

### Diagram of the system
!["test"](/images/asset-tracking-diagram.jpeg)
