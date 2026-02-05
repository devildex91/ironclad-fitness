# ironclad-fitness

## Table of Contents 
1. ### [UX](#1-ux)

+ Primary Goals
+ Business Goals
+ User Goals
+ User Stories 
+ Design Choices 
+ Wireframes 

2. ### [Features](#2-features) 
+ Existing Features 
+ Features left to implement

3. ### [Technologies used](#3-technologies-used)
  
4. ### [Testing](#4-testing)

5. ### [Deployment](#5--deployment)

+ How to run this project

6. ### [Credits](#6-credits) 
+ Content
+ Media
+ Code 
+ Acknoledgements

<details>
<summary> 1. UX </summary>

 ---

#### Primary Goals 
---

The primary goal of Ironclad Fitness is to provide a eye catching, informative, and easy to navigate website that will showcase all the great things about Ironclad Fitness. The main target audience for this website will be current members who want to see what else is avaliable to them at Ironclad Fitness and potential new members looking for somewhere new to train or somewhere to train for the first time.

#### Business Goals
---

The main business goal is to bring in new clients by increasing membership intake while decreasing membership fall off after a new year spike. They aim to showcase all of the great benefits of their gym that far outweigh just the equipment on the floor by showcasing what a great community spirit can be gained as well as showcasing that its not just for bodybuilders but a place for every person at every level of fitness.

#### User Goals
---

+ The user goals for new users are to find somewhere they feel comfortable to either start training for the first time or just somewhere they feel better suited to training. 
+ Current members user goals are to check what i going on at the gym such as classes they could book in for or opening hours during holidays as well as any special offers they may be able to take advantage of.

