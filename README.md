
# The Monkees - A responsive mobile first band website design.

## Link to the website 
https://deganoth.github.io/the-monkees-band-website/

## What is this?

This is project aimed at desiging a fully responsive mobile first designed web application. The styling is that of a 60's era band. The project requested a means of contact for their fans, social media links, and to showcase their music online, along with being able to book the band for upcoming events.

## UX

Since the website was initially aimed at people of an older generation, large fonts with easy to navigate areas were chosen. Fans want to acces band media, and stay up to date via email or social media. What the band wants is to make themselves available to play to their fans. 
During the [wireframe mockup](https://imgur.com/a/rSrGeYD), I decided on a one page design. For the user, it means they never have to leave the page with everything they need on it. Each section rolls on to the next and with mobile centric design in mind, a button linking back to the home menu at the bottom of each section allows the user to get back to the menu at all times. This was a later addition made after testing on multiple screen sizes.

### Design/ Functionality
<img src="https://juiceboxinteractive.com/app/uploads/2018/06/1960s-Color-Palette.png" width=350 style="display: block; float: left; padding-right: 30px;">
Rounded edges, a colour palette from the 60's with faded background image. These style choices make the website more familiar to older fans. The color palette shown was the primary palette for this site. 
The website is a three page design. A primary page for all content, and two "thank you" pages linked to both forms. A "Back to Home" button sits at the bottom of each section linking back to the main menu. Form one is modal requesting and email address for a fan club signup. Form two is a booking form requesting a name, email and details regarding an event. Both forms work correctly. 

## Features

#### 1. Navbar
The navbar menu is fixed to the top of the primary page. In desktop mode it is a scrolling menuwhich follows to each section. On mobile, tablet and notebooks the menu is fixed in place above the home content. It's scaling ability is controlled by the grid system of v4.1.3 of Bootstrap.
#### 2. Return Home Button
A button is appears on screens smaller than 1280px. It allows the user to select any main menu item and instantly have a way to return to the main menu. It deisplays as a small button on the bototm right of the screen and activates within 20px of movement from the top of the webpage. This feature makes use of a W3Schools javscript example.
#### 3. Footer
This section includes an additional fanclub signup option, a futher booking option, and all social media links. The fanclub signup activates a modal requesting and email address. The booking button brings the user to the booking form at the bottom of the main page. Each social medai icon changes color on hovering, and when clicked opens a new page directly to the associated platform and profile. The modal was created using the same code form teh Whiskey bootstrap bootcamp module of the course. 
#### 4. Smooth Scrolling Webpage
To stick with the one page design, a smooth scrolling script was used. An assigned ID with a # symbol in front was associated with each page section. A link to each page section was assigned to each main menu item. Once clicked, the respective menu item scrolls to it's assocaited page section. The timing is set to 800 milliseconds by default. This along with the jQuery animate function allows for smooth scrolling. 
#### 5. Home section
With bootstrap's grid system in use, a flexible two column design was used. labelled "top" and "botton" sections for mobile design reasons, the otp section shows a band logo with a paragraph linking to each feature of the page. In the bototm section, a fanclub signup modal call to action is available.
#### 6. Music section
This area shows 4 embeded music tracks in the top section, and one video in the bottom section. Each track has a background image of the assocaited song, and the video container is fully scalable to any device screen size. 
#### 7. About section
A collection of band photos along with a short bio of each member adds a personal touch to the website. While showcasing the photos supplied by the band, it also shares a short career history of each member.
#### 8. Booking section
With a band image on one side and a booking form on the other, this area allows the user to send details to the band regarding events they wish to book them for. 
#### 9. Thank you Pages
These pages are linked to both the fanclub sign up, and booking form submit pages. They have the same layout as the home section, with only one column showing a band logo, and a thank you message.

## Technologies Used for Development

### Development

##### HTML5/CSS3
These tools were used to create the basic layout and style of each element on the webpage
##### Cloud9 - https://c9.io/
This is a rapid prototyping platform for developers. It allowed me to test any additions or changes made to my code.
##### Bootstrap v4.1.3 - https://getbootstrap.com/
As an extensive library for CSS3, jQuery and Javascript, this allowed me to write less unique CSS, and use exisiting functional templates accepted across all browsers. 
##### Fontawesome - Social Links - https://fontawesome.com/icons?d=gallery
I made use of this for social icons. It has a vast collection of fonts, icons and images available for use. 
##### Google Fonts - https://fonts.google.com/
I found my font here. It has a huge collection of freely available fonts for use in such projects. I chose "Righteous"
##### Git/GitHub - https://github.com/deganoth
I made use of this to host my project. I communicated via Cloud9 and shared all project files and folders, including this file.
##### JavaScript - https://www.javascript.com/
For some simple animation and interactivity on the webapage, I use this. I added the smooth scrolling, floating "Top" button. 
##### jQuery - https://jquery.com/
This was added via google api. It intergrates with JavScript and Bootstrap to make them available for use.

### Testing
##### Sublime - https://www.sublimetext.com/
While struggling with image filepaths, I copied my script to this editor and downloaded the website content. It allowed my to discover the absolute file paths were not accepted by GitHub. Cloud9 allows short hand referencing. I resolved this conflict with local testing.
##### Firefox/Chrome Developer tools
Through the many iterations of section scaling, I made use of the inspector tool to determine correct choices, and which CSS classes were at play. 
##### Manual User Tests
To check functionality of all parts, I made use of the webpage as a typical user would. I ran into issues with the sign up modal, and booking form buttons. I made use of the Bootstrap Bootcamp to see what order a HTML file requires Javascipt items to be placed. 
##### Screenfly - http://quirktools.com/screenfly/
I found this tool most useful and somewhat more detailed than the browser developer tools. It included smaller notebook and latop screen sizes. This allowed my to see flaws in my layout regarding floating navabars and footers. Sizes were altered to suit smaller screens.
With the help of friends and work collegues I determined the ease-of-use on the following devices. 
* iPhone 5 - 8 
* Samsung Galax7 S5, S7, S8
* ChromeBook 10"
* iPad Mini
* iPad Pro
* iPad 2

## Deployment
I made use of GitHub to deploy this project. The link is shown above in this project, along with my cloud9 Developer link. The image file paths are different, as discussed above when referencing Sublime.

## Solutions found
With the help of my Mentor, **Spencer Bariball**, I found solutions to the folloing issues, with the listed links.

Scrolling effect - W3 Schools - JjQuery Script with adjustable parameters for scoll time
* https://www.w3schools.com/howto/howto_css_smooth_scroll.asp#section1 

A fixed footer for making a frame of information around each window
* https://stackoverflow.com/questions/4069734/fixed-header-footer-with-scrollable-content

Image filepaths changed between prototype and github repository.

* Cloud9 - /images/monkees-newsize.jpg
* Github - /the-monkees-band-website/images/monkees-newsize.jpg

Modal use taken from Bootstrap- Bootcamp project.

Back to top button - W3Schools
* https://www.w3schools.com/howto/howto_js_scroll_to_top.asp

band details from https://en.wikipedia.org/wiki

https://juiceboxinteractive.com/blog/color/ color palette

## Credits

* My Mentor, **Spencer Bariball** for showing me the ropes, and being a great teacher. 
* https://wikipedia.org/ - Used to get information about each member of the band.
* https://www.w3schools.com/ - An invaluable resource to problem solving and troubleshooting.
* https://codeinstitute.net/ - For making this possible.