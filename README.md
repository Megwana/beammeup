# Beam Me Up Website 

Beam Me Up is a website designed for visitors to find out about the 'Beam Me Up' movie club. As a movie club, they meet once a month to watch space-themed Sci Fi movies locally in Brighton. They then discuss the movie after watching it and post short reviews giving their opinion on the movie. The reviews are not in depth as it is a recreational club whom enjoy watching this genre as a casual hobby. 

The Website is responsive, which can allow visitors to view the site on a multitude of devices. 

This website was created for educational purposed only and is a fictional concept.

![View Beam Me Up Website on all devices](assets/images/read.me.images/media-mockup.png)

![View the live site here](http)

## 1. User Experience & Project Goals 


### First-time visitors

- For first-time visitors, I want them to understand what the website is about and who it is targeted too. 
- In addition, I want users to find information about the movie club, such as meet times, general information about the club so they can decide whether it something they would want to be a part of. 

### Movie Club members 

- I want the existing members to be able to view our events and meet up details with ease. 
- Furthermore, I would like existing members to view our conjoined reviews of films as a club and still be able to contact formally through our club site, should they have any questions. 

### All visitors

- I want visitors to find the site easy to navigate. 
- I want the home page to invite them into sci-fi notalgia but with still a modern feel. 
- I want visitors to be able to contact the site organisers with ease about any queries they may have. 
- I want visitors to see images of on the about page of our club meeting for movie watching to highlight the social aspect of the club. 
- I want visitors to have easy access to the location of our meet ups via google maps on the website, so they can easily attend meet ups. 

## 2. Features 

### Current Features

-__Navigation Bar__

- On all three pages, there is a navigation bar that is full responsive. The navigation bar includes a the movie club's logo 'Beam Me Up', the Home Page, the About page, the movie review page and the contact page. I have created each the same on each page for ease of navigation. However, there is a difference on the contact page. When you hover over the link is highlights #fff instead of #orange like the others. This is because contacting about joining the club and/or any queries are vital. Therefore, I wanted it have a different identifier to the others to stick out from the other links in on the navigation bar. 
- The navigation bar will allow the user to easily navigate from each page (and across all devices) without having to regress back to the previous page. 

Desktop view:

![View Beam Me Up Navigaton bar in desktop mode](assets/images/read.me.images/navbar-full-screen.png)

Smaller devices below:

![View Beam Me Up Navigaton bar in smaller screen mode](assets/images/read.me.images/mobile-navbar.png)

-__The landing page background image__

The landing page includes a background image of an astronaught. The background image is meant to give an eye-catching feel of space-themes.  

![Landing Page](assets/images/read.me.images/home-background.png)

-__The landing page welcome introduction__

- There is a text overlay on the background image to the left of the landing page to highlight the name of the movie club and a brief description of what the club is; so an unknown vistor can immediately gauge the purpose of the site.

-__Contact Button__

- A button with the words 'join our club' features below the welcome introduction to encourage easy access to the contact page for visitors looking to join. 

![Join Our Club Button](assets/images/read.me.images/welcome-left.col.png)

-__Movie Review Cards__

- The four card segments on the landing page will allow the user to have quick access to the most recent movies viewed by the club. 
- Each segment provides a direct link to each individual month's more detailed review on the website's movie page.
- The four card segments have a space-themed background to match the space-themed science-fiction theme of the movie club.
- This section will be updated as these details change in order to keep members and potential new joiners up to date with the latest movies review each month.

![Review cards](assets/images/read.me.images/cards-right.col.png)

