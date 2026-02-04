# Challenge: Build Your First HTML Page

Now that you've learned about HTML, it's time to put your knowledge into practice! This challenge will guide you through creating your very own simple webpage.

## Your Goal

Your goal is to create a personal "About Me" page using only HTML. It won't look fancy, and that's okay! The focus here is on using the correct HTML tags to structure the content.

## Instructions

1.  **Create a New File:**
    *   Somewhere on your computer (like your Desktop or in a new folder), create a new file named `index.html`.
    *   Open this file in a simple text editor (like Notepad on Windows or TextEdit on Mac).

2.  **Add the Basic HTML Structure:**
    *   Copy and paste the following boilerplate code into your `index.html` file. This provides the essential container for any webpage.
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <title>About Me</title>
    </head>
    <body>

    </body>
    </html>
    ```

3.  **Add Your Content:**
    *   Inside the `<body>` tags, you'll add the content for your page. Try to do this from memory first!
    *   **Add a main heading:** Use an `<h1>` tag for your name.
    *   **Add a short bio:** Use a `<p>` tag to write a sentence or two about yourself.
    *   **Add a list of hobbies:** Use an `<ul>` tag to create a bulleted list. Inside it, use `<li>` tags for at least three hobbies.
    *   **Add an image:** Use an `<img>` tag to add a picture. You can use a placeholder image for now. Use this URL for the `src` attribute: `https://via.placeholder.com/150`
    *   **Add a link:** Use an `<a>` tag to create a link to your favorite of the old websites we looked at. Don't forget the `href` attribute!

4.  **Save and View:**
    *   Save your `index.html` file.
    *   Find the file on your computer and double-click it. It should open in your web browser!

## Bonus Challenge

Can you add a sub-heading (like `<h2>` or `<h3>`) right above your list of hobbies that says "My Hobbies"?

---

## Example Solution

Stuck? That's okay! Here is a complete example of what your final code might look like. Try your best before you peek!

```html
<!DOCTYPE html>
<html>
<head>
    <title>About Me</title>
</head>
<body>

    <h1>I am Ada</h1>

    <p>I'm learning how to build websites and this is my very first page!</p>

    <h2>My Hobbies</h2>
    <ul>
        <li>Reading</li>
        <li>Hiking</li>
        <li>Watching movies</li>
    </ul>

    <img src="https://via.placeholder.com/150" alt="A placeholder image">

    <p>Here is a link to the original Space Jam website:</p>
    <a href="http://www.spacejam.com/1996/">Go to Space Jam!</a>

</body>
</html>
```

Once you've completed this challenge, you've officially created your first webpage! Great job!