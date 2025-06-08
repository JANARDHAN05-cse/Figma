# Ex09 Event Registration Web Application
## Date: 08.05.2025 

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page 1</title>
</head>
<body>
    <div class="container">
  <div class="login-header">
    <div class="title">LOGIN</div>
  </div>

  <div class="section-title">EVENT REGISTRATION</div>
  <div class="section-title">GAME & SPORTS</div>

  <div class="form-container">
    <div class="input-group">
      <label class="input-label">Email</label>
      <div class="input-box">
        <input type="email" placeholder="Enter your email" />
      </div>
    </div>

    <div class="input-group">
      <label class="input-label">Password</label>
      <div class="input-box">
        <input type="password" placeholder="Enter your password" />
      </div>
    </div>

    <div class="checkbox-group">
      <div class="checkbox">
        <svg
          width="16"
          height="16"
          viewBox="0 0 16 16"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <g clip-path="url(#clip0)">
            <path
              d="M0 4C0 1.79086 1.79086 0 4 0H12C14.2091 0 16 1.79086 16 4V12C16 14.2091 14.2091 16 12 16H4C1.79086 16 0 14.2091 0 12V4Z"
              fill="#2C2C2C"
            />
            <path
              d="M13.3333 4L6 11.3333L2.66666 8"
              stroke="#F5F5F5"
              stroke-width="1.6"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
          </g>
          <defs>
            <clipPath id="clip0">
              <path
                d="M0 4C0 1.79086 1.79086 0 4 0H12C14.2091 0 16 1.79086 16 4V12C16 14.2091 14.2091 16 12 16H4C1.79086 16 0 14.2091 0 12V4Z"
                fill="white"
              />
            </clipPath>
          </defs>
        </svg>
        <span class="checkbox-label">Label</span>
      </div>
      <div class="checkbox-description">Description</div>
    </div>

    <div class="submit-button">
      <button type="submit">Register</button>
    </div>
  </div>

  <img src="background.img" alt="Background Image" />

  <svg
    width="437"
    height="113"
    viewBox="0 0 437 113"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect
      opacity="0.2"
      x="-7"
      width="444"
      height="113"
      rx="20"
      fill="url(#paint0_linear)"
    />
    <defs>
      <linearGradient
        id="paint0_linear"
        x1="-7"
        y1="56.5"
        x2="437"
        y2="56.5"
        gradientUnits="userSpaceOnUse"
      >
        <stop stop-color="#D9D9D9" />
        <stop offset="1" stop-color="#002BD5" />
      </linearGradient>
    </defs>
  </svg>
</div>

