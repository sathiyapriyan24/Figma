# Ex09 Event Registration Web Application
## Date: 24.12.2025
# Ref : 25018768

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:

~~~
HTML 
-----

Page-1
Home page

<!DOCTYPE html>
<html>
<head>
    <title>Register</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="phone yellow">
    <div class="header">
        <h3>SAVEETHA<br>ENGINEERING COLLEGE</h3>
        <span class="code">1216</span>
    </div>

    <div class="card center">
        <button class="btn gray" onclick="location.href='page2.html'">
            REGISTER
</button>
    </div>
</div>

</body>
</html>


Page-2
Details

<!DOCTYPE html>
<html>
<head>
    <title>Participants Details</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="phone blue">
    <h2 class="title">Participants Details</h2>

    <div class="card">
        <input type="text" placeholder="Full Name">
        <input type="email" placeholder="Email Address">
        <input type="tel" placeholder="Mobile Number">

        <button class="btn green" onclick="location.href='page3.html'">
            Submit
        </button>
    </div>
</div>

</body>
</html>


Page-3
Thank you

<!DOCTYPE html>
<html>
<head>
    <title>Success</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="phone green-bg">
    <div class="card center">
        <h2 class="success">Registration Successful 🎉</h2>
        <hr>
        <p>Thank you for registering for the event.</p>
        <p>We will contact you soon</p>
    </div>
</div>

</body>
</html>


CSS 
----

body {
    margin: 0;
    background: #eee;
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

/* Mobile Frame */
.phone {
    width: 280px;
    height: 540px;
    border-radius: 35px;
    padding: 20px;
    box-shadow: 0 12px 30px rgba(0,0,0,0.25);
    position: relative;
}

/* Backgrounds */
.yellow {
    background: linear-gradient(#ffb300, #fff1d6);
}

.blue {
    background: linear-gradient(#7bb8cc, #eaf6fa);
}

.green-bg {
    background: linear-gradient(#1aa334, #e6f6ea);
}

/* Header */
.header {
    color: #000;
    font-size: 12px;
    font-weight: bold;
}

.code {
    float: right;
}

/* Title */
.title {
    text-align: center;
    margin-top: 40px;
}

/* Card */
.card {
    background: #f2fbff;
    border-radius: 25px;
    padding: 25px;
    margin-top: 60px;
}

.center {
    text-align: center;
}

/* Inputs */
input {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border-radius: 6px;
    border: 1px solid #888;
}

/* Buttons */
.btn {
    width: 100%;
    padding: 12px;
    border-radius: 6px;
    border: none;
    font-weight: bold;
    cursor: pointer;
}

.gray {
    background: #ddd;
}

.green {
    background: #0a9b18;
    color: white;
}

/* Success */
.success {
    color: #0a8a2a;
}

hr {
    margin: 15px 0;
}


~~~
## OUTPUT:


<img width="1919" height="1019" alt="Screenshot 2025-12-24 101005" src="https://github.com/user-attachments/assets/121db0a9-987d-4634-a3e7-2c68abe84dea" />



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
