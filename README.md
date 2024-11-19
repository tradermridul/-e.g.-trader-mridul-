/* Reset some basic styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  line-height: 1.6;
  background-color: #f4f4f4;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
}

/* Header and Navigation */
header {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
}

header h1 {
  font-size: 2.5em;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  padding: 10px 0;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-size: 1.2em;
}

/* Hero Section */
.hero {
  background: #333 url('hero-image.jpg') center/cover no-repeat;
  color: white;
  text-align: center;
  padding: 100px 0;
}

.hero h2 {
  font-size: 3em;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2em;
  margin-bottom: 20px;
}

.hero .btn {
  background-color: #ff6347;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
}

/* About Section */
#about {
  background-color: white;
  padding: 50px 0;
  text-align: center;
}

/* Services Section */
#services {
  background-color: #f9f9f9;
  padding: 50px 0;
}

#services .service {
  margin-bottom: 20px;
}

#services h2 {
  font-size: 2.5em;
  margin-bottom: 20px;
}

/* Portfolio Section */
#portfolio {
  background-color: white;
  padding: 50px 0;
  text-align: center;
}

.portfolio-item {
  background-color: #f4f4f4;
  padding: 20px;
  margin: 10px 0;
}

/* Contact Form */
#contact {
  background-color: #f9f9f9;
  padding: 50px 0;
}

form {
  display: flex;
  flex-direction: column;
  align-items: center;
}

form input,
form textarea {
  width: 100%;
  max-width: 600px;
  padding: 10px;
  margin: 10px 0;
  border-radius: 5px;
  border: 1px solid #ccc;
}

form button {
  background-color: #333;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

footer {
  background-color: #333;
  color: white;
  padding: 20px 0;
  text-align: center;
}

footer p {
  font-size: 1em;
}
