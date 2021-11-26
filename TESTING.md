# Testing 
After the completion of my site, I conducted testing within different browsers.
- Chrome
- Firefox 
- Internet Explorer 
- Microsoft Edge 

## Browsers 
- Chrome 
  - I used chrome for the development of my site and did all testing on this browser as I went along. 
- Firefox 
  - To test the site on Firefox I used the site within the dev tools to make sure it was responsive across all devices. No issues were found.
- IE 
  - Dev tools were also used within IE to check the capabilities of the site. No issues were found.
- Microsoft Edge 
  - No issues were found. 

Across Firefox, IE and Edge I ran into an error; When clicking on the image with the link to the reserve page I got the below; 
- To fix this issue I asked the Slack community but I am yet to hear any fix or reason for this message. 
![Error 404](assets/docs/images/error-display.png) 
- I later found a fix for this error, I needed to link the page to the deployed site instead of reserve.html.  

## Independent Testing 
To have the best feedback possible I asked a good friend of mine who uses a selection of browsers and sites on a daily basis to use the site as if they were a customer and give me their opinions and any bugs they came across. 
![Friend Review](assets/docs/images/friend-review.png)

To futher improve testing, i used the website myself and put myself in the users shoes. I tested all the forms across the site to check they could by typed in with the particular values. I also used the map to see if i was able to move around and check the iframe worked correctly. 



# Validator 
To validate my HTML I used [W3C](https://validator.w3.org/) 
![Validate HTML](assets/docs/images/html-validate.png)

To validate my CSS I used [W3C](https://jigsaw.w3.org/css-validator/)
![CSS validator](assets/docs/images/css-validate.png)

## DEV tools
Once i finished the design of the page i wanted to check the CSS to ensure there was no unused code. To do this i opened DEV tools and manually deleted code to see if it was in use, i compilied a list of code that wasnt in use i went back into my CSS stylesheet and deleted unused code, this helped clear up the page and add comments too each section of CSS. 
To improve my understanding and targeting certain elements I created a rule to change background-color: yellow; doing this made seeingeach element easier so i knew what i needed to change and adjust in my main css. 

# Lighthouse 
I completed lighthouse audits in incognito mode to ensure any chrome extensions didn't interfere with the report.
To guarantee the most accessibility across all pages I ran audits for each page for both desktop and mobile. 

## Lighthouse Reports
The below screenshots are for lighthouse reports for desktop but when I ran them for mobile they were the same or a little higher, I've chosen to display the desktop reports and lowest to show how I repaired them to increase the report. 
--- 

**Home Page**
![Home Page Lighthouse](/assets/docs/images/index.lighthouse.png)

**Menu Page**
![Menu Page Lighthouse](/assets/docs/images/menu.lighthouse.png)

**Reserve Page Before & After**
![Reserve Page Lighthouse](/assets/docs/images/reserve.lighthouse.png)
  - I read through the report and made changes to ARIA ids along with removing an aria label from the navbar. 
![Fixed Reserve Page Lighthouse](/assets/docs/images/fix.reserve.lighthouse.png)

**Review Page** 
![Review Page Lighthouse](/assets/docs/images/reviews.lighthouse.png)

**Contact Page Before & After**
![Contact Us Page Lighthouse](/assets/docs/images/contact.lighthouse.png)
  - After going through the report I needed to make the ID's in the form input titles unique, instead of going through each and making new values for them I created a class making it easier to target them within the CSS stylesheet.
![Fixed Contact Us Page Lighthouse](/assets/docs/images/new.contact.lighthouse.png)

As well as using lighthouse I found another [Independent Accessibility Checker](https://www.siteimprove.com/) to further improve my understanding of the accessibility of my website. 
![Independent Check](assets/docs/images/self-check.png)
After checking and going through all of the reports and editing on Dev Tools I feel much more comfortable and confident using HTML and CSS. On making my next project I will have a head start in making the site more accessible from the start thus ensuring I have more time to perfect the project and less time going over elements, of course still conducting regular tests.

# Changes Along the Way 
Throughout the course of my project I made decisons that effected the way the website runs and displays now as a finished project. 
- On each of the forms I origanlly used a code from [W3](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_input_button) But after testing this feature out i realised that it did not clear the form like a submit button would. If my knowledge of JavaScript was better i would of kept this in but to keep my site as realisitc and funcitnol as possible i decided to stick with a simple submit type. 
- When I started the project there were only infact three pages, Home, Reviews and menu. Booking a table was on the home page as I wanted to force this upon the user, but it was pointed out to me by peers and fellow students that when they visited the site for the first time it didnt feel like they were on a home page and often tried refreshing the page. After hearing this feedback i decided to make the reserve page. By doing this I made an additional page which is now fully funcitnal and created the home page we see today, with a simple paragraph and some images it quickly became a much better feeling site. 
- The forms on media querys, at first i created the site for desktop and when it came to the forms for smaller devices it massively deformed the screen, so i took the inititive to create forms for smaller screens and displying them as hidden, i found this to work effective and also improved my ability in CSS. 


 [Back to README](/README.md) 





    