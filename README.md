# enhance-your-personal-web-page-with-forms-and-navbar-YOUR_USERNAME
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Personal Website</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; scroll-behavior: smooth; }
    nav {
      position: fixed;
      width: 100%;
      top: 0;
      background-color: #333;
      z-index: 1000;
    }
    nav a {
      float: left;
      display: block;
      color: white;
      padding: 14px 16px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #575757;
    }
    .section {
      padding: 80px 20px 40px; /* Extra top padding for navbar */
      margin-top: 40px;
    }
    img {
      max-width: 300px;
      height: auto;
    }
    form {
      max-width: 500px;
    }
    input, textarea {
      width: 100%;
      margin-bottom: 10px;
      padding: 8px;
    }
    button {
      padding: 10px 20px;
      background-color: #333;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #575757;
    }
  </style>
</head>
<body>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#resume">Resume</a>
    <a href="#contact">Contact Me</a>
  </nav>

  <div class="section" id="home">
    <h1>Welcome to My Website!</h1>
    <p>Welcome to My Personal Website!

On this website, you'll find information about me, my hobbies, my resume, and how to contact me..</p>
  </div>

  <div class="section" id="about">
    <h1>Your Name</h1>
    <img src="https://via.placeholder.com/300" alt="A descriptive image" />
    <p> Hi, I'm Kam Carter. I am a student studying computer science at Blue Mountain University. I enjoy video games, which I find to be an exciting escape into fictional worlds.
 .</p>
    <p>One of my greatest hobbies is Riding Horses. I love the joy of animals and just being behind a set of ears is imagining .</p>
  </div>

  <div class="section" id="resume">
    <h1>Resume</h1>
    <h2>Education</h2>
    <p> NorthEast Community College — Associate Degree (2023)</p>

    <h2>Experience</h2>
    <p> 

      ASHLEY SUMMER PROGRAM ECRU MS
FILTER CLEANER MAY 2018 - 2023
CLEANING THE PLANT AIR VENTS - MAINTENANCE WORKER
May 2024 - August 2024
Attendant and server at club facilities (Boys & Girls
Club)
Organized work schedule
May 2022 - August 2025
Camp counselor for children attending Jones
community, Northeast Community, Blue Mountain
Basketball Camp
Assisted in organization of daily curriculum and
facilitation of activites </p>

    <h2>Skills</h2>
    <ul>
      <li>Effective Communicator</li>
      <li>In-Depth Research</li>
      <li>Presentation Skills</li>
    </ul>
  </div>

  <div class="section" id="contact">
    <h1>Contact Me</h1>
    <form action="#" method="post">
      <label>Name:</label>
      <input type="text" name="name" required />

      <label>Email:</label>
      <input type="email" name="email" required />

      <label>Subject:</label>
      <input type="text" name="subject" required />

      <label>Message:</label>
      <textarea name="message" rows="5" required></textarea>

      <button type="submit">Submit</button>
    </form>
  </div>

</body>
</html>
