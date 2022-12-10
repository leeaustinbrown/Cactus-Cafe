# Cactus Cafe

Cactus cafe is a website for a cafe in Bristol England.  The site aims to provide the user with an overview of the Cafe's features and purpose.  Cactus Cafe is a small independently run coffeeshop selling great coffee, juice and of course cati plants. The site is aimed towards people who have a love for single origin coffee and Cactus plants.  Cactus Cafe will be useful to users to be able to check the Cafe's opening time menu and to just get a feel for the Cafe.  Throughout the site I have used a constant font and color theme in keeping with the Cactus theme i.e Greens colors and legible but funky type text as I beleive my target audience will mainly be young and looking for something outside the norm.
 

## Features

### Navigation Bar
The site features a Nav bar to help the user navigate to the most relevant part of the site to them.  This feature works across all devices and will highlight upon user hovering over the intended section of the site to navigate to.  All nav links take you tot he correct section of the site.
![navbar](vscode-local:/navbar.PNG)

### About Section
The About section of the page has a short clear easy to read description of what the Cafe is about and also displays a picture of Cactus plants, which is eye catching to the user.
![about](vscode-local:/about.PNG)

### Cafe Menu Section
There is a section to display the Cafe Menu split down into relevant sections for Single Origin Coffee, Cacti Plants and Cold pressed Juice.  This section is clear to read with concise information as its purpose is to enable the user to quickly identify an item which they would like to purchase.  The indiviual menus have clear headings and have kept with the theme of the Cactus Cafe website by using the same fonts and color scheme.
![cafemenu](vscode-local:/cafemenu.PNG)

### Contact Us Sction
The site has a section for the user to interact with the Cactus Cafe and join up by entering there email address.  This section also holds improtant information like the Cafe's opening hours which are clearly displayed and easy to read.  Next to this there are a further 2 more images showcasing the other two main reasons to visit the cafe, Coffee and Juice. 
![contactus](vscode-local:/contactus.PNG)

### Footer Section
Finally there is Footer to the page which holds the copyright information for the Cafe and also holds links to our social media sites which have been tested and all open in a new tab.
![footer](vscode-local:/footer.PNG)

### Features Left to Implement.
Future ideas for the site include linking a map of the location of the Cafe with Google Maps and also maybe adding a live webcam stream from within the Cafe so people can view live inside the Cafe to hopefully entice them to make a visit.


## Testing
Having tested the site I am happy all site features are working well.  
The Nav bar link elements take you to the intened locations throughout the site.  
The Social links in the footer have been tested and these all open to the intended site in a new tab of the users browser. 
The signup form only allows users to enter the correct format i.e. email address and when they submit this a new tab will open to confirm they have successfully joined.

Upon using the 'inspect' tool and the 'responsive design' element of this tool I was able to test the site for use on different sized devices i.e mobile phones or tablets.  I needed to envoke some media querys to enable the site content to be rearranged accordingly.  To check this I used https://amiresponsive.co.uk/
![amiresponsive](vscode-local:/Am%20I%20responsive.PNG)

I used the 'W3' validator tools for both my HTML and CSS.  During this testing I came across some interesting bugs;
**Google Font Bug** I came across a bug with the font I had chosen for the website.  The error was indicating that the URL link file was not found even though the fonts were applied and working.  I discovered that Google uses the piping character '|' to seperate fonts however this does not conform to current HTML5 and URL standards.  I had to replace these symbols with '%7C'.
**<br>** I realised I had a few bugs relating to the use of the line break '<br>'.  Looking through my code I believe this to be an issue whereby I copied and pasted somehting several times in error.  These were invetigated and resolved accordingly.
![nuhtmlvalidator](vscode-local:/NU%20Html%20checker.PNG)
![w3cssvalidator](vscode-local:/W3%20CSS%20checker.PNG)

## Unfixed Bugs
There are no know unfixed bugs.

## Deployment
Once happy with the site I deployed it to GitHub pages, the steps I used to complete this are as follows:
* - Naviagted to the Settings tab of the GitHub repository.
* - Select the 'Master Branch' from the source section dropdown.
* - The page will refresh with a detailed ribbon display to indicate successful deployment.

The Live link can be found here https://leeaustinbrown.github.io/Cactus-Cafe/index.html

## Credits
I would like to give credit for some of the content used on this site.

### Content
The fonts used on this site, Nerko One & Klee One were both taken from https://fonts.google.com/about
The icons in the footer of the page were taken from - https://fontawesome.com/

### Media
The images used on the site were all taken from https://www.pexels.com/ 

