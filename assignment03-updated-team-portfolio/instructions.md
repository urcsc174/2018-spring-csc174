# Assignment 3: Updated Team Portfolio Website

*Due: Wednesday, February 28, 2018*

The goal of this assignment is to develop a new Information Architecture and apply the guidelines and best practices of visual page design.

This is a **team assignment**, however you will be graded for the work you do as an individual within the team.  

The primary focus of this assignment will be on:

- **Information Architect**
- **Design Artist**

The **Technical Coder** will only be held to the standards and best practices of CSC 170.

## Requirements

The team is responsible for delivering another four page website: an index page plus three student pages.

- The index must function as an index, meaning that it summarizes the website and leads the website visitor to the other webpages
- The index page must have a JavaScript-powered feature that provides a visual element, like a slideshow, gallery, accordion ...anything like that
- The three student pages must exist as three separate entities and follow the same architecture
- All best practices must be followed - too many to list; it is assumed that all students who took CSC 170 are familiar with them and everything that's been covered to-date in CSC 174

### Information Architect

The IA must gather content from any three CSC 174 students who all have something in common.  

- The IA may decide what commonality the three students share; it can be anything, e.g. students from the mid-west United States, or Bioengineering majors, or Gamers, et cetera
- Use our shared Google Sheet: [Student List of Portfolio Pages](https://docs.google.com/spreadsheets/d/1XZ5Mb0bx8_47E0WvC3AtHd4TVFPnkUQB1IquWz4YFag/edit#gid=0) to find students; read to find out things about them
- The student portfolios selected by the IA do *not* have to be the same students in the IA's city-team

The IA must tweak, change, re-arrange, and/or gather new content as needed to clearly structure the website in a way to present the common theme clearly to the website visitor.  That includes the acquisition and editing of new content and photographic images as necessary.  

The IA will be graded on clear representation of the ontology, taxonomy, and choreography

The IA will be graded on the structure and layout apparent in the website's HTML structure and use of HTML elements

#### IA Giving Direction to the Designer and Coder

The IA will also be graded on their ability to provide clear direction to the Designer and Coder:

- Layout required by the information architecture - what should be positioned where
- Suggestions for typefaces/fonts, and where and how they are to be applied 
- The type of JavaScript effect required by the homepage

#### Documentation in the HTML Comments

In addition to regular team communication (live meetings with doodles on the backs of napkins, messages in Slack, mental telepathy, ...whatever!), the IA needs to communicate their choices to the TAs and Professor so they can see what the IA *intended* as opposed to what the Designer and Coder actually implemented.

**Required:** IA must write HTML comments in each HTML document to explain their choices and direction for the Designer and Coder

* Use liberal amounts of `<!-- comments like this -->` in relative proximity to what's being described
* Things to specify in HTML comments
  * Suggested typefaces/fonts and where and how to apply them
  * Layout - general descriptions what should be where on each page
  * Suggested behaviors - think JavaScript/user interactions; what happens when

#### Colophon - readme.md

The IA will also develop a "colophon" that describes how the website was created.  

- The colophon must be in a `readme.md` file in the repository (not part of the actual website)
- The colophon must indicate the specific things that were done by the members of the team.  
- The colophon should also describe any interesting aspects of the website, e.g. a JavaScript plugin or CSS library that your team is particularly proud of.

## Design Artist

The Design Artist must use what we covered in CSC 174 regarding visual page design.

- Apply the principles of page design (the CRAP principles)
- Use page patterns (Z - and F-patterns)
- Exercise good practices of readability (the list of 10 Principles Of Readability and Web Typography)
- Choose, install and use TWO (no more, no less) custom fonts while applying best practices in typography (considerations of the six typographic groups: GHOTMS)

Note: the number of things the Designer must consider is huge!  There is no single rubric to define every aspect of a website design.  But be aware: the graders will *look for mistakes* - things that were objectively done poorly based on what we've covered in CSC 174.  Your job as designer is to try to consider ALL the principles of visual page design - review every aspect of every element and try and determine if the presentation is the best it can be.

## Coder

Until we cover new technical development skills in CSC 174, the Coder simply needs to make sure the website is technically perfect which includes: 

- The HTML and CSS must pass validation
- The website must use **PHP Includes** to factor-out common elements, e.g. the navigation element
  - Don't forget: the navigation element must indicate which is the current page
- The files and file system must be clean and follow industry best practices
- Working with the IA, the JS plugin on the homepage needs to work well and be optimized. (Basically, make sure it's installed properly.)  

## Installation

- The website must be installed on the class web server in the folder named: **assignment03** (…which already exists); then create a folder with a name based on the team city that you're in.

## Submit the Assignment

You will *each* create your own submission in Blackboard using the *assignment* that relates to the role you did.

- Create a Blackboard submission in: **Assignment 3: Updated Team Portfolio Website (IA *or* Designer *or* Coder)** based on whatever you did.
- In the "Write Submission" area, submit a **link to the website** on the class web server
- Also write-in 
  - The **city-name** of your team
  - The names of **each team member** and the **role** they performed (including your own)
- Also, submit a **link to the repository** the team used.  (Make sure the repository is "public")