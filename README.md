# Code Refactor Starter Code
# GIVEN a webpage meets accessibility standards

## WHEN I view the source code
## THEN I find semantic HTML elements
Modified div class="header" and div class="footer" to use header and footer elements
Modified main content to use section elements as opposed to div elements
Converted content div elements to article elements

## WHEN I view the structure of the HTML elements
## THEN I find that the elements follow a logical structure independent of styling and positioning
Repaired issue linking header to Search Engine Optimization section through a href="#search-engine-optimization"Search Engine Optimization by 
modifying div id="search-engine-optimization" class="search-engine-optimization"

Introduced section elements which contain article elements, which contain heading and div elements

Consolidated classes to minimize CSS elements in style sheet.

## WHEN I view the image elements
## THEN I find accessible alt attributes
Added alt attributes to all images, fixed image tag in cost management section

## WHEN I view the heading attributes
## THEN they fall in sequential order
Changed heading element in footer to h4

## WHEN I view the title element
## THEN I find a concise, descriptive title
Modified title to reflect Horiseon company name and role