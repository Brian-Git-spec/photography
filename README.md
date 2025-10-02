# Photography Portfolio Website

A personal photography portfolio built with HTML5 and CSS3, showcasing favorite photos, team members, and a contact form.

## Features

- Dark modern design with gold highlights.
- Responsive photo gallery with hover effects.
- Team section with styled profile cards.
- Project design section showing the wireframe/mockup.
- Contact form 
- Fully semantic HTML — uses <section>, <figure>, <fieldset>, <legend> instead of unnecessary <div>/<span>.

## 📂 Project Structure
Photography-portfolio

1. index.html        # Main HTML file
2. style.css         # Stylesheet
3. images/           # Photos, team images
│   ├── photo1.jpg
│   ├── photo2.jpg
│   ├── photo3.jpg
│   ├── photo4.jpg
│   ├── member1.jpg
│   ├── member2.jpg
│   ├── member3.jpg
    └── member4.jpg
4. README.md         

## Getting Started
1. Clone this repository
git clone https://github.com/Brian-Git-spec/photography.git
cd photography-portfolio

2. Open the project

Simply open index.html in your favorite browser.
No build tools required.

## Contact Form Behavior

- By default, the form uses:
<form class="contact-form" action="#" method="post">---
which does not send data anywhere.

- To make it functional, you can:
1.Add a JavaScript handler (onsubmit) to show a thank-you message.
2.Connect to a service like Formspree or Netlify Forms.
3.Hook up a backend with PHP, Node.js, or Python.


## 📜 License

This project is open-source and free to use.
You can customize it for personal or professional use.

✨ Built with love for photography.