# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## TABLE OF CONTENTS

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## OVERVIEW

### THE CHALLENGE

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### SCREENSHOTS

  ![](design/375px_width_smartphone_view.jpeg)
  ![](design/iPad_landscape_%20view.jpeg)
  ![](design/iPad_portrait_view.jpeg)

## MY PROCESS:

### BUILT WITH:

- Paper/pencil/calculator: to draft skeleton structure of over-all grid.
- Semantic HTML5 markup: only the &lt;heading&gt; and &lt;footer&gt; tags were semantic; the rest were separated by, and contained in, &lt;div&gt; tags, marked with either an id-attribute or a class-attribute.
	- Additional HTML5 notes: used inline sytle formatting for short/isolated sections.
	- e.g., &lt;font size=" "&gt;, &lt;a id=" "&gt;.
- CSS custom properties: none.
- Flexbox: used display:flex for a button.
- CSS Grid: used named-grids, with combination of fixed/relative/proportional units.  Elements would not render properly without resorting to combination.
	- i.e., fixed (px), relative (%), proportional (fr).
- Mobile-first workflow: used mobile-first approach by first specifying single-column grid for mobile devices; then adding a media-query that specifies grid specifications for larger screens/displays by using @media only screen and (min-width: #px) {}.
- Framework/Library: none used.
- Styled Components: not used.

### WHAT I LEARNED:

First had to measure jpg sample images of specified product specifications - to identify their precise proportions.
Then, HTML5 draft was emplaced.
Immediately began specifying grid specs on CSS3 stylesheet (thinking all was rather simple and straightforward).
- Ouput of tested product did not comply with expected output, however.
- Had to resort to redrafting grid - manually, by paper & pencil.
	- Paper/pencil method facilitated better grasp of grid structure.
	- Paper/pencil method also afforded grander view (can simultaneously see both mobile grid and desktop grid, and easily).
	- Had initially opted to bypass this manual process to save time/effort; but it turned out to be the more INEFFICIENT route.
- Grid row-&-columns were very sensitive to meaurement units chosen.  Depending on combination of units (fixed/relative/fractional) chosen, the rendered result varied, contradicting the equivalent calculated projections for the several combinations drafted.  This fact imposed a process of trial-&-error to arrrive at a combination of measuement units that renders the grid items (elements) properly in both grid versions (mobile & desktop).

### NOTABLE CODES USED IN THIS PROJECT:

CSS:
	
- button:hover {}
- transition:transform #s ease;
- transition:transform #s ease;
- transform:translateY()translateX();
- box-shadow: #px #px #px color;	

### CONTINUED DEVELOPMENT:
  
  Improper rendering of grid that contradicts calculations remains a PUZZLE.

### USEFUL RESOURCES:
  
Read numerous CSS articles online to help understand both flex-box and grid systems.  Resorted to reading many articles to see different angles/views on the same topic, which helped fill grasp of grids, especially.

### USEFUL SITES VISITED:

  - CSS-Tricks
  - MDN Web Docs (mozilla.org)
  - Learn to Code - for Free | Codecademy
  - The Beginner's Guide to Responsive Web Design in 2021 (kinsta.com)
  - https://www.aastudio.fr/A-basic-16-lines-of-code-CSS-fluid-grid.html
  - CSS Unit Guide: CSS em, rem, vh, vw, and more, Explained (freecodecamp.org)
  - CSS (quackit.com)
  	- Create a Responsive Grid (quackit.com)
  - W3Schools Online Web Tutorials
      	- https://www.w3schools.com/css/css_grid_item.asp
  - Online Courses - Learn Anything, On Your Schedule | Udemy
  	- https://blog.udemy.com/css-grid-vs-flexbox/
  	- https://blog.udemy.com/css-grid-vs-flexbox/
  	- https://blog.udemy.com/css-grid-vs-flexbox/

## AUTHOR:

- Frontend Mentor - @learner-one
- Twitter - @_Learner_One

## ACKNOWLEDGEMENTS:
  
The above mentioned websites were mined for clarifying & instructive information.
