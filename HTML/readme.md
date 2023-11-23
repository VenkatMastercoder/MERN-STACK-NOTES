# HTML FULL NOTES

by [﻿Venkatesan G](https://www.linkedin.com/in/venkatesan-tech/)﻿

# **1. Basic Structure**
The basic structure of any HTML document is as follows:

```html
<!DOCTYPE html>
<html>
<head>
    <!-- Head Section -->
</head>
<body>
    <!-- Body Section -->
    Your code goes here
</body>
</html>
```
1. `<!DOCTYPE html>` : This is the document type declaration. It informs the web browser that the document is an HTML5 document. HTML5 is the latest version of HTML and is widely used for creating web pages.
2. `<html>` : This tag represents the root of the HTML document. All other elements are nested inside this tag.
3. `<head>` : This section contains meta-information about the HTML document, such as the title of the page, links to external stylesheets or scripts, and other meta tags. It doesn't display any content on the web page itself.
4. `<body>` : This section contains the actual content of the web page, such as text, images, links, and other elements. This is where you put the visible part of your webpage.
5. `<!-- ... -->` : This is an HTML comment. Comments are not displayed on the webpage, but they can be used to provide notes or explanations for the code.
6. `**Your code goes here**` : This is a placeholder for the actual content of your webpage. You would replace this with the HTML elements that make up your webpage, such as headings, paragraphs, images, links, etc.
7. Closing tags: Each HTML tag has a corresponding closing tag that begins with a forward slash (`</` ). For example, `<head>`  has a closing tag `</head>` , and `<body>`  has a closing tag `</body>` . Closing tags are used to define the end of a particular section.


## **TEXT ELEMENTS**
# **1. Heading Element**
The HTML

**h1** element defines a main heading.

```html
<h1>This is Heading 1</h1>
<h2>This is Heading 2</h2>
<h3>This is Heading 3</h3>
<h4>This is Heading 4</h4>
<h5>This is Heading 5</h5>
<h6>This is Heading 6</h6>
```
# **3. Paragraph Element**
The HTML

**p** element defines a paragraph.

```html
<p>Plan your trip wherever you want to go</p
```
# **4. Button Element**
The HTML

**button** element defines a button.

```html
<button>Get Started</button>
```
# **6. Anchor Element**
The HTML

**a **element defines a Anchor.

```
<a href="https://www.example.com" target="_blank">
Visit Example.com
</a>
```
The first `<a>` tag creates a hyperlink to an external website (in this case, "[﻿https://www.example.com](https://www.example.com/)") with the link text "Visit Example.com." 

The `target="_blank"` attribute opens the link in a new browser tab or window.

```
<a href="https://www.example.com" target="_blank" id="#Section1" >
Visit Call to Action Sectionfvv   88fvv   
</a>
```
`<a>` tag creates a hyperlink to another section within the same page using the `href` attribute with the corresponding section's ID as the value.



# **7. **SPAN **Element**
The HTML

`span` element defines a span.

```
<p>This is a 
<span style="color: red; font-weight: bold;">highlighted</span> 
word in a paragraph.</p>
```
the `<span>` tag is used to highlight the word

# **8. Strong Element**
The `<strong>` tag in HTML is used to give importance to the enclosed text,

```
<p>This is a <strong>strong</strong> emphasis on a word in a paragraph.</p>
```
Browsers usually render text within the `<strong>` tag in a bold font by default



## Container Elements
# **1. Container Element**
The HTML

**div** element defines a container.

```html
<div>
  <h1>Tourism</h1>
  <p>Plan your trip wherever you want to go</p>
  <button>Get Started</button>
</div>
```
## MEDIA ELEMENTS
# 1. **Image Element**
The `<img>` tag in HTML is used to embed images on a webpage

**This is for Signal Image **

```html
<img src="IMAGE_URL" alt=""/>
```
**This is for Multiple Images **

```
<picture>
  <source srcset="large.jpg" media="(min-width: 800px)">
  <source srcset="medium.jpg" media="(min-width: 600px)">
  <img src="small.jpg" alt="Responsive Image">
</picture>
```
It is a self-closing tag is know as **VOID **Elements.

it requires the `src` attribute to specify the source (URL or file path) of the image.

The `alt` attribute provides alternative text for accessibility and is displayed if the image cannot be loaded. 

# 2. Audio** Element**
The `<audio>` tag in HTML is used to embed audio content on a webpage

**This is for Signal Video **

```
<audio src="example.mp3" type="audio/mp3" controls></audio>
```
#### This is For Multiple Audio 
```html
<!-- The audio tag with the src attribute pointing to the audio file -->
<audio controls>
  <source src="example.mp3" type="audio/mp3">
  <source src="example.mp3" type="audio/mp3">
  Your browser does not support the audio element.
</audio>
```
 It supports various audio formats and provides controls for users to play, pause, adjust volume, and more

The `controls` attribute adds playback controls to the audio player.

 If the **browser does not support the audio element** or the specified audio format, **the text within the **`**<audio>**`** tag will be displayed as a fallback.**

# 3. Video** Element**
The `<video>` tag in HTML is used to embed video content on a webpage

**This is for Signal Video **

```
<video src="example.mp3" type="audio/mp3" controls></video>
```
#### This is For Multiple Video
```
<!-- The video tag with the src attribute pointing to the video file -->
<video width="640" height="360" controls>
  <source src="example.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```
It supports various video formats and provides controls for users to play, pause, adjust volume, and more.

The `width` and `height` attributes define the dimensions of the video player.

the `controls` attribute adds playback controls.

If the **browser does not support the video element** or the specified video format, **the text within the **`**<video>**`** tag will be displayed as a fallback**.

# LIST
In HTML, there are two main types of lists

## Unordered list `**<ul>**` 
- The `<ul>` element is used to create an unordered list.
- Unordered lists typically represent a collection of items and are displayed with bullet points or other symbols by default.
- Each item in the list is represented by the `<li>`  (list item) element.
```
<!-- Unordered list with list items -->
<ul>
  <li>Apple</li>
  <li>Orange</li>
  <li>Banana</li>
</ul>
```


## ordered list `**<ol>**` 
- The `<ol>`  element is used to create an ordered list.
- Ordered lists typically represent a sequence of items and are displayed with numbers or letters by default.
- Each item in the list is represented by the `<li>`  (list item) element.
```
<!-- Ordered list with list items -->
<ol>
<li>Step 1</li>
<li>Step 2</li>
<li>Step 3</li>
</ol>
```
# BR ELEMENT
The `<br>` element in HTML is a line break element

```
<p>This is some text, and<br>this is on a new line.</p>
```
It's a self-closing tag, meaning it doesn't have a closing tag.

It is used to create a line break in the content, forcing the text or elements that follow it to appear on the next line.

# **FORM**
the `<form>` tag is used to create an HTML form.

that allows users to input data and submit it to a server for processing

```
<form action="/submit_form" method="post">
    
    <!-- Text input field -->
<label for="username">Username:</label>
<input type="text" id="username" name="username" required>

    <br>

    <!-- Password input field -->
<label for="password">Password:</label>
<input type="password" id="password" name="password" required>

    <br>

    <!-- Submit button -->
<input type="submit" value="Submit">

  </form>
```
- `<form>` tag creates the form, and the `action` attribute specifies the URL or file to handle the form data when submitted.
- `method`  attribute indicates the HTTP method to be used (commonly "post" or "get").
- `<label>`   tags are used to associate labels with form elements for better accessibility.
- `<input>`   tags create form fields. In this case, there's a text input for the username, a password input for the password, and a submit button to submit the form.
- `required`   attribute is used to indicate that the user must fill out the input fields before submitting the form.
# SEMANTIC ELEMENTS 
Semantic HTML tags are designed to add meaning and structure to the content they enclose and improve SEO 

 `<article>`: Represents a self-contained piece of content that could be distributed and reused independently, such as a news article or blog post.

`<aside>` : Represents content that is tangentially related to the content around it, often represented as a sidebar.

`<details>` : Represents a disclosure widget from which the user can obtain additional information or controls.

`<footer>` : Represents the footer of a section or page, often containing metadata, copyright information, or links to related resources.

`<header>` : Represents introductory content, usually at the beginning of a page or section, containing headings, logos, and navigation.

`<main>` : Represents the main content of the document, excluding headers, footers, and sidebars.

`<mark>` : Represents text that has been highlighted or marked for reference or notation.

`<nav>` : Represents a navigation bar or menu for navigating within or outside the current page.

`<section>` : Represents a thematic grouping of content within a document, typically with a heading.

`<summary>` : Represents a summary, caption, or legend for the content of a `<details>`  element.

`<time>` : Represents a specific period in time or a range of time, typically used for dates.

## EXAMPLE 
```
<header>
  <h1>Company Name</h1>
  <nav>
    <a href="/">Home</a>
    <a href="/products">Products</a>
    <a href="/contact">Contact</a>
  </nav>
</header>
```
```
<main>
  <h2>Welcome to our Website!</h2>
  <p>Main content goes here.</p>
  <article>
    <h3>Featured Article</h3>
    <p>Article details.</p>
  </article>
  <!-- Additional content goes here -->
</main>
```
```
<footer>
  <p>&copy; 2023 My Website. All rights reserved.</p>
</footer>
```
## **META ELEMENT**
The `<meta>` element in HTML is used to provide metadata about the HTML document.

Metadata is information about the document that is not part of the document content but provides additional information for browsers, search engines, and other web services.

Here are some common uses of the `<meta>` element:

**Character Set Declaration:**

Specifies the character encoding for the document. In this example, UTF-8 is a widely used character encoding that supports a broad range of characters.

```
<meta charset="UTF-8">
```
**Viewport Settings for Responsive Design:**

Helps to control the viewport settings, making the web page responsive on various devices by adjusting the width and initial scale.

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
**Page Description for Search Engines:**

Provides a short description of the page content. This can be used by search engines when displaying search results.

```
<meta name="description" content="A brief description of the page content.">
```
**Keywords for Search Engines:**

Specifies a comma-separated list of keywords relevant to the page. Historically, this was used more for search engine optimization (SEO).

```
<meta name="keywords" content="HTML, CSS, JavaScript, web development">
```
**Author Information:**

```html
<meta name="author" content="Author Name">
```
Indicates the author of the document.



# WHAT IS HTML ENTRIES
HTML entities are special codes used to represent reserved characters and symbols in HTML

These codes begin with an ampersand (`&`) and end with a semicolon (`;`).

### EXAMPLE
![image.png](https://eraser.imgix.net/workspaces/w5iX8SmPeXQq444su05G/cW4TYXUmCph0yuFtGhfXbN9Xayl1/uEolpqy4NwVVY5biHIC9W.png?ixlib=js-3.7.0 "image.png")

## WHAT IS VOID ELEMENT 
- Void elements, also known as self-closing or empty elements
- HTML elements that do not have a closing tag.
Here are some examples of void elements:

1. `<img>` : Represents an image.
```
<img src="image.jpg" alt="Description">
```
1. `<br>` : Represents a line break.
```
<p>This is some text.<br>This is on a new line.</p>
```
1. `<hr>` : Represents a thematic break or horizontal line.
```
<p>Some content above<hr>Some content below.</p>
```
1. `<input>` : Represents an input field in a form.
```
<input type="text" name="username" />
```
1. `<meta>` : Provides metadata about the HTML document.
```
<meta charset="UTF-8">
```
These elements are called **"void"** because they don't have content, and their purpose is often to insert something into the document rather than encapsulating content. The self-closing syntax (`<element />`) is equivalent to `<element></element>` but is more concise.