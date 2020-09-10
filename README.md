# Depolyed Horiseon Code Refactor 

## Table of contents 
* [Refactoring](#What)
* [Steps](#Why&How)
* [Picture of webpage](#Picture)
* [License](#license)




### Refactoring 

I was tasked with refactoring the Horiseon webpage. After observing the code i quickly understood that i would have to make some alterations since there were redundencies. Also, and most importantly the web page was not meeting the ADA standards so i had to make sure that it was complient with thoes standards by adding alt tags on img.Furthermore, i made sure that the html had semantic elements to make code readable and purposeful.

### Steps 
    
* Replaced div with semantic elements for readability and meaningfull tags 
    * removed <div> replaced with <section>, <article>
* Added alt tags to images for ADA compliance
    * <img= src"" alt="" > alt tags were added to all picture on the webpage 
* consolidated css selectors
    * selectors with the same properties were combined and seperated with a space and a comma
* reorganized headings to follow sequential order
    * headings h1, h2, h3 all in order 
* removed id selector and kept class for consistency 
    *  (#) was changed to (.) in the css to reflect change in html 

### Picture of Webpage 

![Deployed image of webpage](assets/images/Webpage screen shot.jpg)


### MIT License

Copyright (c) [2020] [Samuel Endrias]

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