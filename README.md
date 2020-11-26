![image](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/images/logo/school-logo-readme.png)

# [School of English Galway](https://toto-kotaro-tanaka.github.io/ms1-school-of-english/)

This is a website of an imaginary English Language School based in Galway, Ireland that I create for **Milestone Project 1, Full Stack Software Development in Code Institute**. </br></br> It is **Mobile First** & **Responsive** website.</br>

![image](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/readme/mockup.png)</br>

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

* Image galleries using carousel. 5 images of courses and 5 images of accommodation
* PDF price list is linked with menu and buttons, which open in a separate tab
* Online registration form (static form) that users can access from the menu bar
* Contact form with modal that users can access from header and footer (Added as additional feature while creating the website)

### Structure Plane
The website consists of 4 pages (Home, Courses, Accommodation, Register) plus price list as a separate link. Everything is laid out logically so that users can easily predict and learn about the website.

**`Home page`**
There is a hero image with school's catch phrase **"Go west... to learn English, make friends and have fun!"**.
There are brief course & accommodation descriptions and feedback underneath hero image.

**`Courses`**
Outlining the details of each course with a link to the price list. There are image galleries of the courses. Same layout as Accommodation.

**`Accommodation`**
Outlining the details of each accommodation with a link to the price list. There are image galleries of the accommodation. Same layout as Courses.

**`Register`**
Online registration form (static form) that is kept simple. Some fields have drop down menu to make users life easier.

**`Header & Footer`**
All pages are designed with the same header and footer so that users can get familiar with the website quickly. There is a navigation bar on the header which includes logo and menu. School's details and social icons are on the footer.
~~Green~~ Off white* is used for header and green is used for footer, white for body and orange for buttons.

