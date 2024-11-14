# Ex09 Event Registration Web Application
## Date: 14.11.2024

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
### thank.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thank You Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="thank-you-container">
        <h2>THANK YOU!</h2>
        <p>WE ARE EAGERLY WAITING FOR YOUR PARTICIPATION</p>
        <div class="contact-info">
            <p>FOR MORE DETAILS</p>
            <p>CONTACT</p>
            <p><b>COORDINATOR</b></p>
            <p>V DIVYASHREE</p>
            <p>9498306889</p>
        </div>
    </div>
</body>
</html>
```
### page1.css:
```
body {
    font-family: Arial, sans-serif;
    background-image: url('background.jpg'); /* Add your background image here */
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    margin: 0;
}

.container {
    text-align: center;
    background-color: rgba(255, 255, 255, 0.9);
    padding: 20px;
    border-radius: 10px;
    width: 350px;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
}

.banner {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.college-logo {
    width: 60px;
    height: auto;
    margin-right: 10px;
}

.banner-text h1 {
    font-size: 18px;
    color: #003366;
    margin: 0;
}

.banner-text p {
    font-size: 12px;
    margin: 0;
    color: #666;
}

h2 {
    margin: 20px 0;
    font-size: 24px;
    color: #8B0000;
}

.button-container {
    margin: 20px 0;
}

.btn {
    display: block;
    width: 150px;
    padding: 10px;
    margin: 10px auto;
    font-size: 16px;
    color: white;
    background-color: #8B4513;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.btn:hover {
    background-color: #5A2D1A;
}

footer {
    margin-top: 20px;
    font-size: 16px;
    color: #333;
}
```
### page2.css:
```
body {
    font-family: Arial, sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    margin: 0;
    background-color: #f5f5f5;
}

.event-container {
    background: linear-gradient(to bottom, #f0e68c, #fdf5e6);
    padding: 20px;
    border-radius: 10px;
    width: 300px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

h2 {
    font-size: 24px;
    color: #6e2b77;
    text-shadow: 1px 1px #e0e0e0;
    margin-bottom: 10px;
}

hr {
    border: none;
    border-top: 2px solid #6e2b77;
    width: 50px;
    margin: 10px auto;
}

.event-list {
    list-style-type: disc;
    color: #b30059;
    text-align: left;
    padding-left: 20px;
}

.event-list li {
    margin: 5px 0;
}

```

### page3.css:

```
body {
    font-family: Arial, sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    margin: 0;
    background-color: #f5f5f5;
}

.registration-container {
    background: linear-gradient(to bottom, #f0e68c, #fdf5e6);
    padding: 30px;
    border-radius: 10px;
    width: 350px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

h2 {
    font-size: 24px;
    color: #b30000;
    margin-bottom: 20px;
}

p {
    font-size: 18px;
    color: #333;
    margin-bottom: 15px;
}

.registration-form {
    display: flex;
    flex-direction: column;
}

.registration-form input {
    margin: 10px 0;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
    background-color: #f0f0f5;
    font-size: 16px;
}

.registration-form input:focus {
    outline: none;
    border-color: #6e2b77;
}

.registration-form button {
    margin-top: 15px;
    padding: 10px;
    background-color: #6e2b77;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

.registration-form button:hover {
    background-color: #5a2360;
}
```
### page4.css:
```
body {
    font-family: Arial, sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    margin: 0;
    background-image: linear-gradient(to bottom, #e0f7fa, #b2ebf2);
    background-size: cover;
}

.thank-you-container {
    text-align: center;
    padding: 50px;
    background: rgba(255, 255, 255, 0.8);
    border-radius: 10px;
    width: 350px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

h2 {
    font-size: 28px;
    color: #b30000;
    margin-bottom: 20px;
}

p {
    font-size: 18px;
    color: #333;
    margin: 5px 0;
}

.contact-info p {
    margin: 8px 0;
    font-size: 16px;
    color: #444;
}

.contact-info b {
    font-weight: bold;
    color: #6e2b77;
}
```

## OUTPUT:
### PAGE 1:

![image](https://github.com/user-attachments/assets/247c382e-9bb2-42fc-8983-f700a434f1e0)


### PAGE 2:

![image](https://github.com/user-attachments/assets/47d54c75-6656-4e4e-b8e9-48d7e350ef03)


### PAGE 3:

![image](https://github.com/user-attachments/assets/b8c1dea2-28cf-424e-ac83-9ed51a78cc58)


### PAGE 4:

![image](https://github.com/user-attachments/assets/3767ea93-a250-411f-b585-2a821f36fd6e)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
