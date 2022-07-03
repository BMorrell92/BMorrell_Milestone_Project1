# Jams Galatica FM

JAMS Galatica FM is a project conceived by my friend, and it is his aspiration to turn a hobby of mixing music and DJing into a digital radio station. The primary purpose of this site is to showcase a variety of music mixes and other media content. Furthermore, information about upcoming events and contact forms can be found here. JAMS Galactica FM targeted audience is as follows:
- Anyone that enjoys listening to a particular genre of electronic music and would like a centralised location to check out music mixes and view videos and photos. 
- Event organisers that may be interested in booking my friend to play at their events.
- Music producers that would like their tracks to be showcased. 

JAMS Galatica FM features three pages and is a fully responsive website, meaning the layout will be adjusted according the device it is being viewed on. This is my Milestone Project 1 submission for Code Institute's Diploma in Web Application Development course.

![Device Emulator](https://github.com/BMorrell92/BMorrell_Milestone_Project1/blob/main/assets/images/emulator-mockup.JPG)

It should be noted, that this is currently a concept website. The JAMS Galatica FM project as a whole is still in it's infancy stage, which means much of the content intended for the website is still a working progress. For purposes of this submission, the work of others or repeating content has been used. However, the principal purpose of the website has been displayed, and new content can easily be added once it is readily available.

## Contents
- [User Stories](#user-stories)
    + [Electronic Music Listeners](#electronic-music-listener)
    + [Events Organisers](#events-organisers)
    + [Music Producers](#music-producers)
    + [JAMS Galatica FM Creator](#jams-galatica-fm-creator)
- [Website Structure and Features](#Website-Structure-and-Features)
  + [Wireframes](#wireframes)
  + [Website Architecture](#website-architecture)
  + [Current Feautures](#current-features)
  + [Future Feautures](#future-features)
- [Technologies and Libaries Used](#Technologies-and-Libaries-Used)
- [Testing](#testing)
  + [Validator Testing](#validtor-testing)
  + [Browser Compatability](#browser-compatability)
  + [Device Compatability](#device-compatability)
  + [Challenging User Stories](#Challenging-User-Stories)
  + [User Feedback](#User-Feedback)
- [Deployment](#deployment)
- [Credits](#credits)
  + [Content](#content)
  + [Media](#media)

## User Stories

### Electronic Music Listener 

These are mainly users that are familiar with the work of the JAMS Galatica FM creator and would like a one stop shop to listen or watch his work. They would also like to keep informed about any upcoming events they may be interested in tuning into or attending.

* As a listener I would like to access the latest mixes. 
* As a listener I would like to access to a full mix discography.
* As a listener I would like to watch any recorded sessions.
* As a listener I would like to keep up to date with any events that I may be nterested in tuning into or attending.
* As a listener I may wish to view photos from past events.

### Events Organisers 

These are users who may be interested in booking the creator of JAMS Galatica FM for an event.

* As an event organiser I would like to listen to or watch a selection of mixes to assess if the music style will suit my event and the quality of work is satisfactory.   
* As an event organiser I would like to get in touch to discuss the potential for work opportunities. 

### Music Producers

These are users who create electronic music and would be interested in getting their work showcased.

* As a music producer I would like to listen to or watch a selection of mixes to assess if my work will be suitable to be showcased.
* As a music producer I would like to get in touch to discuss the potential for showcasing my work. 

### JAMS Galatica FM Creator

This is the JAMS Galatica FM creator who would like a centralised location to showcase his work to an audience.

* As the JAMS Galatica FM creator I would like my work to be easily accessible from any device.
* As the JAMS Galatica FM creator I would like to introduce new audience members to my project and give them a snapshot of my work.
* As the JAMS Galatica FM creator I would like to showcase all of my Soundcloud and Youtube mixes.
* As the JAMS Galatica FM Creator I would like to keep my audience informed about upcoming events.
* As the JAMS Galatica FM Creator I would like to share photos from past events.
* As the JAMS Galatica FM creator I would like to give people the possibility to get in touch about work opportunities.

## Website Structure and Features

### Wireframes

[View my wireframes in PDF format here.](https://github.com/BMorrell92/BMorrell_Milestone_Project1/blob/main/assets/wireframe/Wireframes.pdf)

### Website Architecture

- __General__

The website has a total of three pages; Home, Media and Contact. The content on the Home and Media pages have been structured in a rule of thirds grid. Content which doesn't require much space takes up a third of the page, and content requiring a larger amount of space take up two thirds of the page. 

- Home: This is the landing page and provides a breif introduction about the project and what to expect from the website. The landing page also hosts the Soundcloud Mixes, Upcoming Events, and latest recorded session. This page will be updated as the times change to keep the user up to date. 

![Home Page](https://github.com/BMorrell92/BMorrell_Milestone_Project1/blob/main/assets/images/website_home.JPG)

- Media: On the media page the user can dive into a more comprehensive selection of Soundcloud mixes, recorded sessions and can view photos from past events. This section will be updated as the times change to keep the user up to date.

![Media Page](https://github.com/BMorrell92/BMorrell_Milestone_Project1/blob/main/assets/images/website_media.JPG)

- Contact: This page features the contact form to allow the user to get in touch.

![Contact Page](https://github.com/BMorrell92/BMorrell_Milestone_Project1/blob/main/assets/images/website_contact.JPG)

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Home page, Media page, Contact form, and Upcoming and is identical on each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](https://github.com/BMorrell92/BMorrell_Milestone_Project1/blob/main/assets/images/website_nav_bar.JPG)

- __Website Title Banner__

  - Featured on all three pages, the Title Banner covers the full width and includes a GIF with the title as text overlay to introduce the name of the project. 
  - This section introduces the user to JAMS Galatica FM with a fun and eye-catching animation to grab their attention and sets a "Cosmic" tone to the website.

![Title Banner](https://github.com/BMorrell92/BMorrell_Milestone_Project1/blob/main/assets/images/website_title_banner.JPG)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for JAMS Galatica FM. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media

![Footer](https://github.com/BMorrell92/BMorrell_Milestone_Project1/blob/main/assets/images/website_footer.JPG)

### Current Features

- __Responsive Design__

 - By designing with a Mobile First philosophy JAMS Galatica FM can be viewed on any device, adjusting the layout according to the device.  
 - Bootstrap grid systems and flex classes have been used to acheive the responsive design.

 - __Interactive Features__

 - Soundcloud Iframe on the Home and Media pages. The user can scroll through the mix tracklist, select songs, and play and pause.
 - Youtube Iframe on the Home and Media pages. The user can play, pause and skip ahead.
 - Contact form to allow the user to input relevant information and submit it to be viewed.

### Future Features

- An interactive events timeline that allows the user to select indvidual elements and get further information about events.
- A blog section to share insights and updates with users.
- E-commerce section to advertise and sell merch.

## Technologies and Libaries Used
1. [HTML5](https://www.w3.org/TR/html52/)
2. [CSS3](https://www.w3.org/Style/CSS/Overview.en.html)
3. [Bootstrap framework for structuring](http://getbootstrap.com/)
4. [Github for Repo creation and managment](https://github.com/)
5. [Gitpod for file creation and code editing](https://gitpod.io/)
6. [Balsamiq was used to create Wireframes for the project](https://balsamiq.com/)
7. [Google Chrome's Dev Tools were used while building the project to test responsiveness and for debugging](https://developer.chrome.com/docs/devtools/)
8. [The icons used were taken from Font Awesome](https://fontawesome.com/)

## Testing 

### Validator Testing 

- HTML:
  - index.html: 0 errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fbmorrell92.github.io%2FBMorrell_Milestone_Project1%2Findex.html).
  - media.html: 0 errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?showsource=yes&showimagereport=yes&doc=https%3A%2F%2Fbmorrell92.github.io%2FBMorrell_Milestone_Project1%2Fmedia.html). 
  - contact.html: 0 errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fbmorrell92.github.io%2FBMorrell_Milestone_Project1%2Fcontact.html)

- CSS:
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fbmorrell92.github.io%2FBMorrell_Milestone_Project1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

- Errors Fixed During Validator Testing:
  - After initially testing the Home and Media pages, errors were being returned in relation to the width attribute on the Soundcloud and Youtube Iframes. These errors were solved by using CSS to define the width and height attributes.

### Browser Compatability
The website has been tested on the following browsers:

- Chrome
- Edge/IE
- Firefox
- Opera
- Safari

The wesbite and all it's functionalities work as intended on all broswers. 

### Device Compatability
By using Google Chrome's Dev Tool, compatability was checked on the following devices:

- IPhone SE
- IPhone XR
- IPhone 12 Pro
- Pixel 5
- Samsung Galaxy S8+
- Samsung Galaxy Ultra S20 Ultra
- Surface Pro 7
- IPad
- IPad Pro

It was found that on some devices the contact page was too short and the footer was not at the bottom of the page. This was fixed by adding bottom padding to the contact form. The website was found to be responsive on all devices.

### Challenging User Stories 

- __Electronic Music Listener__

- *"As a listener I would like to access the latest mixes"* - **A latest Soundcloud mix section is available on the Home page.**
- *"As a listener I would like to access to a full mix discography"* - **A full Soundcloud mix discography section is available on the Media page.**
- *"As a listener I would like to watch any recorded sessions"* - **A latest Recorded session section is available on the Home page and a full catalougue of recorded sessions are available on the media page.**
- *"As a listener I would like to keep up to date with any events that I may be interested in tuning into or attending"* - **An events timeline is available on the Home page.**
- *"As a listener I may wish to view photos from past events"* - **A gallery section is available on the Media page.**

- __Events Organiser__

- *"As an event organiser I would like to listen to or watch a selection of mixes to assess if the music style will suit my event and the quality of work is satisfactory"* - **The user could listen to mixes from the Home page and Media page. In addition the user can view recorded sessions from both the Home and Media pages.**
- *"As an event organiser I would like to get in touch to discuss the potential for work opportunities"* - **A contact form is available on the Contact page.**

- __Music Producer__

- *"As a music producer I would like to listen to or watch a selection of mixes to assess if my work will be suitable to be showcased"* - **The user could listen to mixes from the Home page and Media page. In addition the user can view recorded sessions from both the Home and Media pages.**
- *"As a music producer I would like to get in touch to discuss the potential for showcasing my work"* - **A contact form is available on the Contact page.**

- __JAMS Galatica FM Creator__

- *"As the JAMS Galatica FM creator I would like my work to be easily accessible from any device"* - **The website has been designed to be accessible from any device.**
- *"As the JAMS Galatica FM creator I would like to introduce new audience members to my project and give them a snapshot of my work"* - **The home page introduces the vistor to my project and lets the view my latest mixes and recorded session.**
- *"As the JAMS Galatica FM creator I would like to showcase all of my Soundcloud and Youtube mixes"* - **A full Soundcloud mix discography section is available on the Media page.**
- *"As the JAMS Galatica FM Creator I would like to keep my audience informed about upcoming events"* - **An events timeline is available on the Home page.**
- *"As the JAMS Galatica FM Creator I would like to share photos from past events"* - **A gallery section is available on the Media page.**
- *"As the JAMS Galatica FM creator I would like to give people the possibility to get in touch about work opportunities"* - **A contact form is available on the Contact page.**

### User Feedback

I asked a small cohort of friends - potential users - to test the website and provide feedback. The initial feedback was as follows:

- The Home Page contains too little content.
- The title text color doesn't have sufficient contrast with the title banner GIF.
- The section scrolling features on the Media Page does not feel right when viewing on a mobile.
- The Media page should also contain a Recorded Session section to post sessions that have been recorded.
- The Events Timeline doesn't really need a dedicated page.

The following changes were made after receiving user feedback:

- The events timeline was moved to the homepage.
- An extra section titled "Latest Recorded Session" was added to the homepage.
- The title text color was changed to provide a deeper contrast from the backgrounf GIF.
- The section scrolling features were on the media page were removed.
- A "Recorded Sessions" section was added to the media page.


## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the main Branch
  - Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://bmorrell92.github.io/BMorrell_Milestone_Project1/ 
The Github repo can be found here - https://github.com/BMorrell92/BMorrell_Milestone_Project1

## Credits 

I would like to credit Code Institute for providing easy to follow content and all the necassary source code from their tutorials. The structure of JAMS Galatica FM was heavily based on the Resume mini project. Other functionalities added to the website were taken from open source content available online. 

### Content 

- The icons used were taken from [Font Awesome](https://fontawesome.com/)
- The main website structure and code used for this project has been duplicated from the Code Institutes Resume website mini project. Various styling and layout changes have been made to repurpose the website specific to this project.
- The footer code used for this project has been dulicated from the Code Institutes Love Running website mini project.
- The source code for the gallery layout of Media page was taken from https://mdbootstrap.com/docs/standard/extended/gallery/

### Media

- The GIFs used for the Title Banner and Events page were taken from open source website https://giphy.com/explore/open-source




