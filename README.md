# Castleia 
Castleia is a restaurant that I have plucked out of thin air, to make this restaurant a reality I have created a user-friendly website. As Castlia is a professional place to visit I wanted to create a sleek, smart and professional layout to match the quality.  

![screenshot of responsive website](assets/docs/images/responsive.png) 

- My live project is located here [Castleia](https://jakdudley.github.io/Portfolio.1/)



## Project Aims 
Before even thinking about what HTML and CSS I was going to be using I needed to think of a few items:
1. Business type
2. Target Audience
3. Site Aims 
4. Color Scheme 
5. Navigation

### Business Type 
- Restaurant, I chose to go down the restaurant path purely because I've been in the hospitality industry for 7 years myself and chose this giving myself the advantage of content for the site. 
- As I said being in the industry I know what the competition is, I know what the users want and desire on a restaurants site 
- Customers expect, simple but yet elegancy, the better looking and organised website the higher the chance of them getting a better experience at the venue
### Target Audience
- Families looking to enjoy great food and a warm, welcoming restaurant. 
- Businesses looking to book professional dinner dates and staff meetings. 
- Friend Groups looking to be able to come and have a memorable time in a great environment. 
- Users that are looking for a new place to dine out who just want to see what information they need ie; booking a table, seeing the menu without having to complete a maze to find and all the needed information to get in touch if need be or even find us on a map. 

### User Stories
- As a user, I want to see when the restaurant is open.
- As a user, I want to be able to view the menu on offer.
- As a user, I want to be able to reserve a table for any time in the future with multiple guests. 
- As a user, I want to be able to see past customer reviews.
- As a user, I want to be able to give my feedback after visiting the restaurant. 
- As a user, I want to be able to contact the restaurant with any queries I may have on the site.
- As a user, I want to be able to find the restaurant on a live map. 
- As a user, I want to be able to call the restaurant from my phone while using the site. 
- As a user, I want to be able to send the restaurant an email. 

### Site Aims 
- When creating my site I wanted users to be aesthetically pleased
- I wanted the customer to not be confused and redirect to another restaurant site
- To offer the user an easy to navigate and accessible experience across whatever device they desire to use 
### Color Scheme 
 - When deciding the color scheme I wanted to make the site look smart and fresh as well as professional, to do this I stuck to two main colors one of which is #e2d6bd as the background and #F5F5F5. The navbar color has changed over the cause of time as you can see in the below screenshots, but I've gone with RGB(255, 255, 255, 0.4) to make it easier to identify across each device. 
### Meta Description and Title 
- When deciding what description to give the page I used [Smart Copy](https://unbounce.com/product/smart-copy/?gclid=Cj0KCQiA-eeMBhCpARIsAAZfxZCUAoiSbSXIyGfYcJGbYaeFRR6PMR4r1QzC_kqyJhuPF2Mxeda07iEaAqj0EALw_wcB) to generate a meaningful description. 
- The title of the page is a simple feature but I wanted to make it mine, so for each page, I used the title of the page within the title so the user can see what page they are on within the tab bar. 
![Picture of each page title in the window tab](assets/docs/images/title-tabs.png)

## Features that are used across the site
To keep the professionalism of the site I kept certain features the same across each page this also makes navigating around easier for the user. 


  **Nav Bar** 
---
The Navbar appears on all pages, it has interactive links to all pages, home, menu, contact us and review. To make the user understand which page they are currently on I used a class of "active" to change the background color of the active page. To add to the user experience I implemented a :hover function, so when the user hovers over each page the background color is changed. For the media query of (Max-width: 620px;) I removed the :hover function so the hero image text was overlapped with the background color.
Update - 16/11/2021 I have made the navbar have a bigger font and changed the text color to make the contrast better when the user is scrolling.

![old nav bar screenshot](assets/docs/images/old-navbar.jpg)
---
Throughout testing and hearing feedback I learned that my nav bar color scheme wasn't very user friendly and didn't contrast so well, I needed a new navbar so below I will display it. 

![navbar screenshot](assets/docs/images/new-navbar-ss.png)
After twiddling and adjusting my navbar I found a contrast that worked for all devices to make the navbar keep the professional feel and look. When users are using a desktop with the hover function it looks like such: 

![navbar with hover](assets/docs/images/new-navbar-hover.jpg)
 

  **Hero Image** 
---
The hero image is shown at the top of each page (below the nav), by continuing to show the hero image across each page it creates a familiar feel for the user and reminds them of which restaurant they're visiting. To further increase the user experience I have placed text within the hero image which is sat on top, the information within this text makes it possible for the user to have all info on one page if needs be. Upon loading into each page the hero image has a zoom effect, to essentially show off the brand of which is Castleia and force them to notice it and its surrounding elements. 
Within the marketing industry repetition is a key factor, reminding the customer how they can get in touch is a key factor to improving the chances of the user getting in contact and using the product, in this case visiting the restaurant.
  
  ![hero image display](/assets/docs/images/hero-image-sc.jpg) 

**Footer**
---
I placed the footer at the bottom of my site mirrored with the navbar to keep consistency across all pages, I used only icons for the footer, Facebook, Twitter, Instagram and Pinterest, again all icons were taken from Font awesome. I made a hover effect for these icons with text and box shadows 

`code` 
 .footer-main :hover {
    font-size: 40px;
    color: #e2d6bd;
    box-shadow: 0 0 5px #e2d6bd;
    text-shadow: 0 0 5px black;
} 

![footer hover](assets/docs/images/footer-hover.png)

## Icons and Font use 
Across the site I have used two fonts:
 -  Source Code Pro  [Google fonts](https://fonts.google.com/)
 -  Dosis [Google fonts](https://fonts.google.com/)
I used these two fonts as they compliment each other quite well and keep to my style of simple, professional and elegant. 
All of the fonts I used were sourced from Google Fonts.

Across the site, I used many icons to make the site work for all audiences as well as make navigation easier. 
All icons I used were from Font Awesome. [FontAwesome](https://fontawesome.com/)

# Individual Page Content

## Home Page content
- As this is the first page the user loads into I needed to make it look classy and appealing. 
- I typed up phrases to make the customer feel good, I also used capitalization on the word "you" to grab the users attention and involve them within the site.
- I've included three separate images to catch the users attention by making them bright and related to the content written above, I used style to have them all line up next to each other with the same zoom effect that I used on the hero image.
- Further on down the line I decide to change the image displaying in the centre of the three to the opening times table taken from the reserve page, to make the site even more interactive I made this image a hyperlink to the reserve a table page and placed text in in the paragraph informing the user of the link to make their life easier.
![Screenshot of home page](/assets/docs/images/home-page.png) 


## Menu Page
- The layout of this page was crucial, although it isn't packed with images, videos and links, the purpose of the site entirety is to get the customers falling in love with the food. To make them purely fall in love with food, I've centred the entire menu and made it easier to read with different header elements. 
- This page also uses icons to display that different dietary needs are met, making the site more applicable for a wider range of the user.
- To help the user navigate to the opening hours section of the site I created an image with a link to the appropriate site page.
![Screenshot of menu page](/assets/docs/images/menu-page.png)


## Review Page
- On this page I made the content read left to right so the user is drawn to fill in the review form. 
- I used placeholders for each form input type to make the user experience easier. 
- Each field is requested to put a stop to false information being input. 
![Screenshot of review page](/assets/docs/images/remove-js.png)

## Contact Page
- The contact page is one of my favourites because I got to use a variation of different code, such as "Display - Padding - Vertical Align" using many CSS styles allowed me to understand how they all worked, improving my knowledge. 
- I created three smart looking, simple effective boxes with relevant information regarding different ways to help the user. 
- Below my helpful boxes I used a form with the use of (name - input) (email - input) (email - input) and a (textarea) again using an onclick command with a relevant popup. I decided to have this form in a horizontal position so the user can locate the google map which I included inside an iframe. 
- The iframe I used on this page was a link from google maps, as Castleia isn't a real location I used the destination of my old workplace with a similar name. 

![Screenshot of contact page](/assets/docs/images/contact-us.png)
![Screenshot of iframe on contact page](/assets/docs/images/iframe.png)

## Reserve Page 
- I created this page with the idea of focusing on the reserve form I did this by placing images on either side and the form in the center. 
- Also displayed on the page is the opening hours of the restaurant which is also available on the home page with a hyperlink. 
- I used a form with multiple input types to show my understanding of each element such as 
- [x] Name
- [x] Number
- [x] Email
- [x] Textarea
- [x] Option
![Screenshot of reserve page](assets/docs/images/reserve-page.png)

# Future Developments 
* In the future I would like to be able to add 
  - A pre-book function, when the user opts for 6+ party members the menu is displayed with an option to choose what items each party member wants + adjustments to the food item. 
  - A team page, where the customer can see all of the staff, with images of each person and their role within the company. 
  - A page for guests to buy gift vouchers with the desired value they want with all the details forwarded to their email address. 
* Indefinitely I would have to understand Javascript to make this possible, I could have created a mock version of this within CSS and HTML but didn't seem fit for my time to do so.  
* Forms 
    - I wish to make all the forms with the value of push, of course, this would have to make Castleia a real location. 

# Testing 
I have created a seperate [Testing.md](/TESTING.md) 

# Credits 
## Personal Mentions
Across my project I have had great support from the following people. 

- [Ollie Train](https://github.com/Olivertrain1221) From the start of my project I have had assistance from a new friend called Ollie who i met within the Slack community, he has helped me realise that I do have the abilaty to complete what i have, we have shared many calls together to work through problems together, a massive shout out to this man. 

- [David Bowers](https://github.com/dnlbowers) David has been nothing but a 1st class hero when its come to this project, he's helped me across the board with testing, advising and supporting I wouldnt be where I am today without him. 

- [Stephen Darcy](https://github.com/darco31) Mr Stephen Darcy, a fellow student, a living legend has been through thick and thin with me over this project, he to has advised, supported and tested my site multiple times. A great prospur in the coding world. 

- [Richard Wslls](https://github.com/D0nni387) Last but certanily not least, the best mentor on planet earth. Richard has gone above and beyond to support me. When I was apointed MR Wells as a new mentor I wasnt sure what tot ecpect but he has pushed me to eveyrhting i am today, he has pushed all boundries to keeping me grounded and lifting me up when i needed it the most, this man deserves all the praise he gets. 

- [The Entire Slack Community](https://slack.com/intl/en-gb/) What a fantastic community we really have, constant support and guidance even at silly o'clock in the morning/ night. I am proud to be a part of it.

## General 

Throughout my project I have tried to keep everything my own code but some code was influenced by The Love Running project. 
i Used [W3 Schools](https://www.w3schools.com/), [Stack Overflow](https://stackoverflow.com/) and the Code institue tutor live chat throughout my project to acomplish what i have. 

# Content 
- All content on the pages is that of my own. 
- All icons i used on the page were used from [Font Awesome](https://fontawesome.com/).
- My fonts were taken from [Google Fonts](https://fonts.google.com/)
- My personal ![Independent Checker](assets/docs/images/self-check.png)
- When it came to converting images to WEBp i used [Convertio](https://convertio.co/png-webp/)
- To compress my images i used [TinyPNG](https://tinypng.com/)
- To calculate pixels to rems i used [PX to Rem Calculator](https://nekocalc.com/px-to-rem-converter)

# Media 
- For all my images i used [Pexels](https://www.pexels.com/)
- Screenshot thats on the top of README.md [Am I Responsive](http://ami.responsivedesign.is/)





