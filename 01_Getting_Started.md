# Session 1 - Getting Started

## Goals
1. Create a [Glitch](https://glitch.com/) account.  
2. Get familiar with Glitch website features.
3. Review creating elements in HTML and styling elements in CSS.
4. Practice adding information about Type 2 Diabetes to your website.  

## Resources
- General Coding Reference - https://www.w3schools.com/

## Review

### Create HTML elements

1. An HTML element is the basic building block of a webpage. [Elements](https://w3schools.com/html/html_elements.asp) have the following structure. Elements consist of a **start tag** and **end tag**, with content in between. More information about the element can be found in the start tag in the form of **attributes** (e.g. id, class, src, href...etc.).

```HTML
<h1 id="title">Hello World!</h1>
```

2. In your text editor, practice creating the following HTML elements. The tag name is in parenthesis:
* headings (**h1**, **h2**, **h3**, **h4**, **h5**, **h6**)
* paragraph (**p**)
* link (**a**)
* image (**img**)
* button (**button**)

``` html
<!-- Headings -->
<h1>Title1</h1>
<h2>Title2</h2>
<h3>Title3</h3>
<h4>Title4</h4>
<h5>Title5</h5>
<h6>Title6</h6>

<!-- Paragraph -->
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

<!-- Link -->
<a href="https://www.w3schools.com/html/html_links.asp">Learn about Links</a>

<!-- Image -->
<img src=https://s3.amazonaws.com/cdn-origin-etr.akc.org/wp-content/uploads/2017/11/12231413/Labrador-Retriever-MP.jpg"" alt="A puppy">

<!-- Button -->
<button>Click Me!</button>

```

### Style elements in CSS

1. To add style to our elements, we need to [select](https://www.w3schools.com/css/css_selectors.asp) which elements to style, then specify which [properties](https://www.w3schools.com/cssref/default.asp) to change. We can select elements by tag name, ids, or classes as follows:

``` html
<!-- HTML -->

<h1>Title1</h1>
<h1>Title2</h1>

<p id="p1">Paragraph 1</p>

<p>Paragraph 2</p>

<div class="profile">
  <h2>Bob</h2>
  <p>I like pizza.</p>
</div>

<div class="profile">
  <h2>Sally</h2>
  <p>I am 21 years old.</p>
</div>
```

``` css
/* CSS */

/* Select all h1 elements and change the text color to red. */
h1 {
  color: red;
}
/* Select the element with id of p1 and change the background color to blue and position it 100px from the left and 150 px from the top of the window. */
#p1 {
  background-color: blue;
  position: fixed;
  left: 100px;
  top: 150px;
}
/* Select all elements with class of profile and change the width, height, and color. */
.profile {
  width: 300px;
  height: 500px;
  color: yellow;
}
/* Select all h2 elements within the class of profile and change the text color to red. */
.profile h2 {
  color: red;
}
```
