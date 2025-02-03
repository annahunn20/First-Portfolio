# First-Portfolio
First Attempt at a Portfolio Using HTML, CSS, and JavaScript

index.html
1. HTML Boilerplate (<!DOCTYPE html> - </html>)
This defines the document structure and ensures proper rendering in web browsers.

<!DOCTYPE html> → Declares HTML5.
<html lang="en"> → Specifies English as the document language.
<head> → Contains metadata (not visible on the page).
<body> → Holds all the content displayed on the webpage.

2. Head Section (<head> - </head>)
Contains essential metadata and linked resources.
<meta charset="UTF-8"> → Supports special characters and multiple languages.
<meta name="viewport" content="width=device-width, initial-scale=1.0">
Makes the site responsive on all devices.
<title>My Portfolio</title>
Sets the webpage title (visible on the browser tab).
<link rel="stylesheet" href="style.css">
Links an external CSS file (style.css) for styling.

3. Header Section (<header> - </header>)
Displays the portfolio title: "Anika's Portfolio".
<h1>Anika's Portfolio</h1> → Main heading (largest text).

4. About Me Section (<section id="about"> - </section>)
Introduces you and your background.
<h2>About Me</h2> → Section heading.
<p>I'm a second-year Computer Science student at KIIT Bhubaneswar, passionate about software development, AI, and web technologies.</p>
Paragraph describing you.

5. Skills Section (<section id="skills"> - </section>)
Lists your programming skills.
<h2>Skills</h2> → Section heading.
<ul> → Creates an unordered (bulleted) list.
<li>C, Java</li> → Skill #1.
<li>HTML, CSS, JavaScript (learning stage)</li> → Skill #2 with a note.

6. Contact & Socials Section (<section id="contact"> - </section>)
Displays social media links for LinkedIn and GitHub.
<h2>Contact & Socials</h2> → Section heading.
<a href="https://www.linkedin.com/in/anika-gangwar-3a10772b1/" target="_blank">LinkedIn</a>
Clickable link to your LinkedIn profile (target="_blank" opens in a new tab).
<a href="https://github.com/annahunn20/Leetcode/tree/main" target="_blank">GitHub</a>
Clickable link to your GitHub repository.
Correction:
Your target attributes should be target="_blank" (instead of target="URL").

7. JavaScript File Link (<script src="script.js"></script>)
Links an external JavaScript file (script.js) for adding interactive behavior.
Currently, your script.js is empty, but you can use it to add animations, buttons, or effects.

style.css
---
1. Global Styles (`body`)
```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #121212;
    color: white;
    text-align: center;
}
```
Explanation:
- `font-family: Arial, sans-serif;` → Uses **Arial** as the default font and falls back to a generic sans-serif if Arial is unavailable.
- `margin: 0; padding: 0;` → Removes default browser margins and padding.
- `background-color: #121212;` → Sets a dark background color (blackish-gray).
- `color: white;` → Makes all text **white** for contrast.
- `text-align: center;` → Centers all text horizontally.

---

2. Header Styling (`header`)
```css
header {
    background-color: #1f1f1f;
    padding: 20px;
    font-size: 24px;
}
```
Explanation:
- `background-color: #1f1f1f;` → Sets a slightly lighter dark background for the **header**.
- `padding: 20px;` → Adds space inside the header to make it more visually appealing.
- `font-size: 24px;` → Increases the header text size.

---

3. Section Styling (`section`)
```css
section {
    margin: 20px;
    padding: 20px;
    background-color: #1c1c1c;
    border-radius: 10px;
    display: inline-block;
    width: 80%;
}
```
Explanation:
- `margin: 20px;` → Adds space around each section.
- `padding: 20px;` → Adds space inside each section for better readability.
- `background-color: #1c1c1c;` → Sets a slightly lighter **dark gray** background.
- `border-radius: 10px;` → Rounds the corners for a smooth look.
- `display: inline-block;` → Ensures the sections don’t take the full width but still fit well.
- `width: 80%;` → Makes the section width **80% of the screen** for a balanced layout.

---

4. Unordered List Styling (`ul`)
```css
ul {
    list-style-type: none;
    padding: 0;
}
```
Explanation:
- `list-style-type: none;` → Removes default bullet points from the **unordered list**.
- `padding: 0;` → Removes extra padding to keep things clean.

---

5. Link (Button-like) Styling (`a`)
```css
a {
    display: block;
    margin: 10px;
    padding: 10px;
    background-color: #007bff;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}
```
Explanation:
- `display: block;` → Makes each link a **block element** (so each link appears on a new line).
- `margin: 10px;` → Adds space between each link.
- `padding: 10px;` → Makes the clickable area **larger and easier to tap**.
- `background-color: #007bff;` → Sets the link background to **blue**.
- `color: white;` → Makes text **white** for contrast.
- `text-decoration: none;` → Removes the default underline from links.
- `border-radius: 5px;` → Rounds the corners for a modern button-like look.

---

6. Link Hover Effect (`a:hover`)
```css
a:hover {
    background-color: #0056b3;
}
```
Explanation:
- `background-color: #0056b3;` → When a user **hovers over** a link, the background turns into a **darker shade of blue** for a smooth effect.
