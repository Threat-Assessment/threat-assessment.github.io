# Assessing argument maps for conservation threat assessments 

## Table of contents

* [Overview](#overview)
* [Project Updates](#project-updates)
* [Implementation](#implementation)
* [Team](#team)

## Overview

Our team aims to develop a desktop application for the School of Life Sciences (SoLS) at the University of Hawaiʻi at Mānoa. Twenty SoLS graduate students evaluated threat assessments for endangered species in the [IUCN Red List](https://www.iucnredlist.org/), translating the reasoning into argument maps. This application will read and interpret texts from Excel spreadsheets and assess the quality of the students' argument maps.

## Introduction 
Dr. Mark Burgman provided example Excel sheets created by graduate students
that contain threat assessments. The critical components of each assessment are
the threat, reasons, evidence, and strength of evidence fields.

(insert image)

Ensuring the assessment templates follow a consistent format is more important
than simply completing the assessments. Consistent formatting allows the GUI to
parse the contents accurately or flag problematic files.

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

We continued developing and testing the application. We mainly focused on formatting the output into a clear, easily readable summary and fixing various bugs. 

### Week of 03/24
<!--03/26/25-->

We met with Dr. Burgman through Zoom to demonstrate the application's progress and gather feedback on what needed to be changed or removed. He requested that we send him the application so he could test it himself and provide more informed feedback. 

### Week of 03/31 
<!--03/31/25-->

Dr. Burgman encountered difficulties setting up the application, so we met in person to assist with installation and dependency setup. However, when attempting to run the application, an error prevented it from launching. Since we developed and tested the app on Windows and Dr. Burgman was using macOS, we were unaware of the issue, as Windows compiled and ran the program without error.

### Week of 04/07
<!--04/10/25-->

We identified the cause of the crash and removed the features responsible for the issue, which were no longer necessary. After these changes, the application ran smoothly. We demonstrated the updated version to Dr. Burgman and provided the revised files so he could run it on his machine and give us real-time feedback.

### Week of 04/14 and 04/21 

Using the Python library NLTK, we updated the app to flag key terms or phrases that appeared only once in the reasons column of the Excel files, a feature requested by Dr. Burgman. While the program successfully identified these terms and phrases, it flagged every instance that occurred once, rather than isolating only the most important ones.

### Week of 04/28

We continued working on refining the app so that it only flags truly important words and phrases. However, achieving this perfectly proved challenging, as the app doesn't learn what the keywords are. Instead, it simply analyzes each reason and looks for repeated words or phrases across other reasons. 

We met with Dr. Burgman one final time to present the completed application and gather feedback on its analysis. Although we weren’t able to fully perfect the keyword detection, Dr. Burgman was satisfied with the overall summary output.

### Week of 05/05 

We made several last-minute improvements to the output layout, adding clearer and more descriptive labels. For instance, we changed "Argument 1" to "Reason 1" to better align with the Excel format. We also enhanced terminology, updating vague labels like "Missing Terms" to more specific phrases such as "Missing terms from threat," and replacing unclear messages with clearer alternatives like "Terms/phrases only used once."

On May 8th, we showcased our application at the ICS Project Day. Many attendees expressed interest in the project and appreciated the concept and its potential applications.


## Team

IUCN Spreadsheet Analyzer is designed, implemented, and maintained by Karissa Tabadero and Chester Leoso. 
