<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Gym Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Welcome to My Gym</h1>
  </header>

  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Classes</a></li>
      <li><a href="#">Membership</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <div class="main-content">
    <h2>Our Classes</h2>
    <div class="gym-classes">
      <div class="gym-class">
        <h3>Yoga</h3>
        <p>Improve flexibility and reduce stress</p>
      </div>
      <div class="gym-class">
        <h3>Zumba</h3>
        <p>Fun dance workout for all levels</p>
      </div>
      <div class="gym-class">
        <h3>Strength Training</h3>
        <p>Build muscle and increase metabolism</p>
      </div>
    </div>
  </div>

  <footer>
    <p>&copy; 2024 My Gym. All rights reserved.</p>
  </footer>
</body>
</html>
/* Styles for the header */
header {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

/* Styles for the navigation menu */
nav {
  background-color: #444;
  padding: 10px;
  text-align: center;
}

nav ul {
  list-style-type: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

/* Styles for the main content area */
.main-content {
  padding: 20px;
}

/* Styles for the gym classes section */
.gym-classes {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.gym-class {
  background-color: #f4f4f4;
  padding: 10px;
  border-radius: 5px;
}

.gym-class h3 {
  margin-top: 0;
}

.gym-class p {
  margin-bottom: 0;
}

/* Styles for the footer */
footer {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}
