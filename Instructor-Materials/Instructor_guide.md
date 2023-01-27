***Environmental Informatics using Research Infrastructures and their Data***

------------------------------------------------------------------------

# Instructor Guide

*Katharyn Duffy*

*Ben Ruddell*

*Rohan Boone*

**Northern Arizona University, School of Informatics, Computing, and Cyber Systems**

------------------------------------------------------------------------

LI = Lead Instructor

PI = Programming Instructor

TA = Teaching Assistant

See the suggested syllabus and digital textbook fro references to lecture, unit, and assignment content.

Course meetings are designed based on a 3 credit-hour, semester-long course (i.e. 15 weeks with 2, 1.5 hour meetings per week). The organization of the course may be altered to reflect varying schedules.

It is recommended that student questions be directed to a course chat-room (e.g. Gitter, Slack) or mailing list to reduce instructor workload by allowing students to answer each other's questions, particularly if there is no PI or TA.

### Day 1, Chapter 0-1

-   LI covers introduction to Ecoinformatics and the purpose of the course ([Pre-Course Setup: Ecoinformatics Tools](https://nau-ecoinfo.github.io/INF550-textbook/pre-course-setup-ecoinformatics-tools.html#pre-course-skills-setup)), syllabus (if applicable), and course expectations ([0.6 How we will be Conducting this Course](https://nau-ecoinfo.github.io/INF550-textbook/pre-course-setup-ecoinformatics-tools.html#how-we-will-be-conducting-this-course)) (\~15 minutes).

-   LI directs students to post questions about course content to a course chat-room or mailing list (if applicable, \~ 3 minutes).

-   PI or LI covers resources to catch up if some of the required skill are rusty or missing and git assignment ([0.7.1: A git introduction](https://nau-ecoinfo.github.io/INF550-textbook/pre-course-setup-ecoinformatics-tools.html#exercises)) (\~ 10 minutes).

-   LI covers [Chapter 1: Why 'Ecoinformatics'?](https://nau-ecoinfo.github.io/INF550-textbook/why-ecoinformatics.html) (\~ 30 minutes).

-   Overview of course framework ([1.1 The Framework of this Course](https://nau-ecoinfo.github.io/INF550-textbook/why-ecoinformatics.html#the-framework-of-this-course)) and final project ([1.2 Final Course Project: Proposed Derived Data Product](https://nau-ecoinfo.github.io/INF550-textbook/why-ecoinformatics.html#final-course-project-proposed-derived-data-product)) (\~ 15-20 minutes).

-   One or two example assignemnts that exemplify what is expected (if applicable, \~ 5 minutes).

### Day 2, Chapter 2

-   PI or LI leads a check-in on last lecture's git assignment ([Exercise 0.1: A Git Introduction](https://nau-ecoinfo.github.io/INF550-textbook/pre-course-setup-ecoinformatics-tools.html#exercises), \~ 3-5 minutes).

-   Sections [2.2](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#the-neon-project-mission-design)-[2.5](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#how-neon-collects-data); LI (and guest speaker, if available) introduces NEON , its mission, its design (\~ 10-20 minutes).

-   **Guest Lecture**: [Donal O'Leary - Introduction to the National Ecological Observatory Network (NEON)](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#introduction-to-the-national-ecological-observatory-netowrk-neon)

    -   Donal O'Leary, Research Scientist, Education and Outreach, NEON - Battelle, outlines NEON's Ten Big Ideas, talks about program funding and the Battelle takeover, and explains NEON data availability, site selection, and constraints.

-   LI or PI briefly goes over NEON API tokens ([2.7 Hands on: Accessing NEON Data & User Tokens](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#hands-on-accessing-neon-data-user-tokens))

    -   Students will need a Token for the hands on coding exercise in the next class. Instruct them to obtain one by following the directions in section 2.7.1-2.7.4 of the textbook. Students do not need to complete [2.7.3 Use the NEON token in neonUtilities](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#things-youll-need-to-complete-this-tutorial).

    -   Assign the firt part of [2.10.1 NEON Coding Lab - TOS Vegetation Structure](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#exercise-2.1-neon-coding-lab---tos-vegetation-structure), in which students obtain a NEON API token.

-   If time permits: go over the first assignment as a class.

### Day 3, Chapter 2

- PI introduces 'best practices' for taking live coding notes and git ignore (\~ 10 minutes).
  - The recorded lecture below and many that follow include a coding demonstration ([2.8 Hands On: NEON TOS Data](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#hands-on-neon-tos-data)).
  Students should be advised to code along with Donal in the recorded lecture. Remind students to download `R` packages necessary for the exercise (see first few code chunks in 2.8)
  
- **Guest Lecture**: [Donal O'Leary - Interfacing with NEON and its Data](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#interfacing-with-neon-and-its-data)
  - Donal O???Leary, Research Scientist, Education and Outreach, NEON - Battelle, demonstrates best practices for accessing NEON data using NEON???s online platform and RStudio.
  - The video is \~ 1 hour, but may be paused to give students time to code along.

- PI or LI walks through [NEON Coding Lab - TOS Vegetation Structure](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#neon-coding-lab---tos-vegetation-structure) with the class (remaining time).
  - This exercise consists of two parts: first students submit an .Rmd and .pdf of a scupt that proves that they have a NEON API token, then they will complete a coding lab using NEON TOS data.
  
### Day 4, Chapter 2

- LI checks in with students, cirlces up on expectations (\~ 5 minutes).

- PI or LI reviews [NEON Coding Lab - TOS Vegetation Structure](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#neon-coding-lab---tos-vegetation-structure).

- PI or LI: [2.11 What is an API](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#what-is-an-api)

- Discussion Topics:

  - Why are APIs important?
  
  - What was life like before APIs?
  
  - When should you use an API versus pulling the data locally? Why would each strategy be important?
  
  - What is a JSON and why would NEON use it to wrap data from their API?
  
  - The commonality of API pulls despite the data retrieved
  
- PI lectures through stacking NEON data

- Remaining time: go over [NEON Written Questions](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#neon-written-questions) and [NEON Coding Lab - Further Exploration of NEON Data](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#neon-coding-lab---further-exploration-of-neon-data)

### Day 5, Chapter 2

- PI: History of 'levels' of observations in NEON 

  - What made the cut, what didn't, and why?
  
- Class discussion:

  - What NEON data products interest you? Why?
  
  - What data do you think is 'missing' from NEON? What other data could you bring in?
  
  - If time permits, ask each student to give their #1 product and #1 missing product. 
    
    - Ask students to consider combining those two into a new derived data product.
  
- LI: [NEON Culmination Activity](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-neon-its-data.html#intro-to-neon-culmination-activity) goals and expectations

### Day 6, Chapter 3

- LI: Introduction to USA-NPN and the power of citizen science (\~ 5 minutes).

  - Even if some not interested in phenology, we are covering this network and this type of data because it has unique challenges and opportunities. This type of citizen science data extends to other disciplines.
  
- **Guest Lecture**: [Theresa Crimmins - Introduction to the USA National Phenology Network](https://nau-ecoinfo.github.io/INF550-textbook/introduction-to-usa-npn-its-data.html#introduction-to-the-usa-national-phenology-network)

  - Theresa Crimmins, USA-NPN director, introduces the USA National Phenology Network, describes the platform???s citizen science approach to gathering data, and explains how to access USA-NPN data (1 hour, 6 minutes).
  
- LI or PI: Q&A about USA-NPN (remaining time)


