![image](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/images/logo/school-logo-readme.png)

# School of English Galway 
(web needs to be linked↑)

This is a website of an imaginary English Language School based in Galway, Ireland that I create for **Milestone Project 1, Full Stack Software Development in Code Institute**.

## Who's this website for?

People whose first language is <ins>NOT</ins> English and who are looking for a school to improve their English for various purposes, as well as who would like to have some experiences living in a foreign country while they study English. They could be from anywhere in the world so some might know about Galway / Ireland quite well and some might not. User's goals are to be able to find out core information about the school, such as location, courses, accommodation, prices and feedback from the former students in order to make up their mind, and to be able to contact the school or make a booking without any difficulties if they wish to do so.

## Who is the owner?

The owner of the language school. Owner's goals are to increase the number of direct students (direct sales) as currently a lot of students come from agents that they work with.

## UX 5 Planes

### Strategy Plane

As users are non-native English speakers, **keeping the website simple** is essential and **using more visual contents** than text contents would help them to understand the information easily. It targets business-to-consumer (B2C) so all the information must be clear and well presented.

The main aims for this website are;

- To provide users enough information about the school
- To provide users easy access to a booking process

Below tables show what should be included on the website to make the website valuable to the users. I would like to implement all of them on the website, however `Different Languages` and `Quotation Calculator` are not implemented due to lack of my current skills.

| Opportunity                      | Importance | Viability / Feasibility |
| :------------------------------- | :--------: | :---------------------: |
| Course and Accommodation Details |     5      |            5            |
| PDF Price List                   |     5      |            5            |
| Booking Form                     |     5      |            4            |
| Gallery                          |     4      |            4            |
| Feedback                         |     4      |            4            |
| Different Languages (X)          |     3      |            2            |
| Quotation Calculator (X)         |     4      |            1            |

### Scope Plane

Features to be included on this project are;

- Image galleries using carousel. 5 images of courses and 5 images of accommodation.
- PDF price list is linked with menu and buttons, which open in a separate tab.
- Online registration form (static form) that users can access from the menu bar.

### Structure Plane

The website consists of 4 pages (Home, Course, Accommodation, Register) plus price list as a separate link. Everything is laid out logically so that users can easily predict and learn about the website.

**`Home page`**

There is a hero image with school's catch phrase **"Go west... to learn English, make friends and have fun!"**.
There are brief course descriptions, brief accommodation descriptions and feedback underneath hero image.

**`Courses`**

Outlining the details of each course with a link to the price list. There are image galleries of the courses. Same layout as Accommodation.

**`Accommodation`**

Outlining the details of each accommodation with a link to the price list. There are image galleries of the accommodation. Same layout as Courses.

**`Register`**

Online registration form (static form) that is kept simple. Some fields have drowp down menu to make users life easier.

**`Header & Footer`**

All pages are designed with the same header and footer so that users can get familiar with the website quickly. There is a navigation bar on the header which includes logo and menu. School's details and social icons are on the footer.
~~Green~~ Off white* is used for header and green is for footer, white for body and orange for buttons.

