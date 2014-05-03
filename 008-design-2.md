####Team Sentence Sense
###Sentence Sense Website Redesign
####Software Design Document











Pen Han Chang, Tsz Hang Ng, Derick Nguyen, Dylan Shigekawa, Darien Vidaure

05/03/2014

###Table of Contents

##1.      Introduction
    1.1    Purpose
    1.2    Scope
    1.3    Overview
##2.     System Overview
##3.     System Architecture
    3.1     Architectural Design
##4.      Human Interface Design
    4.1    Overview of User Design
    4.2    Screen Objects and Actions
##5.      Requirements Matrix

























### Introduction

We are creating a new website for Sentence Sense.  The new website will draw from the old website’s Part One.  The new website will revise content from the old website and reorganize and compress content from the original site.  

Sentence Sense is an interactive online learning experience.  The website will have interactive learning exercises for the students.  The results of these exercises will be able to be tracked and analyzed by instructors or tutors.  At the end of each chapter, there will be a Review and Practice section that will test the user and link them to the sections corresponding to the incorrect answers.  The results from this test will also be able to be tracked by an instructor or tutor.

Because the website will be used by students ages twelve and up, it is important to design a lean, intuitive and easily navigable website.  Furthermore, this website will be built on a custom content management system which will allow our sponsor to change its content herself quickly and easily.

#### Purpose

This website will satisfy the need for an online resource, not found on any other similar website, that teaches “how a sentence works.” Other websites do well to teach prescriptive grammar (how to fix errors) but there are none that focus on how sentences work (descriptive grammar). This website will hope to be the resource which provides this missing information by providing interactive lessons with games and visualizations.

There will be various types of users who will be able to utilize this website including students in college, high school, home school programs, as well as adults and independent learners. The website will cater to users age 12 and up who are able to read English at an 8th grade level. Due to this wide audience the website will need to not only be appealing to all these different types of users, but also still teach them valuable lessons that are applicable to each individual’s personal life and situations for which they are using this resource in the first place.

Building a CMS for our sponsor will allow her to easily change the website’s content without requiring much technical knowledge. This will remove the need for a dedicated website technician once we are finished with this project.

#### Scope
After we finished building the new webpage, the webpage should provide a new, simple, more interactive between teachers and students, and user-friendly function for users to learn English, viewing grades, and communicate. Simple, client requires the whole web page look simple, this can prevent user to feel confuse when they access the website. More interactive, for example students can play games on the website, teachers can leave comments on the exercises for students and students can communicate with the teachers through the website, so students can have more understanding what are the mistake that they have made and they can ask question to teachers immediately. 


#### Overview
The document will contain a description and requirement overview of the website. The most important part of the document will explain how the system design and architecture work. The sponsor-Evelyn Farbman was professor of english at Capital Community College in Hartford. She was also an author of two books. Addition for teaching, she teaches english as second language and literature. 


### System Overview
Usability:
+ Activity on the site will be individual and self-paced
+ Design should be lean, intuitive, and easily navigable
+ Consolidate and revise the site for unity and consistency
+ Guiding users in their review of each topic
+ The website should be viewable on any type of browser
+ The website should be available 24/7 and if it crashes it should be up again within 24 hours
+ The website should be equally fast on a mobile device as on a computer

Use Case #1 Admin adds content
Admin points the browser to admin.experimentalsentencesyntax.com.
Site asks for password. Admin enters password.
Admin sees an overview of all content.
List of all parts
Under each part, there are chapters.
Under each chapter, there are sections.
Under the whole list, admin can click “New Part”.
Within the “Part”, admin can click “New Chapter”.
Next to each “Chapter”, there are options to “View”, “Edit” and “Delete.
After editing content, admin can publish to website.
 
Use Case #2 User uses the website
User points the browser to experiemntalsentencesyntax.com.
User clicks on Part desired.
User clicks on Chapter desired.
If user wishes to continue from within a chapter, user clicks on section desired.
After completing the chapter, user will be given a test.
User fills in the test and clicks to submit results.
User reviews mistakes and can click on section where the mistake was taught.
User can send the result to another party (teacher, professor, tutor, etc.) via an email.


### System Architecture
The website will:

   +Allow the admin to modify the website’s content
   +Be viewable on screen sizes 4x6 and larger
   +Provide  tracking, diagnostic analysis, evaluation, and recordkeeping of user activity for use by   the sponsor as feedback
   +Allow interaction between users
+ This will probably require users to have their own accounts
+ The results of exercises could be shared electronically with teachers or tutors for help in lesson planning
+ Mastery Test, and results can be reported to teachers for assessment and recordkeeping
+ Activities will be adapted for electronic communication among fellow site-users
+ Culminating activities in each chapter will prompt collaboration with other site users
   +Facilitate the trading of exercise either through a class discussion board or some posting location for users who are not members of a class
   +Site should have a search box for key term
   +Expansion and maintenance:
+ Site design can expand to incorporate later chapters
+ New site can be launched on server that can support and pilot it while the remaining parts are being built


### Human Interface Design

#### Overview of user interface
Our User Interface of the whole system is the website itself. The buttons on the home page can link to the learning materials and background resource of the website, also there is a search bar on the home page. The whole design of the User Interface is focusing on making it clean and simple.

#### Screen objects and actions
Drop down menus
+ Allow for navigation of different sections and parts of the site and book

Buttons
+ Varying actions with each button
+ Click to navigate to certain Part, Chapter or Section
+ Click to navigate to certain part of the website
+ Click to submit form
+ Click to “View”, “Edit” or “Delete”

Text Field
+ Varying actions with each part of the website
+ Allows content to be update
+ Allows input for “tests” 

Search Box
+ Searches website for term in search box

Interactive Games
+ Drag and drop games to enhance learning

Text
+ Material that is being taught

Email Results
+ Input email of party that will receive test results

### Requirements Matrix


System Component that Satisfies Functional Requriement








Custom Content Management System
Allow admin to modify content
Allow admin to add content
Have 7 parts
Viewable on screens 4x6 and larger
JavaScript inside HTML5 Canvas
Interactive modules






Email add on
Provide recordkeeping






Search add on
Search Box for key term






Unresolved
Community interaction (e.g. messageboard, forum)
Collaboration in modules of games





