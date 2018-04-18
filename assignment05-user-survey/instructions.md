# Assignment 5: User Survey Website

*Due date for the **Information Architect**'s content and intent: **Monday, April 23, 2018***<br>*Due date for the final website: **Monday, April 30, 2018***

This is a **team assignment**, however you will be graded for the work you do as an individual within the team.  

For this assignment you will build a **new website around a topic** of your city-team's choice.

**The goal of the website** is to get website visitors to fill-out a survey that is related to the topic.

There will also be a **login for administrators** so they can access a private section of the website that is off-limits to non-logged-in visitors.  

In the private section, website administrators will be able to perform these **four functions on the database table** that holds the survey data:

- [ ] Ability to **see** all the surveys, in table form
- [ ] Ability to **add** records to the database table
- [ ] Ability to **edit** any of the records in the database table
- [ ] Ability to **delete** any of the records in the database table

*NOTE: there are many ways to accomplish the four functions.  You do not necessarily have to use AJAX, JSON or other advanced techniques we never covered in CSC 174.  You can do it "the old fashioned way" using four separate PHP scripts on four separate webpages ...it doesn't matter, so long as it works.*

## Information Architecture

The following is in effect, the rubric for the IA:

- [ ] Come up with the **ontology** within the chosen domain that gets represented in a **semantically-clean document structure in HTML** (i.e. the IA creates all the HTML documents and initially sets all the HTML structural tags around the words and pictures)
- [ ] Words in the structure need to clearly demonstrate a **taxonomy** used to describe the ontology (i.e. the headings need to be consistent and clear ...and lots of them)
- [ ] The structure, which may (typically) include multiple webpage documents, must indicate an optimal **choreography** by which the website visitor should progress through the website; that includes website navigation as necessary (sometimes, multiple menu systems!)
- [ ] It is the IA's responsibility to **create the team's repository** and make sure it is set to public so the TAs and professor can access it (and the readme.md file)
- [ ] The IA will need to communicate the following by way of a **readme.md** file in the team's shared repository (*not* part of the website!):
  - [ ] **Intended layout** of each page from a high-level (think: wireframes and sketches) so the designer can execute the layout in CSS
  - [ ] **Intended mood/feeling** of the website so the designer can execute the formatting including typeface choices, color choices and other embellishments
  - [ ] **Intended interactivity** (especially in regard to the survey, the login system, and the database functions) to be executed by the coder (keep in mind: you can't ask the coder to do really complex things if they're not capable of such things! - keep it realistic - talk to each other!)

On **Monday, April 23, 2018**, the professor will poll your city-team's Designer and Coder to see if *they* think the IA has done enough work for them to do their work.  

- **If the Designer and Coder are okay with the IA's work so far:** they may proceed, keeping in mind that the IA is still responsible for continuing work with the rest of the team and ensuing that the information architecture (ontology, taxonomy, choreography) remains intact until the website is launched on Monday, April 30.  (I.e. the IA is not done working on April 23)
- **If the Designer and Coder say that the IA has *not* sufficiently fulfilled their role** by Monday, April 23: the work will be reassigned to one of the other team members and the IA will FAIL the assignment.  
  - Remember: if you do multiple roles, you get the benefit of the grade for each 
  - Possible: the IA that dropped the ball can try to convince the designer or coder to swap roles with them; however that might not be possible because they might need to fulfil the requirement of performing each role at least once
  - Remember: if the Designer and Coder fail to report that their IA isn't doing their job on April 23, they cannot use that excuse when the website is due else they too will fail the assignment

## Design

The following is in effect, the rubric for the Design Artist:

- [ ] **Execute the layout(s)**: in CSS: layouts based on the direction from the Information Architect (that includes the layout of all HTML forms, login systems, and administration areas)
- [ ] **Implement all formatting** including font installation, color choices and embellishments based on the direction from the Information Architect (keep in mind that the entire website - including the administration area - must look like it belongs to one, unified website)<br>Specific attention to:
  - [ ] Best practices of **page layout** (use of page layout patterns like Z- or F-patterns, used appropriately)
  - [ ] Best practices of **typography** including well-chose and paired fonts, in terms of **readability** and **legibility**
  - [ ] The **principles of page design** in terms of use of the C.R.A.P. principles


## Coding

The following is in effect the rubric for the Technical Coder:

- [ ] Creation of a **MySQL database** and powering of the HTML forms using **PHP** to write POST data to the database tables; and to retrieve data from the database to display in HTML tables
    - [ ] One HTML form for the **User Survey**
    - [ ] One HTML form for the **User Account Creation** process 
    - [ ] One HTML form for the the **User Login** Process
    - [ ] As many HTML forms and PHP scripts as necessary to enable the **four database functions** (described earlier) in the administration area
- [ ] Ensuring that the entire website meets **web standards** and follows **best practices**

### One weird thing

NOTE one thing about this website that will *not* be real-worldy: IT IS OKAY that anyone can create an account on this website to become an administrator so they can login and get into the private area of the website. Obviously that wouldn't make sense on a real, production website, but for this academic exercise, it's okay.

## Installation

- The website must be installed on the class web server in the folder named: **assignment05** (…which already exists); then create a folder with a name based on the team city that you're in.  
- The database must be created on the class web server using the city-team database created for your team

## Submit the Assignment

You will *each* create your own submission in Blackboard using the *assignment* that relates to the role you did.

- Create a Blackboard submission in: **Assignment 5: User Survey Website (IA *or* Designer *or* Coder)** based on whatever you did.
- In the "Write Submission" area, submit a **link to the website** on the class web server
- Also write-in 
  - The **city-name** of your team
  - The names of **each team member** and the **role** they performed (including your own)
- Also, submit a **link to the repository** the team used.  (Make sure the repository is "public")