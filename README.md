# Explorer Scouts Website - Emma Scott

# DIWAD_MS1: Diploma in Web Development: Milestone Project 1

ADD MOCKUPS

* St. John's Explorer Scouts are a group of over 20 Scouts who meet weekly from across Sunderland. The aim of the website is to appeal to current members and their parents, to attract new potential members to the group and to showcase the group's succeses and activities. The website is designed to be responsive so that it is appealing and can be used on any device. 
* The website features four pages and has been built using HTML and CSS and Bootstrap.

## Live Project
[View the live project here.](https://www.google.com "View the Live project here")

## Repository
[View the project repository here.](https://github.com/EmmaJane22/explorer-scouts.git "View the project repository here")
___

# Table of Contents:

 
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

## Design Choices
### Colour Palette

![colour palette](assets/readme/colour_scheme.png)

- A simple colour scheme has been used. The teal colours echo the muted colours of the Explorer group's uniform. 

- The footer section has a colour gradient which adds visual appeal, made using a tutorial from W3Schools https://www.w3schools.com/css/css3_gradients.asp 

- I used https://color.adobe.com/ to decide on the colour scheme.

### Typography
- The 'Special Elite' font is used for the logo at the top of the site and for headings. Sans-serif is the fallback font in case the title font is not being imported correctly. 'Special ELite' adds character to the logo, as it creates an image of adventures.
- The 'Roboto' font is used for all other body text. It is a clean and easily legible font.

### Images

- A consistent aspect ratio of 16:9 has been used for all of the hero images to bring consistency to the pages. 

___

## Wireframes

### Site Map
![site map](assets/images/wireframes/site-map.jpg "Site Map")

### Landing Page
![landing page](assets/images/wireframes/low-res-landing-page.png "Landing Page")

### Meeting Page
![meeting page](assets/images/wireframes/low-res-meeting-page.png "Meeting Page")

### Events Page
![events page](assets/images/wireframes/low-res-events-page.png "Events Page")

### Contact Page
![contact page](assets/images/wireframes/low-res-contact-page.png "Contact Page")

___

## Features

#### Navigation Bar

- Code sourced from the Code Institute Whiskey Drop tutorial.

- Hover effects sourced from https://stackoverflow.com/questions/58939609/bootstrap-4-nav-link-hover-effect
#### The Header
#### Hero Images
- Images were compressed to allow faster loading using https://tinypng.com/

#### The Footer
#### Landing Page
#### Meetings Page
#### Contact Us Page
 
# Technologies Used
 
# Testing
## Testing Results:

## Bugs & Fixes:

* When I produced the pages originally I worked from desktop down. This created the need for a lot of media queries which I initally added, however I wasn't happy with the amount of queries needed so decided to rewrite all of the pages starting from mobile-first and using more Bootstrap code to make the elements much more responsive on larger devices. This was a major fix which took a large amount of time, but I am much more satisfied with the end product.

* When I made some final checks to the responsiveness of the pages, I discovered my logo was a broken link as I had a typing error in the link. I fixed this by correcting the typing error.

* During testiing, I realised the YouTube video was not resizing on different size devices. I sourced code from https://getbootstrap.com/docs/4.0/utilities/embed/ to fix this and allow it to resize.

* During my middle mentor meeting, we realised the YouTube video was auto-playing. I sourced code from https://www.w3schools.com/html/html_youtube.asp to prevent it auto-playing.

* While producing the header containing the logo and nav links, I noticed that the logo was pushing the menu links out of alignment when the screen was resized. I decided to use a 'hamburger' menu instead and sourced a tutorial from https://getbootstrap.com/

* During my middle mentor meeting, we realised the hero images were loading slowly, so I fixed this by reducing the image size and compressing the images using tinypng.com. The lower resolution hero images load much faster.

 
# Deployment

# Future Implementations 

# Credits

## Code

* The initial code for the header, footer and circle images/containers was taken from the Code Institute Love Running project.

* Help centering the images on the Landing page circles was found here: https://stackoverflow.com/questions/32477563/how-can-i-fit-images-into-circles-without-stretching

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
* Thank you to my friends, Jeanette and Chelsea and brother, Ian, for participating in testing and review.
* Thank you to the tutors and staff at Code Institute for their support. 