Lab5-Music Site Project
====
Description
----
This website is about music site of Star Wars Theme which Often used as background music in my playlist, most of star wars soundtrack composed and conducted by John Williams, performed by the London Symphony Orchestra, Hollywood Freelance Studio Symphony and (in a few passages) by the Los Angeles Master Chorale.</br>
I choose some of my favorite ones, display with image and description. Add 4 classic Star Wars music,and a youtube video for the next star wars movie, that one will also release a soundtrack for sure.</br>
Project use HTML, styling with CSS.</br>

HTML Structure
---
head:</br>
links for google font, style.css </br>
body:</br>
header:h2 for "music site"-logo and nav part for navigation bar link other pages </br>

section:</br>
1. use card and img, article </br>
2. div use for introduce classic star wars music, use h2, audio tag, and p tag</br>
3. h2 tag for upcoming star wars music/movie, iframe tag linked a youtube video</br>

footer:copyright information</br>

CSS Styling
----
Add CSS classes to header div, section div, footer div, 
* Whole body part set with the same google font, color/background-color, use star wars logo color-yellow to make everything matched.</br>
* a:hover and a:active styling a tag elements for header</br>
* Section:
1. margin padding, display flex/grid, position:absolate, relative, fixed.</br>
2. Fluid typography and media queries to make sure website fit well in different size screen, min-width 1024 and max-width 767px: @media only screen and (min-width: 1024px), @media only screen and (max-width: 1023px) and (min-width: 768px),@media only screen and (max-width: 767px).</br>
3. Position:fixed stying a "star wars" logo, set in website lower right corner</be>
4. card:hover:box-shadow: 0 8px 16px 0 rgba(223, 219, 219, 0.545) </br>
5. display grid for audio part;flexbox styling card, flex-direction as column.</br>

Running the tests
----
Code tested in MS edge and Google Chrome, both work fine.

Built With
----
* HTML5
* CSS3
* Visual Studio Code

Support and contact details
----
If you have any questions, please leave message in Issues or contact me: Fan Zhu - n01648910@humber.ca
