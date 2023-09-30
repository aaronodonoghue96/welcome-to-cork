# Welcome To cork

Welcome To Cork is a website about the city of Cork, which tells users a bit about the city, some things to do in Cork, and shows pictures of places to visit in Cork. It is targeted at tourists who are looking for an idea of where to go on their next holiday, and those who want to see what Cork has to offer.

Welcome To Cork will be useful to tourists to inform them about Cork, giving them a brief overview of different types of places to visit, such as historical sites, places of entertainment and culture, and restaurants. It may also be useful for people living in Cork to discover hidden gems within their own city, and gain a new appreciation for Cork.

## Features

The project has a number of different features, which are listed in more detail below:

### Existing Features

- __Nav Bar__

  ![Nav Bar](https://github.com/aaronodonoghue96/welcome-to-cork/blob/main/navbar.png)

  - The nav bar is located in the header at the top of all three pages, the Home page (index.html), the Pictures page (pictures.html) and the Things To Do page (thingstodo.html). It includes links to all three pages, and indicates the page you are currently on by underlining the link to it. On smaller screens, the links are hidden but will be displayed by clicking on the hamburger icon that appears in the upper right corner.
  - This sections allows users to easily navigate the site without needing to use the browser's forward and back buttons.

- __Landing Image__

  ![Nav Bar](https://github.com/aaronodonoghue96/welcome-to-cork/blob/main/landing.png)

  - The landing image is displayed on the Home page (index.html), and depicts a view of Cork, looking onto Patrick Street. It shows the user what Cork looks like, giving them a good idea of what the site is about.
  - This section introduces the user to Welcome To Cork with a photo of the city's main street, and gives the user a good impression of what to expect.

- __Info Section__

  ![Nav Bar](https://github.com/aaronodonoghue96/welcome-to-cork/blob/main/info.png)

  - The info section shows four sections, namely History, Culture, Entertainment and Cuisine, with a brief paragraph about each topic underneath, showing how each of these things relates to Cork, giving examples of each that can be found in the City.
  - This section gives an overview of what Cork has to offer, and shows there is something for everyone in Cork.

- __Picture Gallery__

  ![Nav Bar](https://github.com/aaronodonoghue96/welcome-to-cork/blob/main/gallery.png)

  - The gallery shows eight pictures of different sites in Cork, along with the name of each underneath the picture. This shows the user what some of the tourist attractions in Cork look like, and what their names are.
  - This section is useful, as it shows the user a number of places in Cork they can visit, and also says the name of each place so they can search for more information or directions.

- __Activities Section__

  ![Nav Bar](https://github.com/aaronodonoghue96/welcome-to-cork/blob/main/activities_section.png)

  - The activities section lists details on some additional activities to do in Cork, such as the Cork City Bus Tour, which passes by Cork City Gaol among other places of significance in Cork, shopping at the Marina Market, and visiting the towns of Cobh and Midleton in County Cork.
  - This section is useful as it outlines extra ideas for things to do on your trip to Cork, and to get a feel for what Cork has to offer.

- __Sign-up Form__

  ![Nav Bar](https://github.com/aaronodonoghue96/welcome-to-cork/blob/main/signup_form.png)

  - The sign-up form at the end of the Things To Do page (thingstodo.html) gives the user the opportunity to sign up for an email-based newsletter on new idea for things to do in Cork, such as upcoming concerts or shows, or other tourist attractions not mentioned on the Welcome To Cork website. It also allows the user select how often they would like to receive these emails.
  - This section allows users to find out additional information about Cork and stay up to date with upcoming events in Cork.

### Unimplemented/Future Features:
  - There was originally going to be a timetable section on the thingstodo.html page with timetables for the Cork City Bus Tour and transport to locations of tourist attractions in Cork such as Blarney and Midleton, but this was scrapped to avoid clutter on the page.

## Testing

This project has been tested on the Chrome and Microsoft Edge browsers, and in both cases, no problems with display or rendering were found.

The Home page (index.html) has been tested on all screen resolutions available on Dev Tools, and in all cases, the main image displays correctly and is visible, the sections below in the info section display in the correct layout based on the screen size, and the red links at the bottom of the page display in line with the surrounding text in the sentence they are part of.

The Pictures page (pictures.html) has been tested on all screen resolutions available on Dev Tools, and in all cases, the images display in the correct layout, are visible, and the captions below them are visible.

The Things To Do page (thingstodo.html) has been tested on all screen resolutions available on Dev Tools, and in all cases, the screen displays correctly, the content is readable, and the form displays in the correct layout.

The nav bar has been confirmed to display correctly on both small screens and large screens using Dev Tools, showing the links on the right with the large screens, and showing the hamburger icon instead on small screens, which when clicked, toggles the display of links.

All of the above were also tested by manually resizing the browser window, which also allowed me to test that the nav bar will revert to displaying on the right when the screen is maximized after being reduced, and the links will be in the same place they started in.

The form in the Things To Do page (thingstodo.html) also has validation for all inputs, the name field will prompt you to enter a name, the email field will prompt you to enter an email (and will only proceed if the email contains the "@" symbol), and one of the radio buttons for frequency is already selected by default when you enter the form.

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/#textarea) (all 3 pages, index.html, pictures.html and thingstodo.html, had their HTML content copied and pasted into the text area and then validated)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator) (style.css has its CSS content copied and pasted into the text area and then validated)

### Fixed Bugs:
- Links in nav bar were displaying in standard blue/purple with underline and bullet points because CSS link was not updated to account for the fact style.css was moved to the css folder. The path is now updated in all pages, and the links are displaying correctly.

- Some captions in pictures.html page were displaying in a different column to their image if the image was at the end of the column because the media queries used column-count to divide the grid into columns, which did not treat each div containing an image and its caption as a unit. This has been fixed by using flexbox to display the images (together with their captions), in rows instead of columns.

### Unfixed Bugs:
- No unfixed bugs were found to remain in this project after testing.

## Deployment

This project was created on GitHub using the CodeAnywhere platform, and changes and new files were added on a regular basis via frequent Git commits in the terminal of the CodeAnywhere platform.

The project was then deployed to GitHub Pages. This was achieved by creating a new repository on GitHub for the deployment, called aaronodonoghue96.github.io, setting it up using GitHub Desktop, adding the changes from the original project on GitHub at https://github.com/aaronodonoghue96/welcome-to-cork, and publishing.

The live link can be found here - https://aaronodonoghue96.github.io/welcome-to-cork/index.html

## Credits

### Content

- The hamburger icon for the nav bar was taken from [Font Awesome](https://fontawesome.com/)
- The CSS rule for the asterisk selector and the HTML form action in thingstodo.html leading to Code institute's form dump were taken from the Love Running project, and have both been also credited in the files where they appear respectively.

### Media

- The main image, depicting a view of Cork, looking onto Patrick Street, is from Flickr https://www.flickr.com/photos/infomatique/7586289188, was taken by William Murphy, and is distributed under the ShareAlike license https://creativecommons.org/licenses/by-sa/2.0/. No changes were made to the image during the creation of the Welcome To Cork project.

- Most of the photos in the gallery are royalty-free images from Dreamstime. Links to the image sources are below:
- Barryscourt Castle https://www.dreamstime.com/stock-photo-barryscourt-castle-county-cork-ireland-located-eastern-southern-close-to-town-carrigtwohill-image87289998
- Blackrock Castle https://www.dreamstime.com/blackrock-castle-observarory-cork-sunset-ireland-image182726780
- Blarney Castle https://www.dreamstime.com/stock-photo-blarney-castle-ireland-irish-caisle%C3%A1n-na-blarnan-medieval-stronghold-near-cork-river-martin-image77960853
- Shandon https://www.dreamstime.com/stock-photo-st-anne-s-church-shandon-cork-aerial-view-ireland-mountains-cloudy-blue-sky-image63020588
- University College Cork (UCC) https://www.dreamstime.com/long-hall-clock-tower-university-college-cork-ireland-horizontal-image241746832

The image of Cork Opera House is from Wikimedia Commons https://commons.wikimedia.org/wiki/File:Cork_Opera_House_%281%29,_1_Emmet_Place,_Cork_-_geograph.org.uk_-_2640543.jpg
The image of Crawford Art Gallery is also from Wikimedia Commons https://commons.wikimedia.org/wiki/File:Crawford_Art_Gallery,_Cork,_Ireland.jpg
The image of Cork City Gaol is from geograph.ie, was taken by Richard Fensome https://www.geograph.ie/photo/1239790, and is distributed under the Creative Commons licence
