# Ex09 Event Registration Web Application
# Date:
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
Homepage
<style>
.sports-day-container {
  background-color: #fff;
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  color: #000;
  text-align: center;
  margin: 0 auto;
  font: 400 36px Lalezar, sans-serif;
}

.content-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 956px;
  width: 100%;
  align-items: center;
  padding: 0 21px 161px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.logo-image {
  aspect-ratio: 3.53;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.event-title {
  position: relative;
  color: #8c6464;
  font-size: 40px;
  margin-top: 77px;
}

.action-button {
  position: relative;
  background-color: #6498b4;
  width: 211px;
  max-width: 100%;
  white-space: nowrap;
  border: 1px solid #000;
  cursor: pointer;
}

.login-button {
  composes: action-button;
  margin-top: 354px;
  padding: 2px 58px;
}

.register-button {
  composes: action-button;
  margin: 68px 0 -32px;
  padding: 2px 33px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="sports-day-container">
  <div class="content-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/568c2c7038414cc99a33edb90eca03e6/8d8f227a3c30ffa77a69ffc842b61db2d5cd1a77a30b01a31eeb5de0de5b50a9?apiKey=568c2c7038414cc99a33edb90eca03e6&"
      class="background-image"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/568c2c7038414cc99a33edb90eca03e6/1e9b8f6c35ba9ae10dcb1ea309a53abdb29901aa9b487c3e420565fb3ff03974?apiKey=568c2c7038414cc99a33edb90eca03e6&"
      class="logo-image"
      alt="Sports Day Events Logo"
    />
    <h1 class="event-title">SPORTS DAY EVENTS</h1>
    <button class="action-button login-button" tabindex="0">LOGIN</button>
    <button class="action-button register-button" tabindex="0">REGISTER</button>
  </div>
</div>

page2
<style>
  .sports-events-container {
    background-color: #fff;
    display: flex;
    max-width: 480px;
    width: 100%;
    flex-direction: column;
    overflow: hidden;
    color: #000;
    text-align: center;
    margin: 0 auto;
    font: 700 20px Lexend Deca, sans-serif;
  }
  .sports-content {
    display: flex;
    flex-direction: column;
    position: relative;
    min-height: 956px;
    width: 100%;
    align-items: start;
    padding: 99px 39px 368px;
  }
  .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
  }
  .main-title {
    position: relative;
    color: #742d3e;
    align-self: end;
    font: 400 36px Lalezar, sans-serif;
  }
  .sport-item {
    position: relative;
    display: flex;
    gap: 17px;
    white-space: nowrap;
  }
  .sport-indicator {
    background-color: #040101;
    border-radius: 50%;
    display: flex;
    width: 11px;
    height: 10px;
    margin: auto 0;
  }
  .sport-name {
    flex-basis: auto;
  }
  .mt-51 {
    margin-top: 51px;
  }
  .mt-45 {
    margin-top: 45px;
  }
  .mt-47 {
    margin-top: 47px;
  }
  .mt-48 {
    margin: 48px 0 -74px;
  }
  .gap-16 {
    gap: 16px;
  }
  .gap-12 {
    gap: 12px;
  }
  .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
  }
</style>

<div class="sports-events-container">
  <div class="sports-content">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/568c2c7038414cc99a33edb90eca03e6/005c3b6d0701be0299f0bbb2595df456c3c41676465486802cc303d4bf35b950?apiKey=568c2c7038414cc99a33edb90eca03e6&"
      alt="Sports day events background"
      class="background-image"
    />
    <h1 class="main-title">SPORTS DAY EVENTS</h1>
    <div class="sport-item mt-51">
      <span class="sport-indicator" role="presentation"></span>
      <div class="sport-name">FOOTBALL</div>
    </div>
    <div class="sport-item mt-45">
      <span class="sport-indicator" role="presentation"></span>
      <div class="sport-name">BASKET BALL</div>
    </div>
    <div class="sport-item mt-47 gap-16">
      <span class="sport-indicator" role="presentation"></span>
      <div class="sport-name">VOLLEYBALL</div>
    </div>
    <div class="sport-item mt-45">
      <span class="sport-indicator" role="presentation"></span>
      <div class="sport-name">SOCCER</div>
    </div>
    <div class="sport-item mt-47 gap-12">
      <span class="sport-indicator" role="presentation"></span>
      <div class="sport-name">CRICKET</div>
    </div>
    <div class="sport-item mt-48 gap-12">
      <span class="sport-indicator" role="presentation"></span>
      <div class="sport-name">JAVELIN THROW</div>
    </div>
  </div>
</div>

page3
<style>
.registration-container {
  background-color: rgba(161, 108, 108, 1);
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  color: #000;
  text-align: center;
  margin: 0 auto;
  font: 400 15px Lato, sans-serif;
}

.registration-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 956px;
  width: 100%;
  align-items: start;
  padding: 89px 37px 143px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.form-title {
  position: relative;
  color: rgba(88, 91, 64, 1);
  align-self: stretch;
  font: 32px Lalezar, sans-serif;
}

.input-field {
  position: relative;
  background-color: #fff;
  padding: 9px 15px;
}

.name-field {
  composes: input-field;
  margin-top: 44px;
  width: 283px;
}