</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Page 2</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    .container {
      padding: 20px;
    }
    .text {
      margin: 10px 0;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Top Bar -->
    <svg width="440" height="49" viewBox="0 0 440 49" fill="none" xmlns="http://www.w3.org/2000/svg">
      <rect width="440" height="49" fill="#D9D9D9"></rect>
    </svg>

    <!-- Back Arrow Icon -->
    <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M13.0417 21.6667L22.375 31L20 33.3333L6.66666 20L20 6.66666L22.375 9L13.0417 18.3333H33.3333V21.6667H13.0417Z" fill="#1D1B20"/>
    </svg>

    <!-- Header Text -->
    <div class="text">EVENTS</div>

    <!-- Decorative Circle -->
    <svg width="45" height="45" viewBox="0 0 45 45" fill="none" xmlns="http://www.w3.org/2000/svg">
      <rect width="45" height="45" rx="20" fill="#D9D9D9" />
    </svg>

    <!-- Further Process Button -->
    <div class="container-0-1-10">
      <div class="text">FURTHER PROCESS</div>
    </div>

    <!-- Forward Arrow Icon -->
    <svg width="41" height="40" viewBox="0 0 41 40" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M27.6323 21.6667H6.83331V18.3334H27.6323L18.0656 9.00002L20.5 6.66669L34.1666 20L20.5 33.3334L18.0656 31L27.6323 21.6667Z" fill="#1D1B20" />
    </svg>

    <!-- Event Items -->
    <div class="container-0-1-12">
      <div class="text">CHESS<br />MAXIMUM CAPACITY: 30 PLAYERS</div>
    </div>

    <div class="container-0-1-13">
      <div class="text">CRICKET<br />11 PLAYERS FOR EACH TEAM</div>
    </div>

    <div class="container-0-1-14">
      <div class="text">FOOTBALL<br />11 PLAYERS FOR EACH TEAM</div>
    </div>

    <div class="container-0-1-15">
      <div class="text">RUBIK'S CUBE<br />MAXIMUM CAPACITY: 20</div>
    </div>

    <div class="container-0-1-16">
      <div class="text">BADMINTON<br />MAXIMUM CAPACITY: 20 PLAYERS</div>
    </div>

    <!-- Bottom Bar -->
    <svg width="440" height="95" viewBox="0 0 440 95" fill="none" xmlns="http://www.w3.org/2000/svg">
      <rect opacity="0.2" width="440" height="95" fill="#D9D9D9"></rect>
    </svg>

    <!-- Menu Icon -->
    <svg width="43" height="35" viewBox="0 0 43 35" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M5.375 26.25V23.3333H37.625V26.25H5.375ZM5.375 18.9583V16.0417H37.625V18.9583H5.375ZM5.375 11.6667V8.75H37.625V11.6667H5.375Z" fill="#1D1B20" />
    </svg>
  </div>
</body>
</html>

```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page 4</title>
</head>
<body>
    <div class="container--0-">
  <svg
    width="339"
    height="456"
    viewBox="0 0 339 456"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      opacity="0.2"
      d="M0 10C0 4.47715 4.47715 0 10 0H329C334.523 0 339 4.47715 339 10V446C339 451.523 334.523 456 329 456H10C4.47715 456 0 451.523 0 446V236.951V10Z"
      fill="url(#paint0_linear_21_569)"
    ></path>
    <defs>
      <linearGradient
        id="paint0_linear_21_569"
        x1="169.5"
        y1="0"
        x2="169.5"
        y2="456"
        gradientUnits="userSpaceOnUse"
      >
        <stop stop-color="#D9D9D9"></stop>
        <stop offset="0.519231"></stop>
      </linearGradient>
    </defs></svg
  ><svg
    width="255"
    height="62"
    viewBox="0 0 255 62"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      opacity="0.8"
      d="M0 15C0 6.71573 6.71573 0 15 0H240C248.284 0 255 6.71573 255 15V47C255 55.2843 248.284 62 240 62H15C6.71573 62 0 55.2843 0 47V15Z"
      fill="#D9D9D9"
    ></path></svg
  ><svg
    width="255"
    height="62"
    viewBox="0 0 255 62"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      opacity="0.8"
      d="M0 15C0 6.71573 6.71573 0 15 0H240C248.284 0 255 6.71573 255 15V47C255 55.2843 248.284 62 240 62H15C6.71573 62 0 55.2843 0 47V15Z"
      fill="#D9D9D9"
    ></path></svg
  ><svg
    width="255"
    height="62"
    viewBox="0 0 255 62"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      opacity="0.8"
      d="M0 15C0 6.71573 6.71573 0 15 0H240C248.284 0 255 6.71573 255 15V47C255 55.2843 248.284 62 240 62H15C6.71573 62 0 55.2843 0 47V15Z"
      fill="#D9D9D9"
    ></path>
  </svg>
  <div class="text-0-1-4">NAME</div>
  <div class="text-0-1-5">AGE</div>
  <div class="text-0-1-6">ENTER YOU SPORT/GAME</div>
  <div class="container-0-1-7"><div class="text-1-2-1">REGISTER</div></div>
  <img
    src="background.img"
  />
</div>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page 4</title>
</head>
<body>
    <div class="container--0-">
  <svg
    width="344"
    height="506"
    viewBox="0 0 344 506"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect opacity="0.2" width="344" height="506" rx="34" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-1">
    THANK YOU<br /><br />FOR <br /><br />REGISTER<br /><br />
    IN SAVEETHA <br />
    <br />SPORTS/GAMES
  </div>
  <svg
    width="240"
    height="60"
    viewBox="0 0 240 60"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect
      opacity="0.8"
      width="240"
      height="60"
      rx="10"
      fill="#D9D9D9"
    ></rect></svg>
  <svg
    width="48"
    height="48"
    viewBox="0 0 48 48"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M18 44V24H30V44M6 18L24 4L42 18V40C42 41.0609 41.5786 42.0783 40.8284 42.8284C40.0783 43.5786 39.0609 44 38 44H10C8.93913 44 7.92172 43.5786 7.17157 42.8284C6.42143 42.0783 6 41.0609 6 40V18Z"
      stroke="#1E1E1E"
      stroke-width="4"
      stroke-linecap="round"
      stroke-linejoin="round"
    ></path>
  </svg>
  <div class="text-0-1-4">HOME</div>
</div>
</body>
</html>
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/6c9e445e-5577-479e-9918-53c1a4812576)
![image](https://github.com/user-attachments/assets/0a57e991-dce3-4076-9679-3383a17999ff)
![image](https://github.com/user-attachments/assets/ee0742d9-a939-4f29-a7d8-b3edbe81550d)
![image](https://github.com/user-attachments/assets/7548daf1-6cb0-4e72-a8e1-812a7b8cffa3)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
