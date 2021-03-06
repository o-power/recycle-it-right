# Recycle it Right
Contamination in recycling bins in Ireland is a major issue with a reported 36% of bins being contaminated in certain areas. China's decision in 2016 to stop importing plastic waste made the export of plastic waste from Ireland more difficult and less economically viable. Contamination in recycling bins exacerbates the problem: it costs money to remove and makes it harder to sell the plastic waste to those countries which have the capabilities to import and recycle it.

The Recycle it Right website motivates and explains the key concepts behind deciding which household items can go into recycling bins. The website is clear and simple with a single goal which is not diluted by any other information. The motivation comes from the main statistics around contamination and a reminder that recycling waste in Ireland has to be exported.

## Demo
A live demo can be found [here](https://o-power.github.io/recycle-it-right/) on Github Pages.

<img src="images/website_deviceframes.jpg" alt="Image of website on iPhone and iPad">

## UX
### Wireframes
Wireframes can be found in the [wireframes](https://github.com/o-power/recycle-it-right/tree/master/wireframes) folder.
### User stories
1. As a householder, I want to know how bad a problem contamination in recycling bins is so that I am motivated to recycle properly.
2. As a householder, I want to know what condition items should be in before being placed in a recycling bin so that I can ensure my recycling bin is not contaminated.
3. As a householder, I want to be able to navigate to a list of items so that I can see what is and isn't recyclable.
4. As a householder, I want to be able to see an explanation of why items are/are not recyclable so that I can understand the logic.

## Technologies/Libraries
1. HTML
2. CSS
3. Flexbox
4. [Bootstrap v4.3](https://getbootstrap.com/)
5. [Font Awesome](https://fontawesome.com/)
6. [Gimp](https://www.gimp.org/)

## Features
### Existing
- A navbar which has collapsed links on mobiles but expands on larger screens.
- A shortcut icon.
- A statistics section which has an animated arrow on medium and large screens to highlight that the user can scroll down. The animated arrow disappears on smaller screens.
- An economics section which uses Font Awesome icons displayed vertically on mobiles but horizontally on larger screens.
- A principle and a categories section with images that display vertically on small screens but display horizontally on medium and large screens.
- Recycling List pages which use the Bootstrap card component to display images of recyclable and non-recyclable items. In each card, additional information is contained in an accordion which has a plus sign to indicate to the user that it can be expanded. The plus sign changes to a minus sign when the accordion is expanded.
### Future
- Add an About/Contact Us section to give more context to the website.
- Add downloadable posters for home and office containing examples of recyclable waste.
- Reduce the size of the images to improve their load speed. Or use a content delivery network (CDN).

## Testing
The HTML was checked using the [W3C Markup Validation Service](https://validator.w3.org/). This helped to identify default values in the ARIA attributes which I had not changed after copying the code from the Bootstrap documentation. It also identified that there were duplicate IDs across the Bootstrap card components and this was fixed.

The CSS was checked using the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/). There were no errors and 9 warnings. The 9 warnings were reviewed and could be ignored.

The website was tested during development on different screen sizes and devices using Chrome DevTools. The website was also tested on a Samsung A5, a 15 inch laptop and a widescreen monitor.

All the links were checked to ensure they were working.

During testing it was found that the website images could be slow to load, especially on poor connections. The images were reduced in size using Gimp to improve load times.

## Deployment
The site is hosted using GitHub pages and is deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

To run locally, clone this repository directly into the editor of your choice by pasting `git clone https://github.com/o-power/recycle-it-right.git` into your terminal. To cut ties with this repository, type `git remote rm origin` into the terminal.

## Credits
### Content
- Contamination statistics taken from [repak.ie](https://repak.ie/our-campaigns/news/save-our-nation-from-contamination/) (accessed 23rd April 2019).
- List of recyclable items taken from [mywaste.ie](https://www.mywaste.ie/what-to-do-with-my-recycling/) (accessed 23rd April 2019).
- Quote "If you’re happy enough to empty your recycle bin on the kitchen floor, we’re happy enough to take it" taken from [Irish Examiner Special Report on Recycling Bin Contamination](https://www.irishexaminer.com/breakingnews/specialreports/special-report-failure-of-irish-households-to-recycle-properly-is-a-massive-waste-of-time-829833.html) (accessed 25th April 2019).
### Media
- All images were taken by myself. Images were edited and their file size reduced using Gimp.
- The shortcut icon is a [Font Awesome Icon](https://fontawesome.com/license) with the color changed.
### Acknowledgements
- Jumping arrow animation inspired by [https://careers.adia.ae/](https://careers.adia.ae/) (accessed 3rd May 2019).
- Shortcut icon generated using [Favicon Generator](https://realfavicongenerator.net/) (accessed 3rd May 2019).
- The CSS for the plus/minus sign on the accordions was adapted from [w3schools.com](https://www.w3schools.com/howto/howto_js_accordion.asp) (accessed 13th May 2019).
