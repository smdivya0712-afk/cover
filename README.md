# Ex.05 Book Cover Page Design
## Date: 14.12.2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
cover.html
<html>
<head>
    <meta charset="UTF-8">
    <title>Book Cover</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="cover">
    <h1>About the Book</h1>
    <hr>

    <p>
        This book <span> Web Application Workshop: From Basics to Real Projects</span>provides
      a hands on introduction to web application, covering the core concepts of HTML, CSS, JavaScripts
      and Basic backend ideas. Designed for beginners it focuses on pratical experiments and Real
      world examples to help students understand hoe modern web application are built. 

    </p>

    <div class="quote">
        "The Web begins with an idea and comes alive through code."
    </div>

    <div class="author">
        <img src="author.jpeg" alt="Author">
        <div>
            <h3>DIVYA.S <br>
               Register No: 25013279 <br>
           Department: B.tech.IT </h3>
            
        </div>
    </div>

    <div class="footer">
        <div>
        <p> SEC Publishers</p>
        <p> Printed in India</p>
    </div>
    <p>Price: ₹499</p>
</div>
</div>

</body>
</html>

styles.css
body {  
    margin: 0;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    font-family: Arial;
    background: #001f3f; 
}
  .cover {
width: 700px;
background: linear-gradient(#001f3f, #003366);
border: 4px solid black;
padding: 30px;
box-sizing: border-box;
border-radius: 10px;
overflow: hidden;
}

h1 {
color: white;
}

hr {
height: 3px;
background: black;
border: none;
}

p {
font-size: 18px;
line-height: 1.6;
color: white;
}

p span {
background: yellow;
padding: 3px;
font-weight: bold;
}

.quote {
margin: 30px 0;
padding: 20px;
background: #002855;
border-left: 6px solid black;
font-style: italic;
font-size: 20px;
color: white;
}

.author {
display: flex;
background: white;
padding: 15px;
border-radius: 10px;
}

.author img {
width: 80px;
height: 100px;
margin-right: 15px;
}

.footer {
background: #0b4f6c;
color: white;
padding: 15px;
display: flex;
justify-content: space-between;
}

```

## OUTPUT:
![alt text](<Screenshot (58).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
