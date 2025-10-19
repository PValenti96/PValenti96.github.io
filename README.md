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

My name is Paolo Valenti. I have an Associate of Science from Tunxis Community College, and with the completion of my program at SNHU, I will have a Bachelor's in Computer Science. It has been a long road, as I have been attending school full time and then part time since the fall of 2019. To see this all the way to the end and organize my thoughts in this portfolio, I aim to accurately reflect on what I have learned and accomplished. This ePortfolio will ideally illustrate the end result of all my learning, while acting as a starting point for the beginning of my professional career in CS.

## Professional Self Assessment

My time spent in the Computer Science program at SNHU and creating my first ePortfolio has been vital in helping me shape my personal development and my future focus in what I want to pursue in my professional career. I have come a long way from following the weekly modules that helped me create small-scale projects, to improving and designing unique improvements to this project in particular that reflected my interest for my future career: mobile development. These projects varied greatly and taught me many lessons. For example, CS-300 DSA Analysis and Design taught me about how data structures can transform your work and sort mounds of data into something applicable for any task, like when I used vector data structures to sort through an animal shelter’s pet list. CS-330 Comp Graphics & Visualization taught me the value of carefully crafted visuals when I recreated a static scene from the objects on my own desk. Another valuable lesson came from CS-370 Emerging Trends in CS, where I learned about deep Q-learning and neural networks which helped me teach a machine learning model to navigate a maze. The great lesson here was that any problem can have multiple approaches to a solution. While I had used a "greedy" DQN, there were other options available to me in this case.

The work I did demonstrated useful software design changes, practical application and manipulation of data structures, and database development to help with scalability and security. Many times throughout my courses I relied upon the discussions I had with my classmates, whether it be through graded discussions, general question threads, or correspondence with my classmates when one of us was struggling. All of this contributed to growing my skills through collaboration and developing interpersonal relationships. By addressing my work to different audiences—hypothetical scenarios, professors, and other students—I learned how to ensure technical and non-technical audiences could grasp my development of these projects and their objectives.

From a more technical standpoint, the CS program challenged me in a variety of ways. In certain cases I had to grow my expertise with specific tools introduced within each class, or learn about those same tools through my own research. Data structures and algorithms knowledge from those past classes helped me greatly. They directly influenced my desire to implement data structures of my own creation and learn the data handling required to make that happen.

In regard to software engineering, my own previous experience in creating the weight tracker app I originally made motivated me to make my own personal spin on it, with newly unique functions assigned to buttons that I came up with. This acted as a springboard to learn about the Android framework and external libraries that I wouldn’t have known about prior to my enhancement ideas. For database concepts, I was inspired to stretch my knowledge about SQL to make my own server database that the app could operate from—a practical development for safety and scalability for users of the app. Allowing for in-depth admin operations like monitoring user logins, permission edits, and account deletions is a great step up compared to a static list of users being stored locally on the device.

The artifacts referenced, and the weight tracker app on which I based all the enhancements, demonstrate the wide range of skills I have developed over the past couple of years at SNHU. Software development, data structures, and database enhancements were not random afterthoughts in this case; they were meticulously researched, developed, and tested. My goal with this portfolio is to show that I can continue to develop and demonstrate my skills at a high level that will make a difference in my future CS employment


## Code Review

This portfolio represents the culmination of my coursework, learning, and skill development for CS at SNHU. The culmination of all this were the improvements I made to a previous project that I worked on in CS: 360 Mobile Architecture & Engineering. The original scope of the project was a simple weight tracking app. The app was written in Java and ran through an Android Emulator. The app allowed users to log in with accounts after setting a username and password. Once logged in, they could track their weight from day to day and compare this information using the list that would populate. Besides tracking weight per day, they could compare their weight to a goal weight that was entered in the settings menu. Furthermore, the user would be able to add, edit, and delete dates with their corresponding weights as needed. Lastly, the settings menu had the options for setting a goal weight, setting up a phone number for the account, and enabling SMS notifications.  

