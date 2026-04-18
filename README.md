# Cognifyz Web Development Internship
## Level 1 — Task 2 (JavaScript)

**Intern Name:** Raj Rakshit Sahoo
**Internship:** Cognifyz Technologies — Web Development
**Level:** 1
**Task:** Task 2 — JavaScript

---

## 📁 Project Structure

```
cognifyz_task2/
├── task2a_colorbutton.html   → Button that changes color on click
├── task2b_greeting.html      → Alert box with time-based greeting
├── task2c_calculator.html    → Basic calculator that adds two numbers
└── README.md                 → Project documentation
```

---

## 🏷️ Languages Used Per File

| File | HTML | CSS | JavaScript |
|------|------|-----|------------|
| `task2a_colorbutton.html` | ✅ Yes | ✅ Yes | ✅ Yes — color change logic |
| `task2b_greeting.html` | ✅ Yes | ✅ Yes | ✅ Yes — time detection & alert |
| `task2c_calculator.html` | ✅ Yes | ✅ Yes | ✅ Yes — addition & result display |

> **Note:** All three files use HTML for structure, CSS for styling, and JavaScript for the interactive functionality required by the task.

---

## ✅ Task 2a — Color Change Button
**File:** `task2a_colorbutton.html`
**Languages Used: HTML, CSS & JavaScript**

**What HTML does in this file:**
- Creates the button using `<button>` tag with an `onclick` attribute
- Displays the color hex value using a `<span>` tag
- Shows the color swatch using a `<div>` element
- Displays the click counter using a `<p>` tag

**What CSS does in this file:**
- Styles the button with background color, padding, and border-radius
- Adds a smooth color transition using `transition: background 0.4s`
- Creates a hover glow effect using `box-shadow`
- Styles the color swatch as a circle using `border-radius: 50%`
- Adds a bounce animation on click using `transform: scale()`

**What JavaScript does in this file:**
- Stores 10 colors in an **array**
- Uses the **modulo operator** (`%`) to cycle through colors endlessly
- Updates `button.style.background` with the new color on each click
- Updates the color hex text using `getElementById` and `textContent`
- Increments and displays the click counter variable

---

## ✅ Task 2b — Time-Based Greeting Alert
**File:** `task2b_greeting.html`
**Languages Used: HTML, CSS & JavaScript**

**What HTML does in this file:**
- Creates the greeting button using `<button>` tag
- Displays the live clock in a `<div>` with a heading structure
- Shows the greeting message in a styled `<div>` box
- Lists all time period rows in a schedule table using `<div>` rows

**What CSS does in this file:**
- Styles the dark blue themed background and card
- Adds a warm yellow ambient glow behind the card using `radial-gradient`
- Styles the live clock with large `JetBrains Mono` monospace font
- Styles each time period badge (morning/afternoon/evening/night) with different colors
- Highlights the active schedule row with a background color change

**What JavaScript does in this file:**
- Uses `new Date()` and `getHours()` to get the **current hour**
- Uses `if / else if / else` to decide which greeting to show based on the hour:

| Time Range | Greeting |
|------------|----------|
| 5:00 AM – 11:59 AM | "Good Morning! Rise and shine! ☀️" |
| 12:00 PM – 4:59 PM | "Good Afternoon! Hope your day is going great! 😊" |
| 5:00 PM – 8:59 PM | "Good Evening! Time to relax and unwind! 🌇" |
| 9:00 PM – 4:59 AM | "Good Night! Sweet dreams! 🌙" |

- Calls `alert()` to show the greeting in a **browser pop-up box**
- Uses `setInterval()` to update the live clock every 1 second

---

## ✅ Task 2c — Basic Calculator
**File:** `task2c_calculator.html`
**Languages Used: HTML, CSS & JavaScript**

**What HTML does in this file:**
- Creates two number inputs using `<input type="number">` tags
- Adds the Calculate button using `<button>` tag
- Adds a Clear button to reset all fields
- Displays the result in a styled `<div>` display area
- Shows calculation history as a list of `<div>` items

**What CSS does in this file:**
- Styles the dark blue themed background and card layout
- Styles both input fields with monospace font and focus glow effect
- Styles the Calculate button in blue and the Clear button in a neutral style
- Adds a slide-in animation for each new history item using `@keyframes`
- Uses Flexbox to place both inputs side by side with the `+` operator in the middle

**What JavaScript does in this file:**
- Reads input values using `.value` from both input fields
- Converts string inputs to numbers using `parseFloat()`
- Performs **addition** using the `+` operator
- Displays the result dynamically using `textContent`
- Stores the last 5 calculations in an **array** and renders them as history
- Listens for the **Enter key** using `addEventListener('keydown')` to trigger calculation

---

## 🛠️ How to Run

1. **Extract** the ZIP file to a folder
2. Open the folder in **VS Code**
3. Install the **Live Server** extension (by Ritwick Dey) if not installed
4. **Right-click** any `.html` file → click **"Open with Live Server"**

**OR** simply double-click any `.html` file to open it directly in your browser.

---

## 🌐 Browser Compatibility

| Browser | Status |
|---------|--------|
| Google Chrome | ✅ Supported |
| Microsoft Edge | ✅ Supported |
| Mozilla Firefox | ✅ Supported |
| Safari | ✅ Supported |

---

## 📝 Notes

- All code is **original** and written from scratch
- No external JavaScript libraries or frameworks were used
- All JavaScript is written inline within each HTML file
- Google Fonts loaded via CDN for typography

---

*Submitted as part of the Cognifyz Technologies Web Development Internship Program.*
