
#### TODO LIST
<ul style="color: red;">

    - CHECK DOUBLE CODE
    - MAKE ONE STYLING CLASS FOR ALL SECTIONS
    - ADD FIGURES INSTEAD OF IMAGES TO MENU
    - CHECK ALL CREDITS
    - CHECK ALL LINKS IN README FILE
    - CHECK SPELLING IN README FILE
    - CHECK CODE OF BUTTONS AND TEXTFIELDS
    - CHECK BACKGROUND COLOUR IN HEADER, HERO IMAGE NOT VISIBLE
    - LOOP JAZZ SONG
    - ADD ARIA LABELS
    - ADD WIREFRAMES
    - CHANGE HERO IMAGE
    - CHECK PARAGRAPH SIZES
    - CHECK TEXTBOX FONT SIZING
    - NO HOOVER COLOR FOR MENU PAGE AND RESERVATIONS PAGE
    - CHECK ALT TEXT

</ul>

#### BUG LIST
<ul>
    - MAP IMAGE DOES NOT FIT 100% IN THE DIV
    - TEXT WON'T ALIGN IN CENTER SECTIONS
    - RESERVATIONS FORM - TIME AND NUMBER OF GUESTS FIELDS NOT WORKING
    - FOOTER COPYRIGHT OVERFLOW AT SMALL DEVICE
</ul>









<h1>Japanese Restaurant Shibuya - Example Website</h1>

<!-- Mock up here-->

