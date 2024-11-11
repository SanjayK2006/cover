# Ex.06 Book Front Cover Page Design
## Date: 11-11-2024

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
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>GUIDE TO WEB DESIGN</title>
        <link rel="stylesheet" href="{% static 'css/index.css' %}">
        <style>
            body{
    color:aquamarine;
    font-family: Helvetica, sans-serif;
    background-color: indian red
}

.book{
    width: 726px;
    height:891px;
    margin:auto;
    position: relative;
    background-image: url(tech.avif);
    background-repeat: no-repeat;
    background-size:cover;
    background-position: bottom 0px center;
}
h1{
    font-size:70px;
    margin:60px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: xx-large;
    font-weight:10px;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    color:aqua

}
h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#top{
    border-bottom:2px solid orange;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 10px;
    border-top:2px solid burlywood;
    padding-top:0px;
    width:726px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.photo{
            position: relative;
            top: 170px;
            left: 550px;
            width: 120px;
            height: 120px;
            background-size: cover;
        }
#HASH {
    display: flex;
    justify-content: space-between;
}
  #HASH span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  #end{
    padding-right:60px;
  }
        </style>
    </head>
    <body>
        <section class="book">
            <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>THE PRINCIPLES OF WEB DESIGN</h1>
            <h4>Crafting Digital Experiences with Design Excellence</h4>
            <h3>NINTH Edition</h3>  
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>SANJAY K</span>
                    <span id="end"><u>SEC</u></span>
                </div>
            </footer>
            <div class="photo">
                <img src="me.jpg" width="150" height="170"alt="">
            </div>  
    </section>
    </body>
</html>
```


## OUTPUT:
![Screenshot (71)](https://github.com/user-attachments/assets/3cedde1f-e878-42e2-b555-74171bc1de82)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
