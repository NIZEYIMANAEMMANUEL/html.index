# html.index
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Landing Page</title>
  <link rel="stylesheet" href="styles.css">
  <div class="about-section">
  <h2>About</h2>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
  <img src="https://igihe.com/local/cache-gd2/b9/64cc9b08ba0571cd6be7e400c7babe.jpg?1687339471" alt="About Image">
</div>
</head>
<body>
  <header>
    <h1>Hero Text</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="section-one">
    <h2>Section One</h2>
    <p>This is the content for section one.</p>
  </section>

  <section class="section-two">
    <h2>Section Two</h2>
    <p>This is the content for section two.</p>
  </section>

  <section class="section-three">
    <h2>Section Three</h2>
    <p>This is the content for section three.</p>
  </section>

  <footer>
    <p>&copy; 2023 Your Company. All rights reserved.</p>
  </footer>
</body>
</html>

/* General Styles */
body {
  margin: 0;
  padding: 0;
  font-family: 'Roboto', sans-serif;
}

/* Header Styles */
header {
  background-color: #f5f5f5;
  padding: 20px;
}

h1 {
  font-size: 32px;
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

nav ul li {
  display: inline;
  margin-right: 10px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
}

/* Section Styles */
section {
  padding: 50px;
}

.section-one {
  background-color: #f9f9f9;
}

.section-two {
  background-color: #e9e9e9;
}

.section-three {
  background-color: #d9d9d9;
}

h2 {
  font-size: 24px;
  margin: 0;
}

/* Footer Styles */
footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 20px;
}
