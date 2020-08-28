# 02 Homework: Code Refactor



##### Changes for header
   * In style.css, header h1.seo was deleted and the contents inside were moved to header h1.
   * Changed html div section with class=header i.e. changed non-semantic header to semantic header
   * Changed inner div of header section to nav
   * Changed .header class in style.css to header
   * Changed div within .header class to nav 

##### Changes for hero div
   * Changed div to section

##### Changes for section
   * Changed outer divs to section 
   * Changed inner divs to article
 
##### Changes for aside
   * Changed outer divs to aside 
   * Changed inner divs to article
   
##### Changes for footer
   * Changed outer divs to footer 
   * Changed css class .footer to footer
    
##### Changes for images
   * Added alt tags for all the images
   
##### Changes for duplicate css classes for section
   * Removed duplicate css classes to common css classes
   * Changed html to use common css class
 
##### Changes for duplicate css classes for aside
   * Removed duplicate css classes to common css classes
   * Changed html to use common css class
   
##### Changes for nav click
   * Add id for section search-engine-optimizer
   
##### Additional changes
   * Changed nav css color to section color
   * Changed aside color to section color
   


> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

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

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
