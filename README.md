# Homework 1 - Code Refactor

## About the Project
This project is the first homework assignment for the UW Coding Bootcamp. With this project we were given HTML and CSS files (along with some pictures) for a webpage. There were several components of this assignment, discussed below.

### De-bugging
At the beginning of this project, it was important to go in and clean up any bugs. I made sure links were working, pictures were appropriately sized, and formatting was appropriate.

### Accessibility 
The main goal of this project was to make the code more accessible. This was accomplished through a couple of avenues. First, I made sure that the order of the HTML code matched the logical flow of the webpage, such that the header was at the top, the footer was at the bottom, and the body was in the middle. This helps search engines and screen readers with the interpretation of code. I added alt tags to photos which provide descriptions of the photos for screen readers, or if a photo does not load. Additionally, I incorporated semantic HTML tags. These tags help to provide a more meaningful label to sections of code - such as header, article, or aside. This helps search engines and screen readers to break down what is in a page and the importance of different content. I also made sure that the title of the page was clear and matched the content. 

### Simplification
A third aspect of this project was to clean up the code. This code used a lot of different class and id tags which were unnecessary or redundant. For instance, the header was a div tag marked with a "header" class. By using semantic HTML and appropriately labeling this as a header rather than a div, I could eliminate this class. As I changed tags, I also had to make sure that the CSS code was updated to match the changes made to the HTML. I also found that several elements had repetitive, identical coding. Using semantic HTML enabled me to simplify the CSS document by coding all of the article sections the same, and all of the aside sections the same, rather than having to give each section a class and coding them independently. 

## Benefits of this project
This project gave me some practice with incorporating semantic HTML elements. This is an important practice to help not only with search engine optimization, but also to ensure that web pages are accessible to all. This gave me the time to think critically about which semantic tags would best represent each section of the code. Additionally, this project showed me how beneficial semantic elements can be in simplifying code. Semantic elements allow you to use far fewer class and id tags, and eliminate some redundancies in coding similar sections.

## Accessing the project
The HTML and CSS files are included in this repository for review. 

Additionally, you can access the deployed webpage at https://aubrey-heim.github.io/homework1_code-refactor/

## Acknowledgments
This original source code was provided by the UW Full-Stack Web Development Bootcamp: https://uwa.bootcampcontent.com/UWA-Bootcamp/uw-sea-fsf-pt-08-2020-u-c
