
<!DOCTYPE html>
<html>
<head>
  <title>My Portfolio</title>

  <style>
    body {
      background: linear-gradient(lightblue, #dff6ff);
      font-family: Arial, sans-serif;
      text-align: center;
      padding-top: 40px;
    }

    .box {
      background-color: white;
      width: 350px;
      margin: auto;
      padding: 25px;
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }

    .box:hover {
      transform: scale(1.05);
    }

    img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 15px;
    }

    h1 {
      color: #2c3e50;
      text-decoration: underline;
    }

    h3 {
      color: #34495e;
      border-bottom: 2px solid lightblue;
      padding-bottom: 5px;
    }

    p {
      color: #555;
    }
  </style>
</head>

<body>

  <div class="box">
    <img src="photo.jpg" alt="My Photo">

    <h1>Aashriya Pageni</h1>
    <p><b>Shree Tribhuwan Shanti Model Secondary School</b></p>

    <h3>About Me</h3>
    <p>Student of Class 9 Jasmine</p>

    <h3>Skills</h3>
    <p>HTML and CSS Basics</p>

    <h3>Contact</h3>
    <p>Phone Number: 9867239834</p>
  </div>

</body>
</html>
