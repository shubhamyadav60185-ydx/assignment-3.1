Aim

To create a simple two-page website using HTML and CSS with working navigation links between the Home and About pages.

Requirements

Create two HTML files: index.html and about.html.

Add the website name and introduction to the Home page.

Create a navigation bar with Home and About links.

Connect both pages using the HTML anchor tag (<a href="">).

Add a link to an external website.

Use target="_blank" and rel="noopener noreferrer" for the external link.

Question 1: Create index.html and about.html

Create a folder named Assignment-3.1 and create these two files inside it.

File 1: index.html

Copy and paste the following code into index.html.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website - Home</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f7fb;
            color: #333;
        }

        header {
            background-color: #174ea6;
            color: white;
            text-align: center;
            padding: 25px;
        }

        nav {
            background-color: #123b7a;
            text-align: center;
            padding: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: yellow;
        }

        main {
            max-width: 800px;
            margin: 30px auto;
            padding: 25px;
            background-color: white;
            line-height: 1.8;
        }

        h2 {
            color: #174ea6;
        }

        footer {
            background-color: #123b7a;
            color: white;
            text-align: center;
            padding: 12px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Welcome to My Website</h1>
        <p>Learning Web Development Step by Step</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
    </nav>

    <main>
        <h2>Home Page</h2>

        <p>
            Hello! Welcome to my personal website.
            This website is created using HTML and CSS
            as part of my Web Development Assignment 3.1.
        </p>

        <p>
            I am learning how to create web pages,
            connect multiple pages, and use navigation
            links to make a website easy to use.
        </p>

        <h2>My Learning Goals</h2>

        <ul>
            <li>Learn HTML and CSS.</li>
            <li>Create attractive websites.</li>
            <li>Learn JavaScript.</li>
            <li>Improve my web development skills.</li>
        </ul>

        <h2>External Website</h2>

        <p>
            Click the following link to learn HTML:
        </p>

        <a href="https://www.w3schools.com/html/"
           target="_blank"
           rel="noopener noreferrer">
            Learn HTML at W3Schools
        </a>
    </main>

    <footer>
        <p>Copyright 2026 - My Website</p>
    </footer>

</body>
</html>

File 2: about.html

Copy and paste the following code into about.html.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website - About</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f7fb;
            color: #333;
        }

        header {
            background-color: #174ea6;
            color: white;
            text-align: center;
            padding: 25px;
        }

        nav {
            background-color: #123b7a;
            text-align: center;
            padding: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: yellow;
        }

        main {
            max-width: 800px;
            margin: 30px auto;
            padding: 25px;
            background-color: white;
            line-height: 1.8;
        }

        h2 {
            color: #174ea6;
        }

        footer {
            background-color: #123b7a;
            color: white;
            text-align: center;
            padding: 12px;
        }
    </style>
</head>

<body>

    <header>
        <h1>About My Website</h1>
        <p>Know More About This Project</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
    </nav>

    <main>
        <h2>About This Website</h2>

        <p>
            This is a simple two-page website developed
            using HTML and CSS. It contains a Home page
            and an About page connected through navigation
            links.
        </p>

        <h2>About Me</h2>

        <p>
            I am a B.Tech Computer Science student
            interested in programming, technology,
            and web development.
        </p>

        <h2>Technologies Used</h2>

        <ul>
            <li>HTML: Used to create the structure of web pages.</li>
            <li>CSS: Used to design and style the website.</li>
            <li>Anchor Tag: Used to connect different web pages.</li>
        </ul>

        <h2>Navigation</h2>

        <p>
            Users can move between the Home page and the
            About page by clicking the navigation links.
        </p>

        <p>
            The Home link opens index.html, while the
            About link opens about.html.
        </p>
    </main>

    <footer>
        <p>Copyright 2026 - My Website</p>
    </footer>

</body>
</html>

Question 2: Create the website name, introduction, and navigation bar

The website name is My Website. The Home page contains an introduction and learning goals. The navigation bar contains Home and About links.

Question 3: Add Home and About links

The following navigation code is used on both pages:

<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
</nav>

Question 4: Connect both pages using anchor tags

The href attribute connects the two HTML pages.

href="index.html" opens the Home page.

href="about.html" opens the About page.

Both pages are stored in the same folder, so the links work without additional paths.

Question 5: Add an external website link

The following code connects the website to W3Schools:

<a href="https://www.w3schools.com/html/"
   target="_blank"
   rel="noopener noreferrer">
    Learn HTML at W3Schools
</a>

Question 6: Explain target="_blank" and rel="noopener noreferrer"

target="_blank" opens the external website in a new browser tab.

rel="noopener noreferrer" improves security and privacy by preventing the opened page from accessing the original page through window.opener and by suppressing referrer information.

Question 7: Run and test the website

Save both files in the same folder.

Open index.html in a web browser or use Live Server in VS Code.

Click the About link to open the About page.

Click the Home link to return to the Home page.

Click the W3Schools link and check that it opens in a new tab.

Take screenshots of both pages after testing the links.

Result

A two-page website was successfully created using HTML and CSS. The Home and About pages are connected through working navigation links, and an external website link opens in a new tab with the appropriate security attributes.

Screenshot Submission

Attach the following screenshots after running the code:

Screenshot of the Home page in the browser.

Screenshot of the About page in the browser.

Optional screenshot showing the working external link.

Files to submit: index.html, about.html, and the screenshots of the working website.