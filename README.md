# First Milestone Project

<p align="center">
  <img src="https://github.com/LuciusVH/goatflix/blob/main/assets/img/readme/logo-readme.png" alt="Goatflix's logo"/>
</p>



Hi there and welcome! 

This is a website created as my first Milestone Project for the Full Stack Developer Course of Code Institute, after completing the three first modules : HTML, CSS & User Centric Front End Development. 

You can find the deployed site [here](https://luciusvh.github.io/goatflix/).

> **NOTE:** The links included in this README will not automatically open in a new tab. Press CTRL+ click on the link to open the target in a new tab.



## Table of Content

1. [UX](https://github.com/LuciusVH/goatflix#ux)
   1. [Structure & Design](https://github.com/LuciusVH/goatflix#structure--design)
   2. [User Stories](https://github.com/LuciusVH/goatflix#user-stories)
2. [Features](https://github.com/LuciusVH/goatflix#features)
   1. [Existing Features](https://github.com/LuciusVH/goatflix#existing-features)
   2. [Features Left to Implement](https://github.com/LuciusVH/goatflix#features-left-to-implement)
3. [Technologies Used](https://github.com/LuciusVH/goatflix#technologies-used)
   1. [Web Technologies](https://github.com/LuciusVH/goatflix#web-technologies)
   2. [Developer tools](https://github.com/LuciusVH/goatflix#web-technologies)
4. [Testing](https://github.com/LuciusVH/goatflix#testing)
5. [Deployment](https://github.com/LuciusVH/goatflix#deployment)
6. [Credits](https://github.com/LuciusVH/goatflix#credits)
   1. [Content](https://github.com/LuciusVH/goatflix#content)
   2. [Media](https://github.com/LuciusVH/goatflix#media)
   3. [Acknowledgements](https://github.com/LuciusVH/goatflix#acknowledgements)
7. [DISCLAIMER](https://github.com/LuciusVH/goatflix#disclaimer)




------
------

## UX

This website is for goats enthusiasts, more specifically Nigerian dwarf goats (which means basically everyone, as everyone loves these little jumping :goat: !). Goatflix provides the possibility to book a 5mn videocall with one of the owner's goat for 5 EUR. It also displays, with a touch of humor, some facts about these animals and tips if you intend to adopt some yourself. 

### 	Structure & Design

Goatflix is structured in a 2 pages website, each divided in several sections. The general theme is heavily inspired by the streaming website [Netflix](https://www.netflix.com) (and so is the name :wink:).

On large screens (above 768px), the [index.html page](https://github.com/LuciusVH/goatflix/blob/main/assets/img/wireframes/index-lg.png) (clicking opens up the wireframe picture) is divided in 3 different sections:

1. The callout section, displaying a large hero image in the background, the logo on the top left corner, a Call To Action (CTA) link on the top right corner opening up the contact modal form to book a videocall, a title & text paragraph followed by another CTA link anchored to the next section (leading the user towards the rest of the webpage). 

2. The "Stars" section, displaying 4 different Nigerian dwarf goats: each with a picture, name, text description of their character & fun facts and finally a CTA button, opening up the contact modal form in order to book a videocall.

3. The customers reviews section, displaying 2 reviews: picture of the customer & text review. 

The navbar appears only once the user has reached the "stars" section, allowing the landing area to have an even more important impact. Once showing up, the navbar is fixed to the top of the screen, overlaying the rest of the content. The navbar displays:

1. The Goatflix logo on the left side, linking to the index.html, as it is conventional.

2. A set of links, from left to right, on the right side of the navbar: "Home", "Our Stars", "Wikigoat" & "Contact". The "Wikigoat" link is a dropdown menu, revealing 2 sub-links: "General info" & "Famous goats". Those two links take the user to the second page of the website.

On a smaller device, under 768px, the only change on [index.html](https://github.com/LuciusVH/goatflix/blob/main/assets/img/wireframes/index-sm.png) is that the navbar links get hidden under a *"hamburger"* icon on the right side, while the logo picture remains on the left. 

The footer, for its part, displays links to different social networks, and the copyright mention below them.

The [wikigoat.html page](https://github.com/LuciusVH/goatflix/blob/main/assets/img/wireframes/wikigoat-lg.png) is divided in 2 sections:

1. The landing section, displaying a large hero video (muted, in loop, without user commands) with the title "General info" on its lower part. Following are: an intro text, a summary and the content divided in sections & sub-sections. One or two pictures will be displayed, in the middle of the content. 

2. The "Famous goats" section is replicating the design of the "Stars" section, with a picture, the name and a text description for each goat, minus the CTA button. 

On smaller screen, [wikigoat.html](https://github.com/LuciusVH/goatflix/blob/main/assets/img/wireframes/wikigoat-sm.png) will be the same but with the side margins reduced to a minimum.

Finally, when clicked on one of the [contact](https://github.com/LuciusVH/goatflix/blob/main/assets/img/wireframes/contactmodal-lg.png) links, the form opens up in a modal alert, overlaying the rest of the website. It shows a picture of Philoctetes (a goat-ish Disney character), side-by-side with the title "Contact & booking". Following, two inputs for the user's name & email and a text area for the message, a "submit" button & a "reset" button. The label for each input and text area is displayed on the left of its respective field. The placeholders displays "Philoctetes" in the name field, "phil@disney.com" (fictional email address) & a Phil's line in the message field, taken from the Disney animation movie *Hercules* (best Disney <u>ever</u>, thanks). 

On smaller screen, the [modal contact form](https://github.com/LuciusVH/goatflix/blob/main/assets/img/wireframes/contactmodal-sm.png) is basically the same but with no picture and each input and text area is displayed below its own label. 

The fonts are taken from [Google Fonts](https://fonts.google.com/):

- The titles font is [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue).
- The regular font is [Roboto](https://fonts.google.com/specimen/Roboto), chosen because identified as "popular pairing" with Bebas Neue. 
- [Helvetica](https://downloadhelvetica.com/) has been chosen as default font, if the others can't load for any reason, as it is reputed to be the perfect font and actually has a quite interesting [documentary](https://downloadhelvetica.com/helvetica-movie/) dedicated to it :movie_camera: ​! 

The logo has been designed using [FontMeme](https://fontmeme.com/netflix-font/), because I don't know how to curve the font in order to replicate the Netflix's logo. After some research, I found that I could somehow do it using SVG but FontMeme provided me with a decent result with less effort, though I will definitely have a look at SVG later on, it seems quite interesting when paired with CSS. 

### User stories

- As a potential customer, I want to find information on the service (price, how does it work, etc.) and how to book the videocall easily.

- As a potential customer, I want to be able to read other customers' reviews before purchasing myself.

- As an aspiring goat owner, I want to find information about Nigerian dwarf goats. 

- As a parent, I want my child to learn about goats in a funny way. 

- As a coworker, I want to make a joke to my colleagues and have a goat in our next team videocall. 



## Features

### Existing Features

- <u>Landing area</u> - this section is a call to action (CTA), helping the customer to get quickly booking his videocall through the contact form, with the CTA link on the top right corner, or the potential customer to get more info on the goats with the CTA button "Meet our stars" under the title. 
- <u>Navbar</u> - allows the user to easily navigate to any section of the website. It's been made sticky, so the navbar stays on the top of the screen, once the uses has reached the "stars" section, and straight on the top of the wikigoat.html page (no landing/CTA section on this page). 
- <u>Stars section</u> - helps the user to familiarize himself/herself with some of the goats available for videocall. Each goat's card also displays a CTA link inviting the customer to book his videocall through the contact form.
- <u>Customer reviews section</u> - allows the potential customer to get a feedback from previous customers and helps the decision process (as if seeing these cute goats wasn't sufficient enough!!)
- <u>General info section</u> - allows the user to get info about these animals, and pro tips if he/she is planning to get a goat himself/herself (or actually a couple of goats, at least, as it's explained in the section :wink:). 
- <u>Famous goats section</u> - allows the user to learn more about some of the most eminent members of the goat community, whether they are real or fictional. 
- <u>Footer</u> - informs and leads the user towards the breeding farm's social media accounts, and displays the copyright mention. 
- <u>Image modal</u> - allows the user to visualize the picture in bigger size.
- <u>Contact modal</u> - allows the user to contact the goats owner, to set up a videocall or ask any question they may have.
- <u>Favicon</u> - allows the user to find more easily the Goatflix tab in his/her browser & improve SEO.

### Features Left to Implement

- <u>"Go to the top" button</u> - allows the user to get to the top of the webpage instantly, without having to scroll his/her way back up.



## Technologies Used

### Web technologies

- [HTML](https://en.wikipedia.org/wiki/HTML)
    - Basic language to structure the pages.
- [CSS](https://en.wikipedia.org/wiki/CSS) 
    - Used to style the website.
- [Bootstrap 5.0](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
    - Used for responsive grid structure & navbar. 
- [JavaScript](https://www.javascript.com/)
    - Used for the modal effect when clicking on picture (code snippet taken from [W3Schools](https://www.w3schools.com/css/css3_images.asp)).
- [Fancybox 3.5](https://fancyapps.com/fancybox/3/)
    - Used for the images galleries & modal effect associated. 

### Developer tools

- [Github](https://github.com/)
  - The project uses **Github** to manage and host the repository.
- [Git](https://git-scm.com/) 
  - The project uses **Git** for Version Control. 
- [Visual Studio Code](https://code.visualstudio.com/)
  - **VSCode** was the IDE used to build this project. 
- [Typora](https://typora.io/)
  - **Typora** was used to write this README.md file.
- [Balsamiq](https://balsamiq.com/)
  - **Balsamiq** was used to create the wireframes. 
- [TinyPNG](https://tinypng.com/)
  - **TinyPNG** was used to compress all pictures, in order to reduce the loading time and improve UX. 
- [Fontmeme](https://fontmeme.com/netflix-font/)
  - **FontMeme** was used to create the Goatflix logo, imitating the Netflix logo in color and shape. 
- [Favicon.io](https://favicon.io/)
  - **FavIcon** was used to create and implement the favicon. 



## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:

    1. Go to the "Contact Us" page

    2. Try to submit the empty form and verify that an error message about the required fields appears

    3. Try to submit the form with an invalid email address and verify that a relevant error message appears

    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

- The image in background, on the landing area, isn't displayed correctly on iPad, though it is when emulated through DevTools. The parameter "cover" doesn't seem to apply (screnshot taken).



## Deployment & cloning

You can find the deployed site [here](https://luciusvh.github.io/goatflix/). 

### Deployment

To deploy the website live through GitHub Pages I:

1. Went on my repository on GitHub and clicked on "Settings"

   <p align="center">
     <img src="https://github.com/LuciusVH/goatflix/blob/main/assets/img/readme/dpl-step1.png" alt="deployment step 1"/>
   </p>

2. Selected "Pages" on the left-side navigation menu

   <p align="center">
     <img src="https://github.com/LuciusVH/goatflix/blob/main/assets/img/readme/dpl-step2.png" alt="deployment step 2"/>
   </p>

3. On the "Source" section, I selected `Branch: main`, `/ (root)` & *Save*

   <p align="center">
     <img src="https://github.com/LuciusVH/goatflix/blob/main/assets/img/readme/dpl-step3.png" alt="deployment step 3"/>
   </p>

4. There you have it! :smile:

   <p align="center">
     <img src="https://github.com/LuciusVH/goatflix/blob/main/assets/img/readme/dpl-step4.png" alt="deployment step 4"/>
   </p>

### Cloning

If you wish to clone the project and run it locally, follow these steps once on the repository:

1. Click on the "Code" button, then on the board icon to copy the link of the repo

   <p align="center">
     <img src="https://github.com/LuciusVH/goatflix/blob/main/assets/img/readme/cln-step1.png" alt="cloning step 1"/>
   </p>

2. Open your preferred IDE

3. Change the current working directory to the location where you want the cloned directory

4. In the terminal of your IDE, type `git clone https://github.com/LuciusVH/goatflix.git` and press **Enter**

5. There you have it! :smile:

For more info and troubleshooting, please check [GitHub documentation](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository).

### 

## Credits

### Content

- The Philoctetes' picture and lines, displayed on the modal contact form, are the property of [Disney Inc.](https://www.disney.com/).

### Media

- The hero picture is taken from [Unsplash](https://unsplash.com/photos/9mxoVvVQsEU).
- The other goats pictures are from [L'élevage Toy & Miniature des Bois Noirs](https://www.facebook.com/ptiteschevres63/), my best friend's own toy goats herd. 

### Acknowledgements

- I was heavily inspired by [Netflix](https://www.netflix.com)'s landing page to design Goatflix.
- The "goat videocall" concept comes from my best friend, living in the French countryside in a small farm place. She owns some toy goats and had this idea of videocalls, to generate more incomes during this pandemic time. She needed a website to develop an online presence & this matched with my MSP#1 requirements. Please read the disclaimer following. 
- The footer social links structure & hover effect are taken from Code Institute's Resume Mini Project, then slightly personalized. 
- The polaroid design is from [Return-true](https://return-true.com/creating-a-polaroid-effect-with-css/).
- The Table of Content's link hover effect is taken from [CSS-Portal](https://www.cssportal.com/blog/css-animated-underline-links/) then customized.

  

------

## DISCLAIMER

This specific website is entirely designed for educational purpose only. 

However, please note that a clone of the Github repository might be done in the next weeks, translated into French, modified and commercially published, under a purchased domain name.  

