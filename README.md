[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TUGW0SrP)
# Welcome to the HTML5 Basics Assignment repository! 

This assignment is designed to help you build foundational knowledge of HTML5, understand its structure, and practice creating web page content using semantic elements.

## Learning Objectives

By completing this assignment, you will:

  Understand the structure and purpose of HTML5 in web development.
  Learn to create basic web page content using core HTML5 elements.
  Explore semantic HTML elements and their benefits for readability and SEO.
  Gain a basic understanding of accessibility and SEO best practices in HTML.
  
## Assignment Content
  1. HTML5 Basics
Learn the structure of an HTML document (e.g., <!DOCTYPE html>, <html>, <head>, <body>).
Explore core elements such as headings, paragraphs, lists, links, and images.
  2. Semantic HTML
Introduction to semantic tags like <header>, <footer>, <nav>, <section>, and <article>.
Learn how semantic elements improve content readability and support SEO.
  3. Accessibility and SEO Basics
Understand the importance of accessible HTML and SEO-friendly practices.
Use attributes like alt, title, and semantic structures to improve usability.

## Activities

Creating a Simple Webpage: Design a basic webpage that includes text, images, and links.
Use common HTML tags like h1, p, a, img, and ul or ol.
Structure a webpage with semantic tags such as header, footer, nav, section, and article.
Ensure the content is well-organized for readability and SEO.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A basic webpage demonstrating HTML structure with text, images, and links.">
    <title>Sample Webpage</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS for styling -->
</head>
<body>
    <header>
        <h1>Welcome to My Sample Webpage</h1>
        <p>Learn more about web design and HTML structure.</p>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Introduction</h2>
        <p>This is a simple webpage to showcase basic HTML elements. It includes headings, paragraphs, images, and links that demonstrate how to structure a webpage for optimal readability and SEO.</p>
        <img src="https://via.placeholder.com/400" alt="Placeholder image" />
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Our website provides useful resources for learning HTML, CSS, and web development. We believe in making coding accessible and fun for everyone!</p>
        <img src="https://via.placeholder.com/300" alt="About Us Image" />
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <article>
            <h3>Web Design</h3>
            <p>We offer professional web design services to help you create a stunning online presence.</p>
            <a href="https://example.com/web-design">Learn more about Web Design</a>
        </article>
        <article>
            <h3>SEO Optimization</h3>
            <p>Improve your website's ranking and visibility on search engines with our SEO optimization services.</p>
            <a href="https://example.com/seo">Learn more about SEO Optimization</a>
        </article>
    </section>

    <footer>
        <p>&copy; 2024 Sample Webpage. All rights reserved.</p>
        <nav>
            <ul>
                <li><a href="https://www.example.com/privacy-policy">Privacy Policy</a></li>
                <li><a href="https://www.example.com/terms-of-service">Terms of Service</a></li>
            </ul>
        </nav>
    </footer>
</body>
</html>
