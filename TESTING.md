## Testing

### Site Testing
Testing in development was done using Google Chrome Developer Tools on a Windows 11 machine. While building the site I used the "inspect" option within Google Chrome to display different device screen sizes. I also tested the site on a 1080p and 4k monitor to check for consistancy accross all larger screen sizes. 

The site was deployed to GitHub pages early in development. I used this as a way to check that implemented features were diplayed correctly when not using my development environment. I would test the deplyed site at the end of every session to ensure it was working as expected through the internet, not just a local server. 

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

I tested the website using Google Chromes Lighthouse tool for accessibility, performance, best practices and SEO. Performance recieved a score of 85% and all other categories recieved 100% scores.

### User Testing
In the website user testing stage I had deployed the site on GitHub Pages and asked friends and course peers to test the site for both functionality and looks. Here is some of the feedback I recieved and what I changed on the site to reflect this feesback.

- Paragraph text did not fit the style of the site and should follow the style of the heading font
    - Changed the font to a more 'handwritten' style to better suit the site
- Signup page form is more of a contact form than a signup form
    - Changed naming of 'Signup' to 'Contact' to better suit
- Desktop headings seems small for the screen size
    - Increased heading sizes in home and calendar pages

Some users thought the contact form could be larger on desktop sized screens, others liked the consistant layout across multiple devices. After some consideration I decided to keep the size of the contact form for consistancy as user feedback was fairly evenly split.

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

### Validator Testing

- HTML
    - No errors were returned when passing through the official [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkylemardell.github.io%2Fci-project-1%2Findex.html)
- CSS
    - No errors were returned when padding though the official [(Jigsaw) Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkylemardell.github.io%2Fci-project-1%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

- User can choose not to select any checkbox on the signup page
    - It is not possible to make at least one checkbox 'required' using only HTML and CSS and requires the use of JavaScript
