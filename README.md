# Gymfinity
A front-end website project for a fictional gym. The aim of the website is to attract potential and retain members, whilst providing information about the gym, its facilities and organised classes.
![am i responsive](docs/gymfinity.png)

Link to the website can be find here: [Gymfinity](https://lestercantor.github.io/gymfinity/index.html)

Link to repository can be find here: [GitHub Respository](https://github.com/lestercantor/gymfinity)
# User Stories
As the site owner, my goals are:
* To promote a healthier lifestyle
* To motivate members to join

User goals for the website are:
* As a first-time visitor, I want to easily find information about the gym (location and opening hours) so that I can make a decision to join
* As a first-time visitor, I want to see pictures of the equipment the gym provides
* As a first-time visitor, I want to easily find the sign up page 
* As a first-time or recurring visitor, I want to easily find information on the classes and their schedule
* As a recurring visitor, I want everything that I saw the first time I visited

# UXD (User Experience Design)
### Strategy
The purpose of the website is to attract new members to sign up for the gym and to retain current members. My target audience are for people aged 16+ and for all levels of fitness. The website will be able to offer the user's goals by ensuring that navigating through the website is simple and the information they need will be clear and concise. Since most, if not all, users of the intended audience have access to mobile phones, it is important that the website is responsive.
### Scope
For a comfortable user experience, features will include:
* Navigation bar to navigate through different pages. A collapsed menu bar to be in place for smaller screens
* Home page providing information about the gym and why to sign up
* Section in the home page detailing the schedule of classes so it's easily visible
* A page dedicated to showing the gym equipment and facilities
* Sign up form 
### Structure
The website will have 3 pages: Home -> Equipment & Facilities -> Sign up. Users can scroll through the home page to find most of the information as it will be the main body of information. Blocks of text will be kept short with images and icons to keep the user's attention and to not overwhelm them. There will be a simple sign up form for users to sign up.
### Skeleton
[Wireframe Mockup](/docs/wireframe%20mockup.png)
### Surface
I will have a dark navigation bar, contrasted with a light background for the main body of the page so the navigation bar clearly anchors the top of the page for users to see. The light background for the main page is so that the information is clearly striking to attract the attention of the user. 

A simple font like "Roboto" from Google fonts will used as it is clear and easily readable. My aim is to have the images to attract the user's attention whilst having text accompanying it to convey the information.

# Features
I intended to design the website mobile first, however, I found it easier to design it desktop first to then make it responsive for smaller screens. There are 3 pages: a home page, a page showcasing equipment and facilities and a sign up page. All pages use the font 'Roboto' for website consistency.

[Link to responiveness](https://ui.dev/amiresponsive?url=https://lestercantor.github.io/gymfinity/index.html)

## Navbar
I have a navigation bar so it's easy for users to navigate through the website. There is a collapsed navbar with a button for mobile users so the bar looks cleaner for the smaller screens, whilst making it accessible for the user.

## Footer
There is a footer for social media links and the basic information about the gym which is across all pages so the user has easy access to them at any time.

# Validator Testing
### HTML Validation
![Alt text](docs/errors.png)

From the [w3c validator website](https://validator.w3.org/nu/?doc=https%3A%2F%2Flestercantor.github.io%2Fgymfinity%2Findex.html), I have errors and warnings about duplicate ID's used, however, I am not sure of a solution to the problem as I needed the same styles for the tags that were used. Since I needed the same styles for the footers, the same errors and warnings are across each page. Another issue I am not sure of how to fix is to make the paragraph tag in the footer to be part of the unordered list, as I needed the list style and tags to make the footer content as it is.

To fix these errors, I realised that ID's are used for unique changes, so having multiple ID's being used was against the validity in the HTML validation. My solution to fix this was to make them a class so that multiple elements can have the styling that I want.

### CSS Validation
![Alt text](docs/css-validation.png)
Passing my direct code through [w3c jigsaw css validator](https://jigsaw.w3.org/css-validator/validator), my CSS stylesheet passed with no errors found.

# Deployment
My website was deployed through GitHub Pages. To deploy it, these steps were followed:
* Open the GitHub Repository
* Click 'Settings'
* Click 'Pages' on the left
* From the Source button: select Deploy from a branch
* From the Branch button: select main and /root
* Click Save

# Technologies Used
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) was used as the basic foundation for the website
* [CSS](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics) was used to style the website
* [Bootstrap](https://getbootstrap.com/) was used to help build the website through their CSS libraries
* [Google Fonts](https://fonts.google.com/) was used to obtain custom fonts 
* [Font Awesome](https://fontawesome.com/) was used to obtain icons
* [Google Developer Tools](https://developer.chrome.com/docs/devtools/) was used to inspect different elements and see responsiveness 
* [GitHub](https://github.com/) was used to store code repository and to deploy website
* [W3C Markup Validation](https://validator.w3.org/) was used to validate the HTML
* [W3C CSS Validation](https://jigsaw.w3.org/css-validator/#validate_by_input) was used to validate the CSS
* [Unsplash](https://unsplash.com/) was used to download free images for the website (as it was for a fictional gym)
* [Pixlr](https://pixlr.com/e/#editor) was used to crop and resize images to better suit the website