[View Beam Me Up Movie Club on Github Pages] (https://megwana.github.io/beammeupm1/)

-__Meet up event times__

- The meet up times enable visitors to view precise dates, times and locations for when the movie club will be meeting. 
- This section will be updated as these details change in order to keep members and potential new joiners up to date.

![Event times](assets/images/read.me.images/event-times.png)

-__The Footer__

The footer bar features links to all the relevant social media sites that Beam Me Up has accounts for. In addition, the links open into a new tab to let the site user easy navigation and the ability to still browse the Beam Me Up website. 

![Footer](assets/images/read.me.images/footer.png)

## 3. Design

### Colour Schemes 

The reason I have chosen this colour scheme for my website is:

I wanted there to be black and white as reoccuring colours to reflect the night sky. The more cream colour was chosen to bring a link between the two and reflect the off-white nature of the moon. The fourth colour I wanted to be rather bright because all my other colours are quite neutral. The Redish Orange, is inspired by the colour of the sun and is used to give a pop of colour and highlight parts of the website. 

![Beam Me Up Website's Colour Pallette](assets/images/read.me.images/color-pallette.png)

### Typography 

Google Fonts were used for the following fonts: 

- Bungee is used for the logo on the site. Bungee is a cursive font.
- Ubuntu is used for the rest of the sites fonts. Ubuntu is a serif font.

### Accessibility 

It is important to ensure that the website is user friendly. I have fufilled this by the following actions:

- I have used semantic HTML.
- Establishing adequate colour contrast on the website overall.
- I have used alt and title attributes on images throughout the website.

## 4. Technologies Applied

### Languages Utilised 

To create this website, I have used two languages, HTML and CSS.

### Other Technologies

- Google Fonts: Imported for the fonts used.
https://fonts.google.com/
- Font Awesome: Used for all iconography.
https://fontawesome.com/
- Google Development Tools: Used to test/ troubleshoot any issues and find solutions.
 In addition, to review the websites responsiveness on different device dimensions.
- Github: Used to save and store all the files for Beam Me Up. 
https://github.com/enterprise?ef_id=3284471c0907111ab5f625fbdab0012a:G:s&OCID=AID2202670_SEM_3284471c0907111ab5f625fbdab0012a:G:s&msclkid=3284471c0907111ab5f625fbdab0012a
- Am I Responsive: To display the website on a variet of devices.

## 5. Testing

### Validator Testing

To test my code, I used W3C Validator for both HTML and CSS.

* [Index Page HTML](image of HTML Passed)
* [About Page HTML](image of HTML Passed)
* [Movies Page HTML](image of HTML Passed)
* [Contact Page HTML](image of HTML Passed)
* [Style.css CSS](image of CSS Passed)

### Bugs 

1. I was warned it was not good practice to have the left column as a h1 tag and should change this to a h2.

2. Removed '="text-input" after required on the contact form. The validator flagged this as a bad value. 'Required' as an attribute can be left on its own and does not require the additional text. Therefore, I removed this. 

2. I was warned it was not good practice to have an anchor tag inside a button. Therefore, instead I found an alternative on W3 Docs (https://www.w3docs.com/snippets/html/how-to-create-an-html-button-that-acts-like-a-link.html), which meant I could add the link using 'onclick' within the button tag.
. Despite the navbar being fixed, when on the contact page the form would overlap and cover the navabar when scrolling. This would prevent users from being able to easily access the menu at all times. They would have to scroll all the way to the top on just the contact page which does not fit flush with the rest of the website, that can access the fixed navbar at all times when scrolling. While reading on W3Schools (https://www.w3schools.com/cssref/pr_pos_z-index.asp) I was reminded about z-index. Therefore, to resolve the issued, I set the navbar to z-index 999 to guarantee it would always be stacked in front of other elements. 

## Deployment

GitHub pages was used to deploy the live website of Beam Me Up. The measures to deploy the website are as follows:

Step 1: Logged on to GitHub Pages.
Step 2: Navigated to the settings tab, which can be found in the GitHub repository.
Step 3: From the source section drop-down menu, selected the Master Branch. 
Step 4: Once the mast branch was selected, the page automatically refreshed with a detailed ribbon display, registering the website's successful deployment. 

The live links can be found here - 

## Credits

### Code Used

- 'Easy Tutorials' Youtube Channel: This inspired the layout for my home page. However, I changed elements to suit my preferences and the website.
https://www.youtube.com/watch?v=Oa9LTDR9ugU

- 'Coding Nepal' Youtube Channel: This inspired the function of the navigation bar when used on devices with a max-width of 992px. 
https://www.youtube.com/watch?v=oLgtucwjVII

- Dom from 'dcode' Youtube Channel: His code for creating an Accordian was how I created my drop down box on the movies review page. I changed parts to suit my website but I directly used the triangle image he has for the drop down symbol.
https://codepen.io/dcode-software/pen/oNjXqzg

### Acknowledgemnts & Thank yous

Thank you to my mentor Jubril Akolade for your support and feedback on my project which helped me develop it into its finished state.

Thank you Ashkat Garg for the recommendation of the following technologies:

- TinyPNG - https://tinypng.com/
- Multi Device Website Generator - http://techsini.com/multi-mockup/index.php
- Flexbox Froggy - https://flexboxfroggy.com/
- Webformatter - https://webformatter.com/

### Content

### Media

All images used on the website were from the following websites where you can use the images for free: 

- Pexels https://www.pexels.com/
- Pixabay https://pixabay.com/

I would loved to have used imagery from the movie's posters however, to avoid any copyright infringements and because the site is for educational purposes only; I decided to source the images from the websites listed above.