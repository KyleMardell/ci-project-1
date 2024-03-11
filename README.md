# Garden Collective

The Garden Collective website is aimed at gardening enthusiasts looking to join a local gardening club. The landing page is aimed at gardeners looking for more information or to join the club. The club encourages people of all ages to get into gardening by growing their own fruit and veg at the allotment the club is based on.

Users of the Garden Collective website can find information about the club, how it is run, who is welcome and club times. There is a club calendar to show which months the club is open and what fruit and veg will be planted and harvested. The site is targeted at gardening enthusiasts local to the manchester area.

![Responsive Mockup](https://github.com/KyleMardell/ci-project-1/blob/main/media/am-i-responsive.png)

## Features

### Existing Features
    
#### Navigation bar
- The navigation bar is identical on all 4 pages of the site and it fixed to the top of the screen for both consitancy and ease of use. 
- The nav bar is fully resposive with a drop down menu for smaller screens and a fixed page list on larger screens. 
- This section allows the user to easily navigate the site and see all available pages without using the browsers "back" button.

![Nav Bar](https://github.com/KyleMardell/ci-project-1/blob/main/media/header.png)

#### Hero section
The landing page or hero section displays a large image of the clubs allotment, with a text overlay of the club location, letting the user know imediately who the site is for.

![Hero Section](https://github.com/KyleMardell/ci-project-1/blob/main/media/hero-section.png)

#### Info section
- The info section gives the user all the information needed about the club and serves to attract more members.
- On small devices(phone screens) the information is split into 4 text boxes, each giving different aspects of information about the club.
- On larger devices, the text boxes are accompaied by a relevant image and is displayed in a grid format to make better use of screen space.

![Info Section](https://github.com/KyleMardell/ci-project-1/blob/main/media/info-section.png)

#### Call-To-Action section
- The call-to-action section is a way to direct users to the contact/sign-up page. 
- This section displays an attractive image with with a textbox overlay. The text box contains a link to the sign-up page. 
- This section provides the user a quick way of navigating to the sign-up page, and the use of a call to action will further entice potential club memebers to join.

![Call To Action Section](https://github.com/KyleMardell/ci-project-1/blob/main/media/cta-section.png)

#### Calendar page
- The calendar page gives the user more information about what produce the club is planting and harvesting from month to month, throughout the growing season. 
- This section gives the user further information about what produce the club grows and what they can expect when joining a session in a particular month. 
- It can also be used as a calendar for home growing, displaying when each vegetable should be planted or harvested.

![Calendar Page](https://github.com/KyleMardell/ci-project-1/blob/main/media/calander-section.png)

#### Gallery page
- The gallery page displays photos of the types of produce that the club grows and what a club member can expect to see at the allotment. 
- It also serves to display all the images from the other pages that are not displayed on smaller devices. This means all photos can still be viewed when using a mobile device to access the site.

![Gallery](https://github.com/KyleMardell/ci-project-1/blob/main/media/gallery%20section.png)

#### Contact page
- The contact page allows the user to send a message to the club. 
- It also serves as a way for potential members to display an interest in joining the club. On the contact page there is an optional checkbox section, designed to let the club oporator easily see what type of question a user may have. 
- The user is required to submit their first and second name, email adress and message in order to send in a contact form.

![Contact Page](https://github.com/KyleMardell/ci-project-1/blob/main/media/contact-section.png)

### Fututre features to implement
- I would like to add a page that displays club memeber messages, feedback and reviews. This feature would be used to show positive messages from club members and would serve to attract new memebers to the club.

## Testing

### Site Testing
Testing in development was done using Google Chrome Developer Tools on a Windows 11 machine. While building the site i used the "inspect" option within Google Chrome to display different device screen sizes. I also tested the site on a 1080p and 4k monitor to check for consistancy accross all larger screen sizes. 

The site was deployed to GitHub pages early in development. I used this as a way to check that implemented features were diplayed correctly when not using my development environment. I would test the deplyed site at the end of every session to ensure it was working as expected through the internet, not just a local server. 

I tested the funtionality of the site on multiple browsers, including Chrome, Firefox, Edge and Safari. 

Testing included, all internal links work correctly, all external links work correctly and open in a new browser tab, all layouts are displayed as intended, contact form required information and warning messages, contact form can be submitted correctly, dropdown menu can be accessed and is displayed correctly.

### User Testing
In the website user testing stage I had deployed the site on GitHub Pages and asked friends and course peers to test the site for both functionality and looks. Here is some of the feedback I recieved and what i changed on the site to reflect this feesback.

- Paragraph text did not fit the style of the site and should follow the style of the heading font
    - Changed the font to a more 'handwritten' style to better suit the site
- Signup page form is more of a contact form than a signup form
    - Changed naming of 'Signup' to 'Contact' to better suit
- Desktop headings seems small for the screen size
    - Increased heading sizes in home and calendar pages

Some users thought the contact form could be larger on desktop sized screens, others liked the consistant layout across multiple devices. After some consideration i decided to keep the size of the contact form for consistancy as user feedback was fairly evenly split.

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

## Deployment
- The site was deployed using GitHub pages.
- The repositary can be found here - https://github.com/KyleMardell/ci-project-1
- The deplayed site can be found here - https://kylemardell.github.io/ci-project-1/index.html

## Credits

### Content
The calendar planting and harvesting content was taken from [Love the garden](https://www.lovethegarden.com/)

### Media
- Photos used on the website are from [Pixabay](https://www.pixabay.com)
- Icons used on the wesite are from [Font Awesome](www.fontawesome.com)
- Font used on the website are from [Google Fonts](www.fonts.google.com)



