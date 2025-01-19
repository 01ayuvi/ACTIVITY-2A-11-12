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
  <title>Activity 12 - Web Design</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Welcome to My Themed Website</h1>
    <p>This website is all about showcasing assignments and creativity with a structured design.</p>
  </header>

  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#navigation">Navigation</a></li>
      <li><a href="#blog">Blog</a></li>
      <li><a href="#contact">Contact Us</a></li>
    </ul>
  </nav>

  <main>
    <section id="home">
      <h2>Home Page</h2>
      <p>This is the homepage where you can find a brief description of the theme and purpose of this website. The theme focuses on learning and implementing web design concepts.</p>
    </section>

    <section id="navigation">
      <h2>Navigation Page</h2>
      <p>Below are the activities listed from Assignment 1A, 1B, and 1C:</p>
      <ul>
        <li>Activity 1A: Understanding HTML Basics</li>
        <li>Activity 1B: Adding CSS for Styling</li>
        <li>Activity 1C: Building a Responsive Layout</li>
      </ul>
    </section>

    <section id="blog">
      <h2>Blog Page</h2>
      <p>Check out some photos, videos, and hyperlinks below:</p>
      <ul>
        <li><a href="https://example.com/photo-gallery" target="_blank">Photo Gallery</a></li>
        <li><a href="https://example.com/video-tutorial" target="_blank">Video Tutorial</a></li>
        <li><a href="https://example.com/resources" target="_blank">Useful Resources</a></li>
      </ul>
    </section>
  </main>

  <footer id="contact">
    <h2>Contact Us</h2>
    <form action="submit_form.php" method="post">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>

      <button type="submit">Submit</button>
    </form>
  </footer>
</body>
</html>