<h2>Code Review Video (YouTube)</h2>  
[![Watch the video](https://img.youtube.com/vi/eMN6PEHvzRw/hqdefault.jpg)](https://youtu.be/eMN6PEHvzRw)  


The original zip code can be found here:

[![Download Full Zipped Code](https://img.shields.io/badge/Download-Full%20Zipped%20Code-blue?style=for-the-badge)](https://github.com/PValenti96/CS-499-Computer-Science-Capstone/blob/main/Weight%20Tracker%20Original.zip)

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
The third and final enhancement built upon the existing local SQLite database by implementing actual SQL Server database connectivity. By doing so, instead of the app just relying on user accounts being stored locally on the device, there was now a server that could be used to track them. The app would automatically connect to the server whenever launched, and an admin could then log in to SQL Server Management Studio to monitor. This SQL Server connectivity made the app highly scalable and more secure, as there was now greater control over who could and could not use the app.  

## Course Outcomes

Just as the enhancements covered different areas of expertise, they also covered different course outcomes I set out to accomplish for this project. These course outcomes were:  

- 1. Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science.  
- 2. Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.  
- 3. Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices.  
- 4. Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.  
- 5. Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources.  

## Enhancement One

**CSV Export Functionality**
The CSV export functionality made the data from the app transferable, marking a significant increase in the overall usefulness of the app. The enhancement combs through the Weight_Data object, extracting dates, current weights, and distances from goal weights. It then writes this data into a shareable .csv file. By setting a properly labeled header row, the file can be easily read in other programs like Excel or Google Sheets. From a planning perspective, this enhancement focuses on user-centered design, as it considers that users may need this data for other applications or uses. Additionally, it demonstrates a strong understanding of the data storage systems in Android devices. By leveraging native tools like the Storage Access Framework, users gain greater control over how these exported files are stored and shared. The longevity of the app is increased as healthcare providers, researchers, and other important parties can analyze the data independently without requiring the app or a user account. This improvment helped me meet course outcopme four, where I, "Demonstrated an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions...".

<img width="552" height="1221" alt="image" src="https://github.com/user-attachments/assets/6408673c-d2dc-443a-92a6-f79bccf1f13e" />

<img width="538" height="1185" alt="image" src="https://github.com/user-attachments/assets/333a5a2d-49f0-43c2-b730-d678b9e61205" />



Click here to see the zipped code and the full accompanying narrative

[![Download Full Zipped Code](https://img.shields.io/badge/Download-Full%20Zipped%20Code-blue?style=for-the-badge)](https://github.com/PValenti96/CS-499-Computer-Science-Capstone/blob/main/WeightApp%20-%20Enhancement%201.zip)

[![View Full Narrative PDF](https://img.shields.io/badge/View-Full%20Narrative%20PDF-red?style=for-the-badge)](https://github.com/PValenti96/CS-499-Computer-Science-Capstone/blob/main/Enhancement%20One.pdf)


## Enhancement Two

**Line and Bar Chart Visualization**
The second enhancement focused on transforming the display of a standard weight list into bar and line charts. This enhancement fits naturally into a mobile app context, allowing users to quickly analyze data and trends rather than scrolling through a long list of dates. Each chart reads the weight list for the logged-in user and plots it by weight (y-axis) and date (x-axis). This was made possible using the MPAndroidChart library, an excellent tool for implementing visualizations in Android development. In both charts, the goal weight is clearly highlighted, making it easy to see whether progress is moving toward or away from the target. This improvement demonstrates practical applications of arrays, charting, and data mapping—core concepts in data structures. Much like the CSV export, this enhancement prioritizes user experience by presenting information in a clear, actionable way that improves the app’s professional quality. The line and bar chart addition helped me meet course outcomes two and three, "Design, develop, and deliver professional-quality oral, written, and visual communications..." and "Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices...".

<img width="554" height="1202" alt="image" src="https://github.com/user-attachments/assets/2cc58efc-d9b1-4a63-8a00-2c02d65ed259" />

<img width="549" height="1194" alt="image" src="https://github.com/user-attachments/assets/cb4ff14a-8d90-4f10-8b53-d54532db980f" />

<img width="554" height="302" alt="image" src="https://github.com/user-attachments/assets/c3bfac3e-0447-4902-9168-88aee88260d8" />


Click here to see the zipped code and the full accompanying narrative

[![Download Full Zipped Code](https://img.shields.io/badge/Download-Full%20Zipped%20Code-blue?style=for-the-badge)](https://github.com/PValenti96/CS-499-Computer-Science-Capstone/blob/main/WeightApp%20-%20Enhance%20v2.zip)

[![View Full Narrative PDF](https://img.shields.io/badge/View-Full%20Narrative%20PDF-red?style=for-the-badge)](https://github.com/PValenti96/CS-499-Computer-Science-Capstone/blob/main/Enhancement%20Two.pdf)

## Enheancement Three

**SQL Server Database Connectivity**
The third and final enhancement upgraded the local SQLite user account system to a full SQL Server database instance running on my PC. This was facilitated by the creation of the ConnectionClass, which utilized the jTDS JDBC driver to directly authenticate and store accounts on the server. With the app successfully connecting to the server on launch, administrators can now verify logins, manage users, synchronize data between the app and the database, and run queries through SQL Server Management Studio. Beyond simple client-server architecture, this enhancement added important capabilities: administrators can add, edit, and remove accounts, strengthening security by restricting access to legitimate users and protecting against potential vulnerabilities. This enhancement showcased my database engineering knowledge, while also making the app far more scalable and secure compared to the original local-only implementation. The SQL Server Database connecivity helped me meet course outcomes one and five, "Employ strategies for building collaborative environments..." and "Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities..."

<img width="599" height="474" alt="image" src="https://github.com/user-attachments/assets/8080c5c2-1f34-4526-b324-3b6d749953f3" />

<img width="695" height="349" alt="image" src="https://github.com/user-attachments/assets/5cc44205-944f-4540-8111-9b9be9c1105d" />


Click here to see the zipped code and the full accompanying narrative

[![Download Full Zipped Code](https://img.shields.io/badge/Download-Full%20Zipped%20Code-blue?style=for-the-badge)](https://github.com/PValenti96/CS-499-Computer-Science-Capstone/blob/main/WeightApp%20-%20Enhance%20v3.zip)

[![View Full Narrative PDF](https://img.shields.io/badge/View-Full%20Narrative%20PDF-red?style=for-the-badge)](https://github.com/PValenti96/CS-499-Computer-Science-Capstone/blob/main/Enhancement%20Three.pdf)








