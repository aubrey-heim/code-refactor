# Homework 1 - Code Refactor

## About the Project
This project is the first homework assignment for the UW Coding Bootcamp. With this project we were given HTML and CSS files (along with some pictures) for a webpage. There were several components of this assignment.

### De-bugging
At the beginning of this project, it was important to go in and clean up any bugs. I made sure links were working, pictures were appropriately sized, and formatting was appropriate.

### Accessibility 
The main goal of this project was to make the code more accessible. This was accomplished through a couple of avenues. First, I made sure that the order of the HTML code matched the logical flow of the webpage, such that the header was at the top, the footer was at the bottom, and the body was in the middle. I added alt tags to photos which provide descriptions of the photos for screen readers, or if a photo does not load. Additionally, I incorporated semantic HTML tags. These tags help to provide a more meaningful label to sections of code - such as header, article, or aside. This helps search engines and screen readers to break down what is in a page and the importance of different content. I also made sure that the title of the page was clear and matched the content. 

### Simplification
A third aspect of this project was to clean up the code. This code used a lot of different class and id tags which were unnecessary or redundant. For instance, the header was marked with a "header" class tag. By using semantic HTML and appropriately labeling the header, we could eliminate this tag. As I changed tags, I also had to make sure that the CSS code was updated to match the changes made to the HTMLl. I also found that several elements had repetitive, identical coding. Using semantic HTML enabled me to simplify the CSS document by coding all of the article sections the same, and all of the aside sections the same, rather than having to give each section a class and code them independently. 

## Accessing the project
The HTML and CSS files are included in this repository for review. 

Additionally, you can access the deployed webpage at https://aubrey-heim.github.io/homework1_code-refactor/

## Acknowledgments
This original source code was provided by the UW Full-Stack Web Development Bootcamp: https://uwa.bootcampcontent.com/UWA-Bootcamp/uw-sea-fsf-pt-08-2020-u-c
