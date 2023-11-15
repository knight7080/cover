# Ex.06 Book Front Cover Page Design
## Date: 28-10-23

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Font ex1</title>
        <link rel="stylesheet", href="book.css">
        <style>
            body {
                background-image: url('samp.png');
                background-size: 500px 750px;
                background-repeat: no-repeat;
            }
        </style>
    </head>
    <body>
        <p class="T1">
            First Edition
        </p>
        <hr class="l1" color="gray">
        
        <p class="T2">
            Elden Ring
        </p>
        
        <p class="T3">
            Hidetaka Miyazaki
        </p>
        
        <hr class="l2">
        <img src="prof.jpg" class="i1" style="vertical-align:bottom">
        
        
    </body>
</html>
```

```css
p{
    font-family: Arial;
    text-align: center;
    margin-top: 0;
    margin-bottom: 0;
}

div{
    text-align: center;
}

.T1{
    font-weight: bold;
    color: rgb(179, 129, 13);
    font-size:17px;
    margin-top: 30px;
    margin-left: -630px;

}
.l1{
    width: 20%;
    margin-left: -10px;
}
.T2{
    font-weight: bold;
    color: rgb(246, 149, 31);
    font-size:45px;
    margin-top:70px;
    margin-left: -265px;
}

.T3{
    font-weight: bold;
    font-size:20px;
    margin-top: 480px;
    color: rgb(179, 129, 13);
    margin-right: 600px;

}
.l2{
    width: 20%;
    margin-left: -10px;
}
.i1{
    filter: grayscale(100%);
    height: 100px;
    margin-left: 410px;
    margin-top: -180px;
}
```

## OUTPUT:
![image](https://github.com/knight7080/cover/assets/88542035/b6f49be6-842e-4a46-9104-e07712518a57)
![image](https://github.com/knight7080/cover/assets/88542035/6af4a650-b7c9-43ed-9903-e3d0cfe5798e)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
