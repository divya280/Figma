# Ex09 Event Registration Web Application
## Date:

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
### index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sports Day Events</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <div class="header">
            <img src="college-logo.png" alt="Saveetha Engineering College Logo" class="college-logo">
            <div class="tnea-code">
                <p>TNEA CODE</p>
                <span>1216</span>
            </div>
        </div>
        
        <!-- Event Logo -->
        <img src="event-logo.png" alt="Event Logo" class="event-logo">

        <!-- Title -->
        <h2 class="title">SPORTS DAY EVENTS</h2>

        <!-- Buttons -->
        <div class="button-container">
            <button class="btn login">LOGIN</button>
            <button class="btn register">REGISTER</button>
        </div>

        <!-- Footer Text -->
        <p class="footer-text">"BORN TO WIN"</p>
    </div>
</body>
</html>
```
### events.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sports Day Events</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="event-container">
        <h2>SPORTS DAY EVENTS</h2>
        <hr>
        <ul class="event-list">
            <li>Cricket</li>
            <li>Badminton</li>
            <li>Football</li>
            <li>Volleyball</li>
            <li>Kho Kho</li>
            <li>Chess</li>
            <li>Carrom</li>
            <li>Relay</li>
            <li>High jump</li>
        </ul>
    </div>
</body>
</html>
```
### register.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Registration Form</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="registration-container">
        <h2>EVENT REGISTRATION FORM</h2>
        <p>Fill the Details:</p>
        <form class="registration-form">
            <input type="text" placeholder="Full Name" required>
            <input type="text" placeholder="Gender" required>
            <input type="number" placeholder="Age" required>
            <input type="text" placeholder="Department" required>
            <input type="tel" placeholder="Mobile Number" required pattern="[0-9]{10}">
            <input type="text" placeholder="Events To Register" required>
            <button type="submit">REGISTER</button>
        </form>
    </div>
</body>
</html>
```

## OUTPUT:


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
