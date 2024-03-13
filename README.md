<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>炫酷首页</title>
  <style>
    body {
      background-color: #222;
      color: #fff;
      font-family: Arial, sans-serif;
    }
    
    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
    }
    
    h1 {
      font-size: 4rem;
      margin-bottom: 2rem;
      text-shadow: 2px 2px 4px #000;
    }
    
    p {
      font-size: 1.5rem;
      margin-bottom: 2rem;
    }
    
    .button {
      display: inline-block;
      padding: 1rem 2rem;
      font-size: 1.2rem;
      background-color: #ff4c4c;
      color: #fff;
      text-decoration: none;
      border-radius: 25px;
      box-shadow: 2px 2px 4px #000;
      transition: background-color 0.3s ease;
    }
    
    .button:hover {
      background-color: #ff1a1a;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Welcome to my Cool Homepage!</h1>
    <p>Discover the world of awesomeness.</p>
    <a href="#" class="button">Get Started</a>
  </div>
</body>
</html>
