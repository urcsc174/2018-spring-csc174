# Assignment 2: Team Portfolio Website
*Due: Monday, February 12, 2018* (The due date for this assignment was moved out due to the confusion caused by our experiment with GitHub Classroom.  Sorry about that!)

The goal of this assignment is to work as a web development team (IA, Designer, Coder) and cobble together three student portfolio websites into one, cohesive *four page* website.  (It'll be three pages, each representing a student, plus an index/home page.)

# Requirements

Each team role will have a separate rubric by which each student will get a separate grade.

### Information Architect

NOTE: this is the primary focus of this assignment.  The IA will get the greatest scrutiny when being graded


- Re-architect the content following the principles of Information Architecture

  - Decide the ontology (what's in the domain? what's not?)
  - Create a structure using the taxonomy (what is the document outline that uses consistent terms that describe the aspects of the ontology?)
  - Choose an appropriate choreography for the content (what is the navigation and/or order the information is presented?)
- The IA creates the three pages - each representing a student.  (This is where the hard work of an IA goes!)
- The IA also creates an "home" page to act as an index to the other three pages.

  - The homepage should (actually, must) be structured differently from the rest of the website; it must also follow the principles of Information Architecture to a lesser extent ...you just have to really think about what goes where, for reasons of good IA.
  - The homepage must feature a JavaScript plugin - slideshow, gallery are obvious choices, but you can do something else.  NOTE: the IA can decide what goes there, but it will be the coder to implement it.  (The IA and the coder should probably work closely together on this!)

#### Colophon - readme.md

A "colophon" is an old fashioned term for an extra page that describes how the publication was created.  

- The IA will also create a `readme.md` file in the repository (not part of the actual website) that describes who did what in this assignment.  
- You can also use the colophon to describe any interesting aspects of the website, e.g. a JavaScript plugin or CSS library that you're particularly proud of.

### Design Artist

Until we cover the design principles and other design-related topics in CSC 174, the Design Artist simply needs to make an attempt to make the website look interesting, and follow general best practices, applying a level of effort to demonstrate basic webpage design skills.  

The design artist also needs to work with the Information Architect to implement the IA's vision for the website.  (E.g. if the IA specifies a particular layout to use, the Designer needs to figure out how to implement it in CSS.)

### Coder

Until we cover new technical development skills in CSC 174, the Coder simply needs to make sure the website is technically perfect which includes: 

- The HTML and CSS must pass validation
- The website must use **PHP Includes** to factor-out common elements, e.g. the navigation element
  - Don't forget: the navigation element must indicate which is the current page
- The files and file system must be clean and follow industry best practices
- Working with the IA, the JS plugin on the homepage needs to work well and be optimized. (Basically, just make sure it's installed properly.)  
## Workflow

They way your team develops the website is up to you, but the professional process follows progressive steps.  You consider building the site this way:

### Information Architect

1. The IA sets up the repository and adds the team as collaborators
2. The IA creates the webpage "stubs" - just basic HTML webpages with rudimentary navigation.  Don't bother with styles at all at this point.  
3. The IA fills in the webpage with HTML structure tags - whatever makes sense for the IA.  I.e., build the document outline and makes it consistent across the three student pages.  (Use of lorem ipsum and FPO images is common at this stage.)
4. The IA also sets up the structure of the home page and comes up with a JavaScript plugin to be used there.  
5. The IA fills in the content while the Designer starts the CSS and the coder impalements the JavaScript.

### Designer

6. The Designer sets up the layout on the student pages and homepage per the suggestions of the IA
7. The Designer fleshes-out the design in CSS; this may include styling the JavaScript plugin picked out by the IA and installed by the Coder.

### Coder

8. In addition to implementing the JavaScript plugin on the homepage, the coder is accountable for all technical aspects including image preparation, and arrangement of the files in the file system.
9. The coder must insure that all the webpages and styles meet W3C standards within reason.
10. When ready, the coder copies the website from the team's repository and FTPs it to the correct location on the class web server.

## Installation

- The website must be installed on the class web server in the folder named: **assignment02** (…which already exists); then create a folder with a name based on the team city that you're in.


## Submit the Assignment

To get credit for your work, **one person on your team** (usually your IA) will submit a link to your website in Blackboard, in the assignment: **Assignment 2: Team Portfolio Website**
