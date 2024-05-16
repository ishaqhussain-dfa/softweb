# Ex.07 Software Product Company Website
## Date:
28/04/2024
## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Development Company</title>
    <style>
        /* CSS styles can go here */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .hero {
            background-image: url('hero-image.jpg');
            background-size: cover;
            color: #0c0cd6;
            text-align: center;
            padding: 50px 0;
        }
        .services {
            padding: 30px 0;
        }
        .portfolio {
            background-color: #f4f4f4;
            padding: 50px 0;
            text-align: center;
        }
        .about-us {
            padding: 50px 0;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            
        }
        .class{
            text-align: center;
            
        }
        .image table img {
            height: 140px;
            width: 140px;
            border: 2px solid white;
            padding: 5px;
            border-radius: 50%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Software Development Company</h1>
    </header>
    <nav>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="home" class="hero">
            <h2>Welcome to our Software Development Company</h2>
            <p>We specialize in creating innovative software solutions.</p>
        </section>
        <section id="services" class="services">
            <h2>Our Services</h2>
            <p>We offer a wide range of software development services.</p>
            <p style="color: red;"> 1. <b> Custom Software Development:</b> Tailored solutions designed to meet specific business needs, including web applications, mobile apps, and desktop software.
            <p style="color: rgb(250, 120, 13);"> 2. <b>Web Development:</b> Building and maintaining websites using technologies such as HTML, CSS, JavaScript, and various web frameworks like React, Angular, or Vue.js.
            <p style="color: rgb(232, 192, 16);"> 3.<b> Mobile App Development:</b> Creating mobile applications for iOS and/or Android platforms using languages like Swift, Objective-C, Java, Kotlin, or cross-platform frameworks like React Native or Flutter.
            <p style="color: rgb(134, 230, 16);"> 4.<b> Software Consulting: </b>Providing expert advice and guidance on software architecture, technology selection, and project planning to help clients make informed decisions.
            <p style="color: rgb(15, 216, 72);"> 5.<b> UI/UX Design:</b> Designing user interfaces and experiences that are intuitive, visually appealing, and user-friendly to enhance customer satisfaction and engagement.
            <p style="color: rgb(9, 221, 211);"> 6.<b> Quality Assurance (QA) and Testing:</b> Ensuring the quality, reliability, and performance of software products through comprehensive testing methodologies, including functional testing, usability testing, and performance testing.
            <p style="color: rgb(13, 78, 209);"> 7. <b>Cloud Computing Solutions:</b> Leveraging cloud platforms such as AWS, Azure, or Google Cloud to build scalable, secure, and cost-effective cloud-based applications and infrastructure.
            <p style="color: rgb(139, 13, 185);"> 8. <b>E-commerce Development:</b> Developing online stores and e-commerce platforms with features like product catalog management, secure payment gateways, and order processing.
            <p style="color: deeppink"> 9.<b> Blockchain Development:</b> Building decentralized applications (DApps) and blockchain-based solutions for industries such as finance, supply chain, healthcare, and more.
            <p style="color: gray"> 10.<b> Internet of Things (IoT) Solutions:</b> Developing applications and systems that connect physical devices to the internet, enabling data collection, analysis, and automation in various domains like smart homes, healthcare, and industrial IoT.</p>
        </section>
        <section id="about" class="about-us">
            <h2>About Us</h2>
            <p>Learn more about our company and our team.</p>
        </div>
        <center>
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="sk.jpeg"> </td>
                    <td> <img src="aadhi.jpg"> </td>
                    <td> <img src="guha.jpeg"> </td>
                    <td> <img src="sanjay.jpg"> </td>

                </tr>
                <tr align="center">
                    <th> Satheesh Kumar KG</th>
                    <th> Ishaq Hussain A</th>
                    <th>Guhanandan V</th>
                    <th> Sanjay P </th>
                  
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                </tr>
                <tr align="center">
                <td>6303868717</td>
                <td>6374492710</td>
                <td>7010277006</td>
                <td>9080581025</td>
            </tr>
            </table>
        </div>
    </div> </center>
        </section>
        <section id="contact" class="contact">
            <center><h2>Contact Us</h2>
            <h4>contact Number : 1800 906 9945</h4>
        </center>    
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Software Development Company. All rights reserved.</p>
    </footer>
</body>
</html>

```

## OUTPUT:
![out1](https://github.com/KGSatheeshKumar/softweb/assets/128453421/82c4819d-8ac2-44c5-b1bc-4b15fa42736c)

![out2](https://github.com/KGSatheeshKumar/softweb/assets/128453421/f4cadb0b-c6ab-4caf-b43b-2098aa1452c9)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
