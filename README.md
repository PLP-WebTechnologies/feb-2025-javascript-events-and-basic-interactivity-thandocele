# 🎯 JavaScript Event Handling & Interactive Elements Assignment

Welcome to the **ultimate JavaScript playground**! 🎉 This assignment is where we turn boring web pages into dynamic, responsive, *alive* experiences. Get ready to master **event handling**, build **interactive components**, and validate forms like a pro! 💪

## 📁 Assignment Structure

```
📂 js-event-assignment/
├── index.html         # Your playground – where it all comes together
├── style.css          # Keep it cute (optional but encouraged)
└── script.js          # The JavaScript wizardry happens here
```

---

## 🧪 What to Build

Here’s what your interactive bundle of joy should include:

### 1. Event Handling 🎈  
- Button click ✅  
- Hover effects ✅  
- Keypress detection ✅  
- Bonus: A secret action for a *double-click* or *long press* 🤫

### 2. Interactive Elements 🎮  
- A button that changes text or color  
- An image gallery or slideshow  
- Tabs or accordion-style content  
- Bonus: Add some animation using JS or CSS ✨

### 3. Form Validation 📋✅  
- Required field checks  
- Email format validation  
- Password rules (e.g., min 8 characters)  
- Bonus: Real-time feedback while typing

---

## 🧙‍♂️ Pro Tips

- Keep your code clean and commented – your future self will thank you!
- Think about **user experience** – what makes your site more *fun* to use?
- Don’t be afraid to **Google and experiment** – that’s how real developers roll!

---

## 🎉 Now Go Make It Fun!

Remember – this isn't just code. It's your **first step toward creating magical user experiences**. So play around, break stuff (then fix it), and most of all, have FUN! 😄

Happy Coding! 💻✨  


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JS Event Assignment</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>🎉 JavaScript Playground</h1>

  <!-- Event Buttons -->
  <section>
    <h2>Event Handling</h2>
    <button id="clickMe">Click Me!</button>
    <button id="hoverMe">Hover Over Me!</button>
    <button id="dblClickMe">Double Click Me!</button>
    <p id="keyPressOutput">Press any key...</p>
  </section>

  <!-- Interactive Elements -->
  <section>
    <h2>Interactive Elements</h2>

    <!-- Color Changer -->
    <button id="colorChanger">Change My Color</button>

    <!-- Image Gallery -->
    <div class="gallery">
      <img id="galleryImage" src="https://via.placeholder.com/300" alt="Gallery">
      <br>
      <button id="prevBtn">Previous</button>
      <button id="nextBtn">Next</button>
    </div>

    <!-- Tabs -->
    <div class="tabs">
      <button class="tab" data-tab="1">Tab 1</button>
      <button class="tab" data-tab="2">Tab 2</button>
      <div id="tab1" class="tab-content">This is Tab 1 content.</div>
      <div id="tab2" class="tab-content">This is Tab 2 content.</div>
    </div>
  </section>

  <!-- Form -->
  <section>
    <h2>Form Validation</h2>
    <form id="signupForm">
      <label>
        Email:
        <input type="email" id="email" required>
        <span class="feedback" id="emailFeedback"></span>
      </label>
      <br>
      <label>
        Password:
        <input type="password" id="password" required>
        <span class="feedback" id="passwordFeedback"></span>
      </label>
      <br>
      <button type="submit">Submit</button>
    </form>
  </section>

  <script src="script.js"></script>
</body>
</html>

