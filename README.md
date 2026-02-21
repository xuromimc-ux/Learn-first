<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Student Business Hub</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Poppins',sans-serif;
}

body{
  background:#0f172a;
  color:white;
  line-height:1.6;
}

header{
  background:#1e293b;
  padding:20px 0;
  text-align:center;
}

header h1{
  font-size:32px;
  color:#38bdf8;
}

nav{
  margin-top:10px;
}

nav a{
  color:white;
  text-decoration:none;
  margin:0 15px;
  font-weight:500;
  transition:0.3s;
}

nav a:hover{
  color:#38bdf8;
}

.hero{
  padding:80px 20px;
  text-align:center;
}

.hero h2{
  font-size:40px;
  margin-bottom:20px;
}

.hero p{
  max-width:600px;
  margin:auto;
  color:#cbd5e1;
}

.btn{
  display:inline-block;
  margin-top:25px;
  padding:12px 30px;
  background:#38bdf8;
  color:black;
  text-decoration:none;
  font-weight:600;
  border-radius:30px;
  transition:0.3s;
}

.btn:hover{
  background:white;
}

.section{
  padding:60px 20px;
  text-align:center;
}

.section h3{
  font-size:28px;
  margin-bottom:40px;
  color:#38bdf8;
}

.cards{
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:20px;
}

.card{
  background:#1e293b;
  padding:25px;
  width:280px;
  border-radius:15px;
  transition:0.3s;
}

.card:hover{
  transform:translateY(-10px);
}

.card h4{
  margin-bottom:15px;
}

footer{
  background:#1e293b;
  padding:20px;
  text-align:center;
  margin-top:40px;
  color:#94a3b8;
}

@media(max-width:768px){
  .cards{
    flex-direction:column;
    align-items:center;
  }
}
</style>
</head>
<body>

<header>
  <h1>Student Business Hub</h1>
  <nav>
    <a href="#">Home</a>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h2>Young Minds, Big Ideas 🚀</h2>
  <p>We are a group of creative students providing digital and academic services to help other students succeed.</p>
  <a href="#services" class="btn">Our Services</a>
</section>

<section class="section" id="services">
  <h3>Our Services</h3>
  <div class="cards">
    <div class="card">
      <h4>Graphic Design</h4>
      <p>Logos, posters, presentations and social media designs for students and small businesses.</p>
    </div>
    <div class="card">
      <h4>Homework Help</h4>
      <p>Support in math, science, and language subjects for middle and high school students.</p>
    </div>
    <div class="card">
      <h4>Website Creation</h4>
      <p>Modern and simple websites for projects, clubs, and small businesses.</p>
    </div>
  </div>
</section>

<section class="section" id="about">
  <h3>About Us</h3>
  <p>We are motivated students who believe in innovation and teamwork. Our goal is to gain experience while providing real value to our community.</p>
</section>

<section class="section" id="contact">
  <h3>Contact Us</h3>
  <p>Email: studentbusiness@email.com</p>
  <p>Instagram: @studentbusinesshub</p>
</section>

<footer>
  <p>© 2026 Student Business Hub | Made by Students</p>
</footer>

</body>
</html>
