# Ex.06 Book Front Cover Page Design
## Date:03.10.2025

## AIM:
To design a book front cover page using HTML and CSS.

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
book.html

<html>
<head>
    <meta name="view report" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="book.css">  
    <title>Book Cover Page</title>
</head>
<body>
    <div class="bookpage">
        <div id="border"></div>
        <div class="insight">
            SEC INSIGHT
        </div>
        <div class="hrstyle">
            <hr style="color:pink;">
        </div>
        <div class="booktitle">
        <h1>EVERY LEARNATHONS IN OUR HAND</h1>
        </div>
        <div class="subtitle">
            with strategies and tricks to crack athons
        </div>
        <div class="mypic">
            <img src="mypic.jpeg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color:pink;">
        </div>
        <div class="author">
            <p><b>SRINIVAS J<b></p>
        </div>
        <div class="pub">
            ref.no:25015562
        </div>
        <div class="ed">
            <b>Precious edition</b>
        </div>
    </div>
</body>
</html>

book.css

.bookpage{
    width:400px;
    height:600px;
    color:blue;
    margin-left:auto;
    padding:20px;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-image: url(book1.jpeg);
    background-size: cover;
    border: 3px solid #333;
    border-radius: 12px;
}
.insight{
    color:black;
}
.hrstyle{
    width:100px;
}
.author{
    display:inline;
    position: relative;
    color: white;
    top:190px;
    font-family: 'Times New Roman', Times, serif;
    font-size: medium;
}
.booktitle{
    font-family: Georgia, 'Times New Roman', Times, serif;
    font-size: larger;
    text-align: center;
    position: relative;
    top:30px;
}
.id{
    width: 400px;
    position: relative;
    top: 180px;
}
.pub{
    font-size: medium;
    position: relative;
    top:155px;
    left: 270px;
}
.ed{
    color:black;
    font-size: medium;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    position: relative;
    top: 85px;
}
.subtitle{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-size:large;
    position: relative;
    top: 40px;
}
.mypic{
    position:relative;
    top: 135px;
    left:260px;
    width: 100px;
    height: 100px;
    background-size: cover;
}
#border{
    border: 4px solid #333;
    position: absolute;
    width:400px;
    height:615px;
    left: 940px;
    top: 20px;
}


```

## OUTPUT:

![alt text](<Screenshot (9).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
