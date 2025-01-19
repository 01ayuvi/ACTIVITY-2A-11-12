<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Table Layout</title>
  <style>
    body {
      background-color: lightblue;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Container for the page */
    .container {
      width: 80%;
      margin: 20px auto;
      padding: 20px;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    table {
      border-collapse: collapse;
      width: 100%;
      margin: 20px auto;
    }

    td {
      border: 1px solid black;
      text-align: center;
      padding: 15px;
      height: 60px;
      width: 120px;
    }

    /* Hover effect for table rows */
    tr:hover {
      background-color: #d3d3d3;
    }

    /* Styling for shaded cells */
    .shaded {
      background-color: lightgreen;
    }

    /* Styling for affirmation text */
    .affirmation {
      font-family: Arial, sans-serif;
      color: green;
      font-size: 18px;
      font-style: italic;
    }

    /* Header styling */
    h2 {
      text-align: center;
      font-weight: bold;
      font-size: 24px;
      color: #333;
    }

    /* Styling for links */
    a {
      color: blue;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Adding extra space between the content and the border in table cells */
    td {
      padding: 15px;
    }
  </style>
</head>
<body>

  <div class="container">
    <h2>Activity 3</h2>
    <table>
      <tr>
        <td colspan="2" rowspan="2">
          <img src="q1.jpg" alt="Image" width="100" height="100">
        </td>
        <td>r1c3</td>
        <td rowspan="2">r1c4</td>
        <td colspan="2" rowspan="2">r1c5</td>
      </tr>
      <tr>
        <td rowspan="2">
          <a href="mailto:someone@example.com">Email</a>
        </td>
        <td rowspan="2">r2c3</td>
      </tr>
      <tr>
        <td colspan="2">
          <a href="assign1.html">Home.html</a>
        </td>
        <td colspan="2">
          <a href="q1.jpg">
            <img src="q1.jpg" alt="Image" width="50" height="50">
          </a>
        </td>
        <td>r3c6</td>
      </tr>
      <tr>
        <td class="shaded">r4c1</td>
        <td class="shaded" colspan="2">r4c2</td>
        <td rowspan="2">r4c4</td>
        <td colspan="2">r4c5</td>
      </tr>
      <tr>
        <td rowspan="2" colspan="2" class="shaded">r5c1</td>
        <td rowspan="2">r5c3</td>
        <td rowspan="2" colspan="2">r5c5</td>
      </tr>
      <tr>
        <td class="affirmation">Stay positive!</td>
      </tr>
      <tr>
        <td>r6c4</td>
        <td class="affirmation" colspan="2">You are capable of amazing things!</td>
        <td>r6c5</td>
      </tr>
    </table>
  </div>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Thematic Web Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #fbd3d3;
    }
    header {
      background: #bdcaed;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      background: #333;
      color: white;
      display: flex;
      justify-content: space-around;
      padding: 10px;
    }
    nav a {
      color: rgb(241, 246, 212);
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    article, section, aside {
      padding: 20px;
    }
    section {
      margin: 20px auto;
      width: 80%;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    aside {
      background: #f9f9f9;
      margin: 20px;
      padding: 20px;
      border-left: 4px solid #4CAF50;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 10px 0;
    }
    footer form {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 10px;
    }
    footer form input, footer form textarea {
      width: 80%;
      margin: 5px 0;
      padding: 10px;
      border-radius: 4px;
      border: 1px solid #ccc;
    }
    footer form input[type="submit"] {
      background: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
    }
    footer form input[type="submit"]:hover {
      background: #45a049;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Welcome to My Thematic Web Page</h1>
    <p>Discover exciting content and more!</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#navigation">Navigation</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact Us</a>
  </nav>

  <!-- Home Page -->
  <section id="home">
    <article>
      <h2>About My Theme</h2>
      <p>
        This website is designed to explore various web development concepts and showcase activities. You can navigate to different sections, view blogs with multimedia, and reach out to us through the Contact Us page.
      </p>
    </article>
  </section>

  <!-- Navigation Page -->
  <section id="navigation">
    <article>
      <h2>Navigation</h2>
      <p>Here is the list of activities from Assignment 1A, 1B, and 1C:</p>
      <ul>
        <li><a href="assign1.html">Activity 1</a></li>
        <li><a href="act2.html">Activity 2</a></li>
        <li><a href="act3.html">Activity 3</a></li>
        <!-- Add more links as needed -->
      </ul>
    </article>
  </section>

  <!-- Blog Page -->
  <section id="blog">
    <article>
      <h2>Blog</h2>
      <p>Check out some interesting photos and videos:</p>
      <div>
        <img src="background.jpg" alt="Sample Photo 1" style="width:50%; margin: auto; display: block; border-radius:8px;">
      </div>
      <div>
        <video controls style="width:100%; margin-top:20px;">
          <source src="mp4.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <p>Visit <a href="https://example.com" target="_blank">this website</a> for more inspiration.</p>
    </article>
  </section>

  <!-- Contact Us -->
  <footer id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <input type="submit" value="Send">
    </form>
    <p>© 2025 My Thematic Web Page</p>
  </footer>

