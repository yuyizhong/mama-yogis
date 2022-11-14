# Mama Yogis


Mama Yogis is presenting a life changing concept of practicing Yoga during prenatal and postpartum. The targeted people are local mums and mums to be who wish to increase their energy level, strengthen their body and mind for easier labour, quicker recovery and happier motherhood. The users of the site will be able to explore the range of the yoga classes provided, Opening time and location, and book a class which suits their time and fits their needs.

 <img src="assets/image/readme-screenshot/amiresponsive.PNG" width=100%>

## Features

### Existing Features

- **Favicon**
   - A site wide favicon will be implemented with the pink pregnant women keeling icon.
   - The Mama Yogis' logo will appear in the the tabs header to allow the user to easily identify the website while multiple tabs open.

   <img src="assets/image/readme-screenshot/favicon.PNG">


- **Logo and Navigation Bar**

   - An eye catching logo of "Mama Yoga" with a pink beautiful pregnant woman kneeling icon (having a heart in the belly), says all about this site. It also contains the link of the home page.
   - The responsive navigation bar sits underneath the logo, including Home, Classes, Book Now and Contact, which is identical in all the other pages. 
   - This will provide users easy navigation on the site from section to section and page to page. It works responsively in different device sizes.

   <img src="assets/image/readme-screenshot/logo-navigation.PNG">

- **Home page main image**

   - By landing on this welcoming background image, users will see a pink yoga mat and a beautiful blooming white Lily next to it. 
   - It hints that "Besides a Mum, you are still yourself. Mums can be fit, healthy and pretty just like the blooming flower." 
   - This image is fixed to the viewport of the block and it allows the cover message gradually scroll over it, which gets users attention to the message itself.
   - The cover message provides users the main yoga style and the overall benefits of practising yoga at those special life stages. It initiates the users' willing to take participation.

   <img src="assets/image/readme-screenshot/mainpage-image.PNG" width=100%>

- **Classes Section**

   - This section lists out the classes provided by the site owner. Each class is illustrated with a supporting photo image and few short text paragraphs. 
   - The photo images give the users a feeling of how the class looks like and the paragraphs provides the details of what benefits the users can expect from each class respectively.   
   - There is a "Book Now" button next to each class title, which will redirect the users to the relevent booking section at Book Now page. It is convenient for users to book the class right after identifying each class type, instead of going back to the top of the page for navigation to the booking page.

   <img src="assets/image/readme-screenshot/class.PNG" width=100%>

- **Contact Section**

   - At this section, users will see where Mama Yogis is located, how to contact them and their opening time.
   - The *tel:* and *mailto:* protocols are coded to telephone and email. After a click, the phone number will be added to the dial box ready to dial and users’ mail box will be opened with a recipient email address filled. 

   <img src="assets/image/readme-screenshot/contact.PNG" width=100%>


- **Footer**

   - This Footer section is fixed to the bottom of the viewport and it is always there while users scroll up and down the page. 
   - It contains a phrase to encourage users to take the action and start the class. Also the links to the relevant social media sites for Mama Yogis are centered at the bottom line. Each link will open to a new tab to allow easy navigation for users.

- **Back to Top icon**

   - This back to top icon is fixed to the footer at the top center for users to quickly jump back to the top of the active page without scrolling.

   <img src="assets/image/readme-screenshot/footer.PNG" width=100%>

- **Book Now Page**

   - This Booking page contains the booking forms for studio class and online class. The Book Now and Sign Up button at the classes section will redirect the users to the specific booking form for the particular class. 
   - Furthermore, there is a navigation bar by class type at the top of the form section to help user to quickly go to the right booking section.

   <img src="assets/image/readme-screenshot/form1.PNG" width=100%>
   <img src="assets/image/readme-screenshot/form2.PNG" width=100%>

- **Thank You Page**

   - This page will pop out after users submitting the form and it gives a thank you / conformation message to show a successful booking.

   <img src="assets/image/readme-screenshot/thankyou.PNG" width=100%>


## Features left to implement

- As the submitted data from form is currently not stored to the server, therefore a further implementation is to build a database.
- Form can be simplified by using JavaScript to filter the different time for different class without adding notes next to each time options.
- Reflexiable images is ideal to inhance users navigation experience to avoid pixelated or unnecessarily stretched image. I will look into it When the time and source become available. 

## Technologies

- *HTML*
   - The structure of the Website was developed using HTML as the main language.
- *CSS*
   - The Website was styled and layed out using CSS in an external file.
- *GitPod*
   - This developer platform with VSCode editor can remotely work through web browser.
- *GitHub*
   - Source code is hosted on GitHub and delpoyed using Git Pages.
- *Git*
   - Used to commit and push code during the development of the Website
- *Font Awesome*
   - Icons obtained from https://fontawesome.com/ were used as the Social media links in the footer section.
- *Tinyjpg*
   - All the images used throughout the website were reduced size at https://tinyjpg.com/ 
- *Favicon.io*
   - Favicon files were created at https://favicon.io/favicon-converter/
- *Am I Responsive*
   - Screen shots of the various device breakpoints for the website were produced at https://ui.dev/amiresponsive/


## Testing

### Responsiveness

All pages were tested to ensure responsiveness on screen sizes from 320px and upwards on Chrome, Edge and Firefox.

*Steps to test:*

- Open browser and paste https://yuyizhong.github.io/mama-yogis to address bar to navigate.
- Right click on the webpage and then inspect to Open the developer tools
- Set to responsive and decrease width to 320px and the zoom to 50%
- Click and drag the responsive window to maximum width

*Result*:

- Website is responsive on all screen sizes and no images are pixelated or stretched. No text were overflowed or cut off. No contents were out of their box or get overlapped.

### Accessibility

