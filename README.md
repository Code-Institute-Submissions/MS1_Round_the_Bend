<h1 align="center">Round the Bend Website</h1>

[View the live project here.](https://msierag.github.io/MS1_Round_the_Bend/)

This is the website for the fictional organisation Round the Bend. The purpose of this website is to provide the biker community with a location to share gps routes. It is designed to be responsive and accessible on a range of devices, making it easy to navigate for potential users.

<h2 align="center"><img src="https://i.ibb.co/TYvTXz1/Example-CI.png"></h2>

## User Experience (UX)

-   ### User stories

    -   #### Visiting User Goals

        1.  
        2. 
        3. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
        4. As a First Time Visitor, I want to locate their social media links to see their followings on social media to determine how trusted and known they are.

        1. As a Returning Visitor, I want to find the best way to get in contact with the organisation with any questions I may have.
        2. As a Returning Visitor, I want to be able to view the details of the routes.
        3. As a Returning Visitor, I want to be able to download the gps files for the route of my choice.

        1. As a Frequent User, I want to be able to post routes.
        2. 
        3. As a Frequent User, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.

-   ### Design
    -   #### Colour Scheme
        -   There are five colours used throughout the site, the first three are main colours and the remaining two are used for accents.
                ![Coolors rendering of colour scheme](./docs/rtbcolourscheme.png)
            The colours #0F306E, #5982DE and F80905 were chosen as they approach the palette of the decals on the 1988 Honda Transalp 600, an iconic enduro motorcycle. The colour #D4AF37 was chosen as an accent colour as it resembles the colour of many motorcycle brake calipers. Finally, #D8F4FB was added as a transition colour to soften the vibrant palette where needed. 
    -   #### Typography
        -   The Domine font is the main font used throughout the whole website with Fira Sans, Raleway and ultimately Sans Serif as the fallback fonts in case for any reason the font isn't being imported into the site correctly. Domine is a serif font which was designed for body text on the web and is friendly on the eyes.
    -   #### Imagery
        -   Imagery is important. The large, background hero image is designed to be striking and catch the user's attention. It puts the user in the position of a biker in the driver's seat. The three images used in the Explore, Connect and Inspire sections of the Home page capture the gist of the text. The image at the top of the Routes page represents the sense of adventure and freedom typically associated with riding a motorcycle. 

*   ### Wireframes

    -   Home page wireframe - [View](./docs/rtbhome.png)

    -   Routes page wireframe - [View](./docs/rtbroutes.png)

    -   Contact page wireframe - [View](./docs/rtbcontact.png)

    -   Uploads page wireframe - [View](./docs/rtbuploads.png)

    -   Mobile wireframes - [View](./docs/rtbsmartphone.png)

    -   Table wireframes - [View](./docs/rtbtablet.png)

## Features

### Existing features

#### Features across all pages

-   Navigation bar which remains fixed at the top of the page. It makes for easy and consistent navigation throughout the site. The current page is highlighted dark.

-   Footer which appears on every page and stays at the bottom. The footer contains the statement that this website is for educational purposes only.

-   Newsletter sign-up button is located in middle of the footer on every page. The colours on the button are inverted when the user hovers over it. When selected, a modal pop-up appears allowing the user to submit their email address.

-   Social media icons are located in the right hand section of the footer and appear on every page. When the user hovers over an icon it appears darker against the background. When selected the icons provide a link to the relevant social medium in a separate page.

#### Page specific features

##### Home page

-   Hero image which takes up the full view height upon opening. The image virtually puts the user in the driver's seat with a view across the handlebars, which aims to create an emotional connection.

-   Scrolling mouse wheel animation to direct the user to scroll down to the content initially hidden from view by the hero image.

-   Content section containing three cards with statement headings and minimal text aimed to elicit an emotional response. The text is flanked by images to match the message. The text is followed by a call to action button which reiterates the statement heading and when selected lands the user on the appropriate page on the website.  

##### Routes page

-   Heading image which conveys the sense of adventure and freedom typically associated with riding a motorcycle. The image is deliberately not full-width nor full view height so as not to obscure the content section or require a scroll invitation.

-   Content section consisting of cards with the details of the routes on offer. The section is subdivided by country and designated by a heading. Each route card contains a call to action button inviting the user to download the gpx file. When selected the download opens on a separate tab. 

##### Contact page

-   Contact Us column contains a form which allows the users  

-   Call to action buttons 

##### Uploads page

-   

### Future features

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Hover.css:](https://ianlunn.github.io/Hover/)
    - Hover.css was used on the Social Media icons in the footer to add the float transition while being hovered over.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand the main purpose of the site.

        1. Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. Underneath there is a Hero Image with Text and a "Learn More" Call to action button.
        2. The main points are made immediately with the hero image
        3. The user has two options, click the call to action buttons or scroll down, both of which will lead to the same place, to learn more about the organisation.

    1. As a First Time Visitor, I want to learn more about the organisation.

        1. The user has two options, click the call to action buttons or scroll down, both of which will lead to the same place, to learn more about the organisation.

    2. As a First Time Visitor, I want to be able to easily be able to navigate throughout the site to find content.

        1. The site has been designed to be fluid and never to entrap the user. At the top of each page there is a clean navigation bar, each link describes what the page they will end up at clearly.
        2. At the bottom of the first 3 pages there is a redirection call to action to ensure the user always has somewhere to go and doesn't feel trapped as they get to the bottom of the page.
        3. On the Contact Us Page, after a form response is submitted, the page refreshes and the user is brought to the top of the page where the navigation bar is.

    3. As a First Time Visitor, I want to locate their social media links to see their following on social media to determine how trusted and known they are.
        1. The user can also scroll to the bottom of any page on the site to locate social media links in the footer.
        2. At the bottom of the Contact Us page, the user is told underneath the form, that alternatively they can contact the organisation on social media which highlights the links to them.
       
-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to find the best way to get in contact with the organisation with any questions I may have.

        1. The navigation bar clearly highlights the "Contact Us" Page.
        2. Here they can fill out the form on the page or are told that alternatively they can message the organisation on social media.
        3. The footer contains links to the organisations Facebook and Instagram page as well as the organization's email.
        4. Whichever link they click, it will be open up in a new tab to ensure the user can easily get back to the website.

    2. As a Returning Visitor, I want to be able to view the details of the routes.

        1. The routes are listed on the "Routes" page by country of destination.
        2. A short description of the route is provided with each route.
        2. Additional facts listed for each route are total length in km, approximate duration, starting location, final destination and the name of the user who submitted the route. 

    3. As a Returning Visitor, I want to download the gps file for the route of my choice.
        1. The routes are located on the "Routes" page.
        2. There is a button with the download symbol marked "GPX file" next to each individual route.
        
-   #### Frequent User Goals

    1. As a Frequent User, I want to be able to post routes.

        1. The user would already be comfortable with the website layout and can easily click the "Uploads" page.
        2. Here they can fill out the form.
        3.  

    2. As a Frequent User, I want to check to see if any new routes have been posted.

        1. The user would already be comfortable with the website layout and can easily click the "Routes" page.
        
    3. As a Frequent User, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.
        1. At the bottom of every page there is a footer which content is consistent throughout all pages.
        2. To the right hand side of the footer the user can see "Subscribe to our Newsletter" and are prompted to Enter their email address.
        3. There is a "Submit" button to the right hand side of the input field which is located close to the field and can easily be distinguished.

### Further Testing

-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

-   On some mobile devices the Hero Image pushes the size of screen out more than any of the other content on the page.
    -   A white gap can be seen to the right of the footer and navigation bar as a result.
-   On Microsoft Edge and Internet Explorer Browsers, all links in Navbar are pushed upwards when hovering over them.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code

-   The full-screen hero image code came from this [StackOverflow post](https://stackoverflow.com)

-   [Bootstrap4](https://getbootstrap.com/docs/4.4/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.

-   [MDN Web Docs](https://developer.mozilla.org/) : For Pattern Validation code. Code was modified to better fit my needs and to match an Irish phone number layout to ensure correct validation. Tutorial Found [Here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/tel#Pattern_validation)

### Content

-   All content was written by the developer.

-   Psychological properties of colours text in the README.md was found [here](http://www.colour-affects.co.uk/psychological-properties-of-colours)

### Media

-   All Images were created by the developer.

### Acknowledgements

-   My Mentor for continuous helpful feedback.

-   Tutor support at Code Institute for their support.