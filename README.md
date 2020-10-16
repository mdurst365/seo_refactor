# SEO Refactor

## Task List
- [x] Replace outdated or poorly descriptive HTML with semantic HTML elements
- [x] Restructure the HTML elements in a logical way
- [x] Edit CSS elements to follow a logical structure independent of styling and positioning
- [x] Add alt tags to all image elements
- [x] Put heading attributes into sequential order
- [x] Update title element to create a concise, descriptive title

## HTML Changes
Updated the title description to create a concise, descriptive title
added id tag to #search-engine-optimization to make the menu link functional
added accesible alt tags to all images
removed unecessary img closing tag from line 68

## Semantic HTML element updates
replaced generic <div id="header"> with semantic tag <header></header> and updated css to reflect that update
replaced generic <div> in the header navbar with semantic tag <nav></nav> and updated css to reflect that update
replaced generic <div id="footer"> with semantic tag <footer></footer> and updated css to reflect that update
replaced generic <div> tags with <section></section> tags but left in id tags to keep unique identifiers for nav menu

## CSS changes
sort to make alphabetical so that redundancies are easier to identify
Merge selectors with the same properties 
optimize color selections with shorthand
targeted class content instead of individual class selections within content to reduce redundant css on images in that section
targeted class benefits instead of individual class selections within content to reduce redundant css on images in that section

## Cleaning up CSS headings
removed redundancies so headings are only defined once
removed h1 from .seo to disallow qualified headings
removed .header from h1 to disallow qualified headings
assigned h4 instead of h2 tags to the footer to remove heading redundancy
merged h3 tags to disallow qualified headings

## Validation Resources
validated https://achecker.ca/checker/index.php and found no errors
validated the html through https://validator.w3.org/ and found no errors
validated the css through https://validator.w3.org/ and found no errors
additional css validation done through http://csslint.net/

## MIT License

Copyright (c) 2020 Molly Durst

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.




