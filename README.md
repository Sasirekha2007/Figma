# Ex09 Event Registration Web Application
## Date:06.10.2025

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
page1

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <div class="text-wrapper">SEC</div>
      <img class="saveetha" src="img/saveetha1-1.png" />
      <div class="div">HOSTEL</div>
      <div class="text-wrapper-2">FEST</div>
      <div class="text-wrapper-3">2k25</div>
      <div class="text-wrapper-4">-</div>
      <img class="college-festival" src="img/college-festival-1.png" />
      <div class="rectangle"></div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-5">register</div>
    </div>
  </body>
</html>

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

.android-compact {
  background-color: #9a0d0d;
  width: 100%;
  min-width: 451px;
  min-height: 809px;
  position: relative;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 113px;
  left: 155px;
  width: 197px;
  font-family: "Londrina Shadow-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .saveetha {
  position: absolute;
  top: 0;
  left: 0;
  width: 451px;
  height: 87px;
  aspect-ratio: 5.01;
  object-fit: cover;
}

.android-compact .div {
  position: absolute;
  top: 204px;
  left: 102px;
  font-family: "Londrina Shadow-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 304px;
  left: 21px;
  font-family: "Londrina Sketch-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-3 {
  position: absolute;
  top: 304px;
  left: 259px;
  text-shadow: 0px 4px 4px #00000040;
  font-family: "Londrina Sketch-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-4 {
  position: absolute;
  top: 304px;
  left: 204px;
  font-family: "Londrina Shadow-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .college-festival {
  position: absolute;
  top: 519px;
  left: 0;
  width: 451px;
  height: 290px;
  aspect-ratio: 1.56;
  object-fit: cover;
}

.android-compact .rectangle {
  position: absolute;
  top: 441px;
  left: 235px;
  width: 4px;
  height: 7px;
  background-color: #d9d9d9;
}

.android-compact .rectangle-2 {
  position: absolute;
  top: 422px;
  left: 53px;
  width: 364px;
  height: 71px;
  background-color: #d91818;
}

