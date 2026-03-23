# Ex09 Event Registration Web Application
## Date: 23.3.2025
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

```
phone 1-html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="rectangle" src="img/rectangle.png" />
      <div class="text-wrapper">Dance Competition</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">Login</div>
      <div class="text-wrapper-3">Register</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-4">Sathiya Priyan G(25018768)</div>
    </div>
  </body>
</html>

phone 1-css

.iphone-pro-max {
  background-color: #be3ed4;
  width: 100%;
  min-width: 433px;
  min-height: 940px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 29px;
  left: 0;
  width: 433px;
  height: 181px;
  aspect-ratio: 2.39;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 209px;
  left: 47px;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 353px;
  left: 59px;
  width: 316px;
  height: 54px;
  background-color: #141414;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 522px;
  left: 59px;
  width: 316px;
  height: 54px;
  background-color: #141414;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 357px;
  left: 164px;
  -webkit-text-stroke: 1px #ff0000;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ff0000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 524px;
  left: 138px;
  -webkit-text-stroke: 1px #f51616;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ef0808;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 890px;
  left: 0;
  width: 433px;
  height: 50px;
  background-color: #e3ef0a;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 899px;
  left: 58px;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #211d1d;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

phone 2-html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="rectangle" src="img/rectangle.png" />
      <div class="text-wrapper">Dance Competition</div>
      <div class="div"></div>
      <div class="text-wrapper-2">Sathiya Priyan G(25018768)</div>
      <div class="text-wrapper-3">solo performance</div>
      <div class="text-wrapper-4">Duo performance</div>
      <div class="text-wrapper-5">Team performance</div>
    </div>
  </body>
</html>

phone 2-css

.iphone-pro-max {
  background-color: #3ac91e;
  overflow: hidden;
  width: 100%;
  min-width: 432px;
  min-height: 939px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 29px;
  left: 0;
  width: 432px;
  height: 181px;
  aspect-ratio: 2.39;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 209px;
  left: 47px;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 890px;
  left: 0;
  width: 433px;
  height: 50px;
  background-color: #e3ef0a;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 899px;
  left: 58px;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #211d1d;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 330px;
  left: 11px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 431px;
  left: 13px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 532px;
  left: 11px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

phone 3-html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="rectangle" src="img/rectangle.png" />
      <div class="text-wrapper">Dance Competition</div>
      <div class="div"></div>
      <div class="text-wrapper-2">Sathiya Priyan G(25018768)</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">Name</div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-4">Reg No</div>
      <div class="text-wrapper-5">Team Name</div>
      <div class="text-wrapper-6">Phone No</div>
    </div>
  </body>
</html>

phone 3-css

.iphone-pro {
  background-color: #f6369c;
  overflow: hidden;
  width: 100%;
  min-width: 483px;
  min-height: 939px;
  position: relative;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 29px;
  left: 25px;
  width: 433px;
  height: 181px;
  aspect-ratio: 2.39;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 209px;
  left: 47px;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .div {
  position: absolute;
  top: 890px;
  left: 0;
  width: 483px;
  height: 50px;
  background-color: #e3ef0a;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 899px;
  left: 82px;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #211d1d;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle-2 {
  position: absolute;
  top: 315px;
  left: 59px;
  width: 316px;
  height: 54px;
  background-color: #15ccff;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 322px;
  left: 167px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #111010;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle-3 {
  position: absolute;
  top: 467px;
  left: 59px;
  width: 316px;
  height: 54px;
  background-color: #12c7eb;
}

.iphone-pro .rectangle-4 {
  position: absolute;
  top: 391px;
  left: 59px;
  width: 316px;
  height: 54px;
  background-color: #1ac5ff;
}

.iphone-pro .rectangle-5 {
  position: absolute;
  top: 543px;
  left: 59px;
  width: 316px;
  height: 54px;
  background-color: #1affeb;
}

.iphone-pro .text-wrapper-4 {
  position: absolute;
  top: 398px;
  left: 156px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #121010;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-5 {
  position: absolute;
  top: 474px;
  left: 126px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #201e1e;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-6 {
  position: absolute;
  top: 550px;
  left: 143px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #2b2626;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

```
## OUTPUT:
<img width="1920" height="1080" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/115fc672-ec4f-4945-9877-fdbc6fe06cea" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