**Note:**
**When I started coding, I felt Dark Green (#065446), that I was going to use initially on the header, was too strong, therefore I used off white (#fafafa) as background colour of header with font colour of Dark Green (#065446). I also decided to add contact section on top of the page so Dark Green is used for this.*  

### Skeleton Plane
Mobile first design and there are wireframes of Home, Courses, Accommodation and Register for mobile, tablet and desktop sizes.

* [Wireframes: Home](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/wireframes/wireframe-home.png)
* [Wireframes: Courses](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/wireframes/wireframe-courses.png)
* [Wireframes: Accommodation](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/wireframes/wireframe-accommodation.png)
* [Wireframes: Register](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/wireframes/wireframe-register.png)

**Note:**
*I changed the design of **Courses** and **Accommodation** for all the sizes. I put the galleries above courses and accommodation details so that they look same as **Home** and this was better layout than the original plan on my wireframes.*

### Surface Plane
#### --- Colour ---
**`Dark Green (#065446)`** is the school colour ~~so this colour is used for header and footer~~ and it is used for main text and background of headings. Background colour is white and orange is used for buttons. Irish flag is imaged for colour coordinations.

**Note:**
*As I mentioned on **Structure Plane** I revisited the colour of header.* 

#### --- Typography ---
**`Serif`** type (Noto Serif) is used for headings to make the website trustful as this is for education. On the other hand, **`San-Serif`** type (Open Sans) is used for contents to make the website easy to read and give friendly atmosphere to the users.

## Features
### Existing Features
* Created with HTML5, CSS3, Bootstrap
* It consists of 4 individual pages plus a price list as separate link page
* Manual carousel for galleries
* Modal for contact form

### Features Left To Implement
* To prevent **contact us** form being sent unless e-mail addresses match. As far as I understand, javaScript is required for this
* More modern registration form which includes better styled calendar and drop down menu. javaScript and other technology are required
* Website in **Different Languages** and **Quotation Calculator** as mentioned on Strategy Plane

## Technologies Used
* [HTML5](https://en.wikipedia.org/wiki/HTML) for markup
* [CSS3](https://en.wikipedia.org/wiki/CSS) for style
* [Google Fonts](https://fonts.google.com/) for fonts
* [Bootstrap](https://getbootstrap.com/) for main frame of the website
* [Font Awesome](https://fontawesome.com/) for icons
* [Visual Studio Code](https://code.visualstudio.com/) as Integrated Development Environment (IDE)
* [Git](https://git-scm.com/) for version control
* [GitHub](https://github.com/) for keeping the files, documents and deploy the website

## Resources
### General Resources
* Code Institute course materials
* Code Institute Slack Community
* [MDN](https://developer.mozilla.org/en-US/)
* [Stackoverflow](https://stackoverflow.com/)
* [Youtube](https://www.youtube.com/)
* [W3schools](https://www.w3schools.com/)

### Tools
* [Adobe](https://www.adobe.com/ie/photoshop/online/resize-image.html) To resize images
* [Autoprefixer](https://autoprefixer.github.io/) To parse CSS and add vendor prefixes

## Testing
### Pre-Testing
The purpose of this was to fix any errors before the second meeting, that was planned almost end of completion of my website, with my mentor.

#### --- Code Validation ---
**[W3C Markup Validation Service](https://validator.w3.org/)** was used to check any errors on html files.

<ins>[Three errors found on index.html](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-w3c-index-html.jpg)</ins>
1. **"Stray end tag *i*":** There were two closing tabs of *i* for Font Awesome icon. Fixed the errors by removing one of the closing tags
2. Same as above in the different line
3. **"*aria-describedby* attribute doesn't point to an element in the same document":** Fixed the errors by putting the id in the same element

**Note:**
*These errors were on header and modal form that are being used on all the pages so I fixed these on all the pages before testing other pages*

<ins>[One warning found on courses.html](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-w3c-courses-html.jpg)</ins>
1. **"section lacks heading":** I used *section* for image gallery on courses.html without any heading and that was the reason of the warning. As I wasn't sure if I needed to use other semantic element or *div* for this, I asked the question in Slack community and I was told "this is a warning and it's usually ok" so decided to leave it

<ins>[One warning found on accommodation.html](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-w3c-accommodation-html.jpg)</ins>
1. Same as warning on courses.html

<ins>[Seven errors and One warning on register.html (error 1 - 5)](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-w3c-register-html-1-5.jpg)</ins> / 
<ins>[error and warning 6 - 8](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-w3c-register-html-6-8.jpg)
1. **"Stray end tag *span*":** There was end tag of *span* on home of navbar. Fixed this by putting on register of navbar
2. **"End tag a violates nesting rules":**  Fixed by putting *span* in this element
3. **"The first child *option* element of a *select* element with a *required* attribute, and without a *multiple* attribute, and without a *size* attribute whose value is greater than *1*, must have either an empty *value* attribute, or must have no text content. Consider either adding a placeholder option label, or adding a *size* attribute with a value equal to the number of *option* elements":** Fixed by adding ~~size="13" on *select* tag~~. Errors from *4 - 6* were also same errors.
4. Same as 3 in different field
5. Same as 3 in different field
6. Same as 3 in different field
7. **"Duplicate ID":** Fixed by replacing another id, which was register-email, for email id on the registration form
8. **"The first occurrence of ID email was here":** Same errors as above and fixed by putting a new id, register-email

**Note:** *Adding size="13" on select tag was not the proper solution for this as all 13 options showed on the registration form. I googled the issue and found that I needed to put **value** of disable option to **none**(value="").*

**[W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)** was used to check any errors on css file.</br></br>
<ins>[No error or warning found](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-w3c-css.jpg)</ins>

#### --- Performance, Accessibility, User Experience ---
**[Lighthouse](https://developers.google.com/web/tools/lighthouse)** was used to check common issues that affect on my site performance, accessibility and user experience. Issues anything below 90 were addressed.

<ins>[index.html - Mobile](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-lighthouse-mobile-index.jpg)</ins>
* **Performance 73:** I thought I could fix this by reducing the size of images but it didn't so need to keep this on hold as there are some other issues that I didn't have time to look at for the moment 
* **Accessibility 95:** OK
* **Best Practices 86:** Fixed by adding rel="noopener" on a tag which has _blank. Also, removed one of javaScript that I copied from Font Awesome CDN that didn't need to be on index.html
* **SEO 92:** OK

**Note:**
*Regarding the issues of Performance, I looked these with my mentor however we weren't able to solve the issues.Please refer the final testing section for more details*

<ins>[index.html - Desktop](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-lighthouse-desktop-index.jpg)</ins>
* **Performance 92:** OK 
* **Accessibility 95** OK
* **Best Practices 93:** OK 
* **SEO 90:** OK

<ins>[courses.html - Mobile](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-lighthouse-mobile-course.jpg)</ins>
* **Performance 94:** OK
* **Accessibility 95:** OK
* **Best Practices 93:** OK 
* **SEO 92:** OK

<ins>[courses.html - Desktop](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-lighthouse-desktop-courses.jpg)</ins>
* **Performance 100:** OK
* **Accessibility 95:** OK
* **Best Practices 93:** OK 
* **SEO 90:** OK

**Note:**
*For both mobile and desktop versions of courses.html, I knew that there were some same issues as index.html (such as the size of images, rel="noopener", javaScript of Font Awesome) so I fixed these first before the test*

<ins>[accommodation.html - Mobile](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-lighthouse-mobile-accommodation.jpg)</ins>
* **Performance 60:** It seemed **Performance** on Lighthouse changes every time. (It may depend on the speed of broadband?) Fixed the issue by reducing the size of images, however this gave an issue for the performance on desktop size as I got a warning saying low resolution image was being used for the first photo so I had to adjust the size of this photo and test it.
* **Accessibility 95:** OK
* **Best Practices 100:** OK 
* **SEO 92:** OK

<ins>[accommodation.html - Desktop](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-lighthouse-desktop-accommodation.jpg)</ins>
* **Performance 100:** OK
* **Accessibility 95:** OK
* **Best Practices 93:** OK 
* **SEO 90:** OK

**Note:**
*For both mobile and desktop versions of accommodation.html, I knew that there were some same issues as courses.html (such as the size of images, rel="noopener", javaScript of Font Awesome) so I fixed these first before the test. For some reason, performance on mobile is not high although it is same as courses and I reduced the size of images.*

<ins>[register.html - Mobile](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-lighthouse-mobile-register.jpg)</ins>
* **Performance 93:** OK
* **Accessibility 85:** Fixed by changing the colour of label from grey to dark green
* **Best Practices 93:** OK 
* **SEO 90:** OK

<ins>[register.html - Desktop](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/pre-test-lighthouse-desktop-register.jpg)</ins>
* **Performance 98:** OK
* **Accessibility 85:** Fixed by changing the colour of label from grey to dark green
* **Best Practices 93:** OK 
* **SEO 90:** OK

### Final Testing
The purpose of this was to make sure that my website was properly functioning before submitting the project.

#### --- Code Validation ---
* **[W3C Markup Validation Service](https://validator.w3.org/)** was used to check any errors on html files. I confirm that there were no errors as some issues were fixed at Pre-Testing point. There was a warning on courses.html and accommodation.html but it was OK as explained on the Pre-Testing section

* **[W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)** was used to check any errors on css file. I confirm that there were no errors which same result as Pre-Testing

#### --- Performance, Accessibility, User Experience ---
* **[Lighthouse](https://developers.google.com/web/tools/lighthouse)** was used to check common issues that affect on my site performance, accessibility and user experience. Everthing was **[90+ scores](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/final-test-lighthouse.png)** except **[index.html - Mobile](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/final-test-index-mobile-errors.png)** and **[accommodation.html - Desktop](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/testing/final-test-accommodation-desktop-error.png)**.</br>
My mentor and I looked at the issues of **index.html - Mobile** but we weren't able to figure out how to solve the issues. According to the report, it mentioned about links of bootstrap and CSS, that suggested that I wasn't using them, but I actually was. I have exactly same layout on other html files and not sure why it caused issues on only **index.html - Mobile** so I had to leave it.</br>
For the other issue that **The Best Practice** for **accommodation.html - Desktop**, this was caused by the size of main image being low resolution. If I increased the size of the image, it would raise issues on mobile size, that images would be too big so I decided to leave this as it is

#### --- Web Browsers ---
* Tested in majour web browsers such as **Google Chrom**, **Safari**, **Firefox**, **Microsoft Edge**, **Opera** and the website worked both visually and functionally. I also tested with **Internet Explorer 11**. Home, Courses and Accommodation pages were fine however Register page didn't show properly. I looked up the solution but learned in Slack community that Bootstrap doesn't work well in Internet Explorer so decided to take no action about it as Internet Explorer 11 wouldn't a major web browser. (Only 2-3% users overall)

#### --- Responsiveness --- 
* I used **Google Chrom Dev Tools** to check the responsiveness of my website. I tested with mobile, tablet and desktop sizes and all worked. It also responded on each breakpoint that I set up on Media Query and no visual or functional errors found  

## Project Barriers & Solutions
I faced some difficulties and issues before starting the project. During the project, I didn't have many difficulties or issues but spent a lot of time on something I wasn't used to doing. Below are the list of them. 
* **Starting the project:** As I had never created a proper website by myself, I wasn't sure how and where to start, although I took the lessons to prepare for this. What I did to solve this was to watch two session videos ([MS1 Planning Session](https://www.youtube.com/watch?v=sH0m9N875SU&feature=youtu.be) by Jim Lynx) & ([README Video](https://www.youtube.com/watch?v=7BteidgLAyM&feature=youtu.be) by Anna Greaves) repeatedly until I understood the process, got an image of it and got ready for it
* **Customising hamburger menu:** I used quite basic HTML and CSS so I didn't have many coding issues, however customising hamburger menu, that I had thought it was straight forward enough, wasn't easy to do so I had to look up solutions on google 
* **List on form:**
I wanted to add more nationalities and languages on the list on registration form. The only option I could think of was to manually add them on HTML. I was looking for better option / solution but couldn't find anything other than a list of template which includes all the countries. This website is my project in the institute, I decided to keep nationalities and languages as they are instead of having so many of them on html file
* **Date picker:** I wanted to style date picker on the registration form in a better format, however it seems javaScript is required for this so decided to leave it for the moment
* **Bootstrap default margin and padding:** When I set up max width of 90rem and trying to put borders around the website, courses and accommodation sections were expanded more than 100% which I think it was caused by Bootstrap's default setting (margin) so I used Chrom Dev Tools and Toggle Pesticide to see where the issues were and fixed them by putting margin 0 on row class
* **New features:** There were some new features that I had never used. For example, README was one of them and it took sometime for me to get used to write in markdown. I learned it by looking up on google as well as by writing as much as possible

## Version Control
### Git
Git was used to commit the changes. Whenever I completed a section or even a group of work, I committed them in order to make sure that the history of the records were properly logged in, as this is an essential practice for developers.
### GitHub
GitHub was used to store all the folders and files of my project.

## Deployment
To deploy the website, I followed the below steps.
1. Go to **"Settings"** on the repository
2. On **"Source"** of **"GitHub Pages"**, select **"main"** for Branch and click save
3. The link is published and confirm above **"Source"**.</br> *URL is "https:// + **`your GitHub username`** + .github.io/ + **`your repository name`** + /"* </br></br>
(e.g. https://toto-kotaro-tanaka.github.io/ms1-school-of-english/)</br></br></br>
![image](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/readme/github-deploy1.png)</br></br></br>
![image](https://github.com/Toto-Kotaro-Tanaka/ms1-school-of-english/blob/main/assets/documents/readme/github-deploy2.png)

## Credits
### code
**`HTML5`**
* [Bootstrap Navbar](https://getbootstrap.com/docs/4.5/components/navbar/) for navigation bar
* [Bootstrap Carousel](https://getbootstrap.com/docs/4.3/components/carousel/) for feedback and image galleries
* [Bootstrap Modal](https://getbootstrap.com/docs/4.5/components/modal/) for contact form
* [Bootstrap Forms](https://getbootstrap.com/docs/4.5/components/forms/) for registration form and form on modal

**`CSS3`**
* [Stackoverflow](https://stackoverflow.com/questions/50668594/remove-border-color-for-navbar-toggler-hamburger-icon-bootstrap-4) to remove border colour of hamburger menu
 * [Stackoverflow](https://stackoverflow.com/questions/42586729/bootstrap-4-change-hamburger-toggler-color) to change the colour of hamburger menu
 * [Stackoverflow](https://stackoverflow.com/questions/46249541/change-arrow-colors-in-bootstraps-carousel) to change the colour of carousel arrows

### Contents

* All contents were written by me

### Media

**`Main Logo`**
* Created by me using [Wix Logo maker](https://www.wix.com/logo/maker)

**`Hero Image`**
* [Unsplash](https://unsplash.com/) by [Ryan Jacobson](https://unsplash.com/photos/cXUOQWdRV4I)

**`Feedback Images`**
* feedback1: [Unsplash](https://unsplash.com/) by [Icons8 Team](https://unsplash.com/photos/FcLyt7lW5wg)
* feedback2: [Unsplash](https://unsplash.com/) by [Johm Kan](https://unsplash.com/photos/71NgiXcdTzE)
* feedback3: [Unsplash](https://unsplash.com/) by [Lars Zhang](https://unsplash.com/photos/bd-tuYm6WWs)
* feedback4: [Unsplash](https://unsplash.com/) by [Tamarcus Brown](https://unsplash.com/photos/29pFbI_D1Sc)
* feedback5: [Unsplash](https://unsplash.com/) by [Irene Strong](https://unsplash.com/photos/MgvAATOwJBc)

**`Courses Images`**
* courses1: [Unsplash](https://unsplash.com/) by [Windows](https://unsplash.com/photos/kRWY72TKB0Y)
* courses2: [Unsplash](https://unsplash.com/) by [You X Ventures](https://unsplash.com/photos/Oalh2MojUuk)
* courses3: [Unsplash](https://unsplash.com/) by [ThisiEnginneringRAEng](https://unsplash.com/photos/TXxiFuQLBKQ)
* courses4: [Unsplash](https://unsplash.com/) by [Devon Divine](https://unsplash.com/photos/Hzp-1ua8DVE)
* courses5: [Unsplash](https://unsplash.com/) by [M. Monk](https://unsplash.com/photos/E813FON0wDQ)

**`Accommodation Images`**
* accommodation1: [Unsplash](https://unsplash.com/) by [Dimitry Anikin](https://unsplash.com/photos/IfPmy_JmIY8)
* accommodation2: [Pexels](https://www.pexels.com/) by [Askar Abayev](https://www.pexels.com/photo/group-of-people-standing-near-brown-wooden-table-5638600/)
* accommodation3: [Pexels](https://www.pexels.com/) by [Yan](https://www.pexels.com/photo/people-riding-bicycle-on-dirt-road-5792903/)
* accommodation4: [Unsplash](https://unsplash.com/) by [Edgar Castrejon](https://unsplash.com/photos/bG5rhvRH0JM)
* accommodation5: [Unsplash](https://unsplash.com/) by [Raphael Schaller](https://unsplash.com/photos/Cz_Xbm3Jyyw)

### Acknowledgements
I would like to thank ;
* My mentor, **Spencer Barriball**, who went through the project with me and assured that I was doing right for the project
* **Jim Lynx** whose ["MS1 planning"](https://www.youtube.com/watch?v=sH0m9N875SU&feature=youtu.be) session video gave me clear guidance and got me start the project
* **Anna Greaves** whose ["README"](https://www.youtube.com/watch?v=7BteidgLAyM&feature=youtu.be) session video gave me ideas of how to write README
* **Code Institute Slack Members** who answered my queries during the project  