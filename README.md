# Explorer Scouts Website - Emma Scott


![mockups](/readme-images/testing/mockup.jpg "Mockup")

* St. John's Explorer Scouts are a group of over 20 Scouts who meet weekly from across Sunderland. The aim of the website is to appeal to current members and their parents, to attract new potential members to the group and to showcase the group's successes and activities. The website is designed to be responsive so that it is appealing and can be used on any device. 
* The website features five pages and has been built using HTML and CSS and Bootstrap.

## Live Project
[View the live project here.](https://emmajane22.github.io/explorer-scouts/ "View the Live project here")

___

# Table of Contents:
[1. User Experience (UX)](#ux)
  - [1.1 User Stories](#user-stories)
  - [1.2 External Users' Goals](#external-users)
  -	[1.3 Site Owners goals](#owner-goals)
  -	[1.4 Features to include](#features)

      
[2. Design Choices](#design)
  - [2.1 Colour Palette](#colour)
  - [2.2 Typography](#typography)
  - [2.3 Images](#images)

[3. Site Structure](#structure)
  - [3.1 Wireframes](#wireframes)
  - [3.2 Home Page](#home)
  - [3.3 Meeting Page](#meeting)
  - [3.4 Events Page](#events)
  - [3.5 Contact Page](#contact)
  - [3.6 Thank-you Page](#thank-you)
 
[4. Features](#sitefeatures)
  - [4.1 Navigation Bar](#nav)
  - [4.2 Hero Images](#hero)
  - [4.3 Gallery](#gallery)
  - [4.4 Video](#video)
  - [4.5 Form](#form)
  - [4.6 Footer](#footer)
  - [4.7 Future Features](#future)

[5. Technologies Used](#tech)

[6. Testing](#testing)
  - [6.1 Chrome DevTools](#devtools)
  - [6.2 Manual Testing](#manual)  
  - [6.3 W3C HTML](#w3chtml)
  - [6.4 W3C CSS](#w3ccss)
  - [6.5 Lighthouse](#lighthouse)
  - [6.6 Peer review](#peer-review)
  - [6.7 Contrast Checker](#contrast)

[7. Bugs & Fixes](#bugs)

[8. Deployment](#deployment)

[9. Credits](#credit)
  - [9.1 Code](#code)
  - [9.2 Images](#image-credit)
  - [9.3 Content](#content)
  - [9.4 Acknowledgements](#acknowledge)
 
<a name="ux"></a>
# 1. User Experience (UX)

<a name="user-stories"></a>
## 1.1 User stories

<a name="external-users"></a>
### 1.2 External Users' Goals:

* The site users are Explorer Scout members and potential members and their parents/carers, who want to know more about the Explorer Scout unit and its activities.

* External users may want to celebrate the Pack's achievements or to explore what events the Pack participates in.

* External users may want to be able to know when and where the group meet and be able to contact leaders directly to find out more information using an online form.

* External users may want to find out who can join Explorer Scout groups, age requirements and Scouting aims and the activities their child might take part in if they become an Explorer. 

<a name="owner-goals"></a>
### 1.3 Site Owner's Goals:

* The Explorer Scout group is interested in attracting new members as well as retaining current members.

* The group also wants to celebrate their successes and showcase their activities/events to a wider community, as parents and the public are not permitted to attend group sessions. Scouting officials from county level are also interested in viewing the group's activities.

* The site owner requires a simple contact form that people can use to ask questions.

<a name="features"></a>
### 1.4 Features to include:

* Showcase photos of members having fun at group activities.

* Provide details of the activities Explorer Scouts participate in and the structure of meetings.

* Provide information on the packs location, meeting times, contact details and any external resources (e.g. Scouts official website). 
___
<a name="design"></a>
# 2. Design Choices

<a name="colour"></a>
## 2.1 Colour Palette

![colour palette](/readme-images/colour_scheme.png)

- A simple colour scheme has been used. The teal colours echo the muted colours of the Explorer group's uniform. 

- The footer section has a colour gradient which adds visual appeal, made using a tutorial from W3Schools https://www.w3schools.com/css/css3_gradients.asp 

- I used https://color.adobe.com/ to decide on the colour scheme.

- The font colour and background colour for the header and body were checked for contrast on https://coolors.co/contrast-checker/ and scored '13.43 - super' showing the contrast makes the accessibility good. The contrast was checked for the footer and was scored '12.44 - Super'.

<a name="typography"></a>
## 2.2 Typography

- The 'Special Elite' font is used for the logo at the top of the site and for headings. Sans-serif is the fallback font in case the title font is not being imported correctly. 'Special Elite' adds character to the logo, as it creates an image of adventures.
- The 'Roboto' font is used for all other body text. It is a clean and easily legible font.

<a name="images"></a>
## 2.3 Images

- A consistent aspect ratio of 16:9 has been used for all of the hero images to bring consistency to the pages. 
- A square ratio has been used for the landing page circles to prevent stretch.
- I used Font Awesome icons for the social media information and contact information to give the user visual clues.

___
<a name="structure"></a>
# 3. Site Structure

The website has a Home page and four other pages. The initial wireframes for these can be found below.

<a name="wireframes"></a>
## 3.1 Wireframes

### 3.1.1 Site Map

![site map](/readme-images/wireframes/site-map.jpg "Site Map")

### 3.1.2 Landing Page

![landing page](/readme-images/wireframes/low-res-landing-page.png "Landing Page")

 
### 3.1.3 Meeting Page

![meeting page](/readme-images/wireframes/low-res-meeting-page.png "Meeting Page")

### 3.1.4 Events Page

![events page](/readme-images/wireframes/low-res-events-page.png "Events Page")

### 3.1.5 Contact Page

![contact page](/readme-images/wireframes/low-res-contact-page.png "Contact Page")

___
<a name="home"></a>
## 3.2 Home Page

![home page](/readme-images/page-screenshots/home-screenshot.jpg "Home page")

Page bottom

![home page bottom](/readme-images/page-screenshots/home-screenshot-2.jpg "Home page bottom")

The home page (index.html) is a simple landing page. It has a welcome message underneath the hero image and below that are three images in circle containers that are hyperlinks to the site pages, allowing very easy site navigation.

<a name="meeting"></a>
## 3.3 Meeting Page

![Meeting page](/readme-images/page-screenshots/meeting-screenshot-1.jpg "Meeting page")

Page bottom

![Meeting page bottom](/readme-images/page-screenshots/meeting-screenshot-2.jpg "Meeting page bottom")

The meeting page (meetings.html) provides clear information about meetings, joining the unit and the badges the unit works towards. There is an accompanying image for each block of text to make it visually appealing.

Beneath the rows of text is an embedded, responsive Google map linked to the groups address and the address is also next to the map to provide information easily and intuitively.  

<a name="events"></a>
## 3.4 Events Page

![Events page](/readme-images/page-screenshots/events-screenshot.jpg "Events page")

Page bottom

![Events page bottom](/readme-images/page-screenshots/events-screenshot-2.jpg "Events page bottom")

The events page (events.html) follows a similar layout to the meeting page, with clear informative text followed by an embedded YouTube video from the official Scouts YouTube channel. The page provides information about the activities the unit participate in and has an image gallery to showcase these.

<a name="contact"></a>
## 3.5 Contact Page

![Contact page](/readme-images/page-screenshots/contact-screenshot.jpg "Contact page")

The contact page (contact.html) provides a simple contact form for users to ask questions. The contact form is not active as I have not learnt this technology yet. The contact form was set to method GET after viewing a post on Slack regarding form methods: https://code-institute-room.slack.com/archives/C7J2ZAVHB/p1653483581074199

In order to do this, I created a copy of the index.html page but changed the content to have an acknowledgement of the form submission rather than going to the Code Institute page. If this site was to go live for the public, this would be changed. The form redirects to the thank-you.html page.

<a name="thank-you"></a>
## 3.6 Thank-you page

![Thank-you page](/readme-images/page-screenshots/thanks-screenshot.jpg "Thank-you page")

The contact form is set to direct to this page rather than the Code Institute form dump. It redirects users back to the site.

___
<a name="sitefeatures"></a>
# 4. Features

<a name="nav"></a>
## 4.1 Navigation Bar

All pages are accessible from the navbar apart from the thank-you.html as this is the form response. This allows the user to easily navigate the site without the need to return to the home page.
The navbar appears as a horizontal list on desktop and changes to a vertical drop-down menu on mobile.
The decision was made to not make the navbar sticky so that the user can see more on the page as they scroll down.
I used Bootstrap to produce the menu and added an underline for the active page and a hover state to non-active pages.

![navbar desktop](/readme-images/navbar.jpg "navbar")

![navbar mobile](/readme-images/navbar-mobile.jpg "navbar mobile")

<a name="hero"></a>
## 4.2 Hero Images

All pages feature a hero image across the top to create a consistent view. The hero images use different images on each page to reflect the content of that page.
The desktop contact page does not feature a hero image to create a greater focus on the form itself. The form has a background image instead with a semi-transparent overlay to maintain the branding. The mobile version has a hero image and the background image removed to increase the loading speed and because the impact of the background image was lost on a small screen.

- All images were compressed to allow faster loading using https://tinypng.com/
- Credit for all images can be found in the Credit section below.

<a name="gallery"></a>
## 4.3 Gallery

The events page (events.html) features a gallery of images showing the Explorers activities. This has been styled to appear as three columns on desktop pages, reduce to two columns on tablets and reduce to one column on mobiles.

<a name="video"></a>
## 4.4 Video

The events page (events.html) features an embedded YouTube video from the official Scouts YouTube channel. This has been styled to be responsive on all device sizes. It is also set to turn off autoplay and to set to mute.

<a name="form"></a>
## 4.5 Form

The contact page (contact.html) features a simple form that users can complete to send enquiries to the Explorer unit. The fields are all set to be required and the large text area features placeholder text. 
<a name="footer"></a>

## 4.6 Footer

The footer element links to social media channels and shows the phone number and email address for ease of contact.
It features a gradient colour for interest.

<a name="future"></a>
## 4.7 Future Features

* I will research using NextGen formats for images in future.
* In order to make the form action POST work, I need to learn the scripting behind the form.
* It was suggested in Peer Review that I make the page one scrolling page rather than separate pages. This is something I will consider for the future.

___
<a name="tech"></a>
# 5. Technologies Used

* HTML -used for structuring and presenting information on the website.
* CSS - used for styling the HTML code.
* Bootstrap v5.1.3 - used to improve the responsiveness of the site for access on different size devices.
* Balsamiq: Balsamiq was used to create wireframes for the project.
* Font Awesome: The project uses icons from Font Awesome version 6.
* Chrome DevTools: This featured heavily as I tested the site throughout to adjust sizing and spacing.
* Google Fonts: The fonts used have been imported from Google Fonts.

 ___
<a name="testing"></a>
# 6. Testing

The St John's Explorer Scouts website has been tested using the following methods:

<a name="devtools"></a>
### 6.1 Chrome Devoloper Tools

* I made use of the Developer Tools to aid debugging throughout the project to inspect my pages and make changes accordingly.

<a name="manual"></a>
## 6.2 Manual Testing

The following aspects were manually tested as I progressed through the project. I checked each element using the Live Server in Gitpod to confirm that what I expected to happen, happened successfully, and then also checked it in an incognito window with the cache cleared.
The following elements were manually tested:

### Navigation Bars

|TEST                  | DESIRED OUTCOME                      | PASS / FAIL  |
| -------------------- | --------------------------------     | ------------ |
| Home page | When 'Home' hyperlink clicked, the browder directs me to index.html. The hover effect (underline) appears when mouse is over hyperlink. The active page effect (underline) displays correctly underneath the Home link.      | PASS |
| Meeting Page | When 'Meeting' hyperlink clicked, the browder directs me to meeting.html. The hover effect (underline) appears when mouse is over hyperlink. The active page effect (underline) displays correctly underneath the Meeting link.     | PASS |
| Events Page | When 'Events' hyperlink clicked, the browder directs me to events.html. The hover effect (underline) appears when mouse is over hyperlink. The active page effect (underline) displays correctly underneath the Events link.     | PASS |
| Contact Page | When 'Contact' hyperlink clicked, the browder directs me to contact.html. The hover effect (underline) appears when mouse is over hyperlink. The active page effect (underline) displays correctly underneath the Contact link.     | PASS |
| Thank you Page | When any hyperlink clicked, the browder directs me to the correct page. The hover effect (underline) appears when mouse is over hyperlink. The active page effect (underline) should not be displayed.     | PASS |
| All pages | All pages responsive using DevTools to resize the screen size for mobile to desktop.     | PASS |
| Background Colour | The background colour does not distract from the text.     | PASS |
| Text Colour | The text colour significantly contrasts to the background colour to allow good accessibility.     | PASS |
| Font-style | The logo font displays as Special Elite and the menu links font appears as Roboto.     | PASS |


### Footer

|TEST                  | DESIRED OUTCOME                      | PASS / FAIL  |
| -------------------- | --------------------------------     | ------------ |
| Background Colour | The background colour does not distract from the text. The colour gradient does not distract from the text.     | PASS |
| Text Colour | The text colour contrasts to the background colour to allow good accessibility.     | PASS |
| Font-style | The heading font displays as Special Elite and the paragraph font appears as Roboto.     | PASS |
| Icons | The Font Awesome icons display as the expected size and colour.     | PASS |
| Social Media Icons | The Font Awesome icons link to the correct social media pages.     | PASS |


### Home Page

|TEST                  | DESIRED OUTCOME                      | PASS / FAIL  |
| -------------------- | --------------------------------     | ------------ |
| Text Colour | The text colour contrasts to the background colour to allow good accessibility.     | PASS |
| Font-style | The heading font displays as Special Elite and the paragraph font appears as Roboto.     | PASS |
| Hero Image | The image covers the width of the screen and is the specified height. The image loads quickly on desktop and mobile. The image is responsive and resizes for different devices.     | PASS |
| Links on circular images | The images are displayed as circles with a border. A transparent overlay and the hyperlink text appears when hovered over. Each circle links to the correct page. The layout of the circles changes on different size devices - 3 columns on desktop, 2 on tablet and 1 column on mobile. The image is static on mobile devices but the animation works on larger devices. | PASS |
| Welcome message | The text is centered on the screen.     | PASS |

### Meeting Page

|TEST                  | DESIRED OUTCOME                      | PASS / FAIL  |
| -------------------- | --------------------------------     | ------------ |
| Text Colour | The text colour contrasts to the background colour to allow good accessibility.     | PASS |
| Font-style | The heading font displays as Special Elite and the paragraph font appears as Roboto.     | PASS |
| Hero Image | The image covers the width of the screen and is the specified height. The image loads quickly on desktop and mobile. The image is responsive and resizes for different devices. The image is static on mobile devices but the animation works on larger devices. | PASS |
| Google Map | Map shows the correct area and resizes on different devices.      | PASS |
| External Link | Link goes to the correct site. Link opens in a new browser window.      | PASS |

### Events Page

|TEST                  | DESIRED OUTCOME                      | PASS / FAIL  |
| -------------------- | --------------------------------     | ------------ |
| Text Colour | The text colour contrasts to the background colour to allow good accessibility.     | PASS |
| Font-style | The heading font displays as Special Elite and the paragraph font appears as Roboto.     | PASS |
| Hero Image | The image covers the width of the screen and is the specified height. The image loads quickly on desktop and mobile. The image is responsive and resizes for different devices. The image is static on mobile devices but the animation works on larger devices. | PASS |
| YouTube video | The video does not autoplay and is muted. It resizes on different devices. It links to the correct video.  | PASS |
| Gallery | The image gallery displays as one column on mobile, two on tablet and three on desktop. The images are aligned with each other. The images load quickly and are not pixelated. | PASS |

### Contact Page

|TEST                  | DESIRED OUTCOME                      | PASS / FAIL  |
| -------------------- | --------------------------------     | ------------ |
| Text Colour | The text colour contrasts to the background colour to allow good accessibility.     | PASS |
| Background image | The background image covers the container. It is hidden on mobile devices.     | PASS |
| Hero Image | The hero image is hidden on tablet and desktop devices but displays on mobile devices. The image covers the width of the screen and is the specified height. The image loads quickly. The image is static. | PASS |
| Form | The form is centered. The background area is transparent. The font can be easily read on the background. The placeholder text is displayed. The submit button directs the form to the Thank-you page. All fields are required.  | PASS |

### Thank You Page

|TEST                  | DESIRED OUTCOME                      | PASS / FAIL  |
| -------------------- | --------------------------------     | ------------ |
| Text Colour | The text colour contrasts to the background colour to allow good accessibility.     | PASS |
| Background image | The background image covers the container. It is hidden on mobile devices.     | PASS |
| Hero Image | The image covers the width of the screen and is the specified height. The image loads quickly on desktop and mobile. The image is responsive and resizes for different devices. The image is static on mobile devices but the animation works on larger devices. | PASS |
| Acknowledgment message | The message is centered and displayed in the Special Elite font. All links direct to the correct page. | PASS |

___

## Code Validation

<a name="w3chtml"></a>
### 6.3 W3C HTML Validator

The HTML code for all pages was tested using W3C Validator. It was validated by direct input.

![w3c home](/readme-images/testing/w3chome.jpg "W3C Validator screenshot home")

![w3c meeting](/readme-images/testing/w3cmeeting.jpg "W3C Validator screenshot meeting")

![w3c events](/readme-images/testing/w3cevents.jpg "W3C Validator screenshot events")

![w3c contact](/readme-images/testing/w3ccontact.jpg "W3C Validator screenshot contact")

![w3c thank-you](/readme-images/testing/w3cthankyou.jpg "W3C Validator screenshot thankyou")

The pages all passed the validator with no errors apart from the events page which had a warning that an article lacks a heading. 

<a name="w3ccss"></a>
### 6.4 W3C CSS Validator

The CSS code was tested using Jigsaw W3C CSS Validator. It was validated by direct input and passed all checks.

![css](/readme-images/testing/jigsawvalidator.jpg "CSS Validator screenshot")

<a name="lighthouse"></a>
### 6.5 Lighthouse - Desktop

I used the Lighthouse reports in Google DevTools to examine the desktop pages of the website for:
* Performance
* Accessibility
* Best Practices
* SEO

Every page was reported as 'good' for all areas. 

index.html

![lighthouse desktop home screenshot](/readme-images/testing/lighthouse-home-desk.jpg "Lighthouse desktop home screenshot")


meetings.html:

![lighthouse desktop meetings screenshot](/readme-images/testing/lighthouse-meeting-desk.jpg "Lighthouse desktop meetings screenshot")

events.html:

![lighthouse desktop events screenshot](/readme-images/testing/lighthouse-events-desk.jpg "Lighthouse desktop events screenshot")

contact.html:

![lighthouse desktop contact screenshot](/readme-images/testing/lighthouse-contact-desk.jpg "Lighthouse desktop contact screenshot")

### Lighthouse - mobile

I used the Lighthouse reports in Google DevTools to examine the mobile pages of the website for:
* Performance
* Accessibility
* Best Practices
* SEO

The results for all pages came back as 'good' for all areas.

index.html

![lighthouse mobile home screenshot](/readme-images/testing/lighhousehome.jpg "Lighthouse mobile home screenshot")


meetings.html:

![lighthouse mobile meetings screenshot](/readme-images/testing/lighhousemeetings.jpg "Lighthouse mobile meetings screenshot")

events.html:

![lighthouse mobile events screenshot](/readme-images/testing/lighthouseevents.jpg "Lighthouse desktop mobile screenshot")

contact.html:

![lighthouse mobile contact screenshot](/readme-images/testing/lighthousecontact.jpg "Lighthouse mobile contact screenshot")

<a name="peer-review"></a>
## 6.6 Peer Review

The project was shared to Slack for peer review and the following changes were made:

* the images for readme.md were moved to their own folder not in assets.
* font sizes were changed to rem.
* the hero image animation was removed on the mobile pages.
* 'integrity' and 'cross origin' code was removed to improve performance.

<a name="contrast"></a>
## 6.7 Contrast Checker

The colours used in the site were checked for contrast using https://coolors.co/contrast-checker/ and results were 'super'.

___
<a name="bugs"></a>
# 7. Bugs & Fixes:

* When I produced the pages originally I worked from desktop down. This created the need for a lot of media queries which I initially added, however I wasn't happy with the amount of queries needed so decided to rewrite all of the pages starting from mobile-first and using more Bootstrap code to make the elements much more responsive on larger devices. This was a major fix which took a large amount of time, but I am much more satisfied with the end product.

* When I made some final checks to the responsiveness of the pages, I discovered my logo was a broken link as I had a typing error in the link. I fixed this by correcting the typing error.

* During testing, I realised the YouTube video was not resizing on different size devices. I sourced code from https://getbootstrap.com/docs/4.0/utilities/embed/ to fix this and allow it to resize.

* During my middle mentor meeting, we realised the YouTube video was auto-playing. I sourced code from https://www.w3schools.com/html/html_youtube.asp to prevent it auto-playing.

* While producing the header containing the logo and nav links, I noticed that the logo was pushing the menu links out of alignment when the screen was resized. I decided to use a 'hamburger' menu instead and sourced a tutorial from https://getbootstrap.com/

* During my middle mentor meeting, we realised the hero images were loading slowly, so I fixed this by reducing the image size and compressing the images using tinypng.com. The lower resolution hero images load much faster.

* Friends and family were asked to test the site and discovered the photos did not display on events.html. This was due to a missing end tag, which fixed the problem.

* After running W3C html validator I discovered that the events.html page didn't display. This was fixed by adding in an end section tag which was missing.

* After running the Lighthouse check, it recommended changing to the latest versions of Bootstrap (v. 5.1.3), therefore I updated my code to this version. This then prevented the hamburger menu working on mobile view. I fixed this by checking the code against the code sourced on getbootstrap.com and found the toggler class needed BS adding. Then then fixed the problem and allowed the hamburger menu to expand again.

* An initial Lighthouse report for the Contact page showed a missing form label, which I fixed.

* The lighhouse reports showed that I needed to update the version of Bootstrap. Updating this to version 5.1.3 resolved this issue.

* To improve the Performance score on Lighthouse on the mobile versions of all pages, I removed the hero image animation which was slowing loading speed.

* Following peer review, I changed the font size specification to rem.

* Following peer review, I removed 'integrity' and 'crossorigin' code from all pages.

___
<a name="deployment"></a>
# 8. Deployment

The project was deployed using these steps:

1. Create a repository: Go to GitHub and create a public repository named username.github.io. Make the username your username on GitHub.
2. Go to your repository.
3. On top right click Settings.
4. Scroll down to GitHub Pages, select main/master branch from the dropdown and press save.
5. A link will be generated for your live site.

___
<a name="credit"></a>
# 9. Credits

<a name="code"></a>
## 9.1 Code

* The initial code for the header, footer and circle images/containers was taken from the Code Institute Love Running project.

* Help centring the images on the Landing page circles was found here: https://stackoverflow.com/questions/32477563/how-can-i-fit-images-into-circles-without-stretching

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

<a name="image-credit"></a>
## 9.2 Images

Most images were sourced from the open source website, pexels.com
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

<a name="content"></a>
## 9.3 Content

* All content was written by myself using information from the official Scouts website https://www.scouts.org.uk/ and the Sunderland District webpage https://www.sunderlandscouts.org.uk/

<a name="acknowledge"></a>
## 9.4 Acknowledgements

* Thank you to my mentor, Marcel, for helpful feedback, industry insights and recommended tools.
* Thank you to my friends, Jeanette and Chelsea and son, Ben, for participating in testing and review.
* Thank you to Eventyret_mentor, Simen Daehlin, for their suggestions during Peer Review of code on Slack.
* Thank you to the tutors and staff at Code Institute for their support. 