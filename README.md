
#### TODO LIST
<ul style="color: red;">

    - CHECK DOUBLE CODE
    - MAKE ONE STYLING CLASS FOR ALL SECTIONS
    - CHECK ALL CREDITS
    - CHECK ALL LINKS IN README FILE
    - CHECK SPELLING IN README FILE
    - ADD ARIA LABELS
    - CHECK PARAGRAPH SIZES
    - CHECK ALT TEXT

</ul>

<h1>Japanese Restaurant Shibuya</h1>

<!-- Responsive Image -->
<img src="assets/readme-images/responsive.png" alt="Responsive Design of Website">


<!-- Links -->
View the live project [here](https://eburonia.github.io/japanese-restaurant-shibuya/)<br>
View the GitHub Repository [here](https://github.com/Eburonia/japanese-restaurant-shibuya)


<!-- About -->
## About
These days there are still restaurant owners who are not active on the internet by owning a website or being active on social media.
By creating this example 'Japanese Restaurant Shibuya' website, we will show the importance of being active on the internet to these restaurant owners.
We will give them an idea how a typical restaurant website will look like and we will show what the added value for them is.
This website could also be valuable for restaurant owners who already own a personal restaurant website, but are looking for inspiration or new ideas.
  

<!-- Table of Contents -->
## Table of Contents

[User Experience (UX)](#UX)

[Features](#features)

[Technologies Used](#technologies)

[Testing](#testing)

[Known Bugs](#bugs)

[Deployment](#deployment)

[Credits](#credits)


<!-- User Experience (UX) -->
<a name="UX"></a>
## User Experience (UX)

### User Stories

#### Potential Restaurant Guest - First-time Visitor Goals
1. As a first-time visitor of the website, I want to understand what the website's purpose is, so I can decide to navigate through the website and read all the available information or leave the website in case it did not meet my expectation.
2. As a first-time visitor of the website, I want to know more about the restaurant's atmosphere.
3. As a first-time visitor of the website, I want to know what food the restaurant has to offer and at what price, so that I can decide whether I want to visit the restaurant somewhere in the future in case it meets my expectations.
4. As a first-time visitor of the website, I want to know where the restaurant is located, so that I can decide whether the restaurant is within my desired traveling distance.
5. As a first-time visitor of the website, I want to know what previous guests have to say about the restaurant, so that I have an idea of what to expect when visiting the restaurant.
6. As a first-time visitor of the website, I want to know whether it is needed to make a reservation, so that I can take that into account when I want to visit the restaurant in the future.
7. As a first-time visitor of the website, I want to know on what day and at what time it is possible to visit the restaurant, so that I know when to make a reservation in case I want to visit the restaurant in the future.
8. As a first-time visitor of the website, I want to know what the methods of payments are, so that I know whether to bring cash or a credit card before visiting the restaurant in the future.
9. As a first-time visitor of the website, I want to know how and if I can get additional information about the restaurant in case it's not mentioned on the website.

#### Returning Restaurant Guest - Returning Visitor Goals
1. As a returning visitor of the website, I want to know whether there are new items added to the menu in the recent weeks or months, so that I can decide whether I might order them next time when I visit the restaurant.
2. As a returning visitor of the website, I want to know whether there is any important news or announcement about the restaurant without having to check the website regularly.


### Design

#### Colour Scheme
- To not get distracted too much, the used colours on the website meet the colours of the background hero image. Three types are used for styling the html elements:
   * Black: rgba(0, 0, 0, 0.95) - used in headers, footers, and sections background.
   * Cream colour type: rgb(195, 161, 104) - used in restaurant logo, h2 and h3 headers, sections, image borders, buttons, and textboxes.
   * Smokewhite: rgb(245, 245, 245) - used in header, footer, navbar, paragraphs, menu items, and form labels.
- The sections of the website have a black transparent colour. This to keep the hero image in the background a little bit visible, but not too much that you can't read the text anymore.
- For emphasizing purposes a red colour is used for new menu items and important messages like required text fields on a form.

#### Typography
- [Libre Franklin](https://fonts.google.com/specimen/Libre+Franklin#about) is the only font used throughout the website. Sans Serif is set as a fallback font type. Libre Franklin is a well-readable font. 
This font is based on the 1912 Morris Fuller Benton classic and was designed by Pablo Impallari, an Argentinian type designer based in Rosario.

#### Imagery
- A background image (hero) has been added to every page showing the restaurant's interior, giving the visitor an idea about the restaurant's atmosphere.
- Potential customers need to have an idea how some of the menu items might look like in reality. For that reason, every menu category has an image belonging to that category added including an example dish.  

#### Wireframes

Wireframes belonging to the website's project have been made in Adobe XD. PDF files of them can be found here:
- Wireframes for Index Page - [link](https://github.com/Eburonia/japanese-restaurant-shibuya/blob/2ffdafa655a8ec6e7725af011a44c6b9dacfc1e8/wireframes/wireframes-index.pdf)
- Wireframes for Menu Page - [link](https://github.com/Eburonia/japanese-restaurant-shibuya/blob/2ffdafa655a8ec6e7725af011a44c6b9dacfc1e8/wireframes/wireframes-menu.pdf)
- Wireframes for Reservations Page - [link](https://github.com/Eburonia/japanese-restaurant-shibuya/blob/2ffdafa655a8ec6e7725af011a44c6b9dacfc1e8/wireframes/wireframes-reservations.pdf)
- Wireframes for Contact Us Page - [link](https://github.com/Eburonia/japanese-restaurant-shibuya/blob/2ffdafa655a8ec6e7725af011a44c6b9dacfc1e8/wireframes/wireframes-contact.pdf)

All wireframes are designed for three different devices:
- Desktop - Web: maximum pixels 1920px
- iPad - Nexus 9: maximum pixels 768px
- iPhone 12 Pro Max: maximum pixels 428px

#### Mockups
- The intention was to also create mockups for the website project. Due to the limited available time of the web developer, it has been skipped. Nevertheless, it is important to also invest time in creating mockups for future projects. Lesson learned by the project creator.


<!-- Features -->
<a name="features"></a>
## Features

### Header
The header is located at the top of every page and exists out of the restaurant logo, navigation bar, and the preferred website language using clickable language flags 'English or Dutch' will be automatically loaded on every page.
* <b>Restaurant Logo</b> - The restaurant logo on the upper left side indicates the website is about a Japanese Restaurant named Shibuya and is a clickable anchor element always linking to the website's index page.
* <b>The Navigation Bar</b> - The navigation bar is part of the header and will be intuitively found by the visitor. A cream coloured stripe above a navbar item makes it clear to visitors on which active page they are on at the moment. The navbar will automatically change to a 'hamburger' type navbar at smaller devices (smart-phones). Hovering the navbar items will change the colour making it clear to visitors it's clickable.
* <b>Background Colour</b> - A black transparent background colour has been chosen for the header to keep the hero image in the background partly visible.
* <b>Language Flags</b> - Visitors can select the preferred language of the website in the header by clicking on one of the two available language flags 'English' or 'Dutch'. The website will be automatically loaded in the English language when landing on the homepage. By hovering over the flags, a tooltip will show up telling which language the flag presents.
* <b>Background Audio</b> - On the bottom right side, directly below the header, a small audio player is introduced. A Jazz styled audio file has been added and to not disturb the visitors when entering the website, you need to push the play button first to start the audio playing in the background. The audio file loops until you press the pause button.

### Footer
The footer has been located at the bottom of every page and exists out of anchor links to the restaurant's social media pages, and a copyright notice.
* <b>Background Colour</b> - A black transparent background colour has been chosen for the footer to keep the hero image in the background partly visible.
* <b>Social Media Links</b> - Icons presenting social media platforms from the fontawesome.com website are introduced as anchor links to redirect the visitor to the restaurant's external social media pages (blank page). By hovering the links the colour changes from white to cream colour, indicating these are clickable links.
* <b>Copyright Notice</b> - A clear copyright notice is visible at the bottom of the footer.

### Sections/Divisions
The website has one or multiple sections/divisions with content, depending on which page you are on. These sections/divisions are recognized by a black transparent box surrounded by a cream-coloured border including a border-radius. All sections/divisions start with a cream-coloured header h2 with a fontawesome.com icon at the end.

### Menu Page
The 'Menu' page exists out of a combination of sections (menu items) and divisions (images). These are inline next to each other for bigger devices. When the device width becomes too small, the sections and divisions will be on top of each other (block) to keep it readable.

### Forms
The forms on the 'Reservations' and 'Contact' pages both have the same styling. The labels, fields, and header h2 will be smaller in size on smaller devices (smart phones) for readability purposes.

### Paragraphs
For consistency, all paragraphs have the same styling.

### Links
Only the index page has clickable links outside the header and footer.
* <b>Index Page</b> - Links on the index page you can find in the 'Welcome' and 'About' sections of the page. The anchor links in the 'Welcome' section are styled in such a way they look like buttons and are styled the same way as real buttons used on the website. The anchor links in the 'About' section are styled by a bold cream colour to distinguish themselves from the remaining text. By hovering the links an underline will appear, making it clear to visitors these are clickable links. 

### Buttons
Buttons can be found on the index, reservations, and contact page and are all styled the same way: cream colour border and text with a black background. When hovering the buttons also the background colour changes to a cream type of colour, making it clear to visitors it's a clickable button.

### Responsiveness
All pages are responsive on all devices. Minimum viewport width: 320px.

### Accessibility
* All images have been foreseen with an alternative (alt) text in case the image cannot be loaded but also helps screen readers.
<span color:red>ARIA LABELS</span>

### Future Features
* Feedback from previous visitors can be found on the social media pages of the restaurant. To directly implement feedback on the website, a guestbook might be a good idea to incorporate on the website in the future.
* An older version of bootstrap has been implemented for the navigation bar only. Update to the latest version in the future.

<!-- Technologies Used -->
<a name="technologies"></a>
## Technologies Used

### Languages Used
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS)

### Frameworks, Libraries & Programs Used
- [Bootstrap v3.4.1](https://getbootstrap.com/docs/3.4/) - Only used for the responsive navigation bar, especially needed for creating the hamburger-styled menu on smaller devices like smartphones.
- [jquery v3.5.1](https://jquery.com/download/) - Used for the hamburger-styled menu for the navigation bar, part of the bootstrap framework.
- [Google Fonts:](https://fonts.google.com/specimen/Libre+Franklin) - The 'Libre Franklin' font is imported from the Google Fonts Website into the header.css file. This font style is used on all pages of the website.
- [Font Awesome](https://www.fontawesome.com/) - Font Awesome icons are used on the website for linking to the social media pages of the restaurant and in the header h2/h3 of the website sections/divisions.
- [Git](https://wwww.git-scm.com/) - Git was used for version control of this project. The terminal in Gitpod was used to commit and to push the project to Github.
- [Github](https://github.com/Eburonia/japanese-restaurant-shibuya) - The project code has been stored on the Github website.
- [GitPod](https://www.gitpod.io/) - GitPod was used for creating the code, testing of the website, commiting, and pushing the code to the github repository. 
- [Photoshop v8.0](https://www.photoshop.com/en) - An older version of Photoshop (Photoshop CS version 8.0) was used to resize images and to create the Dutch and United Kingdom language flags you can find in the header.
- [Adobe XD](https://www.adobe.com/products/xd.html) - Adobe XD was used to create the website's Wireframes. See the Wireframes section above for the endresult.
- [JPEG Optimizer](http://jpeg-optimizer.com/) - JPEG Optimizer website was used to compress image size in order to speed up loading time when loading the website/webpage.


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

<!-- Known Bugs -->
<a name="bugs"></a>
## Known Bugs
- Slow loading time of the hero images and menu images when loading the website for the first time. The problem can probably be solved by reducing the file size.
- Loading the bootstrap navigation bar for the first time shows a small black border around the navigation bar, but will disappear when the custom CSS style of the navigation bar is loaded.

<!-- Deployment -->
<a name="deployment"></a>
## Deployment

### Publishing
GitHub Pages was used for publishing the website. The procedure was as follows:
1. Login to the [GitHub](https://www.github.com/) website.
2. On the left side of your screen, you can find a summary of all your repositories. Select [Eburonia/japanese-restaurant-shibuya](https://github.com/Eburonia/japanese-restaurant-shibuya)
3. You can find a ribbon on the top of your screen, click on 'Settings'.
4. In the selection menu on the left side of your screen, click on 'Pages'.
5. Under 'Source' you will find a small pull-down menu. Click on it and select 'main' and then press the 'Save' button.
6. You will automatically get redirected to the 'GitHub Pages' page. There will be a blue box telling the site will be published.
7. Refresh the page and when this box turns green, the website has been published.
8. Click the link in the green box to check the website.

### Forking
If you want to make a copy of the repository you can Fork it without changing the original repository by following the next procedure:

1. Login to the [GitHub](https://www.github.com/) website.
2. On the left side of your screen, you can find a summary of all your repositories. Select [Eburonia/japanese-restaurant-shibuya](https://github.com/Eburonia/japanese-restaurant-shibuya).
3. On the right side of your screen, next to the 'Unwatch' pull-down menu, and the 'Star' button, you can find the 'Fork' button.
4. By clicking this button, it will create a copy of the website in your repository.

### Cloning

You can clone the repository by following the next procedure:

1. Login to the [GitHub](https://www.github.com/) website.
2. On the left side of your screen, you can find a summary of all your repositories. Select [Eburonia/japanese-restaurant-shibuya](https://github.com/Eburonia/japanese-restaurant-shibuya).
3. Click on the 'Code' button next to the Green 'GitPod' button.
4. Click on 'HTTPS' and copy the hyperlink: https://github.com/Eburonia/Test-project.git below it.
5. Go to the repository where you want to make a clone of the website. Or create a new repository.
6. When in this repository, select the folder or create a folder where you want to copy the cloned directory.
7. Go to the terminal and type: 'Git Clone https://github.com/Eburonia/Test-project.git' and press enter. The directory has been cloned now.

### Downloading

You can download the repository by following the next procedure:

1. Login to the [GitHub](https://www.github.com/) website.
2. On the left side of your screen, you can find a summary of all your repositories. Select [Eburonia/japanese-restaurant-shibuya](https://github.com/Eburonia/japanese-restaurant-shibuya).
3. Click on the 'Code' button next to the Green 'GitPod' button and then click on 'Download ZIP'.
4. A .zip file of the repository content will be downloaded. 


<!-- Credits -->
<a name="credits"></a>
## Credits

### Code
- All code was written by the website creator: Maurice Vossen
- Colours were selected by using Photoshop v8.0
- Understanding float and clear CSS code [link](https://www.youtube.com/watch?v=xara4Z1b18I)
- Understanding display: flex CSS code [link](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

### Content
- The following README files were used as inspiration for creating this README file:
   * Boredom Guide [README](https://github.com/LigaMoon/Boredom-guide/blob/master/README.md) file
   * Code Institute Website[README](https://github.com/Code-Institute-Solutions/SampleREADME) file
   * Code Institute Love Running [README](https://github.com/Code-Institute-Solutions/readme-template) file
- Inspiration for Restaurant's about section
   * Partly copied and adjusted from: [Japanese Restaurant Kobe Maastricht](https://www.restaurantkobe.com/)
   * Partly copied and adjusted from a New York based Japanese restaurant, can't find the link to the website anymore.

- Inspiration for the menu page:
   * Example Japanese menu [link](https://i.pinimg.com/originals/d3/2e/f4/d32ef41a9a546250ab54f856e1f71b6f.jpg)
   * The 8 Most Popular Types of Fish Served as Sashimi [link](https://rbsushi.com/blog/8-most-popular-types-of-fish-served-as-sashimi/)
   * Types of Sashimi in Japan: The Essential Guide [link](https://gurunavi.com/en/japanfoodie/2016/10/sashimi-in-japan.html?__ngt__=TT11bfdb473003ac1e4ae61dJHkbBnFG9SLeZoHOmkr4Ow)
   * Wikipedia: List of Japanese soups and stews [link](https://en.wikipedia.org/wiki/List_of_Japanese_soups_and_stews)
   * 10 Must Drink Types of Popular Japanese Alcohol [link]( https://gurunavi.com/en/japanfoodie/2017/07/10-must-drink-japanese-alcohol.html)
   * How Many of These 10 Popular and Tasty Japanese “Yaki” Dishes Have You Tried? [link](https://jpninfo.com/105574)

### Media

#### Images
- All pictures shown are for illustration purposes only and are not owned by the web developer, all copyrights and credit go to the respective owner
- The free to use background hero image is coming from [Unsplash.com](https://unsplash.com/@dineshramaswamy)
- For the menu page, the following images were taken from the [pixabay](https://www.pixabay.com/) website:
   * Sushi image [link](https://pixabay.com/photos/sushi-food-japan-2363418/)
   * Sashimi image [link](https://pixabay.com/photos/sashimi-food-seafood-tuna-cuisine-2563650/)
   * Okinawa Soba [link](https://pixabay.com/photos/okinawa-soba-okinawa-1697765/)
   * Takoyaki [link](https://pixabay.com/photos/food-takoyaki-ball-1614130/)
   * Highball Whiskey [link](https://pixabay.com/photos/whiskey-highball-nanning-654449/)   
- The Dutch and United Kingdom flag used for selecting the website language were created by the website developer

#### Audio
- The audio player's Jazz Loop mp3 file is a copyright free audio file coming from Youtube / Soundclound: [Ryan - Milk Coffee [No Copyright Music]](https://www.youtube.com/watch?v=eSOV2Zo_J1A)  

### Acknowledgements
- Thanks to my personal mentor Maranatha Ilesanmi for answering my questions and giving feedback.
- The many free coding forums on the internet for providing answers to my coding questions.