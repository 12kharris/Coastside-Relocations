# Coastside Relocations

[Link to final deployed Project](https://12kharris.github.io/Coastside-Relocations/)

Coastside Relocations is a webiite which advertises a portfolio of properties in which a user can chose to stay in when goin on a holiday by the sea. The site is targeted to those who wish to stay in high quality accommodation on their seaside retreat. The site will be provide a description of the property as well as its location to aid the user's choice. There are also pages for the user to contact the company and sign up for more information.

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

  - On all pages is a navigation bar where users can navigate to the home page, the contact page and the sign up page. On small screens this is collapsable. [IMAGE OF NAV BAR IN COLLAPSABLE AND NORMAL STATE]

- __The landing page image__

  - The landing page features a brief sentence in a banner for the goal of the company so it is clear to a user what the company does.
  - The landing page also features images and titles of the properties which the company is advertising for people to stay in. The design is responsive so the images will be displayed appropriately on various screen sizes. There are also buttons which the user can click to get more information on the property.
  - There ia a short 'About Us' paragraph providing more detail on what the company can offer for a user.
  - Finally on the landing page there is an audio clip which a user can interact with to play sea sounds to get them in the mood for a seaside holiday.
  - [IMAGE OF LANDING PAGE]
  
- __The Location Pages__
  - There is a page for each location advertised by the company. They each have the same structure and are used to provide more information on a property.
  - There is a main picture of the exterior of the property followed by a paragraph describing the property so a user can decide whether or not it is the type of property they would like to stay in.
  - Beneath the property description there is a collection of images of the interior of the property for the user to look at and give them more of an idea as to whether they would like to choose this property to stay in.
  - Finally at the bottom of each location page is a google map showing the location of the property. A user can click on this map and it will open google maps in a sepaarte tab for them to explore.
  - [IMAGE OF LOCATION PAGE]

- __The Contact Us Page__

  - This page features a form which users can fill out to submit a question to the company.
  - The form has validation and some fields are required.
  - There also features a text area where users can type their question.
  - [IMAGE OF CONTACT PAGE]

- __The Sign Up Page__

  - This page features another form for a user to sign up to receive emails corresponding to the categories of information they wish to receive in the 'Communication Preferences' buttons.
  - This form also features validation and required fields.
  - [IMAGE OF SIGN UP PAGE]

- __The Footer__

  - The footer conatins links to the major social media platforms if the user wishes to visit them.
  - The footer is always visible on the page.

### Features Left to Implement

- An ability to book directly through the website on each location page. A form which features a date selection from a calendar with dates blocked out for other bookings.
- There is a lot of empty space on large screens for the location pages so having the pictures have a menu which can be selected from and the chosen image displayed as the main image would help this.

## Testing

All navigation links on all pages were tested to ensure they navigated correctly. The Chrome dev tools were used to simulate different screen sizes. On small screens, there is less padding of the main content so the page fills the vast majority of the screen width. On larger screens, a small amount of padding was introduced to focus the content more. Furthermore, on larger screens, the navigation menu is not collapsed. Extensive flex box use for containers means that content will stretch to fill the screen in the case of sections with multiple images for example.

Navigating back to the home page is available on every page of the website and links and buttons will change colour when hovered over to provide good user feedback. If a user is on a page featured in the main navbar, this link will be underlined to show this. The site layout is intuitive and high contrast and consistent colours are used to clearly display to the user whether something is a link, text or button.

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2F12kharris.github.io%2FCoastside-Relocations%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2F12kharris.github.io%2FCoastside-Relocations%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

- The 'back to home' link featured on the location pages has an arrow which doesn't change colour to light blue when just the 'Home' text is hovered over. This should not be the case.

## Deployment

- The site was deployed to GitHub pages early in development to check file paths and internal links. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - [Deployed Website](https://12kharris.github.io/Coastside-Relocations/)

## Credits

### Content

- The collapsable navbar and footer structure were adapted from Code Institute's 'Love Running' project. [Love Running GitHub](https://github.com/Code-Institute-Org/love-running-2.0)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- The IFrame elements of the google maps was taken from the following [Stack Overflow Thread](https://stackoverflow.com/questions/33464192/display-an-embedded-google-map-iframe-with-a-marker-on-a-certain-latitude-and-lo).

### Media

- All images were taken from [Pixabay](https://pixabay.com/).
- The audio clip was downloaded from [Freesound](https://freesound.org/).

