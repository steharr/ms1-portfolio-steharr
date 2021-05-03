# **Stephen Harrold Personal Portfolio / CV Website**

As part of my Code Institute course studies, I have created this personal portfolio / CV website for my first milestone project. The site owner is myself and the primary goal for creating the site is to get a job in software development. The target site viewers are recruiters; they will be visting this site when they are looking at my job application. Presenting my skills, experience and projects in the form of a website distinguishes me from others in the mind of the recruiter and hopefully helps to relieve the repetition of the hiring process for them.  

The website is mobile first and built using HTML, CSS and Bootstrap. 

## **UX**
The **five planes of user experience design** developed by Jesse Jame Garrett was used as the conceptual framework for the development process of this site

### **Strategy Plane**
For the strategy plane, there were two perspectives I needed to take into account when planning out the strategy of my site. These perspectives would help me to create a list of user stories to use when designing the site. These perspectives were:
  * Site Owner Perspective (i.e. a full stack developer)

  * Site Viewer Perspective (i.e. a tech recruiter)

For the perspective of a developer I researched various existing developer personal websites in order to give me an overview of what is normally put on a website like this. This helped me understand what a developer commonly displays on a personal portfolio website. In particular [this article](https://www.freecodecamp.org/news/15-web-developer-portfolios-to-inspire-you-137fb1743cae/) on www.freecodecamp.org gave me a wide variety of examples to draw inspiration from. There was also [this site](https://brittanychiang.com/#about) from boston based software engineer Brittany Chiang which I stumbled upon that was particularly inspiring for me.

For the perspective of a recruiter I researched online articles on what a tech recruiter is typically looking for from someone who is applying for a developer role and what challenges they face. A notable mention was [this article](https://geshan.com.np/blog/2019/01/things-tech-recruiters-look-for/) from a software engineers blog website. It gave an in depth insight into the mind of a tech recruiter.

### **User Stories**

#### Site Owner:

As someone who is undergoing a career change, with this site I want...

1. To get offers for jobs in software development
2. Display my strongest traits to the site visitor: Creativity, Problem Solver, Enthusiastic Learner
3. Demonstrate my technical skills through the design of the site
4. Have a location to store & demonstrate all of my completed and ongoing projects
5. Convey my passion for programming

#### Site Viewer:

As a recruiter,
In order to asses the profile/personality/character of the site owner I want to...

1. Get a comprehensive overview of the experience and skillset of this developer
2. See an eye catching landing page that captures my attention

In order to assess the technical skills of the site owner I want...

3. The project porfolio is to be well presented and accessible
4. The project porfolio is to be easily understandable
5. The experience of navigating through the site is to be enjoyable and smooth
6. The layout of the site to be intuitive
7. The site to perform well on any device

In order to offer an interview to the site owner I want...

8. Easy access to contact details of this person 
9. Have the option to download a traditional CV
10. Always easily within a click's reach of getting in contact

### **Scope Plane**
For the Scope plane, I made some initial key design choices about how I wanted to set up the site based on my research. From there I was able to plan out the scope of the site.

#### **Key Design Choices**

The site is designed to be a one page scrolling site. This is to make the site navigation as smooth as possible for the recruiter. The objective is that the site flows in one direction (ie. from top to bottom) with the final destination being a contact page. This replicates how a recruiter normally reads through a CV (i.e. top to bottom) which will give them a feeling of familarity. 

In order to minimize the amount of manual navigation the site has been designed with the objective that the viewer should not need to press any button in order to view any data. Navigation is primarily done by scrolling. The only time the user should need to press any element on the website is for either of the following situations:
* They want to go back and reevaluate a previously seen page (possible through the main overhead nav bar)
* They want to skip content to go to a page of particular interest (e.g. on the 'about' page there is an option to jump to projects).


### **Structure Plane**
For the structure of the site I decided to include the key elements of a resume/cv: a personal pitch/summary, education, work history, skills, projects. I also included a contact form section in order to fulfill site viewer user stories 8 and 9. When deciding the individual layout of each page, I researched typical website layouts online for inspiration. A notable example which helped was [this article from adobe.com](https://xd.adobe.com/ideas/principles/web-design/11-website-layouts-that-made-content-shine-in-2019/)

#### Site Structure:

`1. Header Nav Bar`
The header of the site contains a horizontal navbar which houses links to each section of the site. It also contains a brand name for the site. The brand acts as a home button which links to the landing page of the site. The brand name is SteHarr - a combination of my first and second name and also my GitHub User name. The navbar is fixed at the top of the page as the user scrolls down the site. This is done to satisfy user story 10.

`2. Landing Page`  
This page contains a hero image, a greeting and a brief summary of myself. On desktop devices the page contains large navigation buttons each for a section of the site i.e. **About**, **Skills**, **Projects** and **Contact**.  The buttons are intended to be visually striking and allow the viewer to jump to an area of the page of particular interest. As there is less screen space available on mobile devices, I had to choose what is the most important button to be displayed. As per my initial design decisions, The objective of the page is to get the viewer to reach out to me. Therefore I chose to display a contact me button underneath the personal summary in the mobile version of the page.

`3. About`  
Since I am developer who is changing careers, I thought I needed to visually explain to the viewer the context of how I made this decision to switch. I therefore decided to use a timeline for the **About** section of the page. The timeline contains three nodes. A description of my educational background, a description of my work history and a description of what I am doing now (i.e. studying in code institute). For the end of the timeline I had planned to include a node on a description of my latest project. During development this was changed to a button that linked to the projects page as three nodes on the timeline looked more visually apealling than four.

`4. Skills`  
For the skills section, I planned to include a progress bar section on the experience I have with various coding languages and a descriptive section on other various software expertise I had. The content is structured in an asymmetrical layout. During development, I decided to include a small section on my soft skills below the coding languages as it fit well in the structure of the page.

`5. Projects`  
For the projects page I decided to use a card layout. Each card is a seperate project that I've worked on. The cards are displayed stacked ontop of each other on mobile devices and on desktop screens they appear in rows.

`6. Contact`  
The contact page contains a descriptive text section and simple static contact form. The text section encourages the user to fill out the form if they want to get in touch and gives my email address if the viewer would prefer to write an email. If the viewer wants more details, this section also includes a link to a downloadable version of my CV.

`7. Footer`
The footer is visible on the contact page section of the site. It contains a short blurb and a social section which contains links to my social media. There is also a copyright watermark at the bottom of the footer. 


### **Skeleton Plane**
For the skeleton plane, I created wireframes of each section of the site using the Balsamiq tool. These wireframes acted as blueprints to work from while the site was in development. They do not represent the final appearance of the site as some elements of the site evolved as I was developing the site.

#### Wireframes:
* [Landing Page](assets/documents/wireframes/landing_page.png)
* [About Page](assets/documents/wireframes/landing_page.png)
* [Skills Page](assets/documents/wireframes/landing_page.png)
* [Projects Page](assets/documents/wireframes/landing_page.png)
* [Contact Page](assets/documents/wireframes/landing_page.png)

### **Surface Plane**

#### Color Palette
In order to choose an overall color palette for the page, I used the color scheme generator site [Coolors](https://coolors.co/). I browsed various trending color palettes on the site until eventually I found one with a selection of orange and turquoise colors which stuck out for me. From there I altered this palette further to accomodate the needs of my site. The final color palette is below:

|Color Name|Hex Value|Used In|
| :-------------: |:---------:| :-----:|
|Gunmetal| ![#272F36](https://via.placeholder.com/15/272F36/000000?text=+) `#272F36` | Contact form input boxes and coding language progress bars|
|Gunmetal| ![#2B343B](https://via.placeholder.com/15/2B343B/000000?text=+) `#2B343B` | Footer and Header Navbar|
|Gunmetal| ![#2A3941](https://via.placeholder.com/15/2A3941/000000?text=+) `#2A3941` | Skills box, project cards and contact form|
|Charcoal| ![#293D47](https://via.placeholder.com/15/293D47/000000?text=+) `#293D47` | |
|Charcoal| ![#264653](https://via.placeholder.com/15/264653/000000?text=+) `#264653` | Main background color of page|
|Orange Yellow Crayola| ![#E9C46A](https://via.placeholder.com/15/E9C46A/000000?text=+) `#E9C46A` | All site buttons, percentage bar gradients, <br> about page timeline items, footer social links|
|Sandy Brown| ![#F4A261](https://via.placeholder.com/15/F4A261/000000?text=+) `#F4A261` | Landing page navigation buttons and hero image border, <br> about page timeline dashed line|
|Burnt Sienna| ![#E76F51](https://via.placeholder.com/15/E76F51/000000?text=+) `#E76F51` | Landing page navigation buttons and hero image background,<br> skills page expertise headers, project cards language tags |


For my user stories I had identified that I wanted the experience of the site to be enjoyable and smooth for a recruiter. I was conscious of the fact that they they are likely going through numerous job applications on a daily basis which could be an arduous task. With this in mind, I wanted the base color of the site to be a dark neutral color that was easy on the eyes. The **Charcoal** color was perfect for this objective. 

Having the base color to be darker allowed me to use brighter colors for the elements on the page which would make them stand out. **Burnt Sienna**, **Mandarin**, **Sandy Brown** and **Orange Yellow Crayola** contrasted very well with the **Charcoal** background of the site. 

The **Gunmetal** color was useful for the less dominant elements of the site such as the navbar and the footer.

#### Font Pairings

<!-- How color palette was used -->

<!-- Icons -->
<!-- Projects & Skills page card designs -->




## Features

### Existing Features
<!-- #### Base Site

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

* ##### Contact Me Section form -->


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
The site was developed using the VSCode Editor. During development, I regularly tested the output of my code using the LiveServer extension to see how the page was being rendered in a Chrome browser. Multiple screen sizes were evaluated during this process using Chrome Dev Tools. 
After the bulk of the development was complete, I tested my code by putting it through the [W3C HTML Validator](https://validator.w3.org/), the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) and then checked its performace using Lighthouse in Chrome Dev Tools. The final period of testing was done by validating the site against each of my User stories.

### Large Bugs Occuring During Development & Lessons Learned
During the development phase of the site, I encountered a number of signifcant bugs while testing the output of my code. These are documented below:
#### **Misplaced Nav Bar**

<img src="assets\documents\testing\error_misplaced_navbar.png" alt="drawing" width="250"/> 

* **Description**  
Early on, an issue ocurred where the nav bar of the site was not appearing fixed to the top of the screen for both desktop and mobile devices even though the bootstrap 'fixed-top' class had been used.  
* **Root Cause and Fix**  
To troubleshoot this issue I removed individual HTML elements one at a time from the page and analyzed how the site then appearred. I eventually found the root cause to be an empty line of code above the body element of my page. This was creating a new line that was empty before the navbar in the site. Removing this line in my code corrected the issue.

#### **HTML Body Width Error**

<img src="assets\documents\testing\error_html_body_width.png" alt="drawing" width="300"/> 

* **Description**  
Late on in development, I noticed that the footer of the site was not spanning the width of the viewport on Ipad screens only. This was especially confusing since the element had the **container-fluid** class. Looking into Chrome Dev Tools, I could see that the width of the html element in the page was not covering the entire width of the Ipad screen.
* **Root Cause and Fix**   
To troubleshoot this issue, I did some research online and came across [this post on stack overflow with a similar issue.](https://stackoverflow.com/questions/30358630/html-body-not-filling-complete-width-on-mobile-devices) I then determined that the issue was being caused by text overflow somewhere on the page. This theory was backed up by the fact that the issue was only occuring on the Ipad, which was showing text overflow on the **About** and **Projects** pages of the site. To fix this issue I refactored the code for both of these pages.

### HTML Validator Results
After passing my code through the HTML validator for the first time, I recieved 7 error messages and a one repeated warning.
#### Error Messages
* Empty ID on Landing Page

   <img src="assets\documents\testing\html_validator_empty_id.png" alt="empty id tag error" width="500"/>

   This was missed during development. Corrected by removing the empty id attribute. 
* Paragraph element entered as direct child of unordered list element

   <img src="assets\documents\testing\html_validator_paragraph_ul.png" alt="paragraph child of unordered list error" width="500"/>

   For the list of software expertise items on the skills page, I had accidentally put paragraph elements as children of the unordered list. The list already had **li** elements containing the headings for these paragraphs, therefore I could easily move the paragraph elements into them to amend this error.

* Stray i Tag

   <img src="assets\documents\testing\html_validator_stray_i.png" alt="stray i tag error" width="500"/>

   This stray tag was likely added when adding font awesome icons. Corrected by removing the tag. 

* Semicolon Typo on Contact Page

   <img src="assets\documents\testing\html_validator_semicolon_typo.png" alt="semicolon typo error" width="500"/>

   Corrected by removing the semicolon before the equals sign

* Character Reference in Footer Not Terminated by Semicolon

   <img src="assets\documents\testing\html_validator_character_reference.png" alt="character reference error" width="500"/>

   When adding a copyright symbol to the footer of my page, I had forgotten to add a semi colon to the end of the character reference. From researching this error online, I found out that it is best practice to always include it even though it can sometimes be ommitted. The error was corrected by adding it in. 

#### Warnings

* Document not Mappable to XML 1.0

   <img src="assets\documents\testing\html_validator_xml.png" alt="xml warning" width="500"/>

   As the site code was contained all in one html file, in order to easily distinguish by eye each section of the page while coding I added wide comments around each section. This had brought about multiple warnings from the HTML validator. To remove this warning, I adjusted the comments to be the normal size.

### CSS Validator

### Lighthouse Performance

### User Stories Validation

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
The website has been deployed using Github pages. In order to do this I followed the steps given in the GitHub docs page on [Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site):

1. In the repository, select **Settings**
2. Select the **Pages** tab
3. Select **main** as the publishing source, using the Branch drop down menu

## Credits

### Content
<!-- - The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z) -->

### Media
<!-- - The photos used in this site were obtained from ... -->

### Acknowledgements

<!-- - I received inspiration for this project from X -->
