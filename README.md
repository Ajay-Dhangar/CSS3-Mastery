# CSS3 Mastery Course

## About Your Instructor

Dear Learner's,

I am super excited to have you in this Course, let's learn and grow together.

I have 2 Year and 6 months of experience working in CSS3. I have put all my experience into this Course to make a successful in 2023.

Check my [LinkedIn Profile](https://www.linkedin.com/in/ajay-dhangar-bb89b4227/)

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

`index.html ` 
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
