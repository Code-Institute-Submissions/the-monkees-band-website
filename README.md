
# The Monkees - A responsive mobile first band website design.

## Link to the website 
https://deganoth.github.io/the-monkees-band-website/

## What is this?

This is project aimed at desiging a fully responsive mobile first designed web application. The styling is that of a 60's era band. The project requested a means of contact for their fans, social media links, and to showcase their music online, along with being able to book the band for upcoming events.

## UX

Since the website was initially aimed at people of an older generation, large fonts with easy to navigate areas were chosen. Fans want to acces band media, and stay up to date via email or social media. What the band wants is to make themselves available to play to their fans. 

During the [wireframe mockup](https://imgur.com/a/rSrGeYD), I decided on a one page design. For the user, it means they never have to leave the page with everything they need on it. Each section rolls on to the next and with mobile centric design in mind, a button linking back to the home menu at the bottom of each section allows the user to get back to the menu at all times. This was a later addition made after testing on multiple screen sizes.

## Features

#### Feaures Used

##### 1. Navbar
The navbar menu is fixed to the top of the primary page. In desktop mode it is a scrolling menuwhich follows to each section. On mobile, tablet and notebooks the menu is fixed in place above the home content. It's scaling ability is controlled by the grid system of v4.1.3 of Bootstrap.
##### 2. Return Home Button
A button is appears on screens smaller than 1280px. It allows the user to select any main menu item and instantly have a way to return to the main menu. It deisplays as a small button on the bototm right of the screen and activates within 20px of movement from the top of the webpage. This feature makes use of a W3Schools javscript example.
##### 3. Footer
This section includes an additional fanclub signup option, a futher booking option, and all social media links. The fanclub signup activates a modal requesting and email address. The booking button brings the user to the booking form at the bottom of the main page. Each social medai icon changes color on hovering, and when clicked opens a new page directly to the associated platform and profile. The modal was created using the same code form teh Whiskey bootstrap bootcamp module of the course. 
##### 4. Smooth Scrolling Webpage
To stick with the one page design, a smooth scrolling script was used. An assigned ID with a # symbol in front was associated with each page section. A link to each page section was assigned to each main menu item. Once clicked, the respective menu item scrolls to it's assocaited page section. The timing is set to 800 milliseconds by default. This along with the jQuery animate function allows for smooth scrolling. 
##### 5. Home section
With bootstrap's grid system in use, a flexible two column design was used. labelled "top" and "botton" sections for mobile design reasons, the otp section shows a band logo with a paragraph linking to each feature of the page. In the bototm section, a fanclub signup modal call to action is available.
##### 6. Music section
This area shows 4 embeded music tracks in the top section, and one video in the bottom section. Each track has a background image of the assocaited song, and the video container is fully scalable to any device screen size. 
##### 7. About section
A collection of band photos along with a short bio of each member adds a personal touch to the website. 
#### Design
Rounded edges, a colour palette from the 60's with faded background image. These style choices make the website more familiar to older fans. 

#### Functionality
The website is a three page design. A primary page for all content, and two "thank you" pages linked to both forms. A "Back to Home" button sits at the bottom of each section linking back to the main menu. Form one is modal requesting and email address for a fan club signup. Form two is a booking form requesting a name, email and details regarding an event. Both forms work correctly. 

## Deployment

