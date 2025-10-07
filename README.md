# Ex.06 Book Front Cover Page Design
## Date:

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
cover.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <link rel="stylesheet" href="style.css">
        <title>COVER</title>
        
    </head>
    <body align="center" color="white">
        <div class="name"><h1 align="center">B.SAM JOEL JOSHUA (25001200)</h1></div>
        <div class="sam">
            <div class="page1">
                <h1>SEC INSIGHT</h1>
                <hr>
            </div>
            <div class="page2">
                <p>THE ALGORITHM ATLAS</p>
            </div>
            <br>
            <div class="page3">
                <h2>THE DEVELOPERS BLUEPRINT </h2> 
                <h3>Getting Started with Full Stack Development</h3>
                <h3>Debugging and Testing Strategies</h3>
                
            </div>
            <div class="picture">
                 <img src="passport.jpg">
            </div>
            <div class="page4">
                <h2>ELITE EDITION</h2>
                <hr>
                <h2 align="center">B.SAM JOEL</h2>
            </div>
            
        </div>
    </body>


style.css
 
 .name{
    text-align:center;
    position: relative;
    right:50px;
}




.body{
    background-color:blueviolet ;
    font-family: Cambria, Georgia, Times, 'Times New Roman', serif;
    font-style:oblique;
    color:rgba(255, 0, 30, 0.916);
}
.sam{
    background-image: url("photo-1644088379091-d574269d422f.avif");
    background-clip: border-box
    background-position-x:right ;
    background-size:cover;
    height: 800px;
    width:600px;
    position:relative;
    left: 400px;
    color:red;
}
.page1{
    margin:auto;
    border:solid 10px rgb(49,44,59);

}
.page2{
    font-size:50px;
    text-align:center;
    position:relative;
    top:50px;

}
.page3{
    position:relative;
    left:15px;
    font-size: 20px;

}

.picture{
    width: 150px; 
    height:150px;      
    position: relative;
    top: 70px;
    left:300px;
    border: 2px solid rgba(255, 0, 0, 0.793);
    background: white;
    overflow: hidden;
}

.picture img{
    width:100%;
    height:100%;
    object-fit:cover;
}
.page4{
    position:relative;
    top:50px;
    left:5px;
    font-weight: bold;
}
.page5{
    position:fixed;
    font-family: Georgia, 'Times New Roman', Times, serif;
    top:50px;
    left:20px;
}


</html>

## OUTPUT:
![alt text](<Screenshot (34).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
