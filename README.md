# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
home.html

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="home.css"> 
    </head>
    <body>
        <nav>
            <a  href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <div class="name">
            <h1>NOBITA RESTAURANT</h1>
            <b>"From Field To Fork -Delicious Foods On Every Day"</b>
            
        </div>
        <div class="offer">
            <h2>Limited Offers</h2>
            <h3>50% off for all Food</h3>
        </div>
        <footer>
            <h6 class="bottom">DHIYA D(25018435)</h6>

        </footer>
    </body>
</html>

home.css

*{
    margin: 0;
    border: 0;
}

body{
    background-image:url("backrd2.jpeg");
    background-position: center;
    background-size:cover;
    width: 100%;
    background-color: rgb(252, 93, 24);
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: rgb(11, 11, 11);
}

a{
    padding: 15px;
    color:rgb(20, 195, 14);
}
a:hover{
    background-color: rgb(15, 14, 14);
    color:rgb(237, 67, 15);
}
.name{
    text-align: center;
    position: relative;
    left: 290px;
    font-weight: bolder;
    font-family: 'Times New Roman', Times, serif;
    color: rgba(10, 9, 9, 0.855);
    font-size: 30px;
    width: 1000px;
    background-color: rgba(251, 246, 246, 0.94);
}
.offer{
    text-align: right;
    font-size: 40px;
    color: rgb(218, 218, 17);
    position: relative;
    right: 100px;
    top:200px;

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 462px;
    background-color: rgb(232, 248, 11);
}

menu.html

<html>
    <head>
        <title>Menu</title>
        <link rel="stylesheet" href="menu.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <h1>Menu Lists</h1>
        <div class="main">
            
            <div class="food1">
                <img src="fried rice.webp"alt="pic">
                <b>FRIED RICE -$20</b>
            </div>
            <div class="food2">
                <img src="naan bread.webp" alt="pic">
                <b>NAAN BREAD-$15</b>
            </div>
            <div class="food3">
                <img src="noodles.webp" alt="pic">
                <b>NOODLES</b>-$50</b>
            </div>
            <div class="food4">
                <img src="pasta.webp" alt="pic">
                <b>PASTA -$60</b>
            </div>
            <div class="food5">
                <img src="pizza.webp" alt="pic">
                <b>PIZZA-$30</b>
            </div>
            <div class="food6">
                <img src="shawarma.webp" alt="pic">
                <b>SHAWARMA-$40</b>
            </div>
            <div class="food7">
                <img src="sushi rolls.webp" alt="pic">
                <b>SUSHI ROLLS-$30</b>
            </div>
            <div class="food8">
                <img src="chapathi.webp" alt="pic">
                <b>CHAPATHI-$40</b>
            </div>
            <div class="food9">
                <img src="Burger.webp" alt="pic">
                <b>BURGER-$50</b>
            </div>
            <div class="food10">
                <img src="biriyani.webp" alt="pic">
                <b>EGG BRIYANI-$40</b>
            </div>
        </div>
        <footer>
            <h6 class="bottom">DHIYA D(25018435)</h6>

        </footer>
    </body>
</html>

menu.css

