# personal-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BRIAN GORI</title>
    <link 
    href="https://fonts.googleleapis.com/css2?family=poppins:wght@400;600&display=swap" rel="stylesheet" >  
  <style>
    body{
      font-family: 'poppins',sans-serif;
      background-color: #f4f4f4;
      color: #333;
      max-width: 800px;
      margin: 50px auto;
      padding: 20px;
      box-shadow:0 0 10px rgba(0,0,0,0.1) ;
      background-color: #ffffff;

    }
    h1,h2,h3{
      text-align: center;
      color: #2c3e50;
    }
    p{
      font-size: 18px;
      line-height: 1.6;
    }
      .notification-bar{
        background-color:#28a745;
        color: white;
        text-align: center;
        padding: 12px;
        font-size: 16px;
        position: relative;
      }
      .Thanks{
        padding: 2px;
        border-radius: 3px;
        text-align: center;
      }
      .dark-mode{
        background-color: #222;
        color: #eee;
      }
      .photo{
        display: block;
        margin: 20px auto;
        width: 150px;
        height: 150px;
        border-radius: 50%;
        object-fit: cover;
        border: 3px solid #2c3e50;

      }
      header h1{
font-size: 42;
margin: 0;
      }
      header p{
        font-size: 18px;

      }
      .footer{
        text-align: center;
        font-size: 14px;
        color: #666;
        margin: 30px 0;

      }
      a{
        color: #1d64a7;
        text-decoration: none;
      }
      a.hover{
        text-decoration: underline;
      }
  </style>
  

  
</head>
<body>
  <header>
    <h1>Brian Gori</h1>
    <p>Software Developer|App Bulider| Tech Enthusiast</p>
  </header>
  <button onclick="togglemode()">Dark Mode</button><br>
  <script>
    function togglemode(){
      document.body.classList.toggle("dark-mode");
    }
  </script>
  <P id="date"></P>
  <script>
    document.getElementById("date").innerText="Today's date is:"+new Date().toDateString();
  </script>

  <div class="notification-bar" id="Notify">
    Welcome to my website!<button onclick="closebar()">Update</button>
  </div>
  <script>
    function closebar(){
      ducument.getElementById("notify").style.display="none";
    }
  </script>
  <img src="images\brian.jpeg" alt="images" class="pictures">
<h1>About me</h1>
    <h2>Welcome to My Website</h2>
    <p>My name is Brian Gori, born on August 28,2002.I'm currently  a student at kisii university, pursuing Bachelor of Science in information Technology.I have a strong passion for programming,with a growing interest in software and app development. I enjoy creating solutions tha make techology more accessible and efficient.</p>

<h2>Projects</h2>
<ul>
  <li>Personal portfolio website"this one"</li>
  <li>simple To-Do List App (html/css/javascript)</li>
  <li>Student management system(java/mysql)</li>

</ul>
<h3>Contact</h3>
Email:<a href="briangori300@gmail.com">briangori300@gmail.com</a><br>
Phone: +254 110443341<br>
GitHub:<a href="https://github.com/ brian12748" target="_blank">github.com/brian12748</a>
<script>
  alert("Welcome to Brian Gori's website!");
</script><br>
<div class="Thanks">
<button onclick="showMessage()">Thanks</button><br>
</div>
  <script>
    function showMessage(){
      alert("Thanks for visiting my site");
    }
  </script>
  <div class="footer">
    &copy; 2025 Brian Gori. All rights reserved
  </div>
 
</body>
</html>
