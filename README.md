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

