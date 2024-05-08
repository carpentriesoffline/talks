# How to build and use a miniHPC for training (50 words max)

## Authors
Name: Jannetta Steyn, email: Jannetta.Steyn@newcastle.ac.uk, ORCID: 0000-0002-0231-9897, Institution: Newcastle University, Country: United Kingdom, Job title: Senior Research Software Engineer

## Abstract (250 words max)
***Enter an abstract of your submission. This should be a brief and attention-grabbing summary of your submission. For accepted submissions, these details will appear in the programme.***

There are several problems with gaining access to an HPC to run a workshop for students. An alternative is to build a mini HPC out of single board computers (SBC) such as Raspberry Pis but this is not an easy task. This workshop aims to introduce the CarpentriesOffline miniHPC solution which allow instructors without specialised HPC hardware and software knowledge to run HPC Carpentries workshops. Delivery of the workshop will be done in the typical Carpentries live coding style. 

## Prerequisites (150 words max)
***Describe the required skills or knowledge for an attendee to engage with your submission. Have you considered how accessible your session will be to a diverse conference audience (attendees comprise people from academia, industry, charity and government, from beginners to experts)? For accepted submissions, these details will appear in the programme.***

1. Attendees will need a laptop and, if possible, if they own any Raspberry Pi 4 or 5s to bring them along.
1. Basic knowledge of bash scripting
2. Online attendees will need a laptop and at least two Raspberry Pis

## Outcomes (150 words max)
***How will your attendees benefit from your session? What are the expected outcomes? For accepted submissions, these details will appear in the programme.***

**At the end of this session attendees will have completed the following: **
1. Writing an RPi OS to an SD card using the Raspberry Pi Imager
2. turning one computer into a head node and another computer into a compute node by installing and configuring the appropriate software
4. creating a network of the two nodes with a hub

## Technical Plan
***Please answer the following questions:***
- ***How will you deliver the Workshop?***
- ***If you are delivering the Workshop in-person, how will you support attendees both in-person and online?***
- ***If you are delivering the Workshop online, how will you support online attendees, and how can the organisers best support you with the in-person aspect?***
- ***Bearing in mind that you will have both in-person and online attendees, how many could you reasonably deliver your Workshop to?***
- ***What software and/or tooling will you be providing access to?***
- ***What will attendees need to install in advance or bring along (e.g. a piece of their own code)?***


1. The organisers will bring some Raspberry Pis, SD cards, networking cables and switches
2. Attendees need to bring a laptop with an ssh client installed, such as PuTTY on Windows or openssh client on Linux. If they don't have the software installed they will need admin rights to the laptop so that the software can be installed during the workshop.
3. Online attendees should be able to follow along if they have at least two RPis of their own and a laptop with which they can ssh into the RPis while following instructors in Zoom. They will need on SD card or USB SSD for one of the RPIs and the RPis and laptop need to be connected via an Ethernet or WiFi network.
4. If possible attendees should try to install the RPi Imager and ssh client beforehand but if they can't we will go through the process in the workshop. The software is downloadable for free from the Internet. The instructors will have copies on site in case it is neccesary.
5. At the moment we have equipment for eight people (to work in four pairs) attending the morning session in person. We might be able to obtain more equipment before the conference that will allow us to accommodate a larger group. We should be able to accommodate up to 8 online attendees.
6. It should be possible to accommodate a larger group of people for the afternoon session - up to 20 in person and up to 20 online.

## Accessibility
***Please comment on how you will ensure your content is accessible, which may include referring to relevant sections of the conference’s accessibility guidance, as well as any other considerations such as considered the contract of colours, and the shape and size of graphics and fonts. You can also use automated accessibility checking tools to help.***



## Delivery Plan for a Hybrid Audience
***How will you ensure that both remote and in-person participants have a comparable experience? Is there anything that might pose a challenge to streaming your proposal? We appreciate that you may not have fully-formed answers to these questions at this stage, but your responses will enable the organisers to support you in delivering a successful presentation.***

- Remote participants who would like to follow along with the hardware setup will need one computer (a laptop or desktop), two Raspberry Pi 4 or 5s and either a switch or a WiFi network. They will also need and SD card for one of the RPis (or an USB SSD)

## In-Person or Online Delivery
***How will your content be delivered?***

- [ ] ***In-Person***
- [ ] ***Online***
- [x] ***Hybrid (Both In-Person and Online Presenters)***


## Research Software Development Principles*
***Please select one or more of the Research Software Development Principles which will feature during your presentation. For clarification, see information about these principles.***

1. FAIR
2. Maintainable
3. Reproducible
4. Inclusive
5. Open & Global
6. Humanist
