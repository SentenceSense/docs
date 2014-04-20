     
	What programming language(s) will you use? 
Ruby, JavaScript, CSS
     
	What framework(s), if any, will you use? 
Rails
     
	What other libraries or dependencies will you use? 
None at this moment
     
	Will you use different languages, frameworks, and/or libraries/dependencies for different parts of your application? 
We will use Ruby on Rails to build a custom CMS and then use Javascript to create the interactive game applications
     
	What is your overall architecture (e.g., MVC)? 
MVC (model-view-controller)
     
	What data will you need to store? 
Content from Sentence Sense and possibly user results from exercises.
     
	What is your database design (or other data storage scheme)? 
At this time we don’t know if we’ll require a database
     
	What are the other parts of your software? For example, for an MVC app: What models will you make? What attributes and methods will they have? What controllers will you make? What methods will they have? What views will you make? 

Models: The content from Sentence Sense. It should divide into Parts > Chapters > Sections > Exercises (Exercises may require interactive JavaScript games).


Views: How the content is represented and how the website looks (Using CSS?)
View will display the website’s content. Each page will be displayed when it is clicked on or directed to. There will be the home page and then subsequent pages for every chapter specific to sections and their exercises.

Controllers: The website itself accessed through a browser. Users will be able to navigate through tabs (menu, parts, chapters, sections, and exercises) with the click of a mouse. For exercises, users will be able to provide input for the exercise and receive output (results).
Controller will be able to update and add content to the website.
Use Case for Controller adding content
Directs browser to admin.experimentalsentencesyntax.com
Site asks for password. Controller enters password.
Overview of website’s content is shown.
All parts and subset are listed. (Chapters > Sections > Exercises)
Under the list is a “New Part” button.
Within each part, there is a “New Chapter” button.
Next to each Part and Chapter there will be buttons marked for “View”, “Edit”, and “Delete”.
