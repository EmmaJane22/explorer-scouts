# Explorer Scouts Website - Emma Scott


![mockups](/readme-images/testing/mockup.jpg "Mockup")

* St. John's Explorer Scouts are a group of over 20 Scouts who meet weekly from across Sunderland. The aim of the website is to appeal to current members and their parents, to attract new potential members to the group and to showcase the group's succeses and activities. The website is designed to be responsive so that it is appealing and can be used on any device. 
* The website features five pages and has been built using HTML and CSS and Bootstrap.

## Live Project
[View the live project here.](https://emmajane22.github.io/explorer-scouts/ "View the Live project here")

## GitHub Repository
[View the project repository here.](https://github.com/EmmaJane22/explorer-scouts.git "View the project repository here")
___

# Table of Contents:
[1. User Expereince (UX)](#ux)
  - [User Stories](#user-stories)
  - [External Users' Goals](#external-users)
  -	[Site Owners goals](#owner-goals)

      
[2. Design Choices](#design)
  - [Colour Palette](#colour)
  - [Typography](#typography)
  - [Images](#images)

[3. Site Structure](#structure)
  - [Wireframes](#wireframes)
  - [Site Map](#map)
  - [Landing Pages](#landing)
  - [Meeting Page](#meeting)
  - [Events Page](#events)
  - [Contact Page](#contact)
 
[4. Features](#sitefeatures)
  - [Navigation Bar](#nav)
  - [Hero Images](#hero)
  - [Footer](#footer)
  - [Future Features](#future)

[5. Technologies Used](#tech)

[6. Testing](#testing)
  - [Chrome DevTools](#devtools)
  - [Code Validation](#val)
  - [W3C HTML](#w3chtml)
  - [W3C CSS](#w3ccss)
  - [Lighthouse](#lighthouse)

[7. Bugs & Fixes](#bugs)

[8. Deployment](#deployment)

[9. Credits](#credit)
  - [Code](#code)
  - [Images](#image-credit)
  - [Content](#content)
  - [Acknowledgements](#acknowledge)
 
# User Experience (UX)

## User stories

### External Users' Goals:

* The site users are Explorer Scout members and potential members and their parents/carers, who want to know more about the Explorer Scout pack and it's activities.

* External users may want to celebrate the Pack's achievements or to explore what events the Pack participates in.

* External users may want to be able to know when and where the group meet and be able to contact leaders directly to find out more information using an online form.

* External users may want to find out who can join Explorer Scout groups, age requirements and Scouting aims and the activities their child might take part in if they become an Explorer. 


### Site Owner's Goals:
* The Explorer Scout group is interested in attracting  new members as well as retaining current members.

* The group also wants to celebrate their successes and showcase their activities/events to a wider community, as parents and the public are not permitted to attend group sessions. Scouting officals from county level are also interested in viewing the group's activities.

* The site owner requires a simple contact form that people can use to ask questions.


### Features to include:
* Showcase photos of members having fun at group activities.

* Provide details of the activities Explorer Scouts participate in and the structure of meetings.

* Provide information on the packs location, meeting times, contact details and any external resources (e.g. Scouts official website). 
___

# Design Choices

## Colour Palette

![colour palette](/readme-images/colour_scheme.png)

- A simple colour scheme has been used. The teal colours echo the muted colours of the Explorer group's uniform. 

- The footer section has a colour gradient which adds visual appeal, made using a tutorial from W3Schools https://www.w3schools.com/css/css3_gradients.asp 

- I used https://color.adobe.com/ to decide on the colour scheme.

- The font colour and background colour for the header and body were checked for contrast on https://coolors.co/contrast-checker/ and scored '13.43 - super' showing the contrast makes the accessibility good. The contrast was checked for the footer and was scored '12.44 - Super'.

## Typography

- The 'Special Elite' font is used for the logo at the top of the site and for headings. Sans-serif is the fallback font in case the title font is not being imported correctly. 'Special ELite' adds character to the logo, as it creates an image of adventures.
- The 'Roboto' font is used for all other body text. It is a clean and easily legible font.

## Images

- A consistent aspect ratio of 16:9 has been used for all of the hero images to bring consistency to the pages. 
- A square ratio has been used for the landing page circles to prevent stretch.
- I used Font Awesome icons for the social media information and contact information to give the user visual clues.

___

# Site Structure

The website has a Home page and four other pages:
- Meetings - provides information about where meetings are and who can join.
- Events - provides information about the activities the unit participate in and has photos to showcase these.
- Contact - provides a simple contact form for users to ask questions.
- Thank you - the contact form is set to direct to this page rather than the Code Institue form dump. It redircets users back to the site.

## Wireframes

### Site Map
![site map](/readme-images/wireframes/site-map.jpg "Site Map")

### Landing Page
![landing page](/readme-images/wireframes/low-res-landing-page.png "Landing Page")

 
### Meeting Page
![meeting page](/readme-images/wireframes/low-res-meeting-page.png "Meeting Page")

### Events Page
![events page](/readme-images/wireframes/low-res-events-page.png "Events Page")

### Contact Page
![contact page](/readme-images/wireframes/low-res-contact-page.png "Contact Page")

The contact form is not active as I have not learnt this technology yet.
The contact form was set to method GET after viewing a post on Slack regarding form methods: https://code-institute-room.slack.com/archives/C7J2ZAVHB/p1653483581074199

In order to do this, I created a copy of the index.html page but changed the content to have an acknowledgement of the form submision rather than going to the Code Institute page. If this site was to go live for the public, this would be changed.
___

# Features

## Navigation Bar
All pages are accessible from the NavBar apart from the thank-you.html as this is the form response. This allows the user to easliy naviagte the site without the need to return to the home page.
The navbar appears as a horizontal list on desktop and changes to a vertical drop down menu on mobile.
The decision was made to not make the navbar sticky so that the user can see more on the page as they scroll down.
I used Bootstrap to produce the menu, and added an underline for the active page and a hover state to non-active pages.

![navbar desktop](/readme-images/navbar.jpg "navbar")

![navbar mobile](/readme-images/navbar-mobile.jpg "navbar mobile")

## Hero Images

All pages feature a hero image across the top to create a consitent view. The hero images use different images on each page to reflect the content  of that page.
The desktop contact page does not feature a hero image to create a greater focus on the form itself. The form has a background image instead with a semi-transparent overlay to maintain the branding. The mobile version has a hero image and the background image removed to increase the loading speed and because the impact of the background image was lost on a small screen.

- All images were compressed to allow faster loading using https://tinypng.com/
- Credit for all images can be found below.

## Footer
The footer element links to social media chanels and shows the phone number and email address for ease of contact.
It features a gradient colour for interest.

## Future Features
* I will research using NextGen formats for images in future.
* In order to make the form action POST work, I need to learn the scripting behind the form.
* It was suggested in Peer Review that I make the page one scrolling page rather than seperate pages. This is something I will consider for the future.

___

# Technologies Used
* HTML -used for structuring and presenting information on the website.
* CSS - used for styling the HTML code.
* Bootstrap v5.1.3 - used to improve the responsiveness of the site for access on different size devices.
* Balsamiq: Balsamiq was used to create wireframes for the project.
* Font Awesome: The project uses icons from Font Awesome version 6.
* Chrome DevTools: This featured heavily as I tested the site throughout to adjust sizings and spacings.
* Google Fonts: The fonts used have been imported from Google Fonts.

 ___

# Testing

The St John's Explorer Scouts website has been tested using the following methods:

### Chrome Devloper Tools
* I made use of the Developer Tools throughout the project to inspect my pages and make changes accordingly.

## Code Validation

### W3C HTML Validator
![w3c screenshot 1](/readme-images/testing/w3c-screenshot1.jpg "W3C Validator screenshot 1")

![w3c screenshot 2](/readme-images/testing/w3c-screenshot2.jpg "W3C Validator screenshot 2")

The following steps were taken to fix the bugs identified by W3C Validator:
1. Additional hypens removed.
2. Section class (hero-outer) changed to div class as no heading was needed.
3. Div id="circle" changed to div class.
4. Section class (landing-circles) changed to div class as no heading was needed.

All identified bugs fixed:
![w3c screenshot 3](/readme-images/testing/w3c-screenshot3.jpg "W3C Validator screenshot 3")

### W3C CSS Validator
The W3C CSS Validator showed the following errors:

![w3c css screenshot](/readme-images/testing/css-screenshot1.jpg "W3C CSS Validator screenshot")

Following research, I realised this error is with the Font Awesome toolkit so I was unable to address this.

### Lighthouse Desktop

I used the Lighthouse reports in Google DevTools to examine the desktop pages of the website for:
* Performance
* Accessibility
* Best Practices
* SEO

The report for index.html on desktop was 'good' for Accessibility and SEO but 'needs improvement' for Performance and Best Practices. 

![lighthouse screenshot](/readme-images/testing/lighthouse1.jpg "Lighthouse screenshot")

![lighthouse 2 screenshot](/readme-images/testing/lighthouse2.jpg "Lighthouse 2 screenshot")

![lighthouse 3 screenshot](/readme-images/testing/lighthouse3.jpg "Lighthouse 3 screenshot")

![lighthouse 4 screenshot](/readme-images/testing/lighthouse4.jpg "Lighthouse 4 screenshot")

The reports showed that I needed to update the version of Bootstrap. Updating this to version 5.1.3 resolved this issue.

A new Lighthouse report was actioned and showed 'good' for all areas. 

![lighthouse desktop screenshot](/readme-images/testing/desktop-home.jpg "Lighthouse desktop screenshot")

Subsequent reports for the other website pages showed all areas to be 'good' on desktop:

meetings.html:

![lighthouse desktop meetings screenshot](/readme-images/testing/desktop-meetings.jpg "Lighthouse desktop meetings screenshot")

events.html:

![lighthouse desktop events screenshot](/readme-images/testing/desktop-events.jpg "Lighthouse desktop events screenshot")

contact.html:

![lighthouse desktop contact screenshot](/readme-images/testing/desktop-contact.jpg "Lighthouse desktop contact screenshot")

### Lighthouse mobile

I used the Lighthouse reports in Google DevTools to examine the mobile pages of the website for:
* Performance
* Accessibility
* Best Practices
* SEO

The reports showed 'good' for Accessibility, Best Practices and SEO on the contact.html and index.html pages: 

![lighthouse mobile contact screenshot](/readme-images/testing/mobile-contact.jpg "Lighthouse mobile contact screenshot")

![lighthouse mobile home screenshot](/readme-images/testing/mobile-home.jpg "Lighthouse mobile index screenshot")

Upon inspection of the Performance errors, it recommended saving images in NextGen formats. This is something I can look into for the future.

The reports for meeting.html and events.html showed 'good' for all areas:

![lighthouse mobile meeting screenshot](/readme-images/testing/mobile-meeting.jpg "Lighthouse mobile meeting screenshot")

![lighthouse mobile events screenshot](/readme-images/testing/mobile-events.jpg "Lighthouse mobile events screenshot")

To try to improve Performance, I changed removed the animation from the hero images on mobile view for all pages and removed the background image on the contact form page, replacing it with a hero image to maintain consistency.

The new reports for the mobile pages were: 

![lighthouse mobile home screenshot](/readme-images/testing/mobile-home-lighthouse.jpg "Lighthouse mobile home screenshot")

![lighthouse mobile events screenshot](/readme-images/testing/mobile-contact-lighthouse.jpg "Lighthouse mobile contact screenshot")

While the Performance score is still 'needs improvement' there has been an improvement. 

## Peer Review
The project was shared to Slack for peer review and the following changes were made:
* the images for readme.md were moved to their own folder not in assets.
* font sizes were changed to rem.

## Contrast Checker
The colours used in the site were checked for contrast using https://coolors.co/contrast-checker/

___

# Bugs & Fixes:

* When I produced the pages originally I worked from desktop down. This created the need for a lot of media queries which I initally added, however I wasn't happy with the amount of queries needed so decided to rewrite all of the pages starting from mobile-first and using more Bootstrap code to make the elements much more responsive on larger devices. This was a major fix which took a large amount of time, but I am much more satisfied with the end product.

* When I made some final checks to the responsiveness of the pages, I discovered my logo was a broken link as I had a typing error in the link. I fixed this by correcting the typing error.

* During testiing, I realised the YouTube video was not resizing on different size devices. I sourced code from https://getbootstrap.com/docs/4.0/utilities/embed/ to fix this and allow it to resize.

* During my middle mentor meeting, we realised the YouTube video was auto-playing. I sourced code from https://www.w3schools.com/html/html_youtube.asp to prevent it auto-playing.

* While producing the header containing the logo and nav links, I noticed that the logo was pushing the menu links out of alignment when the screen was resized. I decided to use a 'hamburger' menu instead and sourced a tutorial from https://getbootstrap.com/

* During my middle mentor meeting, we realised the hero images were loading slowly, so I fixed this by reducing the image size and compressing the images using tinypng.com. The lower resolution hero images load much faster.

* Friends and family were asked to test the site and discovered the photos did not display on events.html. This was due to a missing end tag, which fixed the problem.

* After running W3C html validator I discovered that the events.html page didn't display. This was fixed by adding in an end section tag which was missing.

* After running the Lighthouse check, it recommended changing to the latest versions of Bootstrap (v. 5.1.3), therefore I updated my code to this version. This then prevented the hamburger menu working on mobile view. I fixed this by checking the code against the code sourced on getbootstrap.com and found the toggler class needed BS adding. Then then fixed the problem and allowed the hamburger menu to expand again.

* The Lighthouse report for the Contact page showed a missing form label, which I fixed.

* Following peer review, I changed the font size specification to rem.

* Following peer review, I removed 'intergrity' and 'crossorigin' code from all pages.

* To improve the Performance score on Lighthouse on the mobile versions of all pages, I removed the hero image animation which was slowing loading speed.

___

# Deployment
The project was deployed using these steps:
1. Create a repository: Go to GitHub and create a public repository, named username.github.io. Make the username your username on GitHub.

2. Go to your repository
- on top right click Settings.
- Scroll down to GitHub Pages, select main/master branch from the dropdown and press save.
- A link will be generated for your live site.

___

# Credits

## Code

* The initial code for the header, footer and circle images/containers was taken from the Code Institute Love Running project.

* Help centering the images on the Landing page circles was found here: https://stackoverflow.com/questions/32477563/how-can-i-fit-images-into-circles-without-stretching

* Code sourced from the Code Institute Whiskey Drop tutorial.

* Hover effects sourced from https://stackoverflow.com/questions/58939609/bootstrap-4-nav-link-hover-effect

* Help creating the footer grid layout was found from https://getbootstrap.com/docs/4.0/layout/grid/ and https://codepen.io/cojdev/pen/QGwyOJ

* The stylised social media links in the footer took inspiration from  https://learn.codeinstitute.net/ci_program/diplomainwebappdevelopment

* Help to center the images in the row found here: https://stackoverflow.com/questions/10879955/how-to-align-an-image-dead-center-with-bootstrap#:~:text=To%20center%20an%20image%20in,auto%20d%2Dblock%20...
and https://stackoverflow.com/questions/42388989/bootstrap-center-vertical-and-horizontal-alignment to adjust the row height.

* The gradient effect on the footer was made using a tutorial from W3Schools (https://www.w3schools.com/css/css3_gradients.asp).

* Information about Explorers has been taken from the official Scout website (www.scouts.org.uk) and the Sunderland District website (https://www.sunderlandscouts.org.uk/Explorers.html). 

* Meeting page: Credit for grid used for the information containers on the Meeting page, - from Matt Rudge "Whiskey Drop Project" Code Institute

* Code used to autoplay and mute the video on the Events page, from https://www.w3schools.com/html/html_youtube.asp

* Tutorial to add static images in Bootstrap found here: https://mdbootstrap.com/docs/standard/extended/gallery/

* Tutorial for making Google map responsive: https://blog.duda.co/responsive-google-maps-for-your-website 

* Code sourced from here for embedding a responsive video: https://getbootstrap.com/docs/4.0/utilities/embed/

* Tutorial used to fit images without stretching https://stackoverflow.com/questions/32477563/how-can-i-fit-images-into-circles-without-stretching 

## Images

Most images were sourced from the open source websites, Pexels.
Several of these were produced by EKATERINA BOLOVTSOVA, and used to maintain the colour theme. These include:
* 'Meeting' Photo https://www.pexels.com/photo/happy-children-making-campfire-in-forest-5036955/
* Meeting hero image: https://www.pexels.com/photo/boys-walking-in-forest-together-5036789/
* Events hero image: https://www.pexels.com/photo/scouts-in-forest-smiling-5036700/
* Contact form background image: https://www.pexels.com/photo/kids-holding-hands-on-wooden-bridge-5036782/

Other images were sourced from:
* Landing page Hero Image:"https://www.freepik.com/photos/best-friends" https://www.freepik.com/author/standret
* 'Events' Photo by Spencer Gurley Films from Pexels (Three Men Riding Kayaks On Body Of Water)
* 'Contact' Photo by cottonbro: https://www.pexels.com/photo/scouts-with-a-map-and-a-compass-9292813/
* Events page - High Ropes image: Photo by Mike van Schoonderwalt from Pexels
* Events page - Climbing image: Photo by Mike van Schoonderwalt from Pexels
* Events page - Gokart image:Photo by Tima Miroshnichenko from Pexels
* Events page - Climbing image: Photo by Tima Miroshnichenko: https://www.pexels.com/photo/a-girl-climbing-the-wall-5916172/
* Meetings page - badges Photo by Janneck Lange: https://www.pexels.com/photo/a-two-way-radio-mouthpiece-on-a-scout-collar-6768469/

* #SkillsForLife video sourced from https://www.youtube.com/watch?v=cMGyuucCmuY

## Content

* All content was written by myself using information from the official Scouts website https://www.scouts.org.uk/ and the Sunderland District webpage https://www.sunderlandscouts.org.uk/

## Acknowledgements

* Thank you to my mentor, Marcel, for helpful feedback, industry insights and recommended tools.
* Thank you to my friends, Jeanette and Chelsea and son, Ben, for participating in testing and review.
* Thank you to Eventyret_mentor, Simen Daehlin, for their suggestions during Peer Review of code on Slack.
* Thank you to the tutors and staff at Code Institute for their support. 