**Note**
*When I started coding, I felt Dark Green (#065446), that I was going to use initially, on the header was too strong, therefore I used #fafafa as background colour of header with font colour of Dark Green (#065446). I also decided to add contact section on top of the page so Dark Green is used for this.  

### Skeleton Plane

Mobile first design and there are wireframes of Home, Courses, Accommodation and Register for mobile, tablet and desktop sizes.

- [Wireframes](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/wireframes.pdf)

**Note**
I changed the design on courses.index and acoommodation.index for all the sizes. I put the slideshow above courses and accommodation details so that they look same as index.html and this was better layout than the original plan on my wireframes.

### Surface Plane

#### Colour

**`Dark Green (#065446)`** is the school colour ~~so this colour is used for header and footer~~ and it is used for main text and background of headings. Background colour is white and orange is used for buttons. Irish flag is imaged for colour coordinations.

**Note**
As I mentioned on **Structure Plane** I revisited the colour of header. 

#### Typography

**`Serif`** type (Noto Serif) is used for headings to make the website trustful as this is for education. On the other hand, **`San-Serif`** type (Open Sans) is used for contents to make the website easy to read and give friendly atmosphere to the users.

## Features

### Existing Features

⋅⋅*Created with HTML5, CSS3, Bootstrap
⋅⋅*It consits of 4 individual pages plus a price list as separate link page
⋅⋅*Manual carousel for gallaries
⋅⋅*Modal for contact form

### Features Left To Implement
⋅⋅*To prevent contact us form being sent unless e-mail addresses match. As far as I understand, javaScript is required for this.
⋅⋅*To have more modern calendar which also have only weekends hilited to be selected. Not sure how this can be done for the moment. I didn't have enought time to look into more details
⋅⋅*Nationality and Language drop down menu options. More nationalities and languages need to be added but I am not sure if I need to put all the nationalitis and languages to have this on html or if there is a better way of doing it. I don't have enought time to look into more details

## Technologies Used

⋅⋅*HTML5 for markup
⋅⋅*CSS3 for style
⋅⋅*Google Fonts for fonts
⋅⋅*Bootstrap for main frame of the website
⋅⋅*Font Awesome for icons
⋅⋅*Visual Studio Code as IDE
⋅⋅*Git for version control
⋅⋅*Git for keeping the files and documents

## Resources

### General Resources
Code Institute course materials
Code Institute Slack Community  
[W3schools](https://www.w3schools.com/)
[MDN](https://developer.mozilla.org/en-US/)
[Youtube](https://www.youtube.com/)

## Testing

To be added as project goes on

## Project Barriers & Solutions

I had some difficulties to customise hamburger menu (removing border colour and changing colour of three lines) so I looked up on goole
I want to add more nationalities and languages on registration form
I want to style date picker

## Version Control

To be added as project goes on

## Deployment

To be added as project goes on

## Credits

### code
**`HTML5`**
⋅⋅*[Bootstrap Navbar](https://getbootstrap.com/docs/4.5/components/navbar/) for navigation bar
⋅⋅*[Bootstrap Carousel](https://getbootstrap.com/docs/4.3/components/carousel/) for feedback and image gallaries
⋅⋅*[Bootstrap Modal](https://getbootstrap.com/docs/4.5/components/modal/) for contact form
⋅⋅*[Bootstrap Forms](https://getbootstrap.com/docs/4.5/components/forms/) for registration form and form on modal
⋅⋅*[Stackoverflow](https://stackoverflow.com/questions/50668594/remove-border-color-for-navbar-toggler-hamburger-icon-bootstrap-4) for removing border colour of hamburger menu

**`CSS3`**
⋅⋅*[Stackoverflow](https://stackoverflow.com/questions/42586729/bootstrap-4-change-hamburger-toggler-color) for changing the colour of hamburger menu
⋅⋅*
⋅⋅*
⋅⋅*
Stackoverflow

### Contents

### Media

Main Logo, created by me using Wix Logo maker

Hero image, unsplash by Ryan Jacobson @ https://unsplash.com/photos/cXUOQWdRV4I

Feedback images
feedback1-jessica, unsplash by Icons8 Team @ https://unsplash.com/photos/FcLyt7lW5wg
feedback2-daniel, unsplash by Johm Kan @ https://unsplash.com/photos/71NgiXcdTzE
feedback3-sena, unsplash by Lars Zhang @ https://unsplash.com/photos/bd-tuYm6WWs
feedback4-benjamin, unsplash by Tamarcus Brown @ https://unsplash.com/photos/29pFbI_D1Sc
feedback5-maria, unsplash by Irene Strong @ https://unsplash.com/photos/MgvAATOwJBc \*https://crop-circle.imageonline.co/

Courses images
courses1, unsplash by Windows @ https://unsplash.com/photos/kRWY72TKB0Y
courses2, unsplash by You X Ventures @ https://unsplash.com/photos/Oalh2MojUuk
courses3, unsplash by ThisiEnginneringRAEng @ https://unsplash.com/photos/TXxiFuQLBKQ
courses4, unsplash by Devon Divine @ https://unsplash.com/photos/Hzp-1ua8DVE
courses5, unsplash by M. Monk @ https://unsplash.com/photos/E813FON0wDQ

Accommodation images
accommodation1, unsplash by Dimitry Anikin @ https://unsplash.com/photos/IfPmy_JmIY8
accommodation2, pexels by Askar Abayev @ https://www.pexels.com/photo/group-of-people-standing-near-brown-wooden-table-5638600/
accommodation3, pexels by Yan @ https://www.pexels.com/photo/people-riding-bicycle-on-dirt-road-5792903/
accommodation4, unsplash by Edgar Castrejon @ https://unsplash.com/photos/bG5rhvRH0JM
accommodation5, unsplash by Raphael Schaller @ https://unsplash.com/photos/Cz_Xbm3Jyyw

### Acknowledgements
