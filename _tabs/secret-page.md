---
layout: page
icon: fas fa-thumbs-up
title: Secret Page
order: 7
---

<html>
<head>
  <title>Secret Page</title>
  <style>
    body {
      text-align: center;
      font-family: Arial, sans-serif;
    }
    #content {
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <div id="content">
    <h1>Welcome to my Secret Page!</h1>
    <p>As a reward for randomly stumbling upon this (if you get it once, you have it forever), here's a small thank you video:</p>
    <video id="secret-video" width="560" height="315" controls>
      <source src="https://youtube.com/watch?v=dQw4w9WgXcQ" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <script>
      document.getElementById('secret-video').play();
    </script>
  </div>
</body>
</html>