<!-- check link -->
[View the live project here.](#) <span style="color:red;">CHECK</span>


<!-- About -->
## About

This Japanese Restaurant website is created as an example for restaurant owners without a webpage and shows how a restaurant website might look like in case their business is not active on the internet.
Information about the restaurant you can find on the index (home) page. A stylish menu page is included to give potential customers an idea of what the restaurant has to offer.
Additionally, a reservation and contact page was added to show the usefulness of the website to potential clients.
Because the example website is located in the Netherlands, customers can even select the website's preferred language (English or Dutch). The website is responsive on all devices with a minimum screen width of 320 pixels.  
  

<!-- Table of Contents -->
## Table of Contents

[User Experience (UX)](#UX)

[Features](#features)

[Technologies Used](#technologies)

[Testing](#testing)

[Deployment](#deployment)

[Credits](#credits)





<!-- User Experience -->
<a name="UX"></a>
## User Experience (UX)

### User Stories

#### Potential Restaurant Guest - First Time Visitor Goals
1. As a First Time Visitor of the website, I want to understand what the website's purpose is, so I can decide to navigate through the website and read all the available information or leave the website in case it did not meet my expectation.
2. As a First Time Visitor of the website,  I want to know more about the restaurant's atmosphere.
3. As a First Time Visitor of the website, I want to know what the restaurant has to offer and at what price, so that I can decide whether I want to visit the restaurant somewhere in the future in case it meets my expectations.
4. As a First Time Visitor of the website, I want to know where the restaurant is located, so that I can decide whether the restaurant is within my desired traveling distance.
5. As a First Time Visitor of the website, I want to know what previous guests have to say about the restaurant, so that I have an idea of what to expect when visiting the restaurant.
6. As a First Time Visitor of the website, I want to know whether it is needed to make a reservation, so that I can take that into account when I want to visit the restaurant in the future.
7. As a First Time Visitor of the website,  I want to know on what day and at what time it is possible to visit the restaurant, so that I know when to make a reservation in case I want to visit the restaurant in the future.
8. As a First Time Visitor of the website, I want to know how and if I can get additional information about the restaurant in case it's not mentioned on the website.
9. As a First Time Visitor of the website, I want to know what the methods of payments are, so that I know whether to bring cash or a credit card before visiting the restaurant in the future.


#### Returning Restaurant Guest - Returning Visitor Goals
1. As a Returning Visitor of the website, I want to know whether there are new items added to the menu in the recent weeks or months, so that I can decide whether I might order them next time when visiting the restaurant.
2. As a Returning Visitor of the website, I want to know whether there is any important news or announcement about the restaurant without having to check the website regularly.


### Design


#### Colour Scheme
- Colours used on the website meet the colours of the background hero image. Four types are used for styling the html elements:
   * Black: rgba(0, 0, 0, 0.9) - used for sections background.
   * Orange type: rgb(223, 152, 96) - used for restaurant logo, h2 and h3 headers, section and image borders, and textboxes.
   * Smokewhite: rgb(245, 245, 245) - used in footer, navbar, for paragraphs, menu items, and form labels.
   * Turqoise type: rgb(28, 97, 65) - used as background colour in call to actions buttons, and audio player.
- The sections of the website have a black transparent colour. This to keep the hero image in the background visible.


#### Typography
- [Libre Franklin](https://fonts.google.com/specimen/Libre+Franklin#about) is the only font used throughout the website. Sans Serif is set as fallback font type.  
This font is based on the 1912 Morris Fuller Benton classic and was designed by Pablo Impallari, an Argentinian type designer based in Rosario.

#### Imagery
- A background image (hero) has been added to every page which shows the interior of the restaurant, giving the visitor a good idea about the atmosphere and of how the restaurant looks from the inside.  

#### Wireframes

<p style="color: red">Update links below</p>

- Wireframes for Home Page - [link](#)
- Wireframes for Menu Page - [link](#)
- Wireframes for Reservation Page - [link](#)
- Wireframes for Contact Us Page - [link](#)





<!-- Features -->
<a name="features"></a>
## Features

### Header

* <b>Header</b> - The header is located at the top of every page and exists out of the restaurant logo, navigation bar, and the preferred website language using clickable language flags 'English or Dutch' and is automatically loaded on every page.
* <b>Restaurant Logo</b> - The restaurant logo on the upper left side indicates the website is about a Japanese restaurant named Shibuya and is a clickable anchor element always linking to the website's index page.
* <b>The Navigation Bar</b> - The navigation bar is part of the header to let the visitor intuitively find it.
The Bootstrap CSS wireframe is used for creating the navigation bar. The current page the visitor is on is indicated by underlining the page in the navigation bar. Hovering the remaining links in the navigation bar will change the colour of the link from a white colour to an orange colour, telling the visitor that it is clickable. The navigation bar will collapse in a hamburger-styled menu when viewed on smaller devices like a smartphone.
* <b>Header Background Colour</b> - A black transparent background colour has been chosen to keep the hero image in the background partly visible. An orange colour has been used on the bottom border of the header to indicate where the header stops and the main content starts.
* <b>Language Flags</b> - Visitors can select the preferred language of the website in the header by clicking one of the two available language flags English or Dutch. By hovering over the flags, a tooltip will show up telling which language the flag image presents.
* <b>Background Audio</b> - Directly below the header on the right side, a small audio player is introduced including a Jazz song. The audio will not automatically play to not disturb the visitors when entering the website. By pressing the play button, the audio player will be looping the audio file. Together with the hero background image, it presents the restaurant's atmosphere.

### Footer
* <b>Footer</b> - The footer has been located at the bottom of every page and exists out of links to the restaurant's social media pages, and a copyright notice.
* <b>Social Media Links</b> - Icons presenting specific social media platforms from the fontawesome.com website are introduced in anchor links to redirect the visitor to the restaurant's external social media pages. By hovering the links the colour changes from white to orange, indicating these are clickable links.
* <b>Copyright Notice</b> - A clear copyright notice is visible at the bottom of the footer.

### ARIA labels
* <b>...</b> - 

### Sections

* <b>Sections</b> - The website has one or multiple sections, depending on which page you are on. These sections are recognized by a black transparent box surrounded by an orange border including a border radius. All sections start with an orange header title with a fontawesome.com icon at the end.
* <b>Paragraphs</b> - For consistency, all paragraphs in the sections have the same styling on every page.

### Buttons

* <b>Buttons</b> - For consistency, all buttons are styled the same on every page. When you hover a button, the background colour of the button will change into a darker colour.

### Responsiveness
<b>Responsivess</b> - All pages are Responsive. Minimum viewport width: 320px.


### Images
* <b>Images</b> - All images have been foreseen with 'alt' text.


### Future Features
* Feedback from previous visitors can be found on the social media pages of the restaurant. To directly implement feedback on the website, a guestbook might be a good idea to incorporate on the website. 
* An older version of bootstrap has been implemented, update to the latest version.



* <b></b>
* <b></b>
* <b></b>







<!-- Technologies Used -->
<a name="technologies"></a>
## Technologies Used

### Languages Used
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS)
- [jquery](https://en.wikipedia.org/wiki/JQuery) - Part of bootstrap framework.

### Frameworks, Libraries & Programs Used
- [Bootstrap v3.4.1](https://getbootstrap.com/docs/3.4/) - Only used for the responsive navigation bar, especially needed for creating the hamburger-styled menu on smaller devices like smartphones.
- [jquery v3.5.1](https://jquery.com/download/) - Used for the hamburger-styled menu for the navigation bar.
- [Google Fonts:](https://fonts.google.com/specimen/Libre+Franklin) - The 'Libre Franklin' font is imported from the Google Fonts Website into the style.css file. This font style is used on all pages of the website.
- [Font Awesome](https://www.fontawesome.com/) - Font Awesome icons are used on the website for linking to the social media pages of the restaurant and in the header text of the website sections.
- [Git](https://wwww.git-scm.com/) - Git was used for version control of this project. The terminal in Gitpod was used to commit and to push the project to Github.
- [Github](https://www.github.com/) - The project code has been stored on the Github website.
- [GitPod](https://www.gitpod.io/) - GitPod used for creating code, testing of the website, commiting, and pushing the code to the github repository. 
- [Photoshop v8.0](https://www.photoshop.com/en) - An older version of Photoshop (Photoshop CS version 8.0) was used to resize photos and to create the Dutch and United Kingdom flag.
- [Adobe XD](https://www.adobe.com/products/xd.html) - Adobe XD was used to create the website's Wireframes. See the Wireframes section above for the endresult.
- [JPEG Optimizer](http://jpeg-optimizer.com/) - JPEG Optimizer website used to compress image size in order to speed up loading time when loading the website/webpage.



<!-- Testing -->
<a name="testing"></a>
## Testing

### Functionality Checklist

#### Common
- Check ARIA labels.
- Check alt text.
- Check transparency of sections.
- If possible, reduce image file sizing to speed up the loading time of the images.
- Check the spelling of pages (English and Dutch version of pages).

#### Header
- Check whether the header is always on top of the page.
- Check whether the restaurant logo links back to the index page.
- Check the Active page in the navigation bar and the remaining links change colour while being hovered.
- Check for dead links.
- Check whether website language links are working properly.
- Check the responsiveness of the navbar (change to hamburger-style navbar).
- Check whether there is no overflow while reducing screen size.
- Check audio player is working properly.

#### Footer
- Check whether the footer is always at the bottom of the page.
- Check whether all social media links are working properly and opening a new blank page.
- Check whether the social media links change colour while hovering.
- Check for dead links.
- Check the responsiveness of the footer when changing the size of the viewport.

#### Index Page
- Check for dead links.
- Check whether the mailing list is functioning.
- Check the responsiveness of the sections when changing the size of the viewport.
- Check transparency of the background in the sections.
- Check Functionality of location image.

#### Menu Page
- Check the responsiveness of the menu sections when changing the size of the viewport.
- Check correct order of menu categories and images at smaller viewport width.

#### Reservations Page
- Check the responsiveness of the reservations form when changing the width of the viewport.
- Check the correct html code used for the form.
- Check functionality of required fields.

#### Contact Page
- Check the responsiveness of the contact form when changing the width of the viewport.
- Check the correct html code used for the form.
- Check functionality of required fields.

#### remaining
- 

### Testing Code
The following online validators were used to check whether every page of the project gave any syntax errors:
- [W3C Markup Validator](https://validator.w3.org/) <span style="color:red">Result</span>.
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) <span style="color:red">Result</span>.

### Testing Grammar and Spelling 
- [Grammarly.com](https://www.grammarly.com/) was used to check grammar and spelling mistakes.




### Testing User Stories from User Experience (UX) Section

#### Potential Restaurant Guest - First Time Visitor Goals
1. As a First Time Visitor of the website, I want to understand what the website's purpose is, so I can decide to navigate through the website and read all the available information or leave the website in case it did not meet my expectation.
* At the upper left corner in the website's header, the website's company logo 'Japanese Restaurant Shibuya' immediately tells new visitors that they have ended up on a Japanese Restaurant website.
* To make it even more clear, a background (hero) image of the restaurant has been added to every page, telling first time visitors they probably have ended up on a restaurant website.
* A navigation bar in the header at the top of every page, including links to a 'Menu' and 'Reservation' page also suggest the website is probably about a restaurant.
* To make the purpose of the website fully clear, a 'Welcome' section on the 'Home' page has been added, stating that visitors have ended up on a Japanese Restaurant website. Also, the 'About Section' below the 'Welcome Section' tells more about what the purpose of the website is.

2. As a First Time Visitor of the website,  I want to know more about the restaurant's atmosphere.
* A clear background (hero) image of the restaurant has been added to every page, so that visitors of the website immediately know how the interior of the restaurant looks like. 

3. As a First Time Visitor of the website, I want to know what the restaurant has to offer and at what price, so that I can decide whether I want to visit the restaurant somewhere in the future in case it meets my expectations.
* In the navigation bar, a link to the 'Menu' page has been added. Also in the 'Welcome Section' on the starting page, a call to action button has been added to directly send potential guests to the 'Menu' page.
* On the 'Menu' page, the menu has been subdivided into Categories listing menu items including their price. To make it clear what guests can expect when ordering some of the menu items, images of these menu items have been added to the menu.

4. As a First Time Visitor of the website, I want to know where the restaurant is located, so that I can decide whether the restaurant is within my desired traveling distance.
* In the navigation bar, a link to the 'Menu' page has been added. Also in the 'Welcome Section' on the starting page, a call to action button has been added to directly send potential guests to the 'Menu' page.
* On the 'Menu' page, the menu has been subdivided into Categories listing menu items including their price. To make it clear what guests can expect when ordering some of the menu items, images of these menu items have been added to the menu.

5. As a First Time Visitor of the website, I want to know what previous guests have to say about the restaurant, so that I have an idea of what to expect when visiting the restaurant.
* In the website's footer, external links to the restaurant's social media channels have been added. Here previous and returning guests of the restaurant make comments and discuss with other people how they have experienced their visit to the restaurant.
* Not implemented on the website for now, but an online guestbook on the website would also be a good idea to get feedback from previous guests.

6. As a First Time Visitor of the website, I want to know whether it is needed to make a reservation, so that I can take that into account when I want to visit the restaurant in the future.
* In the navigation bar, a link to the 'Reservation' page has been added.
* In the 'About our Restaurant' Section, a call to action button has been added which will send you to the 'Reservation' page.
* On the 'Reservation' page a clear form has been added with all the needed information to make a reservation at the restaurant.

7. As a First Time Visitor of the website,  I want to know on what day and at what time it is possible to visit the restaurant, so that I know when to make a reservation in case I want to visit the restaurant in the future.
* On the 'Home' page of the restaurant, an 'Opening Hours' section has been added which indicates on what day and between what times the restaurant is opened.
* On the Reservation form on the 'Reservation' page, a pulldown menu where you can select your desired date and a pulldown menu where you can select a limited time when you can make a reservation have been added.

8. As a First Time Visitor of the website, I want to know how and if I can get additional information about the restaurant in case it's not mentioned on the website.
* In the navbar, a link to the 'Contact' page has been added. On this page, a form has been added where you can include a message in case you want to ask a question or you want additional information about the restaurant.
* The 'Where to Find us' section on the 'Home' page, also states the website's e-mail address.

9. As a First Time Visitor of the website, I want to know what the methods of payments are, so that I know whether to bring cash or a credit card before visiting the restaurant in the future.
* On the website 'Home' page a 'Payments Method' section has been added. Next to paying with cash, it also indicates what credit cards are accepted by utilizing small images of the accepted credit cards including their logos. The remaining accepted payment method is bitcoin cash which is also indicated with a small image.

#### Returning Restaurant Guest - Returning Visitor Goals
1. As a Returning Visitor of the website, I want to know whether there are new items added to the menu in the recent weeks or months, so that I can decide whether I might order them next time when visiting the restaurant.
* On the menu, it is indicated which menu items are added by adding next to the menu item's description 'new' with a red colour.
* Also on the menu, it is clearly stated when the menu was updated the last time.

2. As a Returning Visitor of the website, I want to know whether there is any important news or announcement about the restaurant without having to check the website regularly.
* On the 'Home' page a 'Mailing List' section has been added. Here interested visitors can add their e-mail address, so that they will receive the latest news and announcements about the restaurant in their e-mail box.

### Further Testing
...

### Known Bugs
...






<!-- Deployment -->
<a name="deployment"></a>
## Deployment

### GitHub pages
...

### Forking the GitHub Repository
...

### Making a Local Clone
...






<!-- Credits -->
<a name="credits"></a>
## Credits

### Code
...

### Content
...

### Media
- All pictures shown are for illustration purposes only and are not owned by the web developer, all copyrights and credit go to the respective owner.  
- The Dutch and United Kingdom flag used for selecting the website language was created by the website developer.

#### Sources of Used Images
- <span style="color: red">Add</span>


### Acknowledgements
...








## Bugs
* Floating problem: header section moves down together with article section when the top-margin of the article-section is set to 30px. This problem was solved by deleting the CSS rule float: left; in the navbar-div.  

## Testing
* Language flags are too big for iPad and smartphone, size to be adjusted.
* On smaller devices, the English flag stays on top of the Dutch flag, this should be otherway around, to be fixed.
* Map image will not center in section, to be fixed.

## fix
* Background image file to be resized.
* Make background image responsive.