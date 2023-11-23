# **Introduction to CSS**
### 1. Container Element
The HTML **div **element defines a container.

```
<div>
  <h1>Tourism</h1>
  <p>Plan your trip wherever you want to go</p>
  <button>Get Started</button>
</div>
```
## CSS Properties
CSS selectors are used to "find" (or select) the HTML elements you want to style.

- Class Selector
```
selector {
  property1: value1; # Declaration Block
  property2: value2;
}
```
## CSS Text Properties
### 1. Text Align
The CSS **text-align** property specifies the horizontal alignment of the text in an HTML element.

```
.h-center {
  text-align: center;
}
```
![image.png](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/_iETRi5zCodpqEaYTbYFM.png?ixlib=js-3.7.0 "image.png")

### 2. Color
The CSS **color **property specifies the color of the text.

```
.main-heading {
  color: blue;
}
.paragraph {
  color: grey;
}
```
#### Sample Colors
![image.png](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/AQ2l2N1V2a2UeUWyCEwAo.png?ixlib=js-3.7.0 "image.png")

## CSS Colors
### 1. Hex Code
CSS Colors can be represented in multiple ways:

- Color names
- Hex Code
- HSL
- RGB and many more...
Since few colors have the Color names, Hex Codes make a good alternative to pick a wide variety of colors.

Some of the Color names and their Hex Codes are:

![image.png](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/DeWO-z4go5r2ZNoeaC9Q7.png?ixlib=js-3.7.0 "image.png")

```
.button {
  color: #25b1cc;
}
```
#### How to pick a color using Hex Code
The color picker lets you pick a color among the approximately 16,777,216 colors available.

One of the simplest ways to access a color picker is:

Type _color picker_ in the Google Search bar and search it.

![image.png](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/hKH46TBslA9DM1kerXY7_.png?ixlib=js-3.7.0 "image.png")

### 3. Font Family
The CSS **font-family** property specifies the font for an element.

```
@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");
.main-heading {
  font-family: "Roboto";
}
.paragraph {
  font-family: "Roboto";
}
```
You can use one of the below values of the **font-family** property

![image.png](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/KwpDbSv8A1qU3H1urzYpU.png?ixlib=js-3.7.0 "image.png")

**Note**

1. To use font families, you need to import their style sheets into your CSS file.
2. There shouldn't be any spelling mistakes in the values of the font-family property.
3. There must be quotations around the value of the font-family property.
### 4. Font Size
The CSS **font-size** property specifies the size of the font.

```
.main-heading {
  font-size: 36px;
}
.paragraph {
  font-size: 28px;
}
```
### 5. Font Style
The CSS **font-style** property specifies the font style for a text.

You can use one of the below values of the font-style

 property.

![image.png](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/4-U22uEZI0tinEX9t6tVU.png?ixlib=js-3.7.0 "image.png")

```
.main-heading {
  font-style: italic;
}
.paragraph {
  font-style: normal;
}
```
### 6. Font Weight
The CSS **font-weight** property specifies how thick or thin characters in text should be displayed.

```
.main-heading {
  font-weight: bold;
}
.paragraph {
  font-weight: 200;
}
```
You can use one of the below values of the **font-weight** property

![image.png](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/6JcCeUNHvtdg9DTdxWubc.png?ixlib=js-3.7.0 "image.png")

**Note**

1. There shouldn't be any spelling mistakes in the values of the font-weight property.
2. There shouldn't be any quotations around the value of the font-weight property.
3. The numerical values given to the font-weight property must be in the range from 100 to 900 and should be the multiples of 100.
### 7. Text Decoration
The CSS **text-decoration** property specifies the decoration added to the text.

```
.main-heading {
  text-decoration: underline;
}
.paragraph {
  text-decoration: overline;
}
```
You can use one of the below values of the text-decoration property,

![image.png](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/WEHXrSfZ19N8j4URJj6hJ.png?ixlib=js-3.7.0 "image.png")

**Note**

1. There shouldn't be any spelling mistakes in the values of the text-decoration property.
2. There shouldn't be any quotations around the value of the text-decoration property.
3. Ensure that text-decoration and line-through are hyphenated.
## 

## CSS Background Properties
## Background Property 
### 1.Background Color
The CSS **background-color** property specifies the background color of an HTML element.

```
.card {
  background-color: lightblue;
}
```
### 2. Background Image
The CSS **background-image **property specifies the background image of an HTML element.

```
.card {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
}
```
![image.png](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/iDR4mO658tQFPZEQ3SHsm.png?ixlib=js-3.7.0 "image.png")

**Warning**

1. The background image takes the height of the content of an HTML element **if you don't specify the height to it.**
2. The URL given to the background-image must be a valid URL to display the image.
### 3. Background Size
The CSS **background-size **property specifies the size of the background image of an HTML element.

![image.png](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/PRaTGcZlwyatK2gL6WsNt.png?ixlib=js-3.7.0 "image.png")

**Note**

Aspect Ratio is the ratio of the width and height (width/height) of an image.

**HTML**

```
<!DOCTYPE html>
<html>
  <head></head>
  <body>
    <div class="card">
      <h1>Tourism</h1>
      <p>Plan your trip wherever you want to go</p>
      <button>Get Started</button>
    </div>
  </body>
</html>
```
**CSS**

```
.card {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
  background-size: cover;
  width: 250px;
  height: 200px;
}
```