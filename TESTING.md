## Testing

Testing in development was done using Google Chrome Developer Tools on a Windows 11 machine. While building the site I used the "inspect" option within Google Chrome to display different device screen sizes. I also tested the site on a 1080p and 4k monitor to check for consistancy accross larger screen sizes. 

The site was deployed to GitHub pages early in development. I used this as a way to check that implemented features were diplayed and functioning correctly when not using my development environment. I would test the deplyed site at the end of every session to ensure it was working as expected through the internet, not just a local server. 

I used the W3 Validator for both the HTML and CSS to check there were no errors on the site.

### Validator

- HTML Testing Using The [W3C Validator](https://validator.w3.org/)
    - [Index Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkylemardell.github.io%2Fgarden-collective%2Findex.html)
    - [Calendar Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkylemardell.github.io%2Fgarden-collective%2Fcalendar.html)
    - [Gallery Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkylemardell.github.io%2Fgarden-collective%2Fgallery.html)
    - [Contact Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkylemardell.github.io%2Fgarden-collective%2Fcontact.html)
    - [Confirmation Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkylemardell.github.io%2Fgarden-collective%2Fconfirmation.html)
    - [404 Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkylemardell.github.io%2Fgarden-collective%2F404.html)

- CSS Testing Using The [Jigsaw Validator](https://jigsaw.w3.org/css-validator/)
    - [Index Page](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkylemardell.github.io%2Fgarden-collective%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
    - [Calendar Page](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkylemardell.github.io%2Fgarden-collective%2Fcalendar.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
    - [Gallery Page](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkylemardell.github.io%2Fgarden-collective%2Fgallery.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
    - [Contact Page](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkylemardell.github.io%2Fgarden-collective%2Fcontact.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
    - [Confirmation Page](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkylemardell.github.io%2Fgarden-collective%2Fconfirmation.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
    - [404 Page](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkylemardell.github.io%2Fgarden-collective%2F404.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Lighthouse

I tested the website using Google Chromes Lighthouse tool for accessibility, performance, best practices and SEO. All categories recieved high scores across both desktop and mobile testing. When testing on mobile the performance scores dropped slightly as expected due to the use of high quality images, but not enough to noticably affect the user experience. When testing the confirmation page, an accessibility score of 92% was achieved due to the use of a redirection meta tag. Although this reduces the score, I believe the use of a confirmation page  and redirect to the home page increases the overall user experience.

#### Desktop Results
- [Index Page](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/index-lighthouse-desktop.png)
- [Calendar Page](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/calendar-lighthouse-desktop.png)
- [Gallery Page](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/gallery-lighthouse-desktop.png)
- [Contact Page](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/contact-lighthouse-desktop.png)
- [Confirmation Page](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/confirmation-lighthouse-desktop.png)
    - [Accessibility Score](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/accessibility-lighthouse-desktop.png)
- [404 Page](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/404-lighthouse-desktop.png)

#### Mobile Results
- [Index Page](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/index-lighthouse-mobile.png)
- [Calendar Page](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/calendar-lighthouse-mobile.png)
- [Gallery Page](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/gallery-lighthouse-mobile.png)
- [Contact Page](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/contact-lighthouse-mobile.png)
- [Confirmation Page](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/confirmation-lighthouse-mobile.png)
    - [Accessibility Score](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/accessibility-lighthouse-mobile.png)
- [404 Page](https://github.com/KyleMardell/garden-collective/blob/main/media/lighthouse/404-lighthouse-mobile.png)

### WAVE

All pages of the site were tested using the Web Accessibility Evaluation Tool (WAVE)

### User Testing

In the user testing stage I had deployed the site on GitHub Pages and asked friends and course peers to test the site for both functionality and looks. Here is some of the feedback I recieved and what I changed on the site to reflect this feedback.

- Paragraph text did not fit the style of the site and should follow the style of the heading font
    - Changed the font to a more 'handwritten' style to better suit the site
- Signup page form is more of a contact form than a signup form
    - Changed naming of 'Signup' to 'Contact' to better suit
- Desktop headings seems small for the screen size
    - Increased heading sizes in home and calendar pages

Some users thought the contact form could be larger on desktop sized screens, others liked the consistant layout across multiple devices. After some consideration I decided to keep the size of the contact form for consistancy as user feedback was fairly evenly split.

### Site Testing

I tested the funtionality of the site on multiple browsers, including Chrome, Firefox, Edge and Safari. 

I tested responsiveness of the site and links using the following physical devices:
- Windows PC
- Apple Macbook Pro (2023)
- iPad pro (2021)
- iPhone 15
- Galaxy S20

Testing included:
- Internal links
    - Tested all links to internal pages work correctly
- External links
    - Tested all external links open in a new browser window 
- Nav bar
    - Tested dropdown works as intended on mobile devices
    - Tested expanded nav bar is shown correctly on larger deviced
- Home page
    - Tested home page is responsive and changed layout per device
- Gallery
    - Tested gallery is resposive and changes layout per device
    - Tested background colour is displayed on large screens due to masonry style layout
- Calendar
    - Tested calendar page is responsive and changes layout per device
- Contact form
    - Tested contact form for warning messages and correct submission
- Images
    - Tested all images are displayed on all devices

### Manual Testing

### Bugs

- Nav bar text not aligned with logo text
    - Removed padding to correctly align all items is the nav bar
- Hero text not filling container/div
    - Aligned text to center on larger screens
- Info images not resizing to fit design
    - Used a div for consistant sizing and added the image as a background to maintain aspect ratio
- Contact page image not filling the screen
    - I was applying the image to a div instead of the section. Applied image to section background
- Background images on calendar and contact pages exceeded screen height
    - I had set the min 'height' to viewport 'width', changed to viewport height as intended

### Unfixed Bugs

- User can choose not to select any checkbox on the signup page
    - It is not possible to make at least one checkbox 'required' using only HTML and CSS and requires the use of JavaScript

