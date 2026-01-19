<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Deepesh Portfolio </title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background-color: #f4f6f9;
      color: #333;
    }
    header {
      background: linear-gradient(90deg, #004aad, #0077ff);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    nav {
      background-color: #002f6c;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      background-color: #004aad;
    }
    section {
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }
    h2 {
      color: #004aad;
      margin-bottom: 20px;
    }
    .card-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #002f6c;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>K S Rangasamy College of Technology</h1>
    <p>K S R Kalvi Nagar, Tiruchengode, Namakkal (DT)</p>
    <p>Knowledge  Innovation  Excellence</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#courses">Courses</a>
    <a href="#departments">Departments</a>
    <a href="#achievements">Achievements</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Our College</h2>
    <p>
      K S Rangasamy College of Technology (KSRCT) is a premier institution dedicated to academic excellence, innovation, and research.
      The college offers quality technical education and is well known for its strong industry connect and placement record.
    </p>
  </section>

  <section id="student">
    <h2>Student Profile</h2>
    <div class="card">
      <p><strong>Name:</strong> Deepesh G S</p>
      <p><strong>Department:</strong> Artificial Intelligence and Data Science (B.Tech)</p>
      <p><strong>Semester / Year:</strong> 4th Semester / 2nd Year</p>
      <p><strong>College:</strong> K S Rangasamy College of Technology</p>
    </div>
  </section>

  <section id="courses">
    <h2>Courses Offered</h2>
    <div class="card-container">
      <div class="card">
        <h3>B.Tech</h3>
        <p>Artificial Intelligence and Data Science(CSE)</p>
    </div>
        <div class="card">
            <h3>Diploma</h3>
            <p>Computer Science and Engineering</p>
        </div>
  </section>

  <section id="departments">
    <h2>Departments</h2>
    <div class="card-container">
      <div class="card">Computer Science & Engineering</div>
      <div class="card">Artificial Intelligence & Data Science</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Address:</strong> K S Rangasamy College of Technology, K S R Kalvi Nagar, Tiruchengode, Namakkal (DT), Tamil Nadu</p>
    <p><strong>Email:</strong> info@ksrctcollege.edu</p>
    <p><strong>Phone:</strong> +91 73971 37100</p>
  </section>

  <footer>
    <p>2026 K S Rangasamy College of Technology. All Rights Reserved.<br>Student Portfolio by <strong>Deepesh G S</strong></p>
  </footer>

</body>
</html>
