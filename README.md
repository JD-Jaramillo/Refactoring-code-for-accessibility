# Refactoring-code-for-accessibility
 Refactoring Code for Accessibility and correcting semantics in HTML and CSS (Bootcamp Homework), making the code accesible for all. 
See my comments below of the changes made on the HTMl and CSS pages, the comments also appear in-line. 

## Table of Contents

* [Changes-to-HTML](#Changes-to-HTML:)
* [Changes_to_CSS](#Changes_to_CSS:)
* [Requirements](#Requirements)
* [Installation](#Installation)
* [Contributing](#Contributing)

## Changes-to-HTML: 
  * Added Alt descriptions to all the images.
  * Changed the title element to "Horiseon Home Page" as it better describes the page where on
  * Changed most of the section elements to divs to make it more semantic 
  * Added an ID element to the search-engine-optimization div (line 30) to make the link in the header work properly
  * Added the ending '</img>' tag to the end of every img tag to make it more semantic 
  * Replaced the H2 with a span in the footer to make it more semantic 
  * Added a new class to the heart in the footer and wraped it in a span so that I could easily edit it in CSS 
  * Also added the approriate symbol for the heart to make it more accessible (screen reader can read the symbol)  
  
 ## Changes-to-CSS: 
  * Re-organized it all to make it align with the elements in the HTML page (moved a whole section up behind .float-right) 
  * Added the '.heart' element to edit the heart symbol and make it match the one that was previously there (adding color and font-size)
  
Link to deployed application: https://jd-jaramillo.github.io/refactoring-code-for-accessibility/ 

![refactoring-code-for-accessibility](horiseon-home-page.pdf)

## Requirements 
---
```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Installation
---
No need for any installation for this project.

See deployed site here: https://jd-jaramillo.github.io/refactoring-code-for-accessibility/

See repository here: https://github.com/JD-Jaramillo/refactoring-code-for-accessibility

## Contributing 

If you wish to contribute to this project please feel free to reach out to me directly.

Email: jaramillo784@gmail.com
