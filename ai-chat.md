 AI Chat Log – Personal Website Development (SITE 1101)

 User:
I need to create a personal portfolio website for my SITE 1101 course. What pages should my website include?

AI:
For a personal portfolio website, you should include:
- A Home page with a profile photo and short introduction
- An About page describing your background, education, and interests
- A Projects page showcasing your work with titles, descriptions, and images  
You can also add extra pages such as a resume or blog if you want.

---

User:
How should I structure my project files to keep the code clean and organized?

AI:
You should organize your files in a modular way. For example:

/cv
/css
style.css
/images
index.html
about.html
projects.html

This structure makes the project easier to maintain and understand.

---

User:
How should I design the Home page of my website?

AI:
The Home page should include your profile image, name, a short description, and navigation links.

Example HTML structure:
```html
<section class="home">
  <img src="images/profile.jpg" alt="Profile Photo">
  <h1>Shahsanam</h1>
  <p>IT student interested in web development and design.</p>
</section>

User:

How can I create a navigation bar that appears on all pages?

AI:

You can reuse the same navigation bar HTML code on each page.

<nav>
  <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
    <li><a href="projects.html">Projects</a></li>
  </ul>
</nav>


This ensures consistent navigation throughout the website.

⸻

User:

How can I make my website responsive for mobile and tablet screens?

AI:

You can use CSS media queries and flexible layouts such as Flexbox.


@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
  }

  .home img {
    width: 150px;
  }
}


This helps the website adapt to smaller screen sizes.

⸻

User:

Why is responsive design important?

AI:

Responsive design ensures that your website is readable and usable on different devices such as phones, tablets, and desktops.
It improves user experience and is an important requirement for modern web development.

⸻

User:

How can I improve the visual design of my portfolio website?

AI:

You can improve the design by:
	•	Using a simple and consistent color palette
	•	Choosing readable fonts
	•	Keeping spacing and alignment consistent
	•	Avoiding clutter and unnecessary elements

⸻

User:

Why should I make multiple commits while developing my website?

AI:

Making multiple commits shows your development progress and helps track changes over time.
It is also an important practice when using Git and GitHub, especially for academic projects.

⸻

User:

How do I publish my website using GitHub Pages?

AI:

To publish your website using GitHub Pages:
	1.	Push your website files to a public GitHub repository.
	2.	Go to Settings → Pages.
	3.	Select the main branch as the source.
	4.	Save the settings and GitHub will generate a public URL for your website
