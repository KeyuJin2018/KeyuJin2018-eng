---
layout: null
permalink: /cv/
title: "CV"
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>CV | Keyu Jin</title>
  <link rel="icon" href="{{ '/images/favicon.ico' | relative_url }}">
  <style>
    * { box-sizing: border-box; }
    html, body { margin: 0; height: 100%; }
    body { display: flex; flex-direction: column; font-family: Arial, sans-serif; background: #fff; }
    nav { display: flex; align-items: center; flex-wrap: wrap; gap: 16px; padding: 12px 16px; border-bottom: 1px solid #ddd; }
    nav a { color: #222; }
    nav strong { margin-right: auto; }
    iframe { display: block; width: 100%; flex: 1; min-height: 0; border: 0; }
  </style>
</head>
<body>
  <nav aria-label="CV controls">
    <a href="{{ '/bio/' | relative_url }}">Back to website</a>
    <strong>Keyu Jin — CV</strong>
    <a href="{{ '/pdf/cv.pdf' | relative_url }}" download>Download PDF</a>
  </nav>
  <iframe src="{{ '/pdf/cv.pdf' | relative_url }}" title="Keyu Jin’s curriculum vitae"></iframe>
</body>
</html>
