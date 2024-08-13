# Technical Paper: HTML and CSS

## Abstract

This paper presents a set of fundamental questions on HTML (Hypertext Markup Language) and CSS (Cascading Style Sheets). These questions are designed to assess understanding of core concepts and practical skills essential for effective web development.

### 1. Introduction

HTML and CSS are foundational technologies for creating and styling web pages. Understanding these technologies is crucial for developing well-structured and visually appealing websites. This paper aims to test knowledge and practical application of key concepts in both HTML and CSS.

### 2. HTML Questions

Question 1: HTML Document Structure
Explain the purpose of the <!DOCTYPE html> declaration in an HTML document. Why is it important?

Answer: The <!DOCTYPE html> declaration specifies the HTML version being used and ensures that the document is rendered in standards-compliant mode by browsers. It is important because it helps maintain consistency in how web pages are displayed across different browsers.

### Question 2: HTML Form Elements

Write the HTML code to create a basic form with the following fields:

A text input for the user's name.
A password input for the user’s password.
A submit button.
Answer:

<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
    <br>
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required>
    <br>
    <button type="submit">Submit</button>
</form>

## Question 3: Lists in HTML

Describe the difference between an and an list in HTML. Provide a short example demonstrating each.

Answer:

<h3>Unordered List:</h3>
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>

<h3>Ordered List:</h3>
<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ol>

### Question 4: Image Alt Attribute

What is the purpose of the alt attribute in the <img> tag? Write an example of an image element with a descriptive alt attribute.

Answer: The alt attribute provides alternative text for an image if it cannot be displayed. This improves accessibility for users who rely on screen readers and helps with SEO.

Example:

html
Copy code
<img src="logo.png" alt="Company Logo">
Question 5: Semantic HTML Elements
How do semantic HTML elements improve the accessibility and SEO of a web page? Name at least three semantic elements and describe their use.

Answer: Semantic HTML elements provide meaning to the content, improving accessibility for screen readers and enhancing SEO by making the content more understandable to search engines. They also improve code readability.

Examples:

<header>: Represents introductory content or navigational links.
<article>: Defines independent content or a self-contained composition.
<footer>: Represents the footer of a section or page, typically containing metadata or contact information.

## 3. CSS Questions

### Question 1: CSS Selectors

What is the purpose of the class and id selectors in CSS? How do they differ in terms of their application?

Answer:

class selector: Targets multiple elements with the same class name. It uses a dot prefix (e.g., .classname).
id selector: Targets a single unique element with a specific id. It uses a hash prefix (e.g., #idname).
Example:

css
Copy code
/*Class selector*/
.button {
    background-color: blue;
}

/*ID selector*/

# header {

    color: red;
}

## Question 2: Background Color

Write a CSS rule to change the background color of all elements to light blue. Also, set their text color to dark blue.

Answer:

css
Copy code
h1 {
    background-color: lightblue;
    color: darkblue;
}

## Question 3: Box Sizing

Explain what the box-sizing property does in CSS. What are the possible values for this property, and how do they affect element sizing?

Answer: The box-sizing property controls how the width and height of an element are calculated, including padding and border.

Values:

content-box: Default value. Width and height include only the content, not padding or border.
border-box: Width and height include content, padding, and border.
Example:

css
Copy code
/*Default*/
.box1 {
    box-sizing: content-box;
    width: 200px;
    padding: 20px;
    border: 5px solid black;
}

/*With border-box*/
.box2 {
    box-sizing: border-box;
    width: 200px;
    padding: 20px;
    border: 5px solid black;
}

## Question 4: Flexbox Basics

How does the flex property in Flexbox work? Write a CSS snippet to create a flex container with three flex items that are equally spaced.

Answer: The flex property allows items within a flex container to grow or shrink to fit the available space. It defines the ability of a flex item to grow, shrink, and its base size.

Example:

css
Copy code
.container {
    display: flex;
    justify-content: space-between;
}

.item {
    flex: 1;
    margin: 5px;
}

## Question 5: Media Queries

Describe the purpose of media queries in CSS. Write a media query that applies a font size of 16px to paragraphs on screens with a maximum width of 600px.

Answer: Media queries allow for responsive design by applying styles based on device characteristics, such as screen width.

Example:

css
Copy code
@media (max-width: 600px) {
    p {
        font-size: 16px;
    }
}

- 4. Conclusion

This paper has outlined essential questions on HTML and CSS, focusing on fundamental concepts that are vital for web development. Mastery of these topics is key to creating well-structured and styled web pages.

- 5. References

Mozilla Developer Network (MDN) Web Docs
W3Schools
CSS-Tricks
