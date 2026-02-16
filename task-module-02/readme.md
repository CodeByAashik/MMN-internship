# Module 02: Styling & Layout
# OBJECTIVE: CSS Basics and Page Styling
## 1. Define CSS

CSS stands for Cascading Style Sheets. It is a stylesheet language used to control the presentation and layout of web pages. While HTML is used to create the structure of a webpage, CSS is used to design and style that structure.

CSS controls elements such as colors, fonts, spacing, alignment, borders, and overall page layout. It helps in separating content from design, which makes websites easier to maintain and update. By using CSS, developers can apply consistent styles to multiple pages, improving the overall appearance and user experience of a website.

In simple words, HTML builds the structure of a webpage, and CSS makes it visually attractive.

## 2. Types of CSS
There are three main types of CSS:

### 1. Inline CSS
Inline CSS is written directly inside an HTML element using the style attribute. It affects only that specific element.
Example:
`<p style="color: red;">This is a paragraph.</p>`
Inline CSS is useful for applying quick changes, but it is not recommended for large projects because it makes the code difficult to manage.

### 2. Internal CSS
Internal CSS is written inside the `<style>` tag within the `<head>` section of an HTML document. It is used to style a single webpage.
Example:
```
 <style>
 p {
    color: blue;
 }
 </style>

```
Internal CSS is better than inline CSS when styling multiple elements on the same page.

### 3. External CSS
External CSS is written in a separate .css file and linked to the HTML file using the <link> tag.
Example:
`<link rel="stylesheet" href="style.css">`

This is the most recommended method because it keeps the design separate from the structure and allows the same CSS file to be used on multiple pages.

## 3. Styling Explanation

In this webpage, different CSS properties are used to improve design and layout.

The background-color property changes the background of the page and different sections. The color property sets the text color.

The font-family and default font size improve readability. The padding property adds space inside elements, making the content look clean and properly spaced. The margin property adds space outside elements, creating separation between sections.

The border property adds visible lines around sections, which makes the layout structured and organized.

The width: 60% and margin: auto in the content section help center the content horizontally on the page. The text-align: center centers the text inside the page.

Overall, CSS improves the visual appearance of the webpage by controlling colors, spacing, borders, and layout alignment. It makes the webpage look neat, readable, and user-friendly.