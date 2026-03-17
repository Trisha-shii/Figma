# Ex09 Event Registration Web Application
## Date: 17-03-2026

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

### FRAME - 1
```html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-17-1-1">
<img src="images/frame-1-2.png" class="frame-1-2" alt="frame-1" />
</div>

</body>
</html>
```
```css
:root {
}

/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Prototype Links */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.frame-1-2 {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  gap: 47px;
  padding: 171px 127px 391px 107px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 104.97512437810946%;
  border-radius: 25px;
  width: 100%;
  height: auto;
}

.iphone-17-1-1 {
@media (max-width: 1440px) {
  .iphone-17-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-17-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 205, 205, 1);
}
```

### FRAME - 2
```html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-17-2-1">
<img src="images/frame-2-2.png" class="frame-2-2" alt="frame-2" />
</div>

</body>
</html>
```
```css
:root {
}

/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Prototype Links */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.frame-2-2 {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  padding: 97px 215px 196px 45px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 147.51243781094527%;
  width: 100%;
  height: auto;
}

.iphone-17-2-1 {
@media (max-width: 1440px) {
  .iphone-17-2-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-17-2-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  background-color: rgba(255, 205, 205, 1);
}
```

### FRAME - 3
```html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-17-3-1">
<div class="frame-3-2">
<img src="images/image-11-3.png" class="image-11-3" alt="image-11" />
<div class="group-2-4">
<div class="rectangle-2-5"></div>
<div class="rectangle-8-6"></div>
<div class="rectangle-7-7"></div>
<div class="rectangle-6-8"></div>
<div class="rectangle-5-9"></div>
<div class="rectangle-4-10"></div>
<div class="rectangle-3-11"></div>
<p class="text-12"><span class="text-black">FULL NAME :</span></p>
<p class="text-13"><span class="text-black">EVENT :</span></p>
<p class="text-14"><span class="text-black">DEPT :</span></p>
<p class="text-15"><span class="text-black">SEC HOUSE :</span></p>
<p class="text-16"><span class="text-black">PHONE NO :</span></p>
<p class="text-17"><span class="text-black">REG NO :</span></p>
<p class="text-18"><span class="text-black">GENDER :</span></p>
<img src="images/rectangle-9-19.svg" class="rectangle-9-19" alt="rectangle-9" />
<p class="text-20"><span class="text-black">EVENT REGISTRATION FORM</span></p>
<img src="images/rectangle-10-21.svg" class="rectangle-10-21" alt="rectangle-10" />
<p class="text-22"><span class="text-black">REGISTER</span></p>
</div>
</div>
</div>

</body>
</html>
```
```css
/* Add font files for Hanuman */
@font-face {
  font-family: 'Hanuman';
  src: url('fonts/hanuman.woff2') format('woff2'),
       url('fonts/hanuman.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Iceberg */
@font-face {
  font-family: 'Iceberg';
  src: url('fonts/iceberg.woff2') format('woff2'),
       url('fonts/iceberg.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

:root {
  --font-family-hanuman: 'Hanuman', sans-serif;
  --font-family-iceberg: 'Iceberg', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
}

.text-black {
  color: var(--text-black);
}

/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Prototype Links */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.image-11-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-2-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-8-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-7-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-6-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-5-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-4-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-3-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-hanuman);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-hanuman);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-hanuman);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-hanuman);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-hanuman);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-hanuman);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-18 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-hanuman);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-9-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(225, 0, 255, 1);
  border: none;
  outline: none;
}

.text-20 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-iceberg);
  font-weight: normal;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-10-21 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(225, 0, 255, 1);
  border: none;
  outline: none;
}

.text-22 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-iceberg);
  font-weight: normal;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.group-2-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.frame-3-2 {
  flex-grow: 0;
  flex-shrink: 1;
  width: 105.61074024409206%;
}

.iphone-17-3-1 {
@media (max-width: 1440px) {
  .iphone-17-3-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-17-3-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(248, 255, 205, 1);
}
```
### FRAME = 4
```html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-17-4-1">
<img src="images/image-10-2.png" class="image-10-2" alt="image-10" />
<p class="text-3"><span class="text-white">~ REGISTRATION SUCESSFUL ~
SEE YOU SOON--- 
AT CELEANZA’26 ~</span></p>
</div>

</body>
</html>
```
```css
/* Add font files for Handjet */
@font-face {
  font-family: 'Handjet';
  src: url('fonts/handjet.woff2') format('woff2'),
       url('fonts/handjet.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

:root {
  --font-family-handjet: 'Handjet', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
}

.text-white {
  color: var(--text-white);
}

/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Prototype Links */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.image-10-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 15px;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-handjet);
  font-weight: normal;
  font-size: 36px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.iphone-17-4-1 {
@media (max-width: 1440px) {
  .iphone-17-4-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-17-4-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 230, 230, 1);
}
```
## OUTPUT:
<img width="1047" height="563" alt="image" src="https://github.com/user-attachments/assets/5d1483b8-df3f-4448-9541-fcf4cebe2f5a" />
REFERENCE LINK : https://www.figma.com/design/KPfPHJ98INPymENvkzmrV9/Untitled?node-id=0-1&t=oYjAmhTP8B4qP56y-1

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