.gender-field {
  composes: input-field;
  margin-top: 30px;
  width: 157px;
}

.age-field {
  composes: input-field;
  margin-top: 30px;
  width: 114px;
}

.register-number-field {
  composes: input-field;
  margin-top: 30px;
  width: 228px;
}

.department-field {
  composes: input-field;
  margin-top: 30px;
  width: 228px;
}

.mobile-field {
  composes: input-field;
  margin-top: 30px;
  width: 246px;
}

.email-field {
  composes: input-field;
  margin-top: 30px;
  width: 283px;
}

.events-field {
  composes: input-field;
  margin-top: 30px;
  width: 283px;
}

.submit-button {
  position: relative;
  z-index: 10;
  background-color: rgba(152, 183, 113, 1);
  align-self: center;
  width: 268px;
  color: rgba(79, 89, 67, 1);
  margin: 96px 0 -29px;
  padding: 0 38px;
  font: 48px Lalezar, sans-serif;
  border: none;
  cursor: pointer;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="registration-container">
  <div class="registration-wrapper">
    <img
      class="background-image"
      src="https://cdn.builder.io/api/v1/image/assets/568c2c7038414cc99a33edb90eca03e6/9f540d435810eb107fc613158c1adcd1955f8b7d82ce26d5a1a8c84ee99a67bd?apiKey=568c2c7038414cc99a33edb90eca03e6&"
      alt=""
      loading="lazy"
    />
    <h1 class="form-title">EVENT REGISTRATION FORM</h1>
    <form>
      <label for="fullName" class="visually-hidden">Full Name</label>
      <input type="text" id="fullName" class="name-field" placeholder="FULL NAME" required />

      <label for="gender" class="visually-hidden">Gender</label>
      <select id="gender" class="gender-field" required>
        <option value="">GENDER</option>
        <option value="male">Male</option>
        <option value="female">Female</option>
        <option value="other">Other</option>
      </select>

      <label for="age" class="visually-hidden">Age</label>
      <input type="number" id="age" class="age-field" placeholder="AGE" required />

      <label for="regNumber" class="visually-hidden">Register Number</label>
      <input type="text" id="regNumber" class="register-number-field" placeholder="REGISTER NUMBER" required />

      <label for="department" class="visually-hidden">Department</label>
      <input type="text" id="department" class="department-field" placeholder="DEPARTMENT" required />

      <label for="mobile" class="visually-hidden">Mobile Number</label>
      <input type="tel" id="mobile" class="mobile-field" placeholder="MOBILE NUMBER" required />

      <label for="email" class="visually-hidden">Email ID</label>
      <input type="email" id="email" class="email-field" placeholder="EMAIL ID" required />

      <label for="events" class="visually-hidden">Events to Register</label>
      <select id="events" class="events-field" required>
        <option value="">EVENTS TO BE REGISTER</option>
      </select>

      <button type="submit" class="submit-button">REGISTER</button>
    </form>
  </div>
</div>

page4
<div class="thank-you-container">
  <div class="content-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/568c2c7038414cc99a33edb90eca03e6/305b1f71c603f596a3d3611c31d11e96bb77f3ef5063721444777c2a2aad9824?apiKey=568c2c7038414cc99a33edb90eca03e6&"
      class="background-image"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/568c2c7038414cc99a33edb90eca03e6/405bf4a6a0336098c4c7f5219ddd30dff23c77aff2bfc9da382d55204b669633?apiKey=568c2c7038414cc99a33edb90eca03e6&"
      class="header-image"
      alt=""
    />
    <h1 class="title">THANK YOU</h1>
    <p class="message">
      We're excited to have you join us for a day of fun, fitness, and friendly
      competition. Get ready to make amazing memories!&quot;
    </p>
    <h2 class="contact-title">CONTACT US</h2>
    <div class="contact-info">
      <p class="email">EMAIL: sportsday@college.edu</p>
      <p class="phone">Phone: +123-456-7890</p>
      <p class="address">
        Venue: Saveetha Engineering College, Thandalam, Chennai
      </p>
    </div>
  </div>
</div>

<style>
.thank-you-container {
  background: #fff;
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  font-size: 16px;
  color: #000;
  font-weight: 400;
  text-align: center;
  margin: 0 auto;
}

.content-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 956px;
  width: 100%;
  align-items: center;
  padding: 0 15px 110px 0;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.header-image {
  aspect-ratio: 3.48;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.title {
  position: relative;
  margin-top: 210px;
  font: 40px Moul, sans-serif;
}

.message {
  position: relative;
  font-family: Merge One, sans-serif;
  margin-top: 40px;
}

.contact-title {
  position: relative;
  color: #3d3231;
  margin-top: 228px;
  font: 24px Odor Mean Chey, sans-serif;
}

.contact-info {
  position: relative;
  align-self: start;
  display: flex;
  width: 295px;
  max-width: 100%;
  flex-direction: column;
  align-items: start;
  font-family: Amethysta, sans-serif;
  margin: 28px 0 -22px 11px;
}

.phone {
  margin-top: 18px;
}

.address {
  align-self: stretch;
  margin-top: 18px;
}
</style>
```
# OUTPUT:

![image](https://github.com/user-attachments/assets/770a02b6-9de4-450f-bd50-c4ea31546e99)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
