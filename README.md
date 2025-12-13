Full documentation text for Week 1 – Task 1: -
________________________________________
Week 1 – Personal Portfolio Website
Project Documentation (Task 1)
1. Project Overview and Objectives
1.1 Project Description
This project is a simple personal portfolio website built with pure HTML. It was created as Week 1 – Task 1 for The Developers Arena Web Development Internship program.
The portfolio serves as the foundation for future weeks, where CSS styling (Week 2), JavaScript interactivity (Week 3), and responsive design (Week 4) will be progressively added.
1.2 Objectives
The main objectives of this Week 1 project are:
1.	Create a clean, well structured single page portfolio using only HTML5.
2.	Present key personal information in organized sections:
o	About/Bio section
o	Education details with semester wise results
o	Technical and soft skills
o	Hobbies and interests
o	Contact information
3.	Use semantic HTML elements (<header>, <main>, <section>, <footer>) to create a well organized code structure.
4.	Ensure the layout is clean and simple, providing a solid foundation for CSS styling in Week 2.
5.	Implement proper navigation with anchor links that will remain functional as the site evolves.
________________________________________
2. Setup and Installation Instructions
2.1 Prerequisites
•	A text editor (VS Code, Notepad++, Sublime Text, etc.)
•	A modern web browser (Chrome, Firefox, Safari, Edge)
•	Git (optional, for version control and GitHub Pages deployment)
2.2 Step by Step Installation
Option 1: Local Setup
1.	Create a project folder
Example:
o	Create a folder named my-portfolio.
o	Open it in your editor.
2.	Create the required folder structure
Inside my-portfolio, create:
o	index.html
o	README.md (optional but recommended)
o	images/ folder
3.	Create index.html and paste your HTML code
This file contains the complete Week 1 portfolio page.
4.	Add your profile image
o	Place your image inside the images/ folder.
o	Name it Rittik.jpg (or update the src path in the HTML).
o	Recommended size: at least 200x250 pixels.
5.	Open the website
o	Double click index.html, or
o	Right click → “Open with” → select your browser.
Option 2: GitHub Pages Deployment
1.	Initialize a Git repository
o	Open a terminal in your project folder.
o	Run:
	git init
	git add .
	git commit -m "Week 1: Personal Portfolio"
2.	Push to GitHub
o	Create a new repository on GitHub.
o	Add the remote and push:
	git remote add origin https://github.com/<username>/<repo>.git
	git branch -M main
	git push -u origin main
3.	Enable GitHub Pages
o	Go to your GitHub repository → Settings → Pages.
o	Select branch: main and folder: / (root).
o	Save.
o	After a few minutes, your site will be live at:
https://<username>.github.io/<repo>/
2.3 Project Structure
Final directory structure:
•	index.html – Main portfolio page
•	README.md – Project documentation (optional)
•	images/
o	Rittik.jpg – Profile image
________________________________________
3. Code Structure Explanation
3.1 HTML Document Organization
The entire Week 1 project is contained in a single index.html file. The logical structure is:
3.1.1 Document Head (<head>)
Example content:
•	<meta charset="UTF-8"> – Ensures proper text encoding (UTF 8).
•	<meta name="viewport" content="width=device-width, initial-scale=1"> – Basic mobile compatibility (more responsive work is done in Week 4).
•	<title>Rittik Chatterjee – Portfolio</title> – Sets the browser tab title.
3.1.2 Header Section (<header>)
Contains:
•	Main heading with your name, for example:
<h1>Rittik Chatterjee</h1>
•	Navigation menu using <nav> and <ul> with links:
o	#bio
o	#education
o	#skills
o	#contact
These anchor links allow users to jump to sections within the page.
3.1.3 Main Content (<main>)
The <main> element contains all primary sections of the portfolio:
1.	About Me Section (<section id="bio">)
o	A heading: <h2>About Me</h2>
o	Profile image:
<img src="images/Rittik.jpg" alt="Rittik Chatterjee">
o	A paragraph introducing you, your role, and interests.
2.	Education Section (<section id="education">)
o	A heading: <h2>Education</h2>
o	A <table> showing:
	Course
	Institution
	Year
	Percentage or GPA
