# PValenti96.github.io
Paolo Valenti  
CS-499 Capstone Overview for SNHU

1. [Introduction](#introduction)  
2. [Professional Self Assessment](#professional-self-assessment)  
3. [Code Review](#code-review)  
4. [Brief Overview of Enhancements](#brief-overview-of-enhancements)  
5. [Course Outcomes](#course-outcomes)  
6. [Enhancement One](#enhancement-one)  
7. [Enhancement Two](#enhancement-two)  
8. [Enhancement Three](#enhancement-three)  

## Introduction

My name is Paolo Valenti. I have an Associate of Science from Tunxis Community College, and with the completion of my program at SNHU, I will have a Bachelor's in Computer Science. It has been a long road, as I have been attending school full time and then part time since about the fall of 2019. To see this all the way to the end and organize my thoughts in this portfolio, I aim to accurately reflect on what I have learned and accomplished. This ePortfolio will ideally illustrate the end result of all my learning, while acting as a starting point for the beginning of my professional career in CS.  

## Code Review

This portfolio represents the culmination of my coursework, learning, and skill development for CS at SNHU. The culmination of all this were the improvements I made to a previous project that I worked on in CS: 360 Mobile Architecture & Engineering. The original scope of the project was a simple weight tracking app. The app was written in Java and ran through an Android Emulator. The app allowed users to log in with accounts after setting a username and password. Once logged in, they could track their weight from day to day and compare this information using the list that would populate. Besides tracking weight per day, they could compare their weight to a goal weight that was entered in the settings menu. Furthermore, the user would be able to add, edit, and delete dates with their corresponding weights as needed. Lastly, the settings menu had the options for setting a goal weight, setting up a phone number for the account, and enabling SMS notifications.  

<h2>Code Review Video (YouTube)</h2>  
[![Watch the video](https://img.youtube.com/vi/eMN6PEHvzRw/hqdefault.jpg)](https://youtu.be/eMN6PEHvzRw)  

In my code review, I discussed these details at length, among other aspects of the original project. I would say the most important aspect of the project at the time of the code review was simply the fact that it didn’t work. Something had gone wrong when I ported the project from another computer to my current system, and I ran into issues trying to get it working in Android Studio. While my code review did not provide a great demo of the app’s features, I was able to supplement it by using the static XML screens to explain how it should be working. I spent a great amount of time discussing the login screen, the main menu screen, and the settings screen, as most functions of the app operated around those areas. At first, I was a bit worried about how this would affect the enhancements I had planned, but I decided to turn that apprehension into motivation and look at it as part of the skill showcase to improve the project as much as I could.  

## Brief Overview of Enhancements

While I had several artifacts to choose from to perform enhancements on, I decided to only use my weight tracker app. The decision for this was twofold: I enjoyed coding and seeing the results side-by-side with the Android emulator, and I enjoyed working on that project in particular. So much so that I believe my future career lies in mobile development. The enhancements I made to the app stretched across three unique areas of expertise. These categories were:  

- **Software Design & Engineering**  
- **Algorithms & Data Structures**  
- **Databases**  

**E1: CSV Export Functionality (Software Design & Engineering)**  
The first enhancement I went with was adding a button for CSV export functionality. This allowed users to download their current weight history list into a spreadsheet format. Users could then share, analyze, and back up copies of their weight lists as they currently stood. The layout of the exported file was simple, with headers and rows for the date, weight, and distance from goal weight for each entry. This was a meaningful software change, as it took advantage of integrated Android framework technology and increased the usefulness of the app by allowing the data to be used outside the app itself.  

**E2: Line and Bar Chart Visualization (Algorithms & Data Structures)**  
The second enhancement focused on improving the data visualization for the app, making the presentation of data to the user more in line with what would be useful in a mobile app. Through MPAndroidChart imports, I was able to transform the list of weights into both line and bar charts. The charts were set up simply to track dates and weights, with a goal line representing the goal weight present in each visualization to make for simple comparisons. Instead of showing every day of the calendar between dates, only dates with set weights were present on the chart.  

**E3: SQL Server Database Connectivity (Databases)**  
The third and final enhancement built upon the existing local SQLite database by implementing actual SQL Server database connectivity. By doing so, instead of the app just relying on user accounts being stored locally on the device, there was now a server that could be used to track them. The app would automatically connect to the server whenever launched, and an admin could then log in to SQL Server Management Studio to perform queries and track users. This SQL Server connectivity made the app highly scalable and more secure, as there was now greater control over who could and could not use the app.  

## Course Outcomes

Just as the enhancements covered different areas of expertise, they also covered different course outcomes I set out to accomplish for this project. These course outcomes were:  

- Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science.  
- Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.  
- Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices.  
- Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.  
- Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources.  

## Enhancement One

**CSV Export Functionality**
The CSV export functionality made the data from the app transferable, amrking a siginficant increase int he overall useffulness of the app. The enahnbcment combs through the Weight_Data object, extarcting dates, current weights, and distance from goal weights.
It then writes this data into a shareable .csv file. By setting a properly labled header row, the file is easily read in other porgeams like Excel or Google. From a plannong perspective, this enhancemnet focuses on user centered design, as it keeps in mind that users may need this data for other apps/uses.
Additionally, it shows a deep understanding of the data storage system belonging to Android devices. By taking advantage of tools native to Android like its Storage Access Framework users get greater control over what they do with these xported files. The lomgeivty of the app is inmcreased as other users, healthcaren providers, and important parties can anlayze thed ata from this app themsleves without needing the app or suer account.

<img width="552" height="1221" alt="image" src="https://github.com/user-attachments/assets/6408673c-d2dc-443a-92a6-f79bccf1f13e" />

<img width="538" height="1185" alt="image" src="https://github.com/user-attachments/assets/333a5a2d-49f0-43c2-b730-d678b9e61205" />



Click here to see the zipped code and the full accompanying narrative

[![Download Full Zipped Code](https://img.shields.io/badge/Download-Full%20Zipped%20Code-blue?style=for-the-badge)](https://github.com/PValenti96/CS-499-Computer-Science-Capstone/blob/main/WeightApp%20-%20Enhancement%201.zip)

[![View Full Narrative PDF](https://img.shields.io/badge/View-Full%20Narrative%20PDF-red?style=for-the-badge)](https://github.com/PValenti96/CS-499-Computer-Science-Capstone/blob/main/Enhancement%20One.pdf)


## Enhancement Two

**Line and Bar Chart Visualization**
The second enhancement focused on transforming the display of a regualr weight list into a bar and line chart. This enhancement makes sense in the context of a mobile app, as users can analyze data and tresnds quickjly then scrolling throuhg a long list of dates.
Each chart reads the weight list for the logged in user and plots them to match a weight (y-axis) and date (x-axis) easily. This was faciliated through the use of the MPAndroidChart library, and excellent set of tools for setting up display strcutures in android coding environments. 
In both, the goal weight is outlined boldy so it's easy to mark whetehr weight gain or loss is needed. This improvement shows the pracital use in a mobile setting for the use of arrays, charts, and mapping data points. 
The simialiryt between this improvmement and the last one shows that user experience is first and foremost, in the same way that data could be shared via CSV exports it can be efficientily communicated inn a visual manner as well.

<img width="554" height="1202" alt="image" src="https://github.com/user-attachments/assets/2cc58efc-d9b1-4a63-8a00-2c02d65ed259" />

<img width="549" height="1194" alt="image" src="https://github.com/user-attachments/assets/cb4ff14a-8d90-4f10-8b53-d54532db980f" />

<img width="554" height="302" alt="image" src="https://github.com/user-attachments/assets/c3bfac3e-0447-4902-9168-88aee88260d8" />


Click here to see the zipped code and the full accompanying narrative

[![Download Full Zipped Code](https://img.shields.io/badge/Download-Full%20Zipped%20Code-blue?style=for-the-badge)](https://github.com/PValenti96/CS-499-Computer-Science-Capstone/blob/main/WeightApp%20-%20Enhance%20v2.zip)

[![View Full Narrative PDF](https://img.shields.io/badge/View-Full%20Narrative%20PDF-red?style=for-the-badge)](https://github.com/PValenti96/CS-499-Computer-Science-Capstone/blob/main/Enhancement%20Two.pdf)





