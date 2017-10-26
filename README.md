# Build a FAQ-site 

Today we're going to learn how to make an accordion, meaning an area that can collapse to show and hide text. These are very often used on FAQ-websites – so let's build one. The FAQ-website should follow this design: 




The Swedish gym chain SATS has a very nice one on their customer service portal, plz see for more inspiration. [Sats Customer Service](https://www.sats.se/kundservice/)

## How to complete this assignment

Start by reading the assigned readings, they will be of great help this time. 

You FAQ need to fulfill the following requirements: 
1. Expand to show more text on click. 
2. Text that are expanded should collapse back on click. 
3. The icons for plus and minus should be done in CSS. 
4. Every second section should alternate colors, odd ones in one color and even ones in another. 
5. The plus icon should bedome a minus icon when collapsed. 
6. On hover, make the color of the section darker. See the [Sats Example](https://www.sats.se/kundservice/) for inspo. 

Don't care right now about fancy animations for when the text shows – let's leave that for the strech goals. 

### Tutorial

1. In the `starter-code` you will get a boiler plate HTML to start with. Open it. 
1. Start by adding the script.js file into the HTML-file in the `<head>` tag. [Hint](https://www.w3schools.com/tags/att_script_src.asp)
1. The Javascript file contains of a function that toggles the CSS-class to `.active`and a `getElementsbyId`selector that's get's triggered by a click-event. But let's leave this for now. 
1. In CSS, start by hiding the text we want to expand and collapse. [Hint](https://www.w3schools.com/css/css_display_visibility.asp)
1. Add another CSS-class that are called ` .active + .panel`. When the Javascript `toggle` is called it will add or remove the class `.active` on the `.accordion` divs. When both the `.active` and the `.panel` are within the same div this is true and this CSS-class will be used. Make this CSS-class show the text by using `display: block`
1. Does one of your sections now work? Have a look in the inspector to see how the classes changes when you click on them. 
1. Finish the Javascript-file to apply to all sections. 

We think you can figure out the rest of this assignment. 

To complete this assignment, you need to fork this repository, make a folder in your copy and add your code, and then submit a pull request on GitHub (from your repository into the technigo one) for review. [Read the guide on GitHub](https://guides.github.com/activities/forking/) for more info on how to do this.

### :books: Reading List

* [W3Schools – Javascript DOM](https://www.w3schools.com/js/js_htmldom.asp) Read to chapter "DOM HTML". 
* [How to make a circle in CSS](https://davidwalsh.name/css-circles)
* [nth-child in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/%3Anth-child)

---

### :boom: Success!

After completing this assignment, you should know about how to manipulate the DOM with some basic Javascript. You should know how to select a certain HTML-element and make changes to that with Javascript. You should also know some basic Javascript syntax. As a bonus, you will also understand how the `nth-child`selector works in CSS. 

---

### :runner: Stretch Goals

Done with the main task? Here's some ideas for things to continue with:

1. Try and add a hamburger-menu on mobile, that on click shows different menu options. 
1. Align the cards to the center of the page.
1. Use box shadows to make the cards look like Polaroid pictures.
