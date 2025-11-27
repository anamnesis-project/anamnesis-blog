---
title: "Deliverable 4"
date: 2025-10-16
# weight: 1
# aliases: ["/first"]
tags: ["deliverable", "hardware", "software", "electronics"]
# author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Electronic project and partial Software implementation"
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
    image: "images/deliverable-1-banner.png"
    alt: "deliverable 3 cover" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: false
---

This week, the team's effort was channeled towards finishing the electronical implementation, aswell as begining the software implementation.

# Electronics

## Board
!["Board"](/images/board.jpeg)

## Improved Schematics
!["Modified schematics"](/images/design/improved-schematics.png)

# Software

## Backend
In terms of software, we have finished implementing the backend,
which is composed of 2 different services: the **Storate Service**,
that handles patients, reports and employees, and the **Audio and Text Service**,
which exposes endpoints for **Speech To Text (STT)** and **Text To Speech (TTS)** .

## Raspberry Pi
We also began integrating the code handled by the Raspberry Pi into a cohesive program.

This is the example output of a test done using the Gemini LLM for generating questions.

------

**[Ana]:** Hello, I'm here to help. Could you please tell me what symptoms you are experiencing today?\
**[Patient]:** I have trouble breathing, my nose feels clogged up since yesterday

------

**[Ana]:** Thank you for sharing that. Are you experiencing any chest pain or tightness?\
**[Patient]:** no chest pain or anything like that

------

**[Ana]:** Thank you for clarifying. Is your difficulty breathing mainly due to your blocked nose?\
**[Patient]:** yes

------

**[Ana]:** Thank you. Are you also experiencing any fever, cough, or sore throat?\
**[Patient]:** not really, but i've been also getting headaches from time to time

------

**[Ana]:** Thank you for letting me know. When did these headaches start?\
**[Patient]:** yesterday aswell

------

**[Ana]:** Thank you for letting me know. Are these headaches constant, or do they come and go?\
**[Patient]:** they come and go

------

**[Ana]:** Thank you. Can you describe where you feel these headaches?\
**[Patient]:** more towards the front of the head, close to the synuses

------

**[Ana]:** Thank you for sharing that. Do you feel any pressure in your face or around your eyes?\
**[Patient]:** yes

------

**[Ana]:** Thank you for letting me know. Are you experiencing any nasal discharge, and if so, what color is it?\
**[Patient]:** yes, and it is dry and the usual yellow

------

**[Ana]:** Thank you for sharing that. Do you feel any tenderness or pain when you press gently on your forehead or cheekbones?\
**[Patient]:** yes, thats exactly it

------

**[Ana]:** Thank you for letting me know. Are you experiencing any changes in your sense of smell or taste?\
**[Patient]:** apart from not really being able to breath, no.

------
