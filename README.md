
# Plant Haus, a Website

#### A simple website made to complete a Code Review for Week 1 CSS track at Epicodus. Created 10/12/2017.

#### By **Jessie Waite**

## Description

A simple website made for Week 1 of Epicodus CSS track. The website showcases a product for sale. In this case, the product is a plant. The website includes the following requirements:

* _Centered elements_
* _One large image with an absolutely positioned table (used in lieu of a caption)_
* _A table styled with CSS (e.g. sizing chart, color options, order form…)_
* _A gallery of smaller images (i.e. Similar Plants)_
* _This website was made without using Bootstrap. Font Awesome was used in order to use icons_


### Specs
| Spec | Input | Output |
| :-------------     | :------------- | :------------- |
| **Webpage** | Ping-Pong Game | Webpage with user input form |
| **The program takes the number input by the user and returns a count, starting at 1. **| User Input: "4" | Output: "1,2,3,4" |
| **The program replaces numbers divisible by 3 with the word “ping”.**| Input: "4" | Output: "1, 2, “ping”, 4" |
| **The program replaces numbers divisible by 5 with the word “pong”.** | Input: "6" | Output: "1, 2, “ping", 4, “pong”, 6" |
| **The program replaces numbers divisible by 15 are replaced with “ping-pong”.**| Input: "16" | Page Displays: 1, 2, “ping”, 4, “pong”, “ping”, 7, 8, “ping”, “pong”, 11, “ping”, 13, 14, 	“ping-pong”, 16|
| **The user can enter a new number into the input field and see results over and over again.| Input: "3", "2" | Page Displays: 1,2, "ping" ; 1,2 |[[]
'']

## Setup/Installation Requirements

* _Clone the "plant-haus" repository to your desktop from GitHub here: https://github.com/jbellwaite/plant-haus.git_
* _Open the "plant-haus" folder_
* _Open a web-browser, preferably Chrome._
* _Drag "index.html" into an open tab in your web browser to open the application._

_Use a text editor like Atom to edit code._

## GitHub GH-Pages link
_https://jbellwaite.github.io/plant-hause/_

## Known Bugs
* All bugs are the result of creating my page, then reading the project requirements. I easily could have avoided these problems if I had more carefully read the requirements before setting up the website.

* _I had my gallery pictures all neatly lined up in the middle, then read the requirement that we are to use a "float" on the images... When I added the float property, as is expected, the parent element collapsed. Surprisingly, I really liked how the footer looked smooshed up into the gallery pictures. Obviously, I didn't want the footer included, but I added a few more divs to the gallery section to get a similar effect. Kind of like using the opposite of clear-fix. I'm not sure if this is proper coding, but I like how it turned out._

* _Instead of using a caption that was absolutely positioned for the main picture, I absolutely positioned the table the the right of the picture. I really liked how the name and price of the plant hovered over the middle of the plant regardless of the size, but I can easily change that if needed._

* _When the mouse hovers over the navigation links at the top of the page, a leaf appears. However, on the last two items in the navigation, the leaf appearing causes the whole navigation to slide over to adjust. This happened because I used the "float" property on the elements to get them to move to the right of the page._

## Technologies Used
  * CSS
  * HTML

## Support and contact details

_Email Jessie with comments or questions._
_jess.bell@me.com_

### License

*{This software is not licensed under the MIT license}*

Copyright (c) 2017 **_{Jessie Bell Waite}_**
