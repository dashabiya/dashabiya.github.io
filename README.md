#<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>浪漫星空</title>
  <style>
    body {
      background-color: #000;
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
    
    .stars {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1;
      pointer-events: none;
    }
    
    .star {
      position: absolute;
      width: 2px;
      height: 2px;
      background-color: #fff;
      opacity: 0;
      border-radius: 50%;
      animation: twinkling 5s infinite;
    }
    
    @keyframes twinkling {
      0% {
        opacity: 0;
      }
      50% {
        opacity: 1;
      }
      100% {
        opacity: 0;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>浪漫星空</h1>
    <p>感受星星的闪烁之美。</p>
  </div>
  <div class="stars">
    <!-- 添加星星元素 -->
    <div class="star" style="top: 10%; left: 20%;"></div>
    <div class="star" style="top: 50%; left: 50%;"></div>
    <div class="star" style="top: 50%; left: 50%;"></div>
    <div class="star" style="top: 50%; left: 50%;"></div>
    <div class="star" style="top: 50%; left: 50%;"></div>
    <div class="star" style="top: 30%; left: 80%;"></div>
    <div class="star" style="top: 50%; left: 50%;"></div>
    <div class="star" style="top: 50%; left: 50%;"></div>
    <div class="star" style="top: 50%; left: 50%;"></div>
    <div class="star" style="top: 50%; left: 50%;"></div>
    <div class="star" style="top: 50%; left: 50%;"></div>
    <div class="star" style="top: 50%; left: 50%;"></div>
    <div class="star" style="top: 50%; left: 50%;"></div>
    <!-- 添加更多星星元素，可以根据需要增加或调整位置 -->
  </div>
</body>
</html>
