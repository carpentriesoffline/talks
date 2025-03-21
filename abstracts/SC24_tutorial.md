# SC24 Tutorial Submission
https://sc24.supercomputing.org/program/tutorials/

## Session Collaborators:
Name: Jannetta Steyn, email: Jannetta.Steyn@newcastle.ac.uk, ORCID: 0000-0002-0231-9897, Institution: Newcastle University, Country: United Kingdom, Job title: Senior Research Software Engineer

Name: Colin Sauze, email: colin.sauze@noc.ac.uk , ORCID: 0000-0001-5368-9217, Institution: National Oceanography Centre, Country: United Kingdom, Job title: Senior Research Software Engineer

Name: Abhishek Dasgupta , email: abhishek.dasgupta@dtc.ox.ac.uk , ORCID: 0000-0003-4420-0656, Institution: University of Oxford, Country: United Kingdom, Job title: Senior Research Software Engineer

\newpage{}

## Title
Building a miniHPC for delivering HPC Carpentries and other HPC-related workshops

## 1. Abstract
There are several problems with gaining access to an HPC to run a workshop for students. An alternative is to build a mini HPC out of single board computers (SBC) such as Raspberry Pi computers but this is not an easy task. This tutorial aims to introduce the CarpentriesOffline miniHPC solution which allow instructors without specialised HPC hardware and software knowledge to run HPC Carpentries workshops.

\newpage{}

## 2. Description
### Tutorial Goals
1. Introduction to CarpentriesOffline
2. Setting up an RPi
3. Identifying and installing the required software head node (login node)
4. Installing modules with EESSI
5. Identifying and installing the required software for compute nodes
6. Using the miniHPC to deliver workshops
7. Discussion and Q&A

### Relevance for conference attendees
The purpose of the miniHPC is to train users and administrators of HPCs. The miniHPC can also be used for the design and debugging of workflows. Thus, anyone with an interest in training or the development of pipelines would benefit from this session.

### Target audience
1. HPC Carpentries Instructors
2. HPC Admin workshop instructors
3. Developers of scripts and pipelines
4. Enthusiast that would like to build their a miniHPC of their own

### Content level
Intermediate

### Audience prerequisites
1. Attendees will need a laptop and, if possible, if they own any Raspberry Pi 4 or 5s to bring them along.
2. Basic knowledge of bash scripting
3. Basic knowledge of using HPCs
4. Basic knowledge of Linux and how to install software

### Tutorial content
The tutorial will involve the preparation of RPi computers to create a miniHPC that can be used for training and prototyping. Ideally, the desired time for the tutorial is a full day but it is possible to do a condensed version of the tutorial in half a day.

## Cohesion measures
The presenters of this tutorial are all developers of the CarpentriesOffline project. They will take turns presenting parts while the other presenters act as helpers

\newpage{}

## 3. Detailed outline
1. Identifying the hardware requirements for a miniHPC
   - The Raspberry Pi and other suitable single board computers
   - Using PoE to avoid excessive cabling
   - PXE for diskless compute nodes
   - network cabling
   - Internet access (or not)
3. Preparation of an SD card or SSD for use with an RPi
   - using Imager by Raspberry Pi
	- alternatives to RPi Imager
	  - Etcher
	  - dd
5. Installing software
   - identify packages required
   - using apt-get to install packages
6. Configuring software for the head node
7. Configuring software for compute nodes
8. Installing EESSI
9. Adding an access point (AP) to the cluster
   - using the head node as an AP
   - creating an AP with RaspAP
10. Preparing and delivering a Carpentries "Intro to HPC" workshop.
    
\newpage{}

## 4. Hands-on feasibility check/analysis
It is the first time this tutorial will be presented. We will be submitting this tutorial in similar formats to CarpentryCon Heidelberg and RSECon24 which will occur before SC24. Since the tutorial is aimed at instructors and developers we hope to get feedback from participants concerning further development of the CarpentriesOffline miniHPC project as well as the content of the tutorial for future sessions. 

\newpage{}

## 5. Resume or CV for each presenter

CVs attached to the end of this document.

\newpage{}

## 6. Release statement
We agree to release a digital copy of the notes for the SC24 tutorial.

\newpage{}

## 7. Request for travel support
We would like to request travel support for three presenters from the UK.
