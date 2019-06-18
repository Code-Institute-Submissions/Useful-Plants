# Useful Plants
User-Centric Frontend Development @ Code Institute 
Milestone project 1


‘Useful plants’ is a small resource built to present functional plants, that are easy to obtain, grow and care for, no matter the gardener's level of experience. Some of the presented plants are best for gardens, other for indoors. 

This resource is intended as a starting point in researching plants suitable to specific purposes. It is more like a hub linking to other websites and not a place hosting detailed information on its own.

Every plant name (common English and Latin) is accompanied with basic information about its preferences expressed with icons, and a photo allowing visual identification.

The site will allow users: 
* browse through the lists of plants to verify if the plants they own are useful in some way,
* look for plants that are functional for specific purpose,
* compare the plants visually and functionally,
* reach the sources of the pictures for high resolution reference.

The project consists of 7 pages, where 4 of which contain information about plants separated by function; the other 3 provide the user with information, list the credits and allow the contact with the creator. 

The 4 functional categories are: 
* Air purifiers - plants that clean the air out of toxins and pollution
* For bees - plants that serve bees as a place when they can feed or take shelter
* For birds - same as above, this page lists plants allowing birds feed and hide
* Safe for children, dogs and cats - despite it is less than being a 'function' sensu stricto, this page lists plants that are absolutely safe to keep in the houshold with children and/or listed pets. Some of the plants from other categories also appear here. 



## Demo

['Useful Plants' demo is available here](https://ardhanari.github.io/Useful-Plants).


## UX

My goal was to build as simple as possible website that gathers only the most necessary information and encourages users' own further research of plants of their choice. 

Green colour has an intuitive connection to nature so the choice of creating colour palette that is almost uniquely of green hues was a natural one. 

The website was tested on different devices and browsers to ensure the that user's journey would be smooth and wihout any problems. It was also tested by three beta users. Each of them was asked to browse the pages, and then answer questions on: look/feel, functionality and their experience. The only thing that wasn't adjusted to tester's comments was the number of available plants for each category. I plan to conform to their comment in the future. 


## Technologies
1. HTML
2. CSS
3. Javascript

## Features

This site uses javascript to manage the collapsible navbar on mobile devices. Google fonts are used to improve design. Otherwise, website relies heavily on custom written CSS stylesheet. Icons from Font Awesome are added to make the navigation menu a little bit more attractive and ensure it is more intuitive for the user after the first visit. 

### Features Left to Implement

Functional contact form will be added as soon as possible. 

As mentioned in UX part, following testers' comments, I also plan to add more plants to each category (up to 15) to make it more comprehensive without impacting the usability and performance on every device. 

The menu icon for 'For bees' page will be replaced with a bee as soon as that icon is available on Font Awesome. 

Further improvement of the style are also possible. 


## Testing

### Main user story: gardener looking for a concise infromation on plants serving specific function. 

This user's journey is achieved from landing on the home page, which serves as 'a legend' to the symbols used across the page to them browsing through the functionals plants. The legend, however necessary to the structure of the website, may not be necessary to the user themselves. It follows the convention of most of gardeners' resources, using the same/similar icons to present most basic plant preferences. Every use of an icon is also accompanied by alt and title attribute to make sure it's usable even without the image.

All four function pages follow the same structure. They provide a short explanation for each category, followed by separate elements, one for each plant, containing its name (English and Latin), picture and 2-4 icons representing its preferences. Both names and picture are active links linking for this time being to relevant Wikipedia pages. 

On the Acknowledgements page, the user are able to see the sources for both information and photos. Full list of photographers is hidden behind 'See more' link, as to not overcrowd the page at first. 

The Contact page contains contact form (for this time being, not fully functional) and links to my two social media accounts. The form and links are accompanied by short text, encouraging contacting me if any content hosted needs change, correction or improvement. Submitting a form with one for the fields empty will fail, as well as submitting one with incorrect email adress. 

All links were tested to ensure there are none broken. All external links across this site opens in a new tab. 


## Deployment

'Useful Plants' is hosted using GitHub Pages and it is deployed from the master branch. No other branches were used. All pages are separate HTML files with the landing page under the name `index.html`


## Credits

### Content
All text within the website was written by me. Adding specific plant information, I relied not only on my experience but also on Internet sources, from which the most important were: 
* [Gardeners' World](https://www.gardenersworld.com/),
* [The Spruce](https://www.thespruce.com/)
* and [Bee Friendly](https://beefriendly.ca/).

### Media
All photos used for this project were taken from [Wikipedia](https://en.wikipedia.org) and [Unsplash](http://unsplash.com). Full list of authors at [acknowledgements page](https://ardhanari.github.io/Useful-Plants/acknowledgements.html)


**This is for educational use.** 