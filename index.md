# Assessing argument maps for conservation threat assessments 

## Table of contents

* [Overview](#overview)
* [Project Updates](#project-updates)
* [Team](#team)

## Overview

Our team aims to develop a desktop application for the School of Life Sciences (SoLS) at the University of Hawaiʻi at Mānoa. Twenty SoLS graduate students evaluated threat assessments for endangered species in the [IUCN Red List](https://www.iucnredlist.org/), translating the reasoning into argument maps. This application will read and interpret texts from Excel spreadsheets and assess the quality of the students' argument maps.

## Project Updates

This section provides ongoing updates about the project.

### Week of 01/20/25
<!---1/22/25-->

We met as a team to introduce ourselves and discuss the project. We shared our schedules, initialized the project repository, and designated the point of contact.


### Week of 01/27/25
<!--01/28/25-->

We met with our project sponsor, Mark Burgman. Dr. Burgman went over the details of the project and explained his expectations for the application. He also introduced the concept of argument maps, dsicussed the purpose of the project, and shared example argument map spreadsheets that we may use when testing the app.

### Week of 02/10/25
<!--02/10/25-->

We met again to further discuss and develop the application. After assessing the needs for our project, we decided Python would be the best programming language for the project. We also planned another meeting with Dr. Burgman to address some remaining questions about the project.

### Weeks of 02/17 and 02/24/25

We continued developing the application and met occasionally, but most of the work was done separately as one of our team members was sick during this period.

### Weeks of 03/03 to 03/17

We continued to develop and test the application. We mainly focused on formatting the output into a easily readable summary and fixing various bugs. 

### Week of 03/24
<!--03/26/25-->

We met with Dr. Burgman through Zoom to show the progress of our application and get feedback on what should be changed or removed. Dr. Burgman requested that we send him the application so he can test out the app for himself in order to give the most effective feedback. 

### Week of 03/31 
<!--03/31/25-->

Dr. Burgman had trouble setting up the application, so we met in person to help him set up the application and install the necessary dependencies. However, when trying to run the application, an error occurred and the program wouldn't open. Since we used Windows and Dr. Burgman used macOS, we were unaware of the bug until we ran the program on Dr. Burgman's machine, as Windows ignored this bug and still successfully compiled the program during the testing phase. 

### Week of 04/07
<!--04/10/25-->

We figured out what was causing the program to crash and removed the functionalities that were causing this problem, as it was also no longer needed. After removing the functionalities, the program ran smoothly. We showcased this to Dr. Burgman and gave him the updated files so he could run it on his machine and give us real time feedback. 

### Week of 04/14 and 04/21 

Using the Python library NLTK, we updated the app so that it flags key terms or phrases that are only used once in the Excel files, a feature Dr. Burgman requested after our last meeting. We met with him to show our new implementations. The program was able to flag words or phrases that only appeared once but it flagged every word or phrase that was only shown once, not specific types of words

## Team

IUCN Spreadsheet Analyzer is designed, implemented, and maintained by Karissa Tabadero and Chester Leoso. 
