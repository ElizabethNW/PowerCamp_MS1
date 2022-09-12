<h1 align="center">POWERCAMP</h1>

### Developer: Elizabeth West

![Am I Responsive] (INSERT)

[View live website here](https://elizabethnw.github.io/PowerCamp_MS1/)

This is Youth Ministry website created for Portfolio Project #1 (HTML&CSS) for Diploma in Full Stack Software Development at [Code Institute](https://www.codeinstitute.net). It is responsive across a range of devices and it is easy to navigate for site users. 
<br>
The users of this website will be able to find all important information about types of camps we run, FAQ's and a Contact Form.

<br>

# Table of content 

*   [Project](#project)
    *   [Strategy/Scope](#strategyscope)
    *   [Site owner goals](#site-owner-goals)
    *   [Site user goals](#user-goals)
*   [User Experience (UX)](#user-experience-ux)
    *   [Color Scheme](#colour-scheme)
    *   [Typography](#typography)
    *   [Structure](#structure)
*   [Technology](#technology)
    *   [Languages used](#languages-used)
    *   [Frameworks, libraries & software used](#languages-used)
*   [Testing](#testing)
    *   [Accessibility](#accessibility)
    *   [Performance](#performance)
    *   [Validation](#validation)
    *   [HTML](#html)
    *   [CSS](#css)
    *   [Browser compatibility](#browser-compatibility)
    *   [Platforms/devices](#platformsdevices)
    *   [Bugs/known issues](#bugsknown-issues)
    *   [Responsiveness](#responsiveness)
*   [Deployment](#deployment)
*   [Credits](#credits)
    *   [Code](#code)
    *   [Media](#media)
    *   [Acknowledgements](#acknowledgements)



#   Project
##  Strategy/Scope

PowerCamp website aims to provide essential information about the available camps and its offer to the user in a clear and visually pleasing way. It targets families looking for information about our Youth Programs

<br>

 The content is presented on scrolling page with sections dedicated to categorised informations. The <b>primary objective</b> is to encourage sign-ups by leading them to the contact form. 

<br>
To achieve the strategy goals I implemented following features:
* simple website layout with a menu bar sticked to the top of the viewport for easy navigation,  

* informative  "Camps" and FAQ's sections, 
* multiple call-to-action buttons across the whole page,  
* a contact form   
* consistent images across the whole page to immerse the user in Site Owner's story. 
<br>

## Site owner goals

- to promote empowerment focused Youth Camps in the local area  
- to provide booking form for the users allowing them to contact us for enquires   
- provide image gallery with photos of to encourage  people to enquire more
- provide social media links to advertise and gain new visitors to website, 
- to provide an accessible website that looks well across a range of devices (responsiveness).  

##  User goals

- as a new user I want to:
    - navigate easily through the page, 
    - learn more about the available Camps, 
    - check upcoming events/camps, 
    - check the photos to find out what's the "vibe" in there,  
    - book myself/family to participate in camps 
    - contact Camp Organisers, 
    - follow Group on social media, 

    <br>

- as a returning user I want to:
    -   navigate easily through the page, 
    -   contact camp organisers 
    -   get directions to Office
    -   see the pictures from Camp sessions. 

<br>

#   User Experience (UX)

##  Colour Scheme

Colour palette was selected using coolors.co generator. 
For beast readability and clean look white colour was chosen for the bacgkround, and neutral colours to go easy on the eyes while scrolling.

<br>

##  Typography

-   The Roboto font is the main font, Poppons is also used throughout the whole website with Sans Serif as the fallback.They are all clean, modern looking fonts and is attractive. It is sourced from [Google fonts]('https://fonts.googleapis.com/css2?family=Roboto&display=swap'
) and it's linked to css document via @import.  

- [Type Scale](https://type-scale.com/) - tool were used to visualize different font sizes.

<br>

##  Structure

### Wireframes - [ADD LINK TO WIREFRAMES]



Page is designed in well known scrolling page style that users like. It provides fast access to information and immerses user in the story. Navigation bar is always visible in the viewport, that reduces number of clicks to reach desirable content. Website consists of following sections: 

## Navbar 

The navigation bar is customised Bootstrap Navbar. It contains custom logo links to relevant sections. All menu elements are highlighted on hover and navbar is sticked to the top of the viewport when scrolling. On small screens navbar shows well-known "hamburger" icon and collapsible menu. 

![Navbar](IMAGE) 

## Carousel

Bootstrap carousel shows 3 slides with photos that cover whole viewport on big screens. Each caption consists of Header, short slogan and call-to-action button that is linked to relevant key section. Carousel slides cycle through automaticaly but site user can take control over this function thanks to slider buttons and active slide indicator.  

![Carousel](IMAGE)

## About
The About section is descriptive part of a website and provides information about company's goal and purpose. It also promotes Youth Camp interactions as activity that brings wellbeing benefits to the user. The business key points are presented using row of icons. Use of negative space make it easy for user to read the content and focus on important parts. 

![About](IMAGE)


## Camps
In this section there is a short decription of company's offer. Bootstrap accordion feature has been used to accomodate five headers and paragpraphs describing different Youth Camp Events. For those who are looking for on-line learning resources, there are two categories of lessons - for beginner and advanced user. 

![Camps](IMAGE)

## Instructors
This section presents photo avatars of the Youth Camp instructors. 

![Instructors](IMAGE)

## Gallery
[w3cschhols.com](https://www.w3schools.com/howto/howto_js_image_grid.asp) 

![Gallery](IMAGE)

## Affirmations

The "Affirmations" section displays a spiritual/motivational quote that should motivate user, attract him to share or persuade him to make a contact or booking.  

![Affirmation](IMAGE)

## Video
Video section presents full width iframe that contains YouTube video with relevant content. It links the user with business's YouTube channel and encourage him to interact longer with the content and build deeper interest in activities and as a result - to become new customer. 

![Youtube](docs/screenshot_youtube.png)

## "Sign-Up" - booking form
The booking form is a key point of a website where user is being led consequently to make interaction and join the business as a new customer. All form fields are marked as required and are validated. The form provides feedback in case the users input is incorrect. Date select field requires further script to prevent user from picking a date from the past. Upon successful completion of the form website provides user a feedback by transfering him to thankyou.html page.    

![Booking](IMAGE)

## Footer
The classic footer is preceded by Google Map section that indicated precise location of Yoga Studio. The footer contains of three columns, that provides information accordingly about address, contact and opening hours. The last column presents social media icons that encourage user to follow the business on various platforms. In bottom right corner of a website is  located an icon with "back to top" link.    

![Footer](IMAGE)

## Thank you page
The page where user is transferred to upon successful completion of the booking or contact form. User doesn't have to use browser "go back" button, the link to the main page is provided.      


!


#   [Technology](#technology)
    
##  [Languages used](#languages-used)

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    
##  [Frameworks, libraries & software used](#languages-used)

- [Bootstrap 5.2.0:](https://getbootstrap.com) - Bootstrap was used to create website grid and to make it responsive. Other features used and customised: 
    * Navbar,
    * Carousel,
    * Acordion,
    * Shortcode for spacing elements and table cell background colour (eg. px-5, warning). 
- [Balsamiq](https://balsamiq.com/) - Balsamiq was used to create the [wireframes](#structure) during the design process.

- [Coolors.co](https://coolors.co/) - was used to create color palette. 

- [Google Fonts](https://fonts.google.com/specimen/Montserrat) - Google fonts were used to import the 'Montserrat' font into the style.css file which is used on all pages throughout the project.

- [Type Scale](https://type-scale.com/) - a type tool used to visualize font size. 

- [Google Maps](https://www.google.com/maps) - was used to embed map with Yoga Studio location. 

- [YouTube](https://www.youtube.com) - was used to embed video on a website. 

- [Font Awesome:](https://fontawesome.com/) - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

- [Git](https://git-scm.com/) - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

- [GitPod](https://www.gitpod.io) - IDE used to code the project. 

- [Visual Studio Code for Windows](https://code.visualstudio.com/) - IDE used to code the project.  

- [GitHub](https://github.com/) - GitHub is used to store the project's code after being pushed from Git.

- [Adobe Photoshop](https://www.adobe.com/ie/products/photoshop.html) - Photoshop was used to resize the pictures. 

- [Adobe Express](https://express.adobe.com/) - online service used to create logo. 

- [Audioeye.com](https://www.audioeye.com/color-contrast-checker) - used to analyse contrast. 

- [BD_sizer](https://bd-sizer.en.softonic.com/) - used for resizeing pictures in the gallery.

- [TinyPNG](https://tinypng.com/) - used for images compression.

- [Convertio.co](https://convertio.co/jpg-webp/) - online JPG to WEBP converter. 

- [CSS Beautifier](https://www.freeformatter.com/css-beautifier.html) - used for formatting css file for optimal readability. 

- [Am I Responsive](https://ui.dev/amiresponsive) - online tool used to create mockup to present responsive design of this project. 

- [Go Full Page](https://gofullpage.com/) - Google Chrome extension used to capture full page screen shot.  

- [Lightshot](https://app.prntscr.com/) - Google Chrome extension used to capture screenshots for this README document. 

- [Lighthouse](https://developers.google.com/web) - Google webdev tool used for performance testing. 

- [Wave Web Accessibility Evaluation Tool](https://wave.webaim.org/) - used to validate accessibility. 




<br>

#    Testing

##   Accessibility

Foreground and background color contrast check was done using [Audioeye.com](http://www.audioeye.com) online tool.

![Contrast 1](INSERT IMAGE) 

![Contrast 2](INSERT IMAGE) 


[WAVE](https://wave.webaim.org/) Web Accessibility Evaluation Tool was used to check accessibility. It reported one error "Missing alternative text". It is related to carousel background photo linked via CSS stylesheet. Alternative text cannot be set in this case. Four alerts are minor and related to justified text in the paragraphs. 

![](INSERT IMAGE)

##   Performance

 [Lighthouse](https://developers.google.com/web) - Google webdev tool used for performance testing. <br>

![Lighthouse](INSERT IMAGE

##   Validation

###   HTML

- [W3C Markup Validator](https://validator.w3.org/nu/) - validation service used. 



![First test]

![Final test]



###   CSS

- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)  - validation service used. 

- [Custom stylesheet](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Falexkisielewicz.github.io%2FPortfolio-Project-1%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en-EN) -  No Error Found. 

- [Bootstrap stylesheet](https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css) 

![CSS Validator](IMAGE)

##   Browser compatibility

Website was tested manually on following browsers: Google Chrome, Edge, Firefox, Safari, Brave. The results were satisfactory.   

##   Platforms/devices 

Website was tested manually on Apple Iphone 13, Apple iPad, Apple Macbook Air, Samsung Galaxy Tab S7+, Ultrawide display 3440x1440 and classic 16:9 2560x1440 display. The results were satisfactory.  

## Responsiveness 

I confirmed that this website is responsive and all the functions are displayed correctly, all links and contact form work fine.   

##   Bugs/known issues

(LIST IF ANY OR DELETE SECTION)

#   Deployment
    
The project was deployed to GitHub Pages using the following steps: 

1. Log in to GitHub and locate the [GitHub Repository 
Portfolio-Project-1](ADD LINK)
2. Locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "Pages" in "Code and automation" section.
4. Under "Source", click the dropdown called "Select branch:" and select "Main", click the dropdown called "Select folder" and select "/root".
5. The page will automatically refresh and you receive message "Your site is published at (ADD LINK)". Result below: 

![Deployment]

<br>

#   Credits

##  Code

-   [Bootstrap5.2.0](https://getbootstrap.com/) - Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System. Additional features used/implemented and customised: Navbar, Carousel, Acordion, shortcode for aligning and spacing elements.  
-   [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/tel#Pattern_validation) - phone number pattern validation code.
-   [W3C Schools](https://www.w3schools.com/howto/howto_js_image_grid.asp) - inspiration to create responsive image grid gallery. 
-   Code Institute README.md template has been used to create this document. 

##  Media

-   All images used were sourced from free stock photos [Pexels.com](https://pexels.com/) - Photographer [INSERT CREDIT IF ANY]

##  Acknowledgements

-   My Mentor Simen Daehlin for helpful feedback and guidance at all stages of the project. 
-   Code Institute Templates & Slack Community for being invaluable knowledge base. 
-   W3C Schools for great HTML and CSS learning resources.   
-   Bootstrap Docs 


## Disclaimer
-   <b>Power of Self Ministries - Youth Camp Website is initially created for educational purpose only.</b> 