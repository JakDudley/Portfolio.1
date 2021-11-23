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
To have the best feedback possible I asked a few friends to use the site as if they were a customer and give me their opinions and any bugs they came across. 


# Validator 
To validate my HTML I used [W3C](https://validator.w3.org/) 
![Validate HTML](assets/docs/images/html-validate.png)

To validate my CSS I used [W3C](https://jigsaw.w3.org/css-validator/)
![CSS validator](assets/docs/images/css-validate.png)

# Lighthouse 
I completed lighthouse audits in incognito mode to ensure any chrome extensions didn't interfere with the report.
To guarantee the most accessibility across all pages I ran audits for each page for both desktop and mobile. 

## Lighthouse Reports
The below screenshots are for lighthouse reports for desktop but when I ran them for mobile they were the same or a little higher, I've chosen to display the desktop reports and lowest to show how I repaired them to increase the report. 
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

After checking and going through all of the reports and editing on Dev Tools I feel much more comfortable and confident using HTML and CSS. On making my next project I will have a head start in making the site more accessible from the start thus ensuring I have more time to perfect the project and less time going over elements, of course still conducting regular tests. 3


 [Back to README](/README.md) 





    