[WAVE Web Accessibility Evaluation Tools](https://wave.webaim.org/) was used throughout development and for final testing of the deployed website to check for any aid accessibility testing. 

*Result*
- 0 Errors and 0 Contrast errors.
<img src="assets/image/readme-screenshot/wave.PNG">

 - Issue fund during the page development:
   - I originally used 3 identical forms for 3 studio yogo classes booking. All the lables are the same besides the options of the time are different for each class. 
 - Fix:
   - I merged the forms into 1. As without using JavaScript, I wont be able to provide the relevant time options based on the yoga class selected. I add the radio choice for users to select the yoga class and then put all the time slots in the select drop down list, with class name next to each time slot. 

### Lighthouse Testing
- Test on desktop

<img src="assets/image/readme-screenshot/lighthouse-desktop.PNG">


- Test on mobile

<img src="assets/image/readme-screenshot/lighthouse-mobile.PNG">

### Functional Testing

*Navigation Links*

 - Testing was performed to ensure all navigation links on the respective pages, navigating to the correct pages and sections as expected. This was done by clicking on the navigation links located on the top of Home page, Book Now page and Thank you page.
 - At the main navigation bar of each page, it shows the active page with an underline under the corresponding navigation button. Also a hover effect also shows the underline after put the mouse over the links. They were all appeared as expected.
 - Also there are links at classes section, which are supposed to redirect to the specific booking form. They were also worked as expected.
 - There are two links at the top of the booking form. They were also linked to the right section after clicking it.

 *Contact Information*

- Testings were performed on the phone number and email address in the last section of the main page (contact details) to ensure "call-able" and "mail-able".

  *Steps to test Telephone Number*

     - Navigate to Mama Yogis' Home Page and click the phone number in contact details section (Phone: +44 203 666 9898)

  *Result:*

     - A window popped out to suggest "Make a call from Samsung phone (active)".
     - It was as expected.


  *Steps to test Email Link*
     - Navigate to Mama Yogis' Home Page and click the email address in contact details section (Email: info@mamayogis.co.uk)

  *Result:*
     - My outlook popped put open with Mama yogis email address at "to" box.
     - It functioned as expected.

 *Back to top* and *Social Medial Links*
 - Those two features are located at the footer. They were tested by clicking on each links. 
 - The active page went back to the top and the social Medias were opened at a new tab. 

*Form and Thank You page Testing*

- Forms are tested by either filling in each section or omitting few fields and click on 'Book Now'/'Sign Up' or 'Reset Form'.

  *Result:*

   - Each required fields were supposed to put in a data, otherwise an error message popped out and form was not submitted.
   - When a wrong email format was input, an error message popped out and form was not submitted.
   - After all required fields were filled (with a correct email format), by clicking on "Book Now" or "Sign Up" button, it would redirect the user to a Thank you page for submitting confirmation.
   - By clicking on "Reset Form", all the data filled in would be cleared.
   - Over all, form and the thank you page performed as expected.

### Validator Testing ###

  *HTML Testings* were performed to Mama Yogis all three html pages through the [official W3C validator](https://validator.w3.org/). 
  No Error was fund on index.html, book.html and thankyou.html.

  <img src="assets/image/readme-screenshot/w3html-index.PNG">

  <img src="assets/image/readme-screenshot/w3html-book.PNG">

  <img src="assets/image/readme-screenshot/w3html-thankyou.PNG">
 
  *CSS Testing* was performed to Mama Yogis style.css through the [official (jigsaw) validator](https://jigsaw.w3.org/). 
  No Error was fund.

  <img src="assets/image/readme-screenshot/w3c-css.PNG">


### Unfixed Bugs ###
None.

## Deployment ##

### Version Control ###

The site was created at gitpod. It was then pushed to github to the remote repository ‘mama-yogis’ throughout the development.

The commonly used git commands to push code to the remote repository are as follows:

- git add <file>/ git add . - This command was used to add the modified file(s) to the staging area before they are committed.

- git commit -m “commit message” - This command was used to commit changes to the local repository queue ready for the final step.

- git push - This command was used to push all committed code to the remote repository on github.

### To deploy to Github pages ###

The site was deployed to GitHub pages. The steps to deploy are as follows:

- At the GitHub mamayogis repository page, navigate to the Settings tab
- From the menu on left select 'Pages'
- From the source section drop-down menu, select the Branch: main
- Click 'Save'
- A live link will be displayed at top of the page in a banner when published successfully.
The live link can be found here - https://yuyizhong.github.io/mama-yogis/


### Clone the Repository Code from github desktop ###

Navigate to the GitHub Repository you want to clone to use locally:

- Click on the code drop down button
- Click on HTTPS
- Copy the repository link to the clipboard
- Open your IDE of choice (git must be installed for the next steps)
- Type git clone copied-git-url into the IDE terminal
- The project will now of been cloned on your local machine for use.

## Credits ##

I would like to give a big Thank You to my mentor Daisy Mc Girr! She presented me the amazing technologies to enhance the website developing and suggested interesting ideas to fullfil my inspiration. 

 ### Content ###
 - Favicon files were created at [Favicon Generator](https://favicon.io/favicon-converter/)
 - The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
 - I used [W3school](w3schools.com) to check the syntaxes and relevant attributes to get my website presented the way I wanted.
 - To make the Calls to Action feature to the phone number and email address, I read [Elegant Themes Blog](https://www.elegantthemes.com/blog/wordpress/call-link-html-phone-number#:~:text=Adding%20an%20HTML%20Phone%20Number%20Call%20Link%20to%20your%20Website&text=Href%3Dtel%3A%20creates%20the%20call,the%20number%20it%20will%20call)

 ### Media ###

 - The photos used through out of the website are from [Adobe free photo stock](https://stock.adobe.com/)



   


