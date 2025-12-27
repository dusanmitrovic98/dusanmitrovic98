<h1 align="center">Hi, I'm Dule 👋</h1>

<p align="center">Hello World!</p>

<!DOCTYPE html>
<html lang="en">

<head>
  <style>
    @font-face {
      font-family: 'Rubik Gemstones';
      src: url('assets/images/fonts/Google_Sans,Rubik_Gemstones/Rubik_Gemstones/RubikGemstones-Regular.ttf') format('truetype');
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif ;
      background-color: #3F4E4F;
      min-height: 100vh;
      height: 100vh;
      padding: 1rem;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .main-container {
      background-color: #2C3639;
      width: 100%;
      max-width: 400px;
      color: #DCD7C9;
      border-radius: 1rem;
      display: flex;
      flex-direction: column;
      gap: 2rem;
      padding: 2rem;
      text-align: center;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
    }

    .profile-picture {
      background-color: #A27B5C;
      width: 100px;
      height: 100px;
      border-radius: 50%;
      align-self: center;
      border: 4px solid #DCD7C9;
      overflow: hidden;
    }

    img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .bio-container h1 {
      font-family: 'Rubik Gemstones', cursive;
      font-size: 2rem;
      margin-bottom: 0.5rem;
      letter-spacing: 1px;
    }

    .bio-container p {
      font-size: 0.9rem;
      opacity: 0.8;
    }

    .links-container {
      display: flex;
      flex-direction: column;
      gap: 1rem;  
    }

    .list-item {
      display: block;
      background-color: #A27B5C;
      padding: 1rem;
      border-radius: 10px;
      text-decoration: none;
      color: #2C3639;
      font-size: large;
      font-weight: bold;
      transition: transition 0.2s ease, background-color 0.2s ease;
    }

    .list-item:hover {
      background-color: #DCD7C9;
      transition: translateY(-3px);
      cursor: alias;
    } 
  </style>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>

<body class="main-font">
  <div class="main-container">
    <div class="profile-picture">
      <img src="./assets/images/profile.png" alt="Profile Image" srcset="">
    </div>
    <div class="bio-container">
      <h1>Dušan Mitrović</h1>
      <p>Software Developer | 'Architect'</p>
    </div>
    <div class="links-container">
      <a class="list-item" href="https://www.instagram.com/dusanmitrovic98/">Instagram</a>
      <a class="list-item" href="https://github.com/dusanmitrovic-dev">GitHub</a>
      <a class="list-item" href="https://x.com/dusanmitrovic98">x</a>
      <a class="list-item" href="https://dusan.mitrovic.contact@gmail.com">Contact Me</a>
    </div>
  </div>
</body>

</html>
