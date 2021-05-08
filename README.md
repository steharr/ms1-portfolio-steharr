# [**Stephen Harrold Personal Portfolio / CV Website**](https://steharr.github.io/ms1-portfolio-steharr/)

As part of my Code Institute course studies, I have created this personal portfolio / CV website for my first milestone project. The site link is available [here](https://steharr.github.io/ms1-portfolio-steharr/)

<img src="assets\documents\mockup\mockup-steharr-portfolio.PNG" alt="initial lighthouse results for mobile" width="800"/>

The primary goal of this site is to showcase my skills and abilities and gain employment in software development. The target site audience is recruiters; they will be visiting this site when they are looking at my job application. Presenting my skills, experience and projects in the form of a website distinguishes me from others in the mind of the recruiter and hopefully helps to relieve the repetition of the hiring process for them.  

The website is mobile first and built using HTML, CSS and Bootstrap. 
***
## **UX**
The **five planes of user experience design** developed by Jesse James Garrett was used as the conceptual framework for the development process of this site

### **Strategy Plane**
There were two perspectives I needed to take into account when planning out the strategy of my site. These perspectives would help me to create a list of user stories to use when designing the site. These perspectives were:
  * Site Owner Perspective (i.e. a full stack developer)

  * Site Viewer Perspective (i.e. a tech recruiter)

For the perspective of a developer I researched various existing developer personal websites in order to give me an overview of what is normally included on a website like this. This helped me understand what a developer commonly displays on a personal portfolio website. In particular [this article](https://www.freecodecamp.org/news/15-web-developer-portfolios-to-inspire-you-137fb1743cae/) on www.freecodecamp.org gave me a wide variety of examples to draw inspiration from. There was also [this site](https://brittanychiang.com/#about) from Boston based software engineer Brittany Chiang which I stumbled upon that was particularly inspiring for me.

For the perspective of a recruiter, I researched online articles on what a tech recruiter is typically looking for from someone who is applying for a developer role and what challenges they face. A notable mention was [this article](https://geshan.com.np/blog/2019/01/things-tech-recruiters-look-for/) from a software engineers blog website. It gave an in-depth insight into the mind of a tech recruiter.

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
2. See an eye-catching landing page that captures my attention

In order to assess the technical skills of the site owner I want...

3. The project portfolio is to be well presented and accessible
4. The project portfolio is to be easily understandable
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

The site is designed to be a one page scrolling site. This is to make the site navigation as smooth as possible for the recruiter. The objective is that the site flows in one direction (ie. from top to bottom) with the final destination being a contact page. This replicates how a recruiter normally reads through a CV (i.e. top to bottom) which will give them a feeling of familiarity. 

Navigation is on the site is intended to be primarily done by scrolling. The only time the user should need to press any element on the website is for either of the following situations:
* They want to go back and re-evaluate a previously seen page (possible through the main overhead nav bar)
* They want to skip content to go to a page of particular interest (e.g. on the 'about' page there is an option to jump to projects).
* They want go to an external location e.g. a Github project repository

### **Structure Plane**
For the structure of the site I decided to include the key elements of a resume/cv: a personal pitch/summary, education, work history, skills, projects. I also included a contact form section in order to fulfil site viewer user stories 8 and 9. When deciding the individual layout of each page, I researched typical website layouts online for inspiration. A notable example which helped was [this article from adobe.com](https://xd.adobe.com/ideas/principles/web-design/11-website-layouts-that-made-content-shine-in-2019/)

#### Site Structure:

1. **Header Nav Bar**  
The header of the site contains a horizontal navbar which houses links to each section of the site. It also contains a brand name for the site. The brand acts as a home button which links to the landing page of the site. The brand name is SteHarr - a combination of my first and second name and also my GitHub User name. The navbar is fixed at the top of the page as the user scrolls down the site. This is done to satisfy user story 10.

2. **Landing Page**  
This page contains a hero image, a greeting and a brief summary of myself. On desktop devices the page contains large navigation buttons each for a section of the site i.e. **About**, **Skills**, **Projects** and **Contact**.  The buttons are intended to be visually striking and allow the viewer to jump to an area of the page of particular interest. As there is less screen space available on mobile devices, I had to choose what is the most important button to be displayed. As per my initial design decisions, a key objective of the page is to get the viewer to reach out to me. Therefore I chose to display a contact me button underneath the personal summary in the mobile version of the page.

3. **About**  
Since I am developer who is changing careers, I thought I needed to visually explain to the viewer the context of how I made this decision to switch. I therefore decided to use a timeline for the **About** section of the page. The timeline contains three nodes. A description of my educational background, a description of my work history and a description of what I am doing now (i.e. studying in code institute). For the end of the timeline I had planned to include a node on a description of my latest project. During development this was changed to a button that linked to the projects page as three nodes on the timeline looked more visually apealing than four.

4. **Skills**  
For the skills section, I planned to include a progress bar section on the experience I have with various coding languages and a descriptive section on other various software expertise I had. The content is structured in an asymmetrical layout. During development, I decided to include a small section on my soft skills below the coding languages as it fit well in the structure of the page.

5. **Projects**  
For the projects page I decided to use a card layout. Each card is a separate project that I've worked on. The cards are displayed stacked on top of each other on mobile devices and on desktop screens they appear in rows.

6. **Contact**  
The contact page contains a descriptive text section and simple static contact form. The text section encourages the user to fill out the form if they want to get in touch and gives my email address if the viewer would prefer to write an email. If the viewer wants more details, this section also includes a link to a downloadable version of my CV.

7. **Footer**  
The footer is visible on the contact page section of the site. It contains a short blurb and a social section which contains links to my social media. There is also a copyright watermark at the bottom of the footer. 


### **Skeleton Plane**
For the skeleton plane, I created wireframes of each section of the site using the Balsamiq tool. These wireframes acted as blueprints to work from while the site was in development. They do not represent the final appearance of the site as some elements of the site evolved as I was developing the site.

#### Wireframes:
* [Landing Page](assets/documents/wireframes/landing_page.png)
* [About Page](assets/documents/wireframes/about_page.png)
* [Skills Page](assets/documents/wireframes/skills_page.png)
* [Projects Page](assets/documents/wireframes/projects_page.png)
* [Contact Page](assets/documents/wireframes/contact_page.png)

### **Surface Plane**

#### Colour Palette
In order to choose an overall colour palette for the page, I used the colour scheme generator site [Coolors](https://coolors.co/). I browsed various trending colour palettes on the site until eventually I found a palette with a selection of orange and turquoise colours which stuck out for me. From there I altered this palette further to accommodate the needs of my site. The final colour palette is below:

|Colour Name|Hex Value|Used In|
| :-------------: |:---------:| :-----:|
|Gunmetal| ![#272F36](https://via.placeholder.com/15/272F36/000000?text=+) `#272F36` | Contact form input boxes and coding language progress bars|
|Gunmetal| ![#2B343B](https://via.placeholder.com/15/2B343B/000000?text=+) `#2B343B` | Footer and Header Navbar|
|Gunmetal| ![#2A3941](https://via.placeholder.com/15/2A3941/000000?text=+) `#2A3941` | Skills box, project cards and contact form|
|Charcoal| ![#264653](https://via.placeholder.com/15/264653/000000?text=+) `#264653` | Main background colour of page|
|Orange Yellow Crayola| ![#E9C46A](https://via.placeholder.com/15/E9C46A/000000?text=+) `#E9C46A` | All site buttons, percentage bar gradients, <br> about page timeline items, footer social links|
|Sandy Brown| ![#F4A261](https://via.placeholder.com/15/F4A261/000000?text=+) `#F4A261` | Landing page navigation buttons and hero image border, <br> about page timeline dashed line|
|Burnt Sienna| ![#E76F51](https://via.placeholder.com/15/E76F51/000000?text=+) `#E76F51` | Landing page navigation buttons and hero image background,<br> skills page expertise headers |

In my user stories I had identified that I wanted the experience of the site to be enjoyable and smooth for a recruiter. I was conscious of the fact that they they are reading numerous job applications on a daily basis which could be an arduous task. With this in mind, I wanted the base colour of the site to be a dark neutral colour that was gentle on the eyes. The **Charcoal** colour was perfect for this objective. 

Having the base colour darker allowed me to use brighter colours for the elements on the page which made them stand out. **Burnt Sienna**, **Mandarin**, **Sandy Brown** and **Orange Yellow Crayola** contrasted very well with the **Charcoal** background of the site to achieve this effect

The **Gunmetal** colour was useful for the less dominant elements of the site such as the navbar and the footer.

#### Fonts
* For the primary font of the site I chose [**Roboto Mono**](https://fonts.google.com/specimen/Roboto+Mono?query=roboto+mono#standard-styles)
* To accompany this font, I chose [**Roboto Slab**](https://fonts.google.com/specimen/Roboto+Slab?query=roboto+slab) for the main title on the **Landing** page.
* For each of the page headings, I used [**Open Sans**](https://fonts.google.com/specimen/Open+Sans?query=open+sans)

***
## Features
### Existing Features
|Feature|Description|Location|
|:--:|:--:| :--:|
|Responsive Fixed Navbar| Overhead navigation bar that is fixed top throughout the  site. Contains links to all sections of the site. Collapses to hamburger menu on smaller screens| All pages of the site. Fixed to top of viewport |
|Responsive Landing Page Navigation Menu| Navigation menu with large circular buttons which are quicklinks to all pages of the site. Responds to smaller screens by transforming into a single **Contact** button. [ScrollReveal](https://scrollrevealjs.org/) transition effect for buttons to make them blend into view | Landing Page |
|Responsive Education and Work History Timeline |Timeline on the **About** page which displays horizontally or vertically based on screen size. Includes positioned timeline dots which have accompanying images and descriptions | About Page |
|Coding Languages Progress Bars| Customized Bootstrap progress bars used to visually display relative skill level for specific coding languages and frameworks | Skills Page |
|Project Cards| Customized Bootstrap project cards used to visually display project portfolio. Cards include thumbnails, descriptions, coding languages tags and links to the projects on Github. Work in progress banners also included for projects not completed. Projects are contained within a flexbox to ensure that new projects can be easily added to the portfolio without destroying responsive layout of section.| Projects Page |
|Responsive Contact Page Layout| Contact page instructions respond to screen size i.e. on Desktop, since contact form is displayed on the right side of the screen, the contact page instructions inform the viewer to *"Please fill in the form on the **right**"*. Whereas on Mobile screens since the form is below, the instructions refer to a form **below** the instructions  | Contact Page |
|Contact Form| Contact form with submit button to allow the user to get in touch. Form appearance customized in line with aesthetic of site. One particular element to mention: Chrome autofill field colours have been adjusted in line with site colour palette | Contact Page |

### Features Left to Implement
There were several features which I had brainstormed early on which could not be achieved either due to time constraints or because they were beyond the scope of my skills. I will look to implement them in a future release: 

* Navigation Menu Buttons User Interface Improvements  
For a future release, I would like to add more animation and visual feedback to the navigation menu buttons on the **Landing** page

* ScrollReveal Effect Throughout Site   
Since it is a one-page site, I want to expand the use of the ScrollReveal effect which I used on the **Landing** page navigation menu. Adding this effect would make scrolling down the site more pleasant for the site viewer

* Interactive Skills Page  
At the moment the **Skills** page is quite static. I would like to add some more effects to make it more interactive.

* Project Cards Improvements  
I have multiple ideas to improve the project card appearance in the **Projects** page. These ideas include: adding links to the projects' live site, repositioning the coding language tags to the bottom of the card, adding an effect when hovering over the project images.

* Contact Form Functionality  
At the moment the contact form is not functional as this was out of scope for this project. I will look to update this in future.

* VBA Tips/Tutorial Blog  
I got interested in programming by learning Visual Basic for Applications (VBA) in my work to automate Excel tasks. I would like at some point to include a section in my site which gives tips and tutorials on how to make good Excel Add-Ins with VBA. I want to pass on some of the knowledge I have learned as I found it to be a very helpful and beneficial language to learn as someone new to programming.

## Technologies Used

* [Visual Studio Code](https://code.visualstudio.com/)  
Code editor I used to write my code
* [Live Server VS Code Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)  
Extension I used to see in real time the effect that the changes I was making to my code would have
* [HTML](https://en.wikipedia.org/wiki/HTML5)  
For markup
* [CSS](https://en.wikipedia.org/wiki/CSS)  
For styling the site
* [Boostrap Framework](https://getbootstrap.com/)  
I used the bootstrap grid system to help me design responsive layouts and I made customized versions of various boostrap components throughout the page
* [Google Fonts](https://fonts.google.com/)  
For the font used in the site
* [Font Awesome](https://fontawesome.com/)  
Used for icons throughout the site
* [ScrollReveal](https://scrollrevealjs.org/)  
Javascript libray I used to animate elements on the landing page
* [Git](https://git-scm.com/)  
For version control
* [GitHub](https://github.com/)  
For storing my files and for hosting the site on Github Pages
* [Canva](https://www.canva.com/)  
I used a premium version of this tool to create various images throughout the site, most notably the project card images
* [favicon-generator.org](https://www.favicon-generator.org/)  
Used to generate a favicon for the site from an image I created using Canva
* [resizeimage.net](https://resizeimage.net/)  
Used to resize images on the page to improve Lighthouse scores
* [placeholder.com](https://placeholder.com/)  
I used this site to create small blocks of colour for the colour palette section of this README
* [Balsamiq](https://balsamiq.com/  
Used to create wireframes
***
## Testing
During development, I regularly tested the output of my code using the VSCode [LiveServer](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension to see in real time how changes made in the code affected how the page was being rendered in a Chrome browser. Multiple screen sizes were evaluated during this process using Chrome developer tools.
After the bulk of the development was complete, I tested my code by putting it through the [W3C HTML Validator](https://validator.w3.org/), the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) and then checked its performace using Lighthouse in Chrome Dev Tools. The final period of testing was done by validating the site against each of my User stories.

### **Notable Bugs Occurring During Development**
During the development phase of the site, I encountered a number of significant bugs while testing the output of my code. They were all mistakes which led to important lessons learned for future projects. These are documented below:
#### **Misplaced Nav Bar**

<img src="assets\documents\testing\error_misplaced_navbar.png" alt="misplaced navbar error" width="250"/> 

* **Description**  
Early on, an issue occurred where the nav bar of the site was not appearing fixed to the top of the screen for both desktop and mobile devices even though the bootstrap 'fixed-top' class had been used.  
* **Root Cause and Fix**  
To troubleshoot this issue I removed individual HTML elements one at a time from the page and analysed how the site then appeared. I eventually found the root cause to be an empty line of code above the body element of my page. This was creating a new line that was empty before the navbar in the site. Removing this line in my code corrected the issue.

#### **HTML Body Width Error**

<img src="assets\documents\testing\error_html_body_width.png" alt="html body width error" width="300"/> 

* **Description**  
Late on in development, I noticed that the footer of the site was not spanning the width of the viewport on iPad screens only. This was especially confusing since the element had the **container-fluid** class. Looking into Chrome developer tools, I could see that the width of the html element in the page was not covering the entire width of the iPad screen.
* **Root Cause and Fix**   
To troubleshoot this issue, I researched online and came across [this post on stack overflow with a similar issue.](https://stackoverflow.com/questions/30358630/html-body-not-filling-complete-width-on-mobile-devices) I then determined that the issue was being caused by text overflow somewhere on the page. This theory was confirmed by the fact that the issue was only occurring on the iPad, which was showing text overflow on the **About** and **Projects** pages of the site. To fix this issue I refactored the code for both of these pages.

#### **Live Site Contact Form Rounded Input Boxes**

<img src="assets\documents\testing\error_rounded_edges.png" alt="rounded edges error" width="200"/>

* **Description**  
After deploying the site to Github pages, I noticed when viewing the live site on my iPhone that the contact form fields had rounded corners which I had not intended. The aesthetic of the form was designed to be all straight edges. For some reason this was not visible when I was testing the site through Chrome developer tools on my desktop, even when selecting the iPhone frame.

* **Root Cause and Fix**   
To address this I initially set the `border-radius` to equal zero in my CSS rule for these elements. This did not fix the issue so I did some researched online and found that the mobile version of safari can often make HTML input elements looks different to what appears on desktop. I found [this article on medium.com](https://medium.com/@martinbottanek/how-to-disable-rounded-corners-on-input-fields-using-safari-iphone-ipad-2d08a199c39c) which gave me the vendor prefixes and CSS code to override this and get my desired effect.


### HTML Validator Results
After passing my code through the HTML validator for the first time, I received 7 error messages and a one repeated warning. These errors and warnings were all corrected and the validator check was repeated. The second check produced no errors or warnings. Below is how each of the initial validator check results were addressed:

#### Error Messages
* Empty ID on Landing Page

   <img src="assets\documents\testing\html_validator_empty_id.png" alt="empty id tag error" width="500"/>

   This was missed during development. Corrected by removing the empty id attribute. 
* Paragraph element entered as direct child of unordered list element

   <img src="assets\documents\testing\html_validator_paragraph_ul.png" alt="paragraph child of unordered list error" width="500"/>

   For the list of software expertise items on the skills page, I had accidentally put paragraph elements as children of the unordered list. The list already had `<li>` elements containing the headings for these paragraphs, therefore I could easily move the paragraph elements into them to amend this error.

* Stray end `<i>` Tag

   <img src="assets\documents\testing\html_validator_stray_i.png" alt="stray i tag error" width="500"/>

   This stray tag was likely added when adding font awesome icons. Corrected by removing the tag. 

* Semicolon Typo on Contact Page

   <img src="assets\documents\testing\html_validator_semicolon_typo.png" alt="semicolon typo error" width="500"/>

   Corrected by removing the semicolon before the equals sign

* Character Reference in Footer Not Terminated by Semicolon

   <img src="assets\documents\testing\html_validator_character_reference.png" alt="character reference error" width="500"/>

   When adding a copyright symbol to the footer of my page, I had forgotten to add a semi colon to the end of the character reference. From researching this error online, I found out that it is best practice to always include it even though it can sometimes be omitted. The error was corrected by adding it in. 

#### Warnings

* Document not Mappable to XML 1.0

   <img src="assets\documents\testing\html_validator_xml.png" alt="xml warning" width="500"/>

   As the site code was contained all in one html file, in order to easily distinguish by eye each section of the page while coding, I had added wide comments around each section. This had brought about multiple warnings from the HTML validator. To remove this warning, I adjusted the comments to be the normal size.

### CSS Validator
After passing my code through the CSS validator for the first time, there were 2 errors and numerous warnings appearing on the site. The errors given were related to external files I had referenced in my code i.e. Bootstrap CDN links. Since these results were not linked to my code I focused solely and the messages related to my code. The overall results from the validator produced 23 warnings for my code. Below is how each of the initial validator check results were investigated:

#### Warnings

* Unknown Vendor Extensions 

   <img src="assets\documents\testing\css_validator_vendor.png" alt="vendor prefix warning" width="500"/>

  There were multiple vendor prefixes used in my code used in order to ensure compatibility across different browsers. From researching this validator warning online, I understood that these vendor extensions are outside of the scope of the validator since they are proprietary code. Therefore I did not need to address them.

* Same colour for **background-color** and **border-top-color**

   <img src="assets\documents\testing\css_validator_color.png" alt="colour warning" width="500"/>

   The background colour of the timeline images on the **About** had been mistakenly set to the same colour as their borders. This was amended so that the background colour was the same as the background colour of the buttons on the **Landing Page**

### Lighthouse
To analyse the Performance, Accessibility and User Experience of my site, I used [Lighthouse](https://developers.google.com/web/tools/lighthouse) in Chrome developer tools.

#### Results
The initial results for mobile were as below:

   <img src="assets\documents\testing\lighthouse_results_initial_mobile.png" alt="initial lighthouse results for mobile" width="500"/>

The initial results for desktop were as below:

   <img src="assets\documents\testing\lighthouse_results_initial_desktop.png" alt="initial lighthouse results for mobile" width="500"/>

* Improving Performance Score  
From looking at the metrics provided by Lighthouse, the element with the largest contentful paint (LCP) on the page was having the greatest effect on my performance score. The element mentioned was one of the project page card images, the Love Running project image. This element had a 500 x 500 px sized image with lots of detail. I decided to resize the image in line with the size that it was actually being displayed as on the biggest screen the site could be viewed on (i.e. a desktop). I checked Chrome dev tools to get the dimensions of what the image was being displayed at and then used a website called [resizeimage.net](https://resizeimage.net/) to resize the image. This made the file size much smaller. I also repeated this process for multiple other images throughout the site to improve the site performance further.

* Improving Best Practices Score   
From looking at the best practices analysis provided by Lighthouse, I saw a warning that "Links to cross-origin destinations are unsafe". From researching this online, I discovered that there is a security vulnerability with Javascript that can allow a new tab to gain control of its referring window which malicious websites can exploit. The recommended approach to counter this is to use a `rel="noopener"` attribute in all anchor elements which contain `target="_blank"`. I therefore added this attribute to the elements in my site

The final results for mobile were as below:

   <img src="assets\documents\testing\lighthouse_results_final_mobile.png" alt="final lighthouse results for mobile" width="500"/>

The final results for desktop were as below:

   <img src="assets\documents\testing\lighthouse_results_final_desktop.png" alt="final lighthouse results for mobile" width="500"/>

_\*Since running the final lightouse test for mobile shown here, the performance score has dipped slightly in subsequent tests. I unfortunately ran out of time to investigate this further_

### User Stories Validation
_**Note:** For this validation, to make it easy to distinguish between the user stories for each perspective that I outlined in my **Strategy** section, I will abbreviate the Site Owner user stories with the letter **O** (for owner) and for the site viewer User Stories with the letter **V** (for viewer)_ 

**O1 - "with this site I want to get offers for jobs in software development"**  
Of all of the user stories this is the only one which cannot be fully validated yet as I have not yet used this site for job applications. I am confident however that it will satisfy this in the future.

**O2 - "with this site I want display my strongest traits to the site visitor: Creativity, Problem Solver, Enthusiastic Learner"**   
Creativity is demonstrated by overall aesthetic of the site. Problem solving skills can be seen in the **About**, **Skills** and **Projects** page of the site. Enthusiasm is a less tangible concept to validate, however it can be picked up from the timeline in the **About** page of the site. The timeline demonstrates how I have constantly been working to improve my skills and learn more throughout my career.

**O3 - "with this site I want to demonstrate my technical skills through the design of the site"**  
The site demonstrates a high level of technical skill through its responsive layouts, notable evidence of this can be seen in the landing page navigation menu and the elements of the **Contact** page. 

**O4 - "with this site I want to have a location to store & demonstrate all of my completed and ongoing projects"**  
The site has a section for a project portfolio that is designed with flexbox technology. The layout of the portfolio therefore won't be damaged if it gets updated with additional project cards. There is also project banners for work in progress projects. The project cards contain sufficient number of elements to fully demonstrate all aspects of a project. 

**O5 - "with this site I want to convey my passion for programming"**  
The site demonstrates a clear passion for programming through the intricate design elements in various sections of the site e.g. the project cards and the **Skills** page progress bars.

**V1 - "to asses the profile/personality/character of the site owner I want to get a comprehensive overview of the experience and skillset of this developer"**  
A comprehensive overview of my experience is given in the **About** page timeline. My skillset is thoroughly described in the **Skills** page.

**V2 - "to asses the profile/personality/character of the site owner I want to see an eye-catching landing page that captures my attention"**    
The landing page contains a large hero image which captures the viewers' attention. There is a also a big introductory message. 


<img src="assets\documents\testing\user_stories_validation_hero_image.png" alt="user stories validation landing page hero image" width="500"/>


**V3 - "to assess the technical skills of the site owner I want the project porfolio is to be well presented and accessible"**  
The **Projects** page is laid out well with project cards containing visually striking images to entice the viewer.

**V4 - "to assess the technical skills of the site owner I want the project portfolio is to be easily understandable"**  
The project cards visible in the **Projects** page give a detailed overview of each project. A short project description with details on the coding languages used are included. Links to the project GitHub repos are given.

<img src="assets\documents\testing\user_stories_validation_project_card.png" alt="user stories validation project card" width="250"/>


**V5 - "to assess the technical skills of the site owner I want the experience of navigating through the site is to be enjoyable and smooth"**  
The site is designed as a single page site specifically to address this user story.

**V6 - "to assess the technical skills of the site owner I want the layout of the site to be intuitive"**  
The site is designed in a logical manner and replicates all of the key elements of a CV.

**V7 - "to assess the technical skills of the site owner I want the site to perform well on any device"**  
The site layout responds well to all possible screens in Chrome dev tools. The live site was tested on Chrome and Firefox on an Android phone. It was also tested on Safari on an iPhone. Both testing devices showed responsive layouts.

**V8 - "In order to offer an interview to the site owner I want easy access to contact details of this person"**  
In the **Contact** page, there is an available contact form for the viewer to use. In addition to this, the site owner email address is given if the viewer would prefer to send an email. Finally, right below the **Contact** page is the footer which contains a "social" section containing links to the site owner's social media pages.

<img src="assets\documents\testing\user_stories_validation_contact_page.png" alt="user stories validation project card" width="500"/>


**V9 - "In order to offer an interview to the site owner I want have the option to download a traditional CV"**  
This option is available in the **Contact** page instructions.

**V10 - "In order to offer an interview to the site owner I want to be always easily within a click's reach of getting in contact"**  
This is satisfied by the fact that the site navbar is fixed to the top of the viewport at all times. The viewer can quickly navigate to the **Contact** page at any stage while viewing the site. The landing page also includes a quicklink to the contact page to allow even faster access than using the navbar. 

***

## Version Control
* To begin the project I created a remote repository on Github by choosing the **New Repository** button and following the on screen steps.
* I then created a local repository using Git:
   *  I created a directory on my computer called **ms1-portfolio-steharr**
   *  I opened the directory using VS code and started a terminal
   *  I initialized the directory as a Git repository using the command `git init`
   *  I added a README to the file using the command `git add README.md`
   *  I then created an index.html file in the directory and started working on the site
   *  When I was ready to commit my first set of changes, I used the `git add .` and the `git commit -m "Initial commit"` commands in my terminal
   
* In order to store my commits remotely on Github, I linked my local repository to the remote repository:
   * In my VS code terminal, I used the command `git remote add origin https://github.com/steharr/ms1-portfolio-steharr` and `git remote -v`

* Throughout the development process, I would regularly push my commits to Github using the `git push` command 

## Deployment
* The website has been deployed using Github pages. In order to do this, I followed the steps given in the GitHub docs page on [Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site):

   * In the repository, select **Settings**
   * Select the **Pages** tab
   * Select **main** as the publishing source, using the Branch drop down menu

***
## Credits

### Code

* Bootstrap

   * The **Header Nav Bar** was customized from the [Bootstrap Navbar Component](https://getbootstrap.com/docs/4.6/components/navbar/)
   * The **Skills** page progress bars were customized from the [Bootstrap Progress Component](https://getbootstrap.com/docs/4.6/components/progress/)
   * The **Projects** page project cards were customized from the [Bootstrap Card Component](https://getbootstrap.com/docs/4.6/components/card/)
 
* Coolors

   * The gradient colour effect for the **Skills** page progress bars was made using the [Coolors Gradient Maker](https://coolors.co/gradient-maker/e76f51-e9c46a?position=0,100&opacity=100,100&type=linear&rotation=0)

* ScrollReveal

   * The ScrollReveal effect was implemented using the [docs available at the official site](https://scrollrevealjs.org/guide/customization.html)

### Content
All written content was created by me

### Media

* Images
   * about-study.png - [Unsplash - Credit: Aaron Burden](https://unsplash.com/photos/QJDzYT_K8Xg)
   * about-work.png -  [Unsplash - Credit: Jason Jarrach](https://unsplash.com/photos/8grom09QaDs)
   * about-now.png - [Unsplash - Credit: Florian Olivo](https://unsplash.com/photos/4hbJ-eymZ1o)
   * project_card_whiskey_drop.png - logo designed using [Canva](https://www.canva.com/) with background image downloaded from [Unsplash - Credit: Dylan de Jonge](https://unsplash.com/photos/pe9T4ROjpzQ)
   * project_card_loverunning.png - logo designed using [Canva](https://www.canva.com/) with background image downloaded from [Code Institute](http://codeinstitute.s3.amazonaws.com/FundamentalsProjects/HTML-CSS/main-image.png)
   * project_card_python_project.png - logo designed using [Canva](https://www.canva.com/)
   * project_card_steharrportfolio.png - logo designed using [Canva](https://www.canva.com/)
   * project_card_excel_project.png - logo designed using [Canva](https://www.canva.com/)

### Acknowledgements

* My mentor, **Spencer Barriball** who guided me through this project.
* Fellow **Code Institute** students on Slack who helped troubleshoot issues and give me inspiration for this project