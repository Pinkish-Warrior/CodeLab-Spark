# Challenge: Bring Your Page to Life with JavaScript!

You've built a structured page with HTML and styled it with CSS. Now it's time for the final piece of the puzzle: adding interactivity with JavaScript!

## Your Goal

You will add a "Dark Mode" toggle button to your "About Me" page. When you click the button, the page will switch between a light and dark theme. This is a classic beginner project that teaches you the fundamentals of JavaScript.

## Instructions

1.  **Locate Your Project Files:**
    *   Find your `index.html` and `style.css` files from the previous challenges.

2.  **Create Your JavaScript File:**
    *   In the *same folder*, create a new file named `script.js`. This is where your JavaScript code will live.

3.  **Add a Button to Your HTML:**
    *   Open `index.html`. Somewhere on your page (a good spot is right after the `<h1>` tag), add a button. Give it an `id` so JavaScript can find it easily.
    ```html
    <button id="theme-toggle">Toggle Dark Mode</button>
    ```

4.  **Link Your JavaScript File:**
    *   In your `index.html` file, go all the way to the bottom. Just before the closing `</body>` tag, add the following line. We put it here to make sure the HTML is fully loaded before the script tries to interact with it.
    ```html
    <script src="script.js"></script>
    ```

5.  **Add the "Dark Mode" Style to Your CSS:**
    *   Open `style.css`. You need to tell the page what to look like when it's in dark mode. Add the following CSS class at the end of your file. This style will only be applied when the `<body>` element has the class `dark-mode`.
    ```css
    .dark-mode {
        background-color: #2c3e50; /* A dark background */
        color: #ecf0f1; /* A light text color */
    }
    ```
    *   You might need to adjust this if you want your links, headings, etc., to have different colors in dark mode. For example:
    ```css
    .dark-mode h1 {
        color: #95a5a6;
    }
    ```

6.  **Write the JavaScript! (in `script.js`)**
    *   This is where the magic happens. Open `script.js` and write the following code. Read the comments to understand what each line does.

    ```javascript
    // Step 1: Find the button element on the page by its id.
    const themeToggleButton = document.getElementById('theme-toggle');

    // Step 2: Find the body element.
    const body = document.body;

    // Step 3: Add a 'click' event listener to the button.
    // This tells the button to run a function whenever it's clicked.
    themeToggleButton.addEventListener('click', function() {
        
        // Step 4: Inside the function, toggle the 'dark-mode' class on the body.
        // .toggle() is a special method that adds the class if it's not there,
        // and removes it if it is. It's perfect for a switch!
        body.classList.toggle('dark-mode');

        // You can also add an alert to confirm it's working!
        // alert('Button was clicked!');
    });
    ```

7.  **Save and Test:**
    *   Save all three files (`index.html`, `style.css`, and `script.js`).
    *   Open `index.html` in your browser and refresh the page.
    *   Click your "Toggle Dark Mode" button. If everything is set up correctly, your page should switch between your light and dark themes!

## Bonus Challenge

Can you make the button text change depending on the mode? For example, when you switch to dark mode, can you make the button say "Toggle Light Mode"? (Hint: You'll need an `if` statement inside your `click` function to check if the body `classList.contains('dark-mode')`).

---

## Example `script.js` Solution (with Bonus)

```javascript
const themeToggleButton = document.getElementById('theme-toggle');
const body = document.body;

themeToggleButton.addEventListener('click', function() {
    body.classList.toggle('dark-mode');

    // Bonus Challenge part:
    if (body.classList.contains('dark-mode')) {
        // We are in dark mode, so the button should say "Toggle Light Mode"
        themeToggleButton.textContent = 'Toggle Light Mode';
    } else {
        // We are in light mode, so the button should say "Toggle Dark Mode"
        themeToggleButton.textContent = 'Toggle Dark Mode';
    }
});
```

Congratulations! You've now used HTML, CSS, and JavaScript together to create a fully structured, styled, and interactive webpage.