# Simon Paske photography

Simon Paske photography is a website that allows user to read a short story about my photography path and earned achievements. Moreover, user is getting a better understanding what kind of person I am as a human being and what photography means to me. The web page also provides a small collection of various genre images and short presentational video with my works.

You can visit live website --> [here](https://simonpaske.github.io/simon-paske-photography/)

![Mockup](docs/readme_images/mockup.png)

---

### Sitewide

* Dropdown Navigation Menu
  * Contains links to Home, Gallery and Contact pages. It will be responsive on all devices.
  * It will gives user an opportunity to easily use and navigate throught the website on any device.

![Navigation Menu](docs/readme_images/navigation_menu.png)

---

* Footer
  * Footer contains Social Media icons as a links to desired platforms.
  * Icons contains aria labels, therefore visually impaired people are able to reach me out by use of screen reader.

![Footer](docs/readme_images/footer.png)

---

* Favicon
  * Favicon with my logo is visible throughout the website pages.
  * It will help to user faster and easier find my pages if many tabs in a browser are opened.

    ![Favicon](docs/readme_images/favicon.png)

---

* 404 Page
  * Page will be displayed if user navigates to a broken link.
  * 404 page allows user to reach me out easy via Facebook or email. Moreover, by clicking on the logo people will be redirected to home page without need of clicking back button on internet browser.

    ![404_page](docs/readme_images/404_page.png)

---

* Read more / Show less
  * This gives users an option to spread and shrink a text on a home page.

![Read more](docs/readme_images/read_more.png)
![Show less](docs/readme_images/show_less.png)

---

* Embeded Video
  * This gives users an opportunity to visit my Youtube channel and see more of my videos. Furthermore, user can adjust video quality depending on its internet connection.

![Promo video](docs/readme_images/video.png)

---

* Lightbox
  * This gives users a great posibility to see a large image on screen. In addition, customer can see next or previous photograph whithout exiting lightbox.

![Lightbox](docs/readme_images/gallery_lightbox.png)

---

### Landing Page

* Landing page image
  * It includes hero image in which I was photographed as a child with camera in my hands.
  * A text bellow the hero image obviously tells that website content will be related to the photography.

![Landing Page](docs/readme_images/landing_page.png)

---

* Read more
  * This short portion of text gives possibility for users to read more about my photography journey, achievements and companies that I worked with.
  * The story shows that I really love my work, I gained trust from worldwide companies and deliver professional services.

![About me](docs/readme_images/about_me.png)

---

### Gallery Page

* The gallery gives possibility to user see my works of different scenarios and genre. The page is working fully responsive on eny device.
  * For the moment gallery contains 12 pgotographs that can be enlarged.
* Lightbox feature ensure that user can see favorite images in bigger size.

![Gallery](docs/readme_images/gallery_page.png)

![Lightbox](docs/readme_images/gallery_lightbox.png)

---

### Contact Page

* Contact form lets customers to fill the form and leave a message regarding the question. The form consists of following fields and attributes:
  * Full Name (required, type=text)
  * Email (required, type=email)
  * Write your message here (required, type=textarea)
* After succsessful form submition the customer will get confirmation message and possibility to go back to contact.html page.
  * This gives posibility for the customer to contact me if they want to get the price for my services or any other information.

![Contact Form](docs/readme_images/contact_form.png)

---

### Apealing Feature

* Responsive design
* Hidden navigation menu, which gives more attention to the content
* Responsive Lightbox design independent of device orientation
* Contact form with a confirmation about successful form
* Animated social icons
* Embeded video from Youtube with option to adjust the quality

---

### Feature Left to implement

* As a future improvement:
  * The photos could provide EXIF information for other photographers
  * Google maps would be implemented to show photo locations
  * Lightbox would be improved and responsive with an option to swipe and pinch gestures
  * Implement booking system

---

<br><br><br>

## Design

### Wireframes

---

Home page

<br>

![Home page](docs/readme_images/home_wireframe.png)

![Home page mobile](docs/readme_images/home_wireframe_mobile_wireframe.png)

---

<br><br>

Gallery

<br>

![Gallery](docs/readme_images/gallery_wireframe.png)

![Gallery mobile](docs/readme_images/gallery_mobile_wireframe.png)

![LIghtbox](docs/readme_images/gallery_lightbox_wireframe.png)

![Lightbox mobile](docs/readme_images/gallery_lightbox_mobile_wireframe.png)

---

<br><br>

Contact

<br>

![Contact form](docs/readme_images/contact_form_wireframe.png)

![Contact form mobile](docs/readme_images/contact_form_mobile_wireframe.png)

---

<br><br>

Contact form successful submition

<br>

![Contact submition](docs/readme_images/contact_submition_wireframe.png)

![Contact subition mobile](docs/readme_images/contact_form_submition_mobile_wireframe.png)

---

<br><br>

404 Page

<br>

![404 page](docs/readme_images/404.html_wireframe.png)

![404 mobile](docs/readme_images/404.html_mobile_wireframe.png)

---

<br><br>

## Technologies

* HTML
  * The Website structure was developed using HTML as the main language
* CSS
  * For Website styling was used CSS in an external file
* Visual Studio Code
  * The website was developed using Visual Studio Code Desktop version using SSH key
* GitHub
  * Source code is hosted on GitHub and deployed using Git Pages
* Git Easy (extension for Visual Studio Code)
  * Was used to commit and push the code during the development process.
* Visual Studio Code Remote - SSH (extension for Visual Studio Code)
  * Was used to safely connect to the code stored on GitHub
* Git Graph (extension for Visual Studio Code)
  * Was used to follow the history of commits and correction comparison
* HTML Preview (extension for Visual Studio Code)
  * Was used to preview HTML files while editing them in VSCode
* Prettier - Code formatter
  * Was used to format code and keep it consitant
* W3C Web Validator (extension for Visual Studio Code)
  * Was used to check if any issue is detected and correct them
* Favicon.io
  * Favicon files were created at favicon [converter](https://favicon.io/favicon-converter/)
* Adobe Photoshop
  * Was used to convert photos to low size images
* Justinmind
  * Was used to create wireframes
* Ionicons
  * Was used to make website more attractive
* Adobe Fonts
  * Was used to keep a text styling constant
* Formspree.io
  * Was used to receive submitions to my email.

---

<br><br>

## Testing

### Responsivnes

---

All pages were tested to ensure responsivnes for screen sized from 300px up to 5000px. Responsive design was tested on Safari, Chrome and Firefox internet browsers.

Steps for testing:

1. Open browser and enter wbsite [address](https://simonpaske.github.io/simon-paske-photography/)
2. Open developer tools by clicking right button on the mouse or choosing at the internet browser navigation bar.
3. At Safari and Firefox browsers choosing device type and size to see a responsivnes. At Chrome internet browser by changing window size.

Expected:

No overlaping.
No strecthed or pixelated images.

Actual:
The website bahave as expected except on 404.html page at landscape orentation smaller devices. (Details can be found in Unifixed bugs part of documentation).

Website was tested on these devices:

Samsung S9
Samsung S22 Ultra
Samsung Note 9
Samsung S10
IPhone SE

<br><br>

---

### Accessibility

For the final testing I used [WAVE tool](https://wave.webaim.org/) to check aid accessibility.

Testing was focus to meet following criterias:

* All images and non-text elements has aria-labels and alt text and it is implemented correctly
* Pages meets ontrast levels

---

### Issues 

1. Contact form did not have enough contrast
2. Headings are missing or is at incorrect order

### Fixing the issues

1. Change the background of contact form
2. Change headings' sizes to meet sequention

---

<br><br>

### Lighthouse testing

**Navigation menu links**

Testing was performed for all html pages independenly. This was done by entering followqing html addreses to the address line on browser.

| Navigation menu link | Page to Load    |
| -------------------- | --------------- |
| Home                 | index.html      |
| Contact              | contact.html    |
| Gallery              | gallery.html    |
| 404                  | 404.html        |


All links were corectly connected to the desired labeling in Navigation menu list.

<br>

---

**Contact form testing**

The form was tested to make sure that it is fully functional and all submitions will be received to my email.


Steps to test:

1. Navigate to [Contact page](https://simonpaske.github.io/simon-paske-photography/contact.html)
2. Enter following data:
    - Full Name: Simon Paske
    - Email: simas.paskevicius@gmail.com
    - Message: Test Test Test
3. Click on Send button to submit the form
4. User is redirected to submition confirmation and thank you page.

Expected:

Unfilled fiels were showing error message with suggestion to enter information. By filling all the neccessary fields in the form, it submits without warnings and user is redirected to submition confirmation and thank you page.


Actual:

The submition worked as expected.


<br>

---

**Social Icons in the Footer**

Testing was performed on Ionicons by clicking and hovering on each icon to ensure that all links are working, opened in the new tab and has animation on hovered social icon.

<br>
Expected:

An social icons' links opens in a new browser tab. Email icon opens a default email application on device with ready to send window to targeted email address.

<br>
Actual:

Everythink works as expected.

<br>

---

### Validator testing

<br>

**HTML**
  
  no errors were returned when running via the official [W3C validator](https://validator.w3.org)
  
<br>

![index HTML Validator results](docs/testing/Index.html_validator.png)

![gallery HTML Validator](docs/testing/gallery.html_validator.png)

![contact HTM Validator](docs/testing/contact.html_validator.png)

![404 HTML Validator](docs/testing/404.html_validation.png)

<br>

**CSS**

no errors were returned when running via the official [W3C Jigsaw validator](https://jigsaw.w3.org)

![CSS index Validator](docs/testing/CSS_index.html_validator.png)

![CSS gallery Validator](docs/testing/CSS%20gallery.html_validator.png)

![CSS contact Validator](docs/testing/CSS_contact.html_validator.png)

![CSS 404 Validator](docs/testing/CSS_404.html_validator.png)

<br>

---

### Unfixed Bugs

Responsivnes worked for all the website on all devices with exception for smaller screen devices at 404.html landscape orientation. I was unable resolve this issue with my wishfull design.

<br>

---

## Deployment

### Version Control

<br>

The site was created using Visual Studio Code (Desktop version). Code was pushed to Github to the remote repository "simon-paske-photography".

Git commands were used via Git Easy (extension for Visual Studio Code).

<br>

---

### Deployment to Github Pages

The website was deplayed to Github paeges following these steps:

1. In the Github repository, click on the Settings icon
2. On the meniu in left side select "Pages"
3. In the "Build and deplayment" section select Source "Deplay from a branch".
4. In the Branch section select "main" and "root" folder. 
5. Click Save.

The live site link will be displayed at the top of GitHub Pages section in a blue color. Below the link you can find "Visit site" button.

<br>

---

## Credits

<br>

* Part of the code was used for Footer Social Icons and animation. 
  * **@alvarotrigo** (https://codepen.io/alvarotrigo/pen/GRxxWdQ).

<br>

* Part of the code was used to create dropdown navigation button. 
  * **W3SCHOOLS** (https://www.w3schools.com/howto/howto_css_dropdown.asp)

<br>

* Inspiration for a buttons in a lightbox 
  * **Treehouse Community** (https://teamtreehouse.com/community/adding-a-next-button-to-simple-lightbox)

<br>

* Inspiration for "Read more / Show less" option
  * **EnmaScript** (https://enmascript.com/articles/2019/09/26/toggle-content-on-click-without-javascript)

* Inspiration and part of the code was used create a lightbox for gallery
  * **Markus Oberlehner**
  **@maoberleher** (https://perfundo.oberlehner.net/#perfundo-untarget)

---

<br>

### Media

All photographs are copyrighted and belongs to Simon Paske. 