body{
    
    background:url("backrd3.jpeg");
    background-repeat: no-repeat;
    background-position:center;
    background-size: cover;
    font-size: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    margin: auto;
}
.main{
    display: grid;
    grid-template-columns: repeat(5,1fr);
}
a{
    color:rgb(229, 243, 38);
    position: relative;
    left: 1200px;
}
.food1{
    padding: 10px;
    background-color: rgba(245, 45, 14, 0.993);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
}
.food2{
    padding: 10px;
    background-color: rgba(243, 9, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
    
}
.food3{
    padding: 10px;
    background-color: rgba(246, 28, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
}
.food4{
    padding: 10px;
    background-color: rgba(245, 16, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
    
}
.food5{
    padding: 10px;
    background-color: rgba(255, 37, 8, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    bottom: 20px;
    
}
.food6{
    padding: 10px;
    background-color: rgba(244, 4, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food7{
    padding: 10px;
    background-color: rgba(247, 57, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food8{
    padding: 10px;
    background-color: rgba(239, 39, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food9{
    padding: 10px;
    background-color: rgba(250, 32, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food10{
    padding: 10px;
    background-color: rgba(252, 25, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}


img{
    width: 150px;
    height: 100px;
    border: solid rgb(4, 4, 4) 6px;
}
h1{
    text-align: center;
    position: relative;
    bottom: 10px;
   
    color: rgb(12, 226, 41);

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 50px;
    background-color: rgb(206, 237, 7);
}

admin.html


<html>
    <head>
        <title>Admin</title>
        <link rel="stylesheet" href="admin.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <h1>Administration</h1>
        <div class="admin">
            <div class="a1">
                <img src="chef 1.jpeg">
                <b>SIVA</b>
                <b>CEO</b>
            </div>
            <div class="a2">
                <img src="chef 2.jpeg">
                <b>RAHIM</b>
                <b>Manager</b>
            </div>
            <div class="a3">
                <img src="chef 3.jpeg">
                <b>NAVEEN</b>
                <b>Service Manager</b>
            </div>
            <div class="a4">
                <img src="chef 4.jpeg">
                <b>KUMAR </b>
                <b>Chief</b>
            </div>
            <div class="a5">
                <img src="man 4.jpeg">
                <b>VELU</b>
                <b>Accounts Manager</b>
            </div>
            <div class="a6">
                <img src="manager.jpeg">
                <b>VIJAY</b>
                <b>Maintenance Manager</b>
            </div>
        </div>
        <footer>
            <h6 class="bottom">TEJASHREE</h6>

        </footer>
    </body>
</html>

admin.css

body{
    background-image:url("i.jpeg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
a{
    padding: 15px;
    color:rgb(251, 9, 9);
    position: relative;
    left: 1100px;
    top: 20px;
    font-size: 20px;
    font-size: x-large;
}
.admin{
    display: grid;
    grid-template-columns: repeat(6,1fr);
    font-size: 20px;
    gap:10px;
}
img{
    width: 210px;
    height: 300px;
    border:solid 5px rgb(240, 235, 235);
}
.a1,.a2,.a3,.a4,.a5,.a6{
    padding: 5px;
    background-color: rgb(221, 209, 209);
    text-align: center;
    font-size: 24px;
    
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color:white;
    position: relative;
    top: 60px;
    color:white;
}
h1{
    text-align: center;
    color:rgb(250, 21, 21);
    font-size: 40px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 125px;
    background-color: brown;
    width: 1550px;
}

contact.html

<html>
    <head>
        <title>Contact</title>
        <link rel="stylesheet" href="contact.css">
    </head>
    <body>
         <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <div class="contanct-container">
            <h1>Contact Us:</h1>
            <h4>Address: 234 West 42nd Street, FRENCH, NY 10036</h4>
            <h2>Phone no: +1 678-298-2442</h2>
            <h3>Email:nobito@gmail.com</h3>
        </div>
        <footer>
            <h6 class="bottom">TEJASHREE</h6>

        </footer>
    </body>
</html>

contact.css


body{
    background-image:url("backrd1.jpeg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    font-size: 20px;
}

a{
    padding: 15px;
    color:rgb(246, 66, 11);
    position: relative;
    left: 1100px;
    top: 20px;
    font-size: 20px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color: rgba(37, 0, 0, 0.768);
    position: relative;
    top: 150px;
    color: white;
}
.contanct-container{
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
    padding: 30px;
    background-color: rgb(251, 246, 246);
    height:400px;
    width:410px;
    display: block;
    gap: 20px;
    font-size: 20px;
    position: relative;
    left: 600px;
    top:20px;
    border-radius: 10%;
}
h2,h3,h4{
    font-size: 27px;
}
```
# OUTPUT:

<img width="1879" height="970" alt="Screenshot 2025-12-29 105809" src="https://github.com/user-attachments/assets/f38efea9-1263-4c75-b0f2-be3d5266eb57" />

<img width="1903" height="893" alt="Screenshot 2025-12-29 105859" src="https://github.com/user-attachments/assets/c019805a-8330-4bce-8af4-2bb03a7b9af3" />
<img width="1908" height="872" alt="Screenshot 2025-12-29 105927" src="https://github.com/user-attachments/assets/88d0bb32-20b6-4520-b7c7-7f3a0c92b9d7" />

<img width="1918" height="930" alt="image" src="https://github.com/user-attachments/assets/8a65dee4-a84e-48bf-88c9-cbbb6ce4bb82" />

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
