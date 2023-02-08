# CSS3 Mastery Course

## About Your Instructor

Dear Learner's,

I am super excited to have you in this Course, let's learn and grow together.

I have 2 Year and 6 months of experience working in CSS3. I have put all my experience into this Course to make a successful in 2023.

👇 Connect With me 

<a href="https://linkedin.com/in/ajay-dhangar-bb89b4227/" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>

<br />

Happy Learning!

<details id=1 open>
<summary><h2>Section 1: Introduction & Environment Setup </h2></summary>

<h3> What is CSS </h3>

- CSS stands for Cascading Style Sheets.
- CSS describes how HTML elements are to be displayed on screen, paper, or in other media.
- CSS saves a lot of work. It can control the layout of multiple web pages all at once.
- External stylesheets are stored in CSS files.
- CSS extension is `.css` 

<h3>Why Use CSS?</h3>
<p>CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.</p>

## Environment Setup 

1. Download VS-Code [visualstudio.com](https://code.visualstudio.com/download)

2. Now, open vs code and install some extensions 
   - [X] Live Server
   <br/>
   <img src="https://user-images.githubusercontent.com/99037494/215412999-8108144f-7d26-4df5-a017-f65d9859aa7e.png?r=3r9" width="500" height="250" align="center" alt="Ajay Dhangar"/><br /> <hr/.
  
    - [X] Prettier - Code formatter <br />
    <img src="https://user-images.githubusercontent.com/99037494/215414513-6a7ee1ff-262d-4788-81c6-5ba1e17e6262.png?r=3r9" width="500" height="250" align="center" alt="Ajay Dhangar's Dev Card"/><br />



</details>

<details id=2>
<summary><h2>Section 2: Basics of HTML & CSS</h2></summary>

Now, Create a new file

### your first `HTML` and `HTML` Structure.

First create `index.html ` file
in vs code and press key ` ! ` OR ` shift ` + ` 1 ` key then press ` Enter ` Because it is html boilerplate code shortcut key in  vscode. Otherwise write this Code.

`index.html`

``` HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basics of HTML & CSS</title>
</head>
<body>
    <h1>Basics of HTML & CSS</h1>    
</body>
</html>
```
<br />

`Output`

<br />

![image](https://user-images.githubusercontent.com/99037494/215420445-71a3f3c6-cf28-4093-8bbd-438d79ce1525.png)

### Explanation:

- The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document
- The `<html>` element is the root or parent element of an HTML page
- The `<head>` element contains meta information about the HTML page
- The `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
- The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The `<h1>` element defines a large heading
- `lang="en"` difines english language. You can use any lnguage in `lang=" "`.

### What is CSS?

CSS (Cascading Style Sheets) is the code that styles web content.It is not a programming language and not a markup language either. It is a style sheet language. CSS is what you use to selectively style HTML elements. For example, this CSS selects paragraph text, setting the color to green:

```css
p {
  color: green;
}
```

**Explaination :** `p` is `selecter`, `color` is `property`, and `green` is `value`.

### Different ways of using `CSS3`

 CSS can be added to HTML documents in 3 ways:
 - **Inline** - by using the `style` attribute inside HTML elements
 - **Internal** - by using a `<style>` element in the `<head>` section
 - **External** - by using a `<link>` element to link to an external `CSS` file
 
***for Example:*** create `index.html` file and write this cade and view output.

### Inline :

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basics of HTML & CSS</title>
</head>
<body>
    <h1 style="color:blue">Getting Started CSS with <span style="color: green;">Aj Zero Coding</span></h1>
</body>
</html>
```

### Internal :

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basics of HTML & CSS</title>
    <style>
        h1{
            color:blue;
        }
        span{
            color: green;
        }
    </style>
</head>
<body>
    <h1>Getting Started CSS with <span>Aj Zero Coding</span></h1>
</body>
</html>
```

### External :

you need two files: `index.html` and `style.css`.

`index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basics of HTML & CSS</title>
    <link rel="stylesheet" href="./style.css">    
</head>
<body>
    <h1>Getting Started CSS with <span>Aj Zero Coding</span></h1>
</body>
</html>
```

`style.css`

```css
h1 {
  color: blue;
}
span {
  color: green;
}

```

### Output :

![image](https://user-images.githubusercontent.com/99037494/216768238-3249d0c6-50ca-48d5-b413-e6072d6d9c12.png)

</details>


<details id=3>
<summary><h2>Section 3: Font, Color, Background, Float</h2></summary>

## 1. Selectors in CSS
   
 **4 types of selector in CSS**
   
 - CSS element selector 
 - CSS id selector
 - CSS Class selector
 - The CSS grouping selector
   
**For Example :**
   
`index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basics of HTML & CSS</title>
    <link rel="stylesheet" href="./style.css">    
</head>
<body>
    <h1>Getting Started CSS with <span>Aj Zero Coding</span></h1>
    <p>This is paragraph one</p>
    <p id="pera">This is paragraph two</p>
    <p class="pera">This is paragraph three</p>
</body>
</html>
```
   
`style.css`
```css
h1 {
  color: blue;
}
span {
  color: green;
}
/* === CSS element selector === */
p {
  color: red;
  font-size: 20px;
}
/* === CSS id selector === */
#pera {
  color: #fff;
  background-color: cadetblue;
  font-size: 22px;
}
/* === CSS class selector === */
.pera {
  color: #f8f81a;
  background-color: orangered;
  font-size: 22px;
}
/* === The CSS grouping selector === */
h1,
p {
  text-align: center;
}
```

### Output:

![Selectors](https://user-images.githubusercontent.com/99037494/216819382-f1f72e7b-a6d0-4d14-b610-3a18a9ad1cad.png)

## 2. Debugging using developer tool

https://user-images.githubusercontent.com/99037494/216828031-8ae82ebb-5b78-44f3-a44b-467d9ca75ad9.mp4


## 3. Font in CSS

### font-family :
 In CSS there are five generic font families:

 - `Serif` fonts have a small stroke at the edges of each letter.
 - `Sans-serif` fonts have clean lines (no small strokes attached). They create a modern and minimalistic look.
 - `Monospace` fonts - here all the letters have the same fixed width. They create a mechanical look. 
 - `Cursive` fonts imitate human handwriting.
 - `Fantasy` fonts are decorative/playful fonts.
 
 ![image](https://user-images.githubusercontent.com/99037494/216831443-fc6c0ed7-936e-440b-92bb-66d15992406e.png)

### Font Style :

 - `normal` - The text is shown normally
 - `italic` - The text is shown in italics
 - `oblique` - The text is "leaning" (oblique is very similar to italic, but less supported)
 
 ![image](https://user-images.githubusercontent.com/99037494/216831850-586c4c07-2ebd-4d06-a140-d3f4ba8cd268.png)

### Font Weight :

- 100 to 900
- bold
- normal 

![image](https://user-images.githubusercontent.com/99037494/216832164-55b8bb83-318c-45dc-ae5e-d864f4eb1f8a.png)
 
### Font Variant :

- normal 
- small-caps 
 
![image](https://user-images.githubusercontent.com/99037494/216832395-c4db70c1-baeb-4d48-9c3a-bb5218111a85.png)

### Font Size :

- Set Font Size With Pixels
- Set Font Size With Em
- Set Font Size With Percent
- Set Font Size With vw

![image](https://user-images.githubusercontent.com/99037494/216832907-c4b6b099-071a-4732-8bbb-6d1c7fc0fddc.png)

**Relative Units**

**EM:** Relative to the parent element

**REM:** Relative to the root element (HTML tag)

**%:** Relative to the parent element

**VW:** Relative to the viewport’s width

**VH:** Relative to the viewport’s height

**Difference VW, %, and px mobile screen viewport that is `480px` x `800px` For `width`.**

- 1 VW = 1% = 4.8px
- 50 VW = 50% = 240px

**Difference Vh, %, and px mobile screen viewport that is `480px` x `800px` For `height`.**

- 1 Vh = 1% = 8px
- 50 Vh = 50% = 400px

### Google Fonts :

- you need a google fonts link. for example

`<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia">`

```css
font-family: "Sofia", sans-serif;
font-size: 30px;
text-shadow: 3px 3px 3px #ababab;
```

![image](https://user-images.githubusercontent.com/99037494/216833591-6a88f00f-6fe2-48a8-814b-1e3f32f3bea9.png)

More examples of google fonts

![image](https://user-images.githubusercontent.com/99037494/216833639-6142a17a-564d-422b-b621-450ddda59c93.png)

**For Example :**

`index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Font in CSS</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia">
    <link rel="stylesheet" href="./style.css">    
</head>
<body>
    <h3>font-family :</h3>
    <ul>
        <li class="Serif">Serif</li>
        <li class="Sans-serif">Sans-serif</li>
        <li class="Monospace">Monospace</li>
        <li class="Cursive">Cursive</li>
        <li class="Fantasy">Fantasy</li>
    </ul> 
    
    <hr />

    <h3>Font Style :</h3>
    <ul>
        <li id="normal">normal</li>
        <li class="italic">italic</li>
        <li class="oblique">oblique</li>
    </ul> 

    <hr />

    <h3>Font Weight :</h3>
    <ul>
        <li class="normal">normal</li>
        <li class="bold">Bold</li>        
    </ul>

    <hr />

    <h3>Font Variant :</h3>
    <ul>
        <li class="normal-v">normal</li>
        <li class="small">small-caps</li>        
    </ul>
    <hr />

    <h3>Font size :</h3>
    <ul>
        <li class="Pixels">Pixels</li>
        <li class="Em">Em</li> 
        <li class="Percent">Percent</li>
        <li class="vw">vw</li>        
    </ul>

    <hr />
    <h3>Google Fonts :</h3>
    <ul class="google-fonts">
        <li class="name">Ajay Dhangar</li>
        <li class="author">Author of CSS-3 Mastery</li> 
        <li class="number">123456790</li>
    </ul>
</body>
</html>
```

`style.css`

```css
.Serif {
  font-family: serif;
}
.Sans-serif {
  font-family: sans-serif;
}
.Monospace {
  font-family: monospace;
}
.Cursive {
  font-family: cursive;
}
.Fantasy {
  font-family: fantasy;
}
#normal {
  font-style: normal;
}
.italic {
  font-style: italic;
}
.oblique {
  font-style: oblique;
}
.normal {
  font-weight: normal;
}
.bold {
  font-weight: bold;
}
.normal-v {
  font-variant: normal;
}
.small {
  font-variant: small-caps;
}
.Pixels {
  font-size: 10px;
}
.Em {
  font-size: 1em;
}
.Percent {
  font-size: 10%;
}
.vw {
  font-size: 10vm;
}
.google-fonts {
  font-family: "Sofia", sans-serif;
  font-size: 30px;
  text-shadow: 3px 3px 3px #ababab;
}
.name {
  font-size: 1.5em;
}
```

**Output :**

![image](https://user-images.githubusercontent.com/99037494/216834023-0fe028d0-fe9e-4bbb-8940-a08bbda6c672.png)

![image](https://user-images.githubusercontent.com/99037494/216834062-bf67bb6c-de3c-4335-9a0b-f8f93979dc97.png)

## 4. Color in CSS

`index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>color Property in CSS</title>
    <link rel="stylesheet" href="./style.css">    
</head>
<body>
   <h1 id="one">Heading-1</h1> 
   <h1 id="two">Heading-2</h1> 
   <h1 id="three">Heading-3</h1> 
</body>
</html>
```

`style.css`

```css
#one {
  color: red; /* Basic write any color name*/
}
#two {
  color: rgb(103, 93, 188); /* rgb = red, green, blue (Range of this 0-255)*/
}
#three {
  color: #50f111; /* Hex-color Code use 6 digit with the help of # symbol */
}
```

**Output :**

![image](https://user-images.githubusercontent.com/99037494/217153610-30762d9b-1208-48ee-a268-af262324d695.png)

## 5. Border, Background, Height, Width

`index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Border-Background-Height-Width</title>
    <link rel="stylesheet" href="./style.css">    
</head>
<body>
    <h1>Border, Background, Height, Width</h1>
   <p id="one">Heading-1</p> 
   <p id="two">Heading-2</p> 
   <p id="three">Heading-3</p> 
</body>
</html>
```

`style.css`

```css
/* Basic write any color name*/
#one {
  color: white;
  background-color: orange;
}
/* rgb = red, green, blue (Range of this 0-255)*/
#two {
  color: rgb(255, 255, 255);
  background-color: rgb(93, 188, 114);
}
/* Hex-color Code use 6 digit with the help of # symbol */
#three {
  color: #ffffff;
  background-color: #8d7cc5;
}
p {
  border: 1px solid black;
  width: 400px;
  height: 100px;
  text-align: center;
  font-size: 22px;
  font-weight: bold;
}
```

**Output :**

![image](https://user-images.githubusercontent.com/99037494/217184992-92383476-34c0-4cc5-9d0a-e4b31319c49b.png)

### (i) Border

you can create `index.html` file and `style.css` file.

`index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Border</title>
    <link rel="stylesheet" href="./style.css">    
</head>
<body>
    <h1>Border Property in CSS</h1>
   <p id="solid">Solid</p> 
   <p id="dashed">Dashed</p>
   <p id="dotted">Dotted</p>
   <p id="double">Double</p>
   <p id="outset">Outset</p>
   <p id="ridge">Ridge</p>
   
</body>
</html>
```

Now, apply `border` property in `style.css` file.

a. for solid border line

```css
border: 2px solid red;
```

b. for dashed border line

```css
border: 2px dashed red;
```

c. for dotted border line

```css
border: 2px dotted red;
```

d. for double border line

```css
border: 2px double red;
```

e. for hidden border line

```css
border: 2px hidden red;
```

f. for outset border line

```css
border: 2px outset red;
```

g. for ridge border line

```css
border: 2px ridge red;
```

`style.css`

```css
p {
  width: 400px;
  height: 50px;
  font-weight: bold;
  font-size: 22px;
  text-align: center;
}

#solid {
  border: 2px solid red;
}

#dashed {
  border: 2px dashed red;
}
#solid {
  border: 2px solid red;
}
#dotted {
  border: 2px dotted red;
}
#double {
  border: 2px double red;
}
#outset {
  border: 2px outset red;
}

#ridge {
  border: 2px ridge red;
}
```

**Output :**

![image](https://user-images.githubusercontent.com/99037494/217194286-19822b19-bf3e-4ef6-844f-322f705aee72.png)


### border-radius

`index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Border</title>
    <link rel="stylesheet" href="./style.css">    
</head>
<body>
    <h1>Border-radius Property in CSS</h1>
   
</body>
</html>
```

`style.css`

```css
h1 {
  border-radius: 20px;
  background-color: lightgrey;
  text-align: center;
  height: 200px;
  width: 500px;
}
```

**Output :**

![image](https://user-images.githubusercontent.com/99037494/217274032-b90546f5-76dd-41a3-a537-606c33eeac2f.png)


### (ii) Background

Basic properties of css background 

- background-color
- background-image
- background-position
- background-repeat
- background-size
- background-attachment
- backdrop-filter
- background-clip

`index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background</title>
    <link rel="stylesheet" href="./style.css">    
</head>
<body>
    <h1>Background Property in CSS</h1>
    
</body>
</html>
```

`style.css`

```css
body {
  background-image: url(./img.png);
}
h1 {
  background-color: chartreuse;
  text-align: center;

  height: 50px;
}
```

**Output :**

![image](https://user-images.githubusercontent.com/99037494/217198999-efffb4de-5bd9-4629-8e28-7ff3e074d89e.png)

## 6. BoxModel margin, padding

<h3>BoxModel :</h3>

The CSS Box Model is a concept that describes the rectangular boxes that are generated for elements in a web page, and how they are sized, positioned, and layered. The Box Model defines the overall structure of an HTML element and includes the content, padding, borders, and margins.

- **Content:** The content of an element, such as text or images, is the innermost part of the Box Model.

- **Padding:** The padding surrounds the content and creates space between the content and the border.

- **Border:** The border surrounds the padding and the content, and you can set its color, width, and style.

- **Margin:** The margin surrounds the border and creates space between the element and other elements on the page.

When you set the `width` and `height` properties of an element, you are setting the size of the content area. The overall size of the element, including the padding, borders, and margins, can be calculated by adding the `width` and `height` of the content area, plus the widths of the padding, borders, and margins.

It's important to understand the Box Model when working with CSS, as the size and position of an element can be affected by the values set for its padding, borders, and margins.

**In CSS, `margin` and `padding` are properties that add space outside and inside an HTML element, respectively.**

<h3>Margin :</h3>

`Margin` refers to the space outside an element, surrounding it with blank space. 
The `margin` property is used to create space around an element, outside of any defined borders. You can specify the margin size for each side of an element (top, right, bottom, and left) using the following syntax:

```css
margin: top right bottom left;
```

<h3>Padding :</h3>

`Padding`, on the other hand, refers to the space inside an element, between the element's content and its border. The `padding` property is used to create space around the content within an element, inside of any defined borders. You can specify the padding size for each side of an element (top, right, bottom, and left) using the following syntax:

```css
padding: top right bottom left;
```

Both `margin` and `padding` can be specified using either pixels, percentage, em, or other units of measurement.

For example, the following CSS code sets a 10-pixel padding on all sides of a `div` element:

```css
div {
  padding: 10px;
}
```

And the following CSS code sets a 20-pixel margin on the top and bottom and a 10-pixel margin on the left and right of a `p` element:

```css
p {
  margin: 20px 10px;
}
```

## 7. Float clear

In CSS, the `float` property is used to specify that an element should be floated to the left or right of its containing block. When an element is floated, other elements will flow around it, and the element will become a part of the flow of the document.

For example, if you have two adjacent elements and one of them has the `float` property set to left, the element will be moved to the `left` side of the containing block and the other element will wrap around it.

```css
.element1 {
  float: left;
  width: 50%;
}

.element2 {
  width: 50%;
}
```

The `clear` property is used to specify that an element should not be floated on a particular side. This can be useful when you want to prevent elements from flowing around a floated element and ensure that they appear below it.

For example, if you have a floated element followed by another element, and you want the latter to appear below the floated element, you can set its `clear` property to `both`:

```css
.element1 {
  float: left;
  width: 50%;
}

.element2 {
  clear: both;
  width: 100%;
}
```

In this example, `element2` will appear below `element1` and will not be affected by the float.

</details>


<details id=4>
<summary><h2>Section 4: Selector, Display, Position, Z-Index</h2></summary>


</details>

<details id=5>
<summary><h2>Section 5: Flexbox, Media Queries, and Responsive design</h2></summary>


</details>

<details id=6>
<summary><h2>Section 6: Advance Selectors, Effects, and Animation</h2></summary>


</details>

<details id=7>
<summary><h2>Section 7: Source Code</h2></summary>


</details>

<details id=X>
<summary><h2>Finish</h2></summary>

### What's next?

</details>


---


&copy; 2022 GitHub &bull; [Ajay-Dhangar](https://github.com/Ajay-Dhangar) &bull; [CC-BY-4.0 License](#)
