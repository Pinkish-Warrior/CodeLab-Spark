# Challenge: Style Your First Webpage with CSS!

You've built the basic structure of your "About Me" page with HTML. Now it's time to make it look good using CSS!

## Your Goal

Take the `index.html` file you created in the HTML challenge and add some styling to it using CSS. Make it uniquely yours!

## Instructions

1.  **Locate Your `index.html`:**
    *   Find the `index.html` file you created earlier. You'll be working with this file again.

2.  **Create a New CSS File:**
    *   In the *same folder* as your `index.html` file, create a new file named `style.css`.
    *   Open `style.css` in your text editor. This is where all your styling rules will go.

3.  **Link Your CSS to Your HTML:**
    *   Open your `index.html` file.
    *   Inside the `<head>` section (after the `<title>` tag), add the following line. This tells your HTML page to use the `style.css` file for its looks:
    ```html
    <link rel="stylesheet" href="style.css">
    ```

4.  **Add Your Styling (in `style.css`):**
    *   Now, switch to your `style.css` file and start adding rules! Here are some ideas and requirements:

    *   **Body Background:** Change the background color of your entire page.
        ```css
        body {
            background-color: lightblue; /* Try other colors like #f0f0f0, #e6e6fa, or even 'beige' */
        }
        ```

    *   **Main Heading (`<h1>`):**
        *   Change its color.
        *   Change its font family (e.g., `font-family: Arial, sans-serif;`).
        *   Center the text.

    *   **Paragraphs (`<p>`):**
        *   Change the font size.
        *   Adjust the line height (e.g., `line-height: 1.5;`).

    *   **List of Hobbies (`<ul>` and `<li>`):**
        *   Change the color of the list items.
        *   Try removing the default bullet points (`list-style-type: none;` on the `<ul>`).

    *   **Image (`<img>`):**
        *   Give it a border (e.g., `border: 2px solid grey;`).
        *   Make it rounded (`border-radius: 8px;` or `border-radius: 50%;` for a circle!).

    *   **Links (`<a>`):**
        *   Change the link color.
        *   Remove the underline (`text-decoration: none;`).
        *   Add a hover effect (e.g., `a:hover { color: purple; }`).

5.  **Save and Refresh:**
    *   Save both your `index.html` and `style.css` files.
    *   Go back to your web browser and refresh the `index.html` page. You should see all your styles applied!

## Experiment and Have Fun!

CSS is all about creativity. Try different colors, fonts, sizes, and arrangements. Don't be afraid to break things and then fix them!

## Bonus Challenge

*   Add some space (padding or margin) around your elements.
*   Try to center your entire page content on the screen.
*   Make your "About Me" page look like a simple card.

---

## Example `style.css` Solution

Here's an example of what your `style.css` might look like. Remember, your `index.html` file should be the same as from the previous challenge.

```css
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f4f4f4; /* A light grey background */
    color: #333; /* Dark grey text color */
    margin: 20px; /* Some space around the page content */
}

h1 {
    color: #2c3e50; /* Dark blue/grey heading */
    text-align: center; /* Center the main title */
    margin-bottom: 25px;
}

h2 {
    color: #34495e; /* Slightly lighter blue/grey heading */
    border-bottom: 1px solid #ccc; /* A subtle line under hobbies */
    padding-bottom: 5px;
    margin-top: 30px;
}

p {
    font-size: 1.1em; /* Slightly larger paragraph text */
    line-height: 1.6; /* Good spacing between lines */
    margin-bottom: 15px;
}

ul {
    list-style-type: square; /* Change bullet style to squares */
    padding-left: 25px; /* Indent the list */
}

li {
    margin-bottom: 8px; /* Space between list items */
}

img {
    border: 3px solid #3498db; /* A nice blue border */
    border-radius: 10px; /* Slightly rounded corners */
    display: block; /* Makes image take up full width and allows margin auto */
    margin: 20px auto; /* Centers the image and adds vertical space */
    max-width: 150px; /* Ensures image doesn't get too big */
    height: auto;
}

a {
    color: #e74c3c; /* A red link color */
    text-decoration: none; /* Remove underline */
    font-weight: bold;
}

a:hover {
    color: #c0392b; /* Darker red on hover */
    text-decoration: underline; /* Add underline back on hover */
}
```

Good luck, and show off your beautifully styled page!