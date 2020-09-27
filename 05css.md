# 05 - Design web pages with CSS

### CSS

CSS stands for **Cascading Style Sheet**, and it is a way to give your HTML structure a design. Best practice is to create your structure and content in HTML, and design/style it in a separate CSS file.

If your separate CSS file was named `style.css`, here is how you would apply it to your HTML file:

```
<html>
    <head>
        <title>Example</title>
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>
    <p>This is an example.</p>
    </body>
</html>
```

Every element on your page can be thought of as a box, and CSS is the way to format, style, and position those boxes. 

Your basic `style.css` file would look something like this:

```
body { 
    background-color: #000;
    color: #fff;
    font-family: Arial, sans-serif; 
    }

p {
    padding: 20px;
}
```

#### How does CSS "cascade"?

If there are two different styles indicated for the same element, the **latest** style will be used. That means that, in general, whichever style is farthest towards the end of the CSS file will be applied.

--- 

### Color

There are several ways to specify color in CSS. In this table, you can see many different ways to specify the color red.

Type | Red Example
-----|------------
RGB | `rgb(255, 0, 0)`
RGBA | `rgba(255, 0, 0, 0.5)`
HEX | `#ff0000`
hsl | `hsl(0, 100%, 50%)`
hsla | `hsla(0, 100%, 50%, 1)`
HTML Color Name | `red`

It's important to consider readability along with an asthetically-pleasing color design. 

---


[Back to Home](https://superlizzy.github.io/reading-notes/)