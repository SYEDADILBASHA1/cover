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
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
            width: 400px;
            height: 600px;
            color:maroon;
            margin-left: auto;
            margin-right: auto;
            padding:20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIzLTA5L2thdGV2NjQ0N19yb2JvdF90aGlua2luZ18zZF9jYXJ0b29uX2NoYXJhY3Rlcl9pc29sYXRlZF9vbl93aGl0ZV85NjVkZWQ5ZC1kNjZjLTQxMTQtOTkzMS02ZmJiMDU2ZWZmMzYucG5n.webp);
            background-size: cover;
        }

        .insight{
            color: maroon;

        }

        .hrstyle{
            width: 100px;
        }

        .author{
            color: white;
            display: inline;
            position: relative;
            color: red;
            top: 190px;

            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: medium;
        }
        .booktitle{
            margin-top: 30px;
            color:red;
            padding:5px;
            font-size: xx-large
            
        }

        .id{
            width: 400px;
            position: relative;
            top: 180px;

        }

        .pub{
            font-size: big;
            position: relative;
            top: 180px;
            left: 330px;
        }
        .ed{
            color: goldenrod;
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 85px;

        }
        .subtile{
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 10px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>APPLIED ARTIFICIAL INTELLIGENCE</h1>
            </div>
            <div class="subtitle">
            Learn sales management techniques by applying artificial intelligence to automate your business,thanks to machine learning and developing leadership
            </div>
            <div class="mypic">
                <img src="photo_2024-04-24_13-10-40.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
                <p><b>SYED ADIL BASHA</p></b>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Extended Edition</b>
            </div>
        </div>
    </body>
</html>
```


## OUTPUT:
![Screenshot (183)](https://github.com/SYEDADILBASHA1/cover/assets/134796157/1ac02906-1a8f-43db-a3a5-470d37b86c27)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