o	Below the table, an unordered list (<ul>) with semester wise GPA and percentages.
3.	Skills Section (<section id="skills">)
o	A heading: <h2>Skills</h2>
o	Unordered list of technical skills, for example:
	HMI development
	Generative AI applications
	C programming basics
o	A subheading like <h3>Positive Skills</h3> with another list of soft skills.
o	A subheading like <h3>Hobbies</h3> with a list of hobbies.
4.	Contact Section (<section id="contact">)
o	A heading: <h2>Contact Me</h2>
o	A paragraph with:
	Email with mailto: link
	Phone number
	LinkedIn profile link (optionally with an icon in later weeks)
3.1.4 Footer (<footer>)
Typically includes:
•	Text such as: © 2025 Rittik Chatterjee. All rights reserved.
3.2 Key HTML Elements Used
Some of the key elements and their roles:
•	<header> – Top section containing the page title and navigation.
•	<nav> – Wraps the navigation menu.
•	<main> – Wraps the main content of the page.
•	<section> – Groups related content like About, Education, Skills, Contact.
•	<h1>, <h2>, <h3> – Headings that define page and section titles.
•	<table>, <tr>, <th>, <td> – Used for structured education data.
•	<ul>, <li> – Used for lists (skills, hobbies, semester results).
•	<img> – Displays the profile image.
•	<a> – Used for navigation links and external links (email, LinkedIn).
•	<footer> – Bottom section for copyright.
________________________________________
4. Screenshots of Working Application
4.1 How to Capture Screenshots
To include screenshots of your working portfolio:
1.	Open index.html in your browser.
2.	Make sure all sections are visible and content looks correct.
3.	Use your operating system’s screenshot tool:
o	Windows: Snipping Tool, Snip & Sketch, or Print Screen
o	macOS: Command + Shift + 4
o	Linux: Built in screenshot tool or Print Screen
4.	Save the images into the images/ folder with names like:
o	portfolio-desktop.png
o	portfolio-mobile.png (if you capture mobile view)
You can later embed these screenshots into a PDF or upload them separately if required.
4.2 What the Screenshots Should Show
Your screenshots should clearly display:
•	Header Section
o	Your name and the navigation menu.
•	About Me Section
o	Profile image and introductory paragraph.
•	Education Section
o	Education table with diploma, Class XII, and Class X details.
o	Semester wise results list.
•	Skills Section
o	Lists of technical skills, positive skills, and hobbies.
•	Contact Section
o	Email, phone number, and LinkedIn link.
•	Footer
o	Copyright.
________________________________________
5. Explanation of How Technical Requirements Were Met
5.1 Pure HTML Portfolio
•	The entire portfolio is built using only HTML5 in a single index.html file.
•	No CSS files or JavaScript files are required for Week 1.
•	This meets the requirement of creating a basic static site using pure HTML.
5.2 All Required Sections Present
The project includes all essential sections:
•	About Me / Bio
•	Education (with table and semester wise results)
•	Skills (technical, positive skills, hobbies)
•	Contact information (email, phone, LinkedIn)
•	A professional profile image in the About section
•	A header with navigation and a footer at the bottom
5.3 Semantic HTML Structure
•	Uses semantic containers: <header>, <main>, <section>, <footer>.
•	Uses appropriate heading levels: <h1> for the main title, <h2> for section headings, <h3> for subsections.
•	Uses <nav> for the navigation menu and <table> for structured education data.
•	Uses <ul> and <li> for lists, improving readability and accessibility.
•	This makes the portfolio easier to maintain and extend in later weeks.
5.4 Scalable for Future Weeks
•	The structure is ready for CSS in Week 2 (styling), JavaScript in Week 3 (interactivity), and responsive design in Week 4.
•	Section IDs like bio, education, skills, and contact are in place for easy styling and scripting.
•	The HTML layout does not need to change when new features are added.
5.5 GitHub Repository Structure
The project follows the required GitHub structure:
•	index.html – contains the Week 1 portfolio page.
•	README.md – can contain a summary of the project and instructions.
•	images/ – folder holds Rittik.jpg and any screenshots or other images.
This structure makes the project easy to host on GitHub Pages and simple for evaluators to review.
________________________________________


