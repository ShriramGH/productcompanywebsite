# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### home.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Home Page
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    img{
        height: 150px;
        width: 150px;
        align-items:center;
    }
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>SHRI's Universe</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <marquee><b>Feel good through our Store</b></marquee>
                    <p style="color:purple; font-family:'Tahoma'; font-size:20px;"> This is the Official Website of our phone Store</p>
                    </div>
                    <p>Buy all gagets items and phone online for all from <span style="background-color:rgb(112, 137, 112)">SHRIRAM Universe</span>
                         for Rs.100000- | Buy phone in ONE SIZE online | 7 Days Returns | Trend setting models | And much more</p>
                    <br>
                <center>
                    <img src="p1.jpeg">
                    <img src="h2.jpeg">
                    <img src="h3.jpeg">
                </center>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by SHRIRAM S</footer></div>
            </div>
        </div>
    </body>
</html>
```

### style.css
```
.home{
    height: 700px;
    width: 85%;
    border: 12px solid red;
    padding-left:10px;
    padding-right:10px;
    margin-left: auto;
    margin-right:auto;
    background-color:cyan;
}
.content{
    border:1px solid whitesmoke;
    background-color: white;
    width:95%;
    height:1190px;
    padding:10px;
    margin-left:auto;
    margin-right:auto;
}
.header{
    height: 128px;
    width:100%;
    background-image: url(/static/images/header.jpg);
    background-size: cover;
    
}
.logo{
    height:18%;
    width: 10%;
    position:absolute;
    background-image: url(/static/images/icon.png);
    background-size:cover;
    
}
.prod{
    height:auto;
    width:auto;
    position:relative;
    bottom:10px;
    left:550px;
    border:4px solid transparent;
    text-align:center;
    display: inline;
    padding:15px;
    font-family:'Gill Sans MT';
    font-size: large;  
}
.prod:hover{
    background-color:red;
}
.people{
    height:auto;
    width:auto;
    position:relative;
    bottom:10px;
    left:700px;
    border:4px solid transparent;
    text-align:center;
    display: inline;
    padding:15px;
    font-family:'Gill Sans MT';
    font-size: large;  
}
.people:hover{
    background-color:red;
}
.contact{
    height:20px;
    width:10%;
    position:relative;
    bottom:45px;
    left:1000px;
    border:4px solid transparent;
    text-align:center;
    padding:15px;
    font-family:'Gill Sans MT';
    font-size: large;  
}
.contact:hover{
    background-color:red;
}
        
.h{
    height:20px;
    width:10%;
    position:relative;
    top:30px;
    left:200px;
    border:4px solid transparent;
    text-align:center;
    
    padding:15px;
    font-family:'Gill Sans MT';
    font-size: large;  
}
.h:hover{
    background-color:red;
    overflow:hidden;
}
.footer{
    border: 15px solid red;
    width:98%;
    height:10px;
    position:relative;
    bottom: 1px;
    background-color:red;
    text-align:center;

}
.title{
    border:2px solid pink;
    background-color:yellow;
    padding:1px;
    width:99.7%;
    height: 70px;
    text-align:center;
    font-family:'Impact';
    margin-left:auto;
    margin-right: auto;
    
}
.content{
    border:1px solid red;
    background-color: white;
    width:98%;
    height:400px;
    padding:10px;
    margin-left:auto;
    margin-right:auto;

}
```

### products.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Products
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 1555px;
            width: 85%;
            border: 12px solid red;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .text{
            color:blueviolet;
            font-family:'Lucida Sans';
            font-size: 30px;
            text-align:center;
        
        }
        .content{
            border:3px solid red;
            background-color: white;
            width:98%;
            height:1190px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ph1{
            background-image: url(i15.jpeg);
            background-size: 350px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:200px;
            width:30%;
            position:relative;
            left: 50px;
        }
        .l1{
            color: gold;
            position:relative;
            right:380px;
            
            
        }
        .ph2{
            background-image: url(s23.jpeg);
            background-size: 350px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:200px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l2{
            color: sandybrown;
            position:relative;
            right:380px;
        }
        .ph3{
            background-image: url(pixel.jpeg);
            background-size: 370px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:210px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l3{
            color: rgb(19, 16, 12);
            position:relative;
            right:380px;
        }
        .ph4{
            background-image: url("12.jpeg");
            background-position-x: center;
            height:200px;
            width:30%;
            position:relative;
            left: 700px;
            bottom:930px;
            background-size: 350px;
            background-repeat: no-repeat;
            
            
        }
        .l4{
            color: burlywood;
            position:relative;
            left:270px;
            bottom: 930px;
        }
    
        .ph5{
            background-image: url(moto.jpeg);
            background-position-x: center;
            height:200px;
            width:30%;
            position:relative;
            left: 700px;
            bottom:930px;
            background-size: 355px;
            background-repeat: no-repeat;
            
            
        }
        .l5{
            color: cadetblue;
            position:relative;
            left:270px;
            bottom: 930px;
        }

        .ph6{
            background-image: url(all.jpeg);
            background-position-x: center;
            height:200px;
            width:30%;
            position:relative;
            left: 700px;
            bottom:930px;
            background-size: 350px;
            background-repeat: no-repeat;
            
            
        }
        .l6{
            color: crimson  ;
            position:relative;
            left:270px;
            bottom: 930px;
        }
        .bot{
            text-align:center;
            font-size:larger;
            color:magenta;

        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Products</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>These are the products that are available now</p>
                    </div>
                    <div class="ph1"></div>
                    <div class="l1"><p align="center"><b>APPLE I PHONE 15I<br> Price: 1900000</b><br><br><br><br></p></div>
                    <div class="ph2"></div>
                    <div class="l2"><p align="center"><b>SAMSUNG S23<br> Price: 189999.00</b><br><br><br><br></p></div>
                    <div class="ph3"></div>
                    <div class="l3"><p align="center"><b>GOOGLE PIXEL<br> Price: 1999999.00</b><br<br><br><br></p></div>
                    <div class="ph4"></div>
                    <div class="l4"><p align="center"><b>REDMI 13A<br> Price: 699999.00</b><br><br><br><br></p></div>
                    <div class="ph5"></div>
                    <div class="l5"><p align="center"><b>Motorola<br> Price: 3999999.00</b><br><br><br><br></p></div>
                    <div class="ph6"></div>
                    <div class="l6"><p align="center"><b>Primer:ALL WITH OFFER<br> Price: 599999999.00</b><br><br><br><br></p></div>
         
                </div>
                <div class="bot"><p>To Order Online: Call 90 80 70 2009</p></div>

                <div class="footer">
                <footer style="color:rgb(13, 3, 3)">
                Copyright &copy;2023 Developed by SHRIRAM S</footer></div>
            </div>
        </div>
    </body>
</html>
```

