## Welcome to the ePortfolio for Nathan Adrian

This site will attempt to showcase the various projects that I have worked on and completed in both School and Work, as well as freelance items. Like many others, my career and educational path is unique and encompasses various skills and markets some of which including the following:

### Official Career
- Land Surveyor - _in Michigan, in the winter_
- Field Technician - Hydrology Department _Fancy title for one who works with and in Sanitary Sewers, yes IN_
- Network Technician - _Roles included all things technology_
- Sr. SharePoint Administrator
- Sr. Cloud Applications Administrator

### Freelance
- Tax preparation
- Web Developer/Designer _Drupal, SharePoint, jQuery, JavaScript_

### College Courses/Skills
My Collegiate journey has spanned twenty years and four different Colleges/Universities. Some of what these courses and projects taught me, was how to learn new programming languages, how to design a program to best standards, and how to test and verify the code that is written. I also learned how to be a programmer, software designer, tester, analyst, and many other roles. One of the more difficult classes, [CIS 451 - Computer Architecture](https://www.gvsu.edu/catalog/course/cis-451.htm) at Grand Valley State University taught me the inner workings of the CPU and machine language. The course [CIS 343 – Structure of Programming Languages](https://www.gvsu.edu/catalog/course/cis-343.htm) also at GVSU was the most memorable as it showed me that learning new programming languages was a skill that was already learned in previous courses and just needed to be applied differently.

Transferring to SNHU, especially so late in my journey, was daunting at first, progress was made steady and enlightening. The course CS 340: Advanced Programming Concepts at SNHU gave me a glimpse into the day-to-day life of many roles in a Software Development team and many of the skills learned for agile and scrum I still use daily in my career. Similarly, the course CS 310 : Collaboration and Team Project at SNHU has also taught me many skills that I continue to use. Some of these skills are the use of Git and BitBucket including peer review and pull requests as well as how to collaborate better with teammates.

#### Some of the various skills learned
- Java: jUnit testing which can be seen [here](https://bitbucket.org/nathanadrian05/calculator2/src). Other projects include a functional Chess game and a Solitaire game which is described below.
- C++: Various algorithms related to Algorithms and Data Structure can be seen [here](https://github.com/nateadrian5/class_work/tree/master/c%2B%2B) as well as various Visual Graphics using OpenGL.
- Ruby: A few programs can be seen [here](https://github.com/nateadrian5/class_work/tree/master/ruby) including the original version of the solitaire game that is described below. 
- C: Various labs were done investigating the inner workings of the Operating System
- Python: Various modules were completed in a Math class looking at the statistics of a Solar Plant can be seen [here](https://github.com/nateadrian5/class_work/tree/master/python).

One of the courses in specific, **CS 499**, focuses on this ePortfolio and specific projects and skills. In working through this course one of the tasks was to perform a code review on a project we have worked on in the past as well as enhancing it. 

## Project Overview
The original project was a solitaire game that was written in Ruby for a 300 level CS course. It is a version of one-handed solitaire. The game play is automated but allows stepping through it interactively. It is a simple command line interface with no GUI.

## Code Review
The code review was completed and can be seen in the following video: [link](https://drive.google.com/file/d/1B-wucU2X-tE4GrbXRjbZBfcfN7-erDXr/view?usp=sharing)
The original Ruby code can be seen in git: [Car Solitaire - Ruby](https://github.com/nateadrian5/class_work/blob/master/ruby/solitare.rb)
The full Java code can be seen in git: [Car Solitaire - Java](https://github.com/nateadrian5/class_work/tree/master/java/CarSolitaire)

## Project Details
The solitaire game introduced above and shown in the code review video will be enhanced and adjusted while focusing on three areas: **Software Design and Engineering**, **Algorithms and Data Structure**, and **Databases**.

### Software Design and Engineering
The original design will be utilized; however, it was re-engineered by translated to Java instead of Ruby.

Both languages support **Object Orientated Design**. The original code was created via objects, and this will continue in the Java Version as well to keep it modular and flexible. Extending this to provide a GUI, is feasible as well by keeping the Object Orientated Design. 

Further enhancements have been achieved by building in test cases based on what was learned in CS 320, with **Software Testing, Automation, and Quality Assurance. Unit testing** has been added and used to ensure better coding. Unit testing has been included to verify the functionality of the various classes and methods. Tests have been written and verified for the methods in the Card, Hand, Deck, and LeaderBoard classes. A test suite has been created to run all the tests. Currently the tests cover 73% of the code. 

**Advanced Programming Concepts, _CS 340_**, was leveraged to assist in the transition of moving to a different programming language. The lessons learned in learning how to research and comprehend the scope and nuance’s in varying languages have been applied to help with the transition. For instance, in moving from an array to a linked list, the details of how Java handles those needs to be understood fully. 

This can be seen in the topCards method of the Hand class. Ensuring that the top 4 cards are returned requires the knowledge that the subList method in Java for Lists is inclusive for the start index, but exclusive for the end index. 

Also, the use of the Iterator in Java allows the scoring and the output of the hand and deck to be safer and not suffer from out of bounds issues. 

### Algorithms and Data Structure
The data structure has been adjusted to not rely solely on Arrays for the deck, hand, and leader board.

The information learned from **CS 260: Data Structures and Algorithms** has been applied as the data structure to hold the deck and hand collections moves from an array to a Linked List which provides better resource management and faster compute time.

Furthermore, iterating over a Linked List allows for safer built-in functionality to ensure that out of bounds errors do not occurs. This also provide quicker interactions and safer handling of growth or shrinkage with Pop and Push like behavior. 

### Databases
The leader board has been moved outside of a simple text file and converted to a MongoDB which is hosted by Atlas. This is currently retrieved and displayed in the standard output still. The current program does retrieve the leader board and will set new high scores. Functionality has been added to clear the leaderboard as well. This is mainly for testing purposes but could also be implemented to reset the scores on a schedule, perhaps daily or weekly. 

Utilizing MongoDb has simplified the ranking and ordering of the data as the built-in power of how MongoDb handles documents is leveraged. New leaders are created as a simple bson document and loaded into a collection, which is stored in the Database. Ultimately this is how a MongoDb is organized. 

<!---
```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/nateadrian5/nateadrian5.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
*/
-->