.android-compact .text-wrapper-5 {
  position: absolute;
  top: 395px;
  left: 84px;
  font-family: "Londrina Sketch-Regular", Helvetica;
  font-weight: 400;
  color: #e8ff20;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

page2

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="banner" src="img/banner-1.png" />
      <img class="download" src="img/download-1-1.png" />
      <img class="img" src="img/banner-2.png" />
      <img class="download-2" src="img/download-1-2.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">Events</div>
      <div class="div">Cooking</div>
      <div class="text-wrapper-2">*</div>
      <div class="text-wrapper-3">*</div>
      <div class="text-wrapper-4">*</div>
      <div class="text-wrapper-5">sports</div>
      <div class="text-wrapper-6">Dance</div>
      <div class="text-wrapper-7">*</div>
      <div class="text-wrapper-8">Music</div>
      <div class="text-wrapper-9">*</div>
      <div class="text-wrapper-10">Mehandi</div>
      <div class="text-wrapper-11">eagerly</div>
      <div class="text-wrapper-12">waiting</div>
      <div class="text-wrapper-13">...</div>
      <div class="text-wrapper-14">....</div>
    </div>
  </body>
</html>

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

.android-compact {
  background-color: #a90f0f;
  width: 100%;
  min-width: 440px;
  min-height: 809px;
  position: relative;
}

.android-compact .banner {
  top: 0;
  left: 0;
  width: 440px;
  height: 343px;
  position: absolute;
  aspect-ratio: 1.88;
  object-fit: cover;
}

.android-compact .download {
  top: 543px;
  left: 256px;
  width: 10px;
  height: 8px;
  position: absolute;
  aspect-ratio: 1.28;
  object-fit: cover;
}

.android-compact .img {
  top: 335px;
  left: 121px;
  width: 28px;
  height: 15px;
  position: absolute;
  aspect-ratio: 1.88;
  object-fit: cover;
}

.android-compact .download-2 {
  top: 294px;
  left: 0;
  width: 440px;
  height: 506px;
  position: absolute;
  aspect-ratio: 1.28;
  object-fit: cover;
}

.android-compact .rectangle {
  position: absolute;
  top: 224px;
  left: 0;
  width: 440px;
  height: 76px;
  background-color: #980909;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 158px;
  left: 98px;
  font-family: "Londrina Shadow-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .div {
  position: absolute;
  top: 313px;
  left: 135px;
  font-family: "Lobster-Regular", Helvetica;
  font-weight: 400;
  color: #141a03c9;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-2 {
  top: 325px;
  left: 96px;
  font-family: "Lobster-Regular", Helvetica;
  position: absolute;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-3 {
  top: 385px;
  left: 96px;
  font-family: "Lobster-Regular", Helvetica;
  position: absolute;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-4 {
  top: 461px;
  left: 96px;
  font-family: "Lobster-Regular", Helvetica;
  position: absolute;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-5 {
  position: absolute;
  top: 377px;
  left: 140px;
  font-family: "Lobster-Regular", Helvetica;
  font-weight: 400;
  color: #190101;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-6 {
  position: absolute;
  top: 450px;
  left: 140px;
  font-family: "Lobster-Regular", Helvetica;
  font-weight: 400;
  color: #150101;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-7 {
  top: 535px;
  left: 96px;
  font-family: "Lobster-Regular", Helvetica;
  position: absolute;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-8 {
  position: absolute;
  top: 521px;
  left: 140px;
  font-family: "Lobster-Regular", Helvetica;
  font-weight: 400;
  color: #1c0202;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-9 {
  top: 611px;
  left: 96px;
  font-family: "Lobster-Regular", Helvetica;
  position: absolute;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-10 {
  position: absolute;
  top: 599px;
  left: 140px;
  font-family: "Lobster-Regular", Helvetica;
  font-weight: 400;
  color: #1d0303;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-11 {
  position: absolute;
  top: 663px;
  left: 45px;
  font-family: "Manuale-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-12 {
  position: absolute;
  top: 711px;
  left: 167px;
  font-family: "Manuale-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-13 {
  top: 711px;
  left: 332px;
  font-family: "Manuale-Regular", Helvetica;
  position: absolute;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-14 {
  top: 711px;
  left: 362px;
  font-family: "Manuale-Regular", Helvetica;
  position: absolute;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}
page3

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <div class="text-wrapper">Registration</div>
      <div class="div">Form</div>
      <div class="rectangle"></div>
      <img class="img" src="img/rectangle-7.svg" />
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">Department</div>
      <div class="rectangle-3"></div>
      <img class="rectangle-4" src="img/rectangle-10.svg" />
      <div class="text-wrapper-3">Reference number</div>
      <div class="text-wrapper-4">Name</div>
      <div class="text-wrapper-5">Contact number</div>
      <div class="text-wrapper-6">Register</div>
    </div>
  </body>
</html>

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

.android-compact {
  background-color: #b60e0e;
  width: 100%;
  min-width: 458px;
  min-height: 809px;
  position: relative;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 12px;
  left: 90px;
  font-family: "Mandali-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .div {
  position: absolute;
  top: 70px;
  left: 151px;
  font-family: "Mandali-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .rectangle {
  position: absolute;
  top: 186px;
  left: 47px;
  width: 263px;
  height: 67px;
  background-color: #e6f0f1;
}

.android-compact .img {
  position: absolute;
  top: 296px;
  left: 50px;
  width: 257px;
  height: 67px;
}

.android-compact .rectangle-2 {
  position: absolute;
  top: 405px;
  left: 51px;
  width: 253px;
  height: 66px;
  background-color: #d9d9d9;
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 423px;
  left: 103px;
  font-family: "Myanmar Khyay-Regular", Helvetica;
  font-weight: 400;
  color: #3020a3;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .rectangle-3 {
  position: absolute;
  top: 527px;
  left: 54px;
  width: 250px;
  height: 64px;
  background-color: #d9d9d9;
}

.android-compact .rectangle-4 {
  position: absolute;
  top: 629px;
  left: 54px;
  width: 300px;
  height: 117px;
}

.android-compact .text-wrapper-3 {
  position: absolute;
  top: 208px;
  left: 64px;
  font-family: "Myanmar Khyay-Regular", Helvetica;
  font-weight: 400;
  color: #282aa6;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-4 {
  position: absolute;
  top: 316px;
  left: 134px;
  font-family: "Myanmar Khyay-Regular", Helvetica;
  font-weight: 400;
  color: #3039b0;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-5 {
  position: absolute;
  top: 543px;
  left: 78px;
  font-family: "Myanmar Khyay-Regular", Helvetica;
  font-weight: 400;
  color: #1f1da8;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-6 {
  position: absolute;
  top: 663px;
  left: 72px;
  font-family: "Rubik Mono One-Regular", Helvetica;
  font-weight: 400;
  color: #2cc069;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

page4

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="download" src="img/download-1-3.png" />
      <div class="text-wrapper">ThAnk You</div>
      <div class="div">We Eagerly</div>
      <div class="text-wrapper-2">waiting for</div>
      <div class="text-wrapper-3">participation guys........</div>
      <div class="text-wrapper-4">Have fun</div>
      <div class="text-wrapper-5">Enjoy the events</div>
    </div>
  </body>
</html>

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

.android-compact {
  background-color: #ffffff;
  width: 100%;
  min-width: 451px;
  min-height: 789px;
  position: relative;
}

.android-compact .download {
  position: absolute;
  top: 0;
  left: 0;
  width: 451px;
  height: 789px;
  aspect-ratio: 1.28;
  object-fit: cover;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 152px;
  left: 58px;
  font-family: "Rubik Mono One-Regular", Helvetica;
  font-weight: 400;
  color: #2d051f;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .div {
  position: absolute;
  top: 232px;
  left: 48px;
  font-family: "Rethink Sans-Regular", Helvetica;
  font-weight: 400;
  color: #260404;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 232px;
  left: 226px;
  font-family: "Rethink Sans-Regular", Helvetica;
  font-weight: 400;
  color: #1f0202;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-3 {
  position: absolute;
  top: 286px;
  left: 66px;
  font-family: "Rethink Sans-Regular", Helvetica;
  font-weight: 400;
  color: #2e0505;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-4 {
  position: absolute;
  top: 357px;
  left: 126px;
  font-family: "Rethink Sans-Regular", Helvetica;
  font-weight: 400;
  color: #270505;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-5 {
  position: absolute;
  top: 399px;
  left: 66px;
  font-family: "Rethink Sans-Regular", Helvetica;
  font-weight: 400;
  color: #230404;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

```

## OUTPUT:
![alt text](<Screenshot 2025-10-05 233137.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
