# refactoring-code-for-accessibility
 Refactoring Code for Accessibility and correcting semantics in HTML and CSS (Bootcamp Homework), making the code accesible for all. 
See my comments below of the changes made on the HTMl and CSS pages, the comments also appear in-line. 

Changes to HTML: 
  * Added Alt descriptions to all the images.
  * Changed the title element to "Horiseon Home Page" as it better describes the page where on
  * Changed most of the section elements to divs to make it more semantic 
  * Added an ID element to the search-engine-optimization div (line 30) to make the link in the header work properly
  * Added the ending '</img>' tag to the end of every img tag to make it more semantic 
  * Replaced the H2 with a span in the footer to make it more semantic 
  * Added a new class to the heart in the footer and wraped it in a span so that I could easily edit it in CSS 
  * Also added the approriate symbol for the heart to make it more accessible (screen reader can read the symbol)  
  
  Changes to CSS: 
  * Re-organized it all to make it align with the elements in the HTML page (moved a whole section up behind .float-right) 
  * Added the '.heart' element to edit the heart symbol and make it match the one that was previously there (adding color and font-size)
  
Link to deployed application: https://jd-jaramillo.github.io/refactoring-code-for-accessibility/ 