### people.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 3000px;
            width: 85%;
            border: 12px solid red;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:rgb(234, 241, 241);
        }
        .text{
        color:rgb(76, 14, 14);
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:2px solid rgb(6, 7, 6);
            background-color:rgb(78, 154, 225);
            width:98%;
            height:2690px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ceoph{
            background-image: url(mz.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:300px;
            width:20%;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color: rgb(10, 1, 1);
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url(tata.jpeg );
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;            
        }
        .man1{
            color: rgb(20, 5, 5);
            position:relative;
            text-align:center;
            
        }
        .manph2{
            background-image: url(pb.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .man2{
            color: rgb(17, 3, 3);
            position:relative;
            text-align:center;
        }
        
        .amph1{
            background-image: url(images.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color: rgb(25, 7, 7);
            position:relative;
            text-align:center;
        }

        .amph2{
            background-image: url(download.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:220px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am2{
            color: rgb(25, 7, 7);
            position:relative;
            text-align:center;
        }
        .amph3{
            background-image: url(si.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:250px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am3{
            color: rgb(19, 4, 4);
            position:relative;
            text-align:center;
        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>People</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>Board Members</p>
                    <h4><u>Chairman</u></h4>
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2>Mark Zukerberg</h2></b></div>
                    <br>
                    <div class="text">
                        <p><b><u>Head executives</u></b></p><br>
                    </div>
                    <div class="manph1"></div>
                    <div class="man1"><p align="center"><b><h2>Ratan Tata</h2></b></p></div>
                    <div class="manph2"></div>
                    <div class="man2"><p><b><h2>Patrick</h2></b></p></div>
                    <br>
                    <div class="text"><p><b><u>Managers</u></b></p></div><br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="center"><b><h2>Tristan</h2></b></p></div>
                    <div class="amph2"></div>
                    <div class="am2"><p align="center"><b><h2>Andrew Tate</h2></b></p></div>
                    <div class="amph3"></div>
                    <div class="am3"><p align="center"><b><h2>Sundar Pichai</h2></b></p></div><br>
                    <div class="text">Thank you so much for your kind support!<br>Hope our products had made you more HOPEFULL!</div>
                </div>
                <div class="footer">
                <footer style="color:darkred">
                Copyright &copy;2023 SHRIRAM S</footer></div>
            </div>
        </div>
    </body>
</html>
```

### contact.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Contact Us
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Contact Us</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b>Here are the details about us
                    <h5>Do contact us for any need</h5></b></p>
                    
                    </div>
                    <b><h2>Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                        ECR, Chennai, TamilNadu, India.
                    </p>
                    <ul>
                        <li><b>Landline:</b> 12345678</li>
                        <li><b>Mobile</b>: 7339174377</li>
                        <li><b>Facebook</b>: shriramfb</li>
                        <li><b>Email Id:</b>shri@univ.com</li>
                    </ul>
                    <div style="text-align: center;color:violet;font-size:20px;"><b>Use our services and Beautify Yourself!</b></div>

                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by SHRIRAM S</footer></div>
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:

### Home Page:
![Screenshot 2023-05-30 235915](https://github.com/ShriramGH/productcompanywebsite/assets/117991122/b0aee625-9d28-49e4-a298-07cdb7c8091e)

### Product page:
![Screenshot 2023-05-31 000121](https://github.com/ShriramGH/productcompanywebsite/assets/117991122/fd62726b-2668-4b77-bda4-e32816edc909)
![Screenshot 2023-05-31 000141](https://github.com/ShriramGH/productcompanywebsite/assets/117991122/ee75800e-ba52-4d20-9155-55718ef354f7)

### People Page:
![Screenshot 2023-05-31 000257](https://github.com/ShriramGH/productcompanywebsite/assets/117991122/2da8e102-7b56-4156-96a4-86a0d935be43)
![Screenshot 2023-05-31 000345](https://github.com/ShriramGH/productcompanywebsite/assets/117991122/6d774181-c588-4496-b4f4-a777f52da258)
![Screenshot 2023-05-31 000425](https://github.com/ShriramGH/productcompanywebsite/assets/117991122/bbe78a6d-662b-42f1-bb40-28c98510cbb7)

### Contact Page:
![Screenshot 2023-05-31 000546](https://github.com/ShriramGH/productcompanywebsite/assets/117991122/f219356d-0284-4a29-bcf1-a78e34727c41)

## Result:
Thus a website is designed for the software product company and the HTML,CSS code are validated.
