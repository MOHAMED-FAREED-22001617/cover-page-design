# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Write your own steps here.
### Step 2:
Create a static file directory and mention the changes in settings.
### Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.
### Step 4:
Write down the code for book cover using HTML and CSS.
### Step 5:
Add images and other contents using CSS record a screenshot of it.
## Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .bookpage {
            width: 400px;
            height: 600px;
            background-image: url("romeo.jpeg");
            background-repeat: no-repeat;
            background-size: cover;
            color: white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        }
        .fade-overlay {
            width: 100%;
            height: 100%;
            position: absolute;
            top: 0;
            left: 0;
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5));
        }

        .toptext {
            color: white;
        }

        .tophr {
            width: 140px;
            color: rgb(233, 223, 223);
        }

        .author {
            color: rgb(203, 23, 23);
            display: inline;
            position: relative;
            top: 170px;
            font-family: Helvetica, Arial, sans-serif;
            font-size: medium;
        }

        .booktitle {
            font-family: Helvetica, Arial, sans-serif;
            font-size: 20px;
            text-align: center;
            position: relative;
            top: 20px;
        }

        .id {
            width: 400px;
            position: relative;
            top: 190px;
        }

        .publisher {
            font-size: medium;
            position: relative;
            top: 120px;
            left: 330px;
        }

        .edition {
            color: rgb(242, 234, 234);
            font-size: 15px;
            font-family: Verdana;
            position: relative;
            text-align: left;

            top: 25px;
        }

        .subtitle {
            color: hsl(240, 47%, 97%);
            font-family: 'Montserrat',sans-serif;
            font-size: 20px;
            font-weight: bold;
            text-align: center;
            margin-top: 110px;
        }

        .photo {
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
        <div class="fade-overlay"></div>
        <div class="toptext">
            An Unforgettable Tale of Love and Tragedy
        </div>
        <div class="tophr">
            <hr style="color: red;">
        </div>
        <div class="booktitle">
            <h1>Romeo and Juliet</h1>
        </div>
        <div class="subtitle">
            Romeo and Juliet is a tragedy written by William Shakespeare early in his career about the romance between two Italian youths from feuding families.
        </div>
        <div class="photo">
            <img src="WhatsApp Image 2023-05-19 at 9.58.54 PM.jpeg" width="100" height="100" alt="Author Photo">
        </div>
        
        <div class="author">
            <p><b>FOURTH EDITION</b></p>
        </div>
        <div class="publisher">
            SIMON7
        </div>
        <div class="edition">
            <b>F MOHAMED FAREED</b>
        </div>
    </div>
</body>
</html>
```

## Output:

![Screenshot 2023-05-20 161250](https://github.com/MOHAMED-FAREED-22001617/cover-page-design/assets/121412904/e4823489-79c8-48f3-b754-c2dd3eae3261)
![Screenshot 2023-05-20 162012](https://github.com/MOHAMED-FAREED-22001617/cover-page-design/assets/121412904/105b1837-d349-46f2-864f-b0bd15c648ab)

## Result:
Successfully designed a website to display the cover page of the book Responsive Web Design with HTML5 and CSS