#### User Stories
---
 + For full Acceptance Criteria and tasks please follow [this link](https://github.com/users/devildex91/projects/4) to the project board for Ironclad Fitness

 +  As a first time visiter to the site I would like everything to be easy to find to so i can easily navigate to wherever I would like to on the site.
<details>
<summary>screenshot of navbar</summary>

![navbar desktop view](./assets/images/navbar-section-dv.png)
![ section mobile view](./assets/images/navbar-section-mv.png)

</details> 

 + As a member I would like access to a weekly timetable of classes and special events that are happening.
 <details>
 <summary>screenshots of timetables</summary>
 
 ![timetables](./assets/images/timetable.png)
 ![carousel](./assets/images/special-event-ss.png)
 
 </details>

 + As I have a very busy schedule i would like to be able to find out the busiest times of day by visiting your website so i can fit my visits around my lifestyle without standing around waiting for machines and equipment.(to be implemented at a later date see acceptance criteria above for more info)
  
  + As a potential new customer i would like to see some images of the different parts of the gym so i can see what machines are being used and to make sure it has the right feel for me.
  <details>
  <summary>Screenshot of take the tour page</summary>
  
  ![image of ttt mv](./assets/images/ttt.html-mv-ss.png)
   ![image of ttt dv](./assets/images/ttt.html-dv-ss.png)

  </details>

  + I would like to be able able to view this website on any of my devices so i manage my membership on the go. 
<details>
<summary>Screenshot of main pages</summary>

 ![image of homepage mv](./assets/images/index.html-mobile-ss.png)
  ![image of homepage dv](./assets/images/index.html-dv-ss.png)

</details>
  
  + As a customer I would like to know what experience and qualifications the staff have to make sure that they will be able to help me if i need it.(to be implemented at a later date see acceptance criteria above for more info)

  + As a current member I would like to be able to book my place on classes through the website.
  <summary>screenshots of timetables</summary>
 
 ![timetables](./assets/images/timetable.png)
 
 </details>

+ As A new visitor I would like to see membership options and sign up online.
<details>
<summary>Screenshop of membership section</summary>

![membership options](./assets/images/membership-ss.png)

</details>

#### Design Choices
---
+ Responsive navbar that uses the avaliable space whilst keeping things minimalist for the best user experience.
+ Footer kept consistent throughout so that it is intuitive for the user and key information is allways in the same place regardless of what device is used.
+ Image inserted in confirmation page to improve the visuals of the page.
+ Membership options are cards rather than a table to make them stand out and make them clear and consise to the user.
+ Title added to key information carousel to make it stand out more and as a way to keep up with whether week 1 or 2 was being used in the whats on section
+ Footer opening hours and contact details are on the same table for space-saving and visually easier to read as only got to look for all information regarding contacting and hours in the ame place.


##### Fonts
---
+ Archivo black-Titles
+ Kite One- paragraphs  
+ Archivo one because it is bold and strong and subconsciously represents the weight lifting. 
+ Kite one has been chosen for main content as it is easily readable, contrasts well to Archivo and is more of an active looking font to reference the cardio aspects of gym life.

##### Colours
---
 + #000000 black
 + #CFFFE2 Mint
 + #A2D5C6 light-cyan
+ #F6F6F6 grey 

<details>

<summary>palete of colour choices</summary>

 ![palete of colors fron top to bottom black,Mint,light-cyan and grey](./assets/images/color-choices.webp)
</details>

+ I have chosen these colors because black gives it a minimalist feel and has been shwon to add a sense of power as well as the light grey to contrast well with the black and to offer a sense of simplicity and to make it feel larger. The mint and light cyan colours have been added as they have been shown  to offer a sense of tranquility and feeling refreshed. All of these i beleive are key takeaways from what multiple people hope to feel after a gym session. 

##### Styling
---
+ Firstly the overall responsivness of the website will use bootstrap grid properties with a mixture of built in bootstrap styling and and overiding styles will use a local CSS file.
+ Fonts for styling have been imported from [google fonts.](https://fonts.google.com/selection/embed)
+ The overall colour scheme for the styling has been chosen from [color palete.](https://colorhunt.co/palette/000000cfffe2a2d5c6f6f6f6)  
+ Any favicons added in both the title and within any headings and link for readibility will be taken from [fontawesome.](https://fontawesome.com/)
+ The website has been styled so that it is for the most part all centred where possible or evenly spread out to give a regimented feel like most workouts to show that its not about fancy equipment but consistency to get to your goals which means the layout matches with the views of the gym.
+ The only exception to this is the motivational quotes on the take the tour page which are designed to be off center so they stand out like intended.
##### Background
--- 
+ The navbar and footer will be styled with a black background and the light grey from the chosen colours will be used for the font in these for contrast and readability.
+ The header section will be mint and the main content will be light cyan as these colours sit nicely together without drawing too much attention away from the other section while clearly defining  the different parts of the page.
+ I debated using a background image to improve it visually but decided against as felt it would distract from the simplistic design of the page showcasing that training isnt all about using the latest fancy gimics but simple and consistent which reflects in the choices of background.

##### images
---

All images have been sourced from google Gemini to give the appearence of the company giving me a selection of pictures to work from which are of a good enough to display the theme of the website and reflect the palete of colours chosen.
##### Wireframes

---

<details>
<summary>Wireframe for screens < 579px </summary>

+ ![wireframe for screens < 576px](./assets/images/Ironclad%20Fitness%20phoneframe.webp)
</details>
<details>
<summary>Wireframe for screens >=768px</summary>

+ ![wireframe for screens >=768px](./assets/images/Ironclad%20fitness%20tabletframe.webp)
</details>
<details>
<summary>Wireframe for screens >=992px</summary>

+ ![wireframe for screens >=992px](./assets/images/Ironclad%20Fitness%20desktopframe.png)
</details>

</details>
<details>
 <summary> 2. Features </summary>

 ---
  
 #### Existing Features
 ---
 + Responsive layout that works on both mobile and desktop for all pages
  + carousel of text that features key information for users and gym goers
 + Clearly displayed membership options as well as a form to book your membership.
 + Opening times and contact details clearly displayed in same place on every page no matter the screen for a more intuitive experience.
+ Images of both weights room and fitness suitesresponsive for all screen sizes
+ The ability to see what events are on each week as well as a form to book your place as well any costs you may be subject to pay and how to pay.
+ A confimration page that lets the user know they have submitted the form succesfully.
+ hover effects on all forms to know exactly which box you have selected as well as hover effects on links in the nav bar for easier navigation as well as on images.
+ links to every page and links to specific sections of the page such as membership options and to book a class.  

 
 
 
 
 <details>
 <summary>Pages screenshots showing all features mentioned above</summary>
 <details>
 <summary>index.html screenshots</summary>

  ![image of homepage mv](./assets/images/index.html-mobile-ss.png)
  ![image of homepage dv](./assets/images/index.html-dv-ss.png)
  </details>
  <details>
  <summary>take-the-tour.html screenshots</summary>

   ![image of ttt mv](./assets/images/ttt.html-mv-ss.png)
   ![image of ttt dv](./assets/images/ttt.html-dv-ss.png)
    </details>
    <details>
    <summary>whats-on.html screenshots</summary>

   ![image of whats on dv](./assets/images/whatson.html-dv-ss.png)
   ![image of whats on mv](./assets/images/whatson.html-mv-ss.png)
</details>
<details>
<summary>confirmation.html screenshots</summary>

  ![image of confirmation mv](./assets/images/confirmation.html-mv-ss.png)
  ![image of confirmation dv](./assets/images/confimration.html-dv-ss.png)

 </details>
 </details>

 #### Features left to implement
 ---

 + Live updates and peak times have been left to implement at a later date once more data has been collected to provide more accurate results.
 + details on qualifications also to be added as not seen as crucial for this stage of the development
</details>
<details>
 <summary>3. Technologies used </summary>
 
  ---
  + Visual Studios used as the primary IDE. 
  + Bootstrap(v5.3) for main layout and responsive design. 
  + flexbox for improved responsive design.  
  + Google Gemini for photos and company logo used in navbar and copyright at bottom of page 
  + Github for deployment. 
 </details> 
 <details>
 <summary>4. Testing</summary>
 
 ---
+  Manual testing was carried out and all images loaded properly and all links worked perfectly.
+ First batch of photo werent inkeeping with the layout and theme of the page and were not reacting properly so took the desicion to delete all pictures and use AI generated pictures which helped load times and were still good quality images but with a file size about 90% smaller sacrificing a tiny bit of image quality for better visuals and a better overall build.
+ Photos were not being as reactive and sizing was not acting as intended so an extra css class .ttt-pics has been added in to provide a min-height for alignment purposes as screen gets larger to keep it responsive and looking good.
+ Once deployed first round of lighthouse testing was not up to scratch as the photos too large and taking too long to load.
+ Tried converting to webp file types and compressing them which improved the load time considerably but was still taking considerably longer than needed.
+ Fixed this by compressing and reducing image size as well as converting to avif files and load times improved comsiderably.
+ main section of confirmation rising on further inspection so background colour changed for confirmation page to allow the main section to move without effecting the visuals of the page.
<details>

   
<summary>Lighthouse tests screenshots</summary>

 ![lighthouse test for index.html](/assets/images/lighthouse-test-index.png) 
+ ![lighthouse test for take the tour](/assets/images/lighthouse-test-ttt.png)
+ ![lighthouse test for whats on](/assets/images/lighthouse-test-whats-on.png)
+ ![lighthouse test for confirmation](/assets/images/lighthouse-test-confirmation.png)
</details>

+ All lighthose testing in 90s apart from whats-on page as this page displays more content in the form of google fonts slowiong down loading times
+ All photos have been updated to Ai generated ones which have then been converted to avif files and compressed so are of a good enough quality for normal visuals but lower the best practices scores by a couple of percent but improve load times by almost 20% which i believe is a good compromise as if it was a real company photos would all be provided by the company 

<details>
<summary>HTML tests screenshots</summary>

![html test index.html](./assets/images/index.html%20check.png)
![html test ttt.html](./assets/images/ttt.html-check.png)
![html test whats-on](./assets/images/whats-on.htmlcheck.png)
![html test confirmation](./assets/images/confirmation.htmlcheck.png)
</details>

+ HTML code tested at [validator.w3](https://validator.w3.org/) all pages passed with no errors or warnings.

+ CSS tested at[jigsaw.w3](https://jigsaw.w3.org/css-validator/) and the css validates as CSS level 3 + SVG. 
 <p>
    <a href="https://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="https://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p> 
<p>
 <a href="https://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="https://jigsaw.w3.org/css-validator/images/vcss-blue"
            alt="Valid CSS!" />
    </a>
</p>
<details>
<summary>  Contrast testing screenshots</summary>

![navbar/footer colours](./assets/images/navbar-contrast-checker.png)
![header contrast](./assets/images/header-contrast-check.png)
![main contrast](./assets/images/main-contrast-check.png)
</details>

+ Navbar/footer contrast check all passed black background with light grey text(first image)
+ Header contrast check all passed mint background black font(second image)
+ Main contrast check all passed cyan background black font(third image)


</details>
<details>
<summary> 5 . Deployment</summary>

---

[To view site](https://devildex91.github.io/ironclad-fitness/)
<details>

 <summary>Site has been deployed through Github pages by:</summary>

 ---

 1. Go to [devildex91/ironclad-fitness](https://github.com/devildex91/ironclad-fitness).
 2. click on the settings button ![settings](./assets/images/settings.png)
 3. Scroll down and click on pages ![pages](./assets/images/pages.png)
 4. In the branch select main ![main](./assets/images/main-button.png)
 5. Refresh the page(this may take a couple of minutes to update) and click the link to view.
 </details>
 <details>
 <summary> To download and work on the code yourself locally. </summary>

 ---

 1. Navigate to [devildex91/ironclad-fitness](https://github.com/devildex91/ironclad-fitness)
 2. Click on the green code button ![picture of green code button](./assets/images/code-button.webp) 
 3. Select download zip as shown. (This will save a copy of of the repository on your device). ![image of download zip to click on](./assets/images/downloadzip.webp).
 4. Once downloaded unpack zipped file to a location of your choosing and you can work on and run the code in an IDE of your choosing(Have fun). 
 </details>
 <details>
<summary> To fork a repository.</summary>

---

+ please see [github docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) for more detailed and an easier to follow guide than I can produce but remember to navigate to [devildex91/ironclad-fitness](https://github.com/devildex91/ironclad-fitness) to fork this repository.

</details>

+ ##### Note for anybody working on this code that bootstrap 5.3 has been used to create much of the page and should be reused by yourself to ensure it all works as intended.
</details>
<details>
<summary> 6. Credits</summary>
---

#### Content 
---
+ fonts imported from [google fonts.](https://fonts.google.com/selection/embed) 

+ colourscheme from [color palete.](https://colorhunt.co/palette/000000cfffe2a2d5c6f6f6f6) 
+ basic layouts for cards,carousel and tables from [bootstrap](https://getbootstrap.com/)
+ basic form layout and buttons from [bootstrap](https://getbootstrap.com/)
+ All basic bootstrap elements have custom layouts and classes on top of to polish off layout to suit the page.

#### Media 
---
+ All pictures and favicons generated using Google Gemini. 
+ for all image optimisation [squoosh](https://squoosh.app/) has been used to help with the resize of images and compression tasks.

#### Code 
---
+ responsiveness grid from [bootstrap v5.3](https://getbootstrap.com/)
+ flexbox also used to help with alignment issues and customise further from bootstrap standard.
#### Acknoledgements
+ [stack overflow](https://stackoverflow.com/) was used for the inspiration on how to create the text carousel.
+ [geekforgeeks](https://www.geeksforgeeks.org/)used for transform property on hover elements on images and links in navbar. 
</details>














