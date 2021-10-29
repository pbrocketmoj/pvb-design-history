---
title: Manual checks and visitor registry
description: Intervening in the system and avoiding duplicates
date: 2021-07-23
---

In this sprint, we tackled two related but separate issues: 

1. how to create a database with a single profile for each unique visitor
2. what happens when a booking cannot be instantly confirmed by the system

These problems correspond to two of our of riskiest assumptions for Alpha:

1. Can we create a visitor profile or account to allow us to identify a visitor through verified credentials?
2. If we build a standardised booking system, the majority of prisons will be able to adopt it operationally and use efficiently

## What we did

We reviewed the user needs and business requirements for:

- a visitor registry 
- manual checks of booking requests

We used FigJam to summarise these needs and write a problem statement for both issues. We then asked the team to add questions, ideas and potential solutions.

### Visitor registry

From the team’s input, we were able to map out the data we assume is required for each step in the visitor registration process. These assumptions will be checked through user research.

We created draft screens showing how staff might input visitor details to be used as a prompt in testing. We also explored solutions to dealing with duplicates and mocked up a simple flow, borrowing elements from a records matching process used by courts.

Once we have a more thorough understanding of what data is required, we will design and prototype the full journey so it can be tested and iterated.

### Manual checks

We started by listing the reasons why an online booking might be manually checked or rejected. We also listed current issues that we assume the new system will prevent from occurring (such as a prisoner not being available for a time slot). This provided a set of scenarios and likely use cases for our design exploration.

We reviewed screenshots of the old system to better understand how staff previously dealt with online requests, but further research needs to be done to understand the business requirements of a new system. 

### Assisted digital

We created a prototype for call centre staff assisting someone to book over the phone.

Based on the principle that staff should only have access to personal data required for their role, this journey does not use the full DPS prisoner profile. Instead, we designed a prisoner profile with information relevant to prison visits.

In testing, we wanted to explore:

- The steps a call agent takes during a booking call
- What they need to know about the prisoner 
- What they need to know about the visitors
- How they communicate available time slots

## Testing

We tested the assisted digital journey with two call agents and two call centre managers. The research sessions were held in-person at the family services call centre in Birmingham.

Participants gave positive feedback on the use of one system to complete a booking. The current process requires the use of NOMIS, establishment guides and a temporary changes document.

For search results by name, staff mentioned that they’d want ‘sound alike’ results for near matches as there can be errors when the name is entered. On the search results page, staff said they need to see information to identify the prisoner based on the information that they’d ask friends and family to provide over the phone such as the prisoner’s date of birth.

On the prisoner profile, staff said they wanted the number of visiting orders to also show the date these were added. They said this would increase their trust in the system’s accuracy. They gave examples where contextual information had helped them to see the number of visiting orders had not been updated.
