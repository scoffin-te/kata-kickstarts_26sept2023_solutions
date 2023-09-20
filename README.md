# Kata Kickstarts - CSS (September 26, 2023)
​
This is a small Vue project scaled-down from the capstone starter code. The back-end has been removed so we can focus on the front-end. 

<img src="https://media.giphy.com/media/13FrpeVH09Zrb2/giphy.gif" height="200" width="auto" alt="Cartoon character fiddling with window blinds">
<sub>( This GIF ^ is in jest... I actually ❤️ CSS! )</sub>

<br></br>

<img src="./public/before-and-after.png" height="200" width="auto" alt="Before and after images of the application">

This document walks you through how to set up and run the project, as well as providing a handful of katas to work on in the code.
​
## Project setup
​
(1) The first thing you'll need to do is to download any dependencies by running this command:
​
```
npm install
```

(2) Start your Vue application with the following command:
​
```
npm run serve
```

(3) Click on the localhost link that appears to open the application in a browser.

<br>
<hr>
<br>

## Icebreakers

<br>

### Kata #1: Create a custom color palette

Our website needs a solid brand. Part of that brand will be our own custom color scheme. Define variables for each color in your palette so you can reference them by name in a shared style sheet. Then, use the vars to declare the background color and global default text color.

Note: Remember that the scoped variable is used to keep styles local to a given component.

<br>

### Kata #2: Designate a custom site font

To further brand our website, we need to choose a snazzy font. To do this, we'll grab one from [Google Fonts](https://fonts.google.com/) and import it into our centralized CSS.

<br>

### Kata #3: Resize the site content

Our content isn't filling the whole screen. Add some CSS rules to stretch it out.

<br>

### Kata #4: Touch up the main content area

We really need our content to "pop" on the site pages. Style the content area on the homepage to make sure it stands out. A well-contrasted background color and some padding (in and around) might help.


<br>
<hr>
<br>

## Breakout rooms

<br>

### Kata #5: Style the header

Our header looks a bit… Wonky. 
- Import the global colors and assign it a background color.
- What's with that huge site logo?! Locate and resize it so it stays in the header.
- Center the header content (logo image and navigation) vertically and horizontally.
    - Tip: This may be a job for Flexbox or Grid!
- For good measure, throw some padding in there too to make everything line up with the main content.

<br>

### Kata #6: Style the nav links

The site links have left a bit to be desired. Let's style them.
- Change the font color to contrast well with your header (if it doesn't already).
- Remove the underline from the links when they're inactive.
- When someone hovers over the link, readd the underline.


<br>

### Kata #7: Tackle the footer: Part 1

Now that our header is looking great, it's time to make some adjustments to the footer. Yes, the main content is (probably) flowing over top of it (darn you, Pirate Ipsum!) but we'll fix that problem later.
- Give the footer a background color with a high contrast, then adjust the font color so it's visible.
- Resize the content so that it fits inside the footer.
- Center the content vertically and horizontally inside the footer.
    - Tip: This might be a job for Flexbox or Grid!
- Add some padding to make it match the site header and main content spacing.

<br>
<br>

### Kata #8: Style the picture so text flows around it

Our content is looking pretty good, but let's jazz it up with text that flows around the image on the homepage.

<br>
<br>

### Kata #9: Add a media query

Our flow-around text and image look great on desktop now, but once we hit smaller devices, this could get dicey. Add a media query that removes the flow-around text when we hit a breakpoint of 600px.

<br>
<hr>
<br>

## Challenge

### Kata #10: Tackle the footer: Part 2

Ok, so that page content is way out of control. Let's use styling to bring it back into line so it'll play nice with our footer.

… You probably know what I'm going to say now… This is probably a job for (🥁drum roll) Flexbox or Grid!

<br>
<hr>
<br>

## Resources
- [BootcampOS](https://lms.techelevator.com/) units
    - Intro to HTML and CSS
    - CSS selectors and box model
    - CSS Grid
    - CSS Flexbox
- TE Supplemental Resources
    - [CSS Flexbox quick reference](https://docs.google.com/document/d/1jXKdS4TA3uc59e9NlU1_STE36HruwAah2xAUTDSuSO4/edit?usp=drive_link)
    - [CSS Grid quick reference](https://docs.google.com/document/d/18WatnKZ4kk-LywAiAZhEMppB2TjIsx15sBgtBeP4zm8/edit?usp=drive_link)
- Guides and documentation
    - [Basic concepts of Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox) (MDN Web Docs)
    - [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) (CSS Tricks)
    - [CSS grid layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout) (MDN Web Docs)
    - [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) (CSS Tricks)
- Other
    - [Flexbox Froggy](https://flexboxfroggy.com/) (game)
    - [Grid Garden](https://codepip.com/games/grid-garden/) (game)
    - [CSSReference.io](https://cssreference.io/flexbox/) (website)
    - [Grid Generator](https://cssgrid-generator.netlify.app/) (widget)
    - [CSS Grid Beginner's Guide](https://www.codeinwp.com/blog/css-grid-tutorial-layout) (tutorial)