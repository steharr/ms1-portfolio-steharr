# **Stephen Harrold Personal Portfolio / CV Website**

As part of my Code Institute course studies, I have created this personal portfolio / CV website for my first milestone project. The website showcases my skills and experience to a potential recruiter with the aim of convincing them that I would be a valuable addition to their company. The website is built using HTML, CSS and Bootstrap. 
The primary goal of the site is to set me apart from other candidates applying for similar jobs. Presenting my skills, experience and projects in a website distinguishes me from other applicants and helps to relieve the repetition of the hiring process for a recruiter.  
 
## **UX**

<!-- # STRATEGY -->

<!-- ### **Overall Project Goals**
Design a personal portfolio site for myself to help convince tech recruiters that I would be a suitable for the job that I am applying for. The recruitment process  -->

### **User Stories**

**Site Owner**

As someone who is undergoing a career change, with this site I want...
* To get offers for jobs in software development
* Display my strongest traits to the site visitor: Creativity, Problem Solver, Enthusiastic Learner
* Demonstrate my technical skills through the design of the site
* Have a location to store & demonstrate all of my completed and ongoing projects
* Convey my passion for programming

**Site Viewer Goals**
<!-- personality -->
As a recruiter,

In order to asses the profile/personality/character of the developer I want to...
* Get a comprehensive overview of the experience and skillset of this developer
* Read a good 'about me' blurb in the site
* Determine that this developer is a good fit for the job I am recruiting for

<!-- technical -->
In order to assess the technical skills of the developer I want...
* The project porfolio is to be easily accessible
* The project porfolio is to be easily understandable
* The experience of navigating through the site is to be enjoyable and smooth
* The layout of the site to be intuitive
* The site to perform well on any device

<!-- action -->
In order to offer an interview to the developer I want...
* Easy access to contact details of this person 
* Have the option to download a traditional CV
* Always within a click's reach of getting in contact

<!-- # SCOPE -->

### **Design Choices**

<!-- Smooth scrolling -->
The site is designed to be a one page scrolling site. This is to make the site navigation as smooth as possible for the recruiter. The objective is that the site flows in one direction (ie. from top to bottom) with the final destination being a contact page. This replicates how a recruiter normally reads through a CV (i.e. top to bottom) which will give them a feeling of familarity. 

<!-- Minimal Navigation -->
In order to minimize the amount of manual navigation the site has been designed with the objective that the viewer should not need to press any button in order to view any data. Navigation is primarily done by scrolling. The only time the user should need to press any element on the website is for either of the following situations:
* They want to go back and reevaluate a previously seen page (possible through the main overhead nav bar)
* They want to skip content to go to a page of particular interest (e.g. on the 'about' page there is an option to jump to projects).

<!-- Familiar Elements -->
The page structure of the site will contain the key elements of a resume/cv: a personal pitch/summary, education, work history, skills, projects. The page structure of the site is as follows:

1. Landing Page
2. About
3. Skills
4. Project
5. Contact

The initial landing page is to include a short summary of my profile in order to give the viewer an overview of my personailty and interests. After this, the first 'About' page of the site will focus on the non technical aspects of my profile so that the viewer is not initally overwhelmed by detailed content. As the recruiter moves further through the site, the more technical information will be presented in the form of a skills page and a projects page.

<!-- # SKELETON -->

### **Wireframes**

### **Features**

<!-- 
In this section, you should go over the different parts of your project, and describe each in a sentence or so. -->

#### Base Site

There are * key features present throughout the site:

* ##### Overhead Horizontal Navbar

* ##### Navbar Responsiveness

* ##### Navbar Transition

* ##### Smooth Scrolling
   The site is contained in one single long html file that is split up into 5 sections. The viewer scrolls progressively downwards through the site.

#### Landing Page

I designed the landing page to quickly summarise the my profile and entice the viewer to move deeper into the site. Key features of this section include:

* ##### Blurb with Profile Image
   The landing page has an opening summary blurb of the site owner with circular profile image in order to get the viewer quickly familarised with the site owner appearance. This creates an image in the recruiters mind of the applicant.

* ##### Site Large Navigation Section
   The landing page has a set of large circular site navigation buttons in order to allow the viewer the option to jump to a particular section of interest once they have read the summary blurb. These buttons link to the "About" section, "Skills" section, "Projects" section and the "Contact" section. 

* ##### Site Large Navigation Buttons Responsiveness
   The buttons also respond to mobile screens. All buttons disapear except for the "Contact" section button. This design decision was made due to the size of the mobile screen being too small for these buttons. As well as this the nav bar which contains the same options is more present on a mobile device. The only button left on mobile (i.e. the "Contact" button) is prioritised on mobile devices as it is arguably the most important button for advanicing the site owners goals   

* ##### Site Large Navigation Buttons Transitons (not finished)

#### About Me Section

Since I am undergoing a change in career, I decided to design the "About" section in a timeline format in order to give historical context to a recuriter about how I have come to the decision to pursue a coding career. In doing this I am also highlighting all of the elements of my profile which will be transferrable to a coding career. The section condenses three traditional parts of a regular CV (education, work history & key projects) into one compact page.

* ##### About Me Section Timeline
   The timeline of the section starts with my college education, then moves to my work experience and finally to a description of the studies I am doing now with Code Institute

* ##### About Me Section Latest Project Bubble
   Next to the timeline is a "Latest Project" bubble which will give a brief overview of what I am currently working on. It also gives an option to allow the user to skip to the projects section of the site

#### Skills Section

* ##### Coding Languages Progress Bars

* ##### Technologies/ Misc 

* ##### Skills Section Responsiveness

#### Projects Section

* ##### Cards View

#### Contact Section

* ##### Contact Me Section form


### Existing Features
<!-- - Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future: -->

### Features Left to Implement
<!-- - Another feature idea -->
<!-- blog, excel vba courses -->

## Technologies Used

<!-- In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation. -->


## Testing

<!-- In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here. -->

## Deployment

<!-- This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally. -->


## Credits

### Content
<!-- - The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z) -->

### Media
<!-- - The photos used in this site were obtained from ... -->

### Acknowledgements

<!-- - I received inspiration for this project from X -->
