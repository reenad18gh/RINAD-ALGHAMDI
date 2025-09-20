<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rinad Alghamdi</title>
<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  body, html {
    height: 100%;
    font-family: Arial, sans-serif;
  }

  /* الفيديو يغطي كامل الصفحة */
  #bg-video {
    position: fixed;
    top: 0;
    left: 0;
    min-width: 100%;
    min-height: 100%;
    width: auto;
    height: auto;
    z-index: -1;
    object-fit: cover; /* يحافظ على نسبة العرض */
  }

  /* محتوى فوق الفيديو */
  .content {
    position: relative;
    z-index: 1;
    min-height: 100vh; /* ارتفاع الشاشة بالكامل */
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
    background-color: rgba(0,0,0,0.4); /* طبقة شفافة فوق الفيديو */
    padding: 20px;
  }

  .content h1 {
    font-size: 3rem;
    margin-bottom: 20px;
    color: orange;
  }

  .content p {
    font-size: 1.2rem;
    margin-bottom: 20px;
  }

  .badges img {
    margin: 5px;
  }

  .section {
    background-color: rgba(0,0,0,0.6);
    padding: 20px;
    margin-top: 20px;
    border-radius: 12px;
    width: 80%;
    max-width: 800px;
    text-align: left;
  }

  .section h2 {
    color: orange;
    margin-bottom: 10px;
  }

  .section ul, .section table {
    color: white;
    font-size: 1rem;
  }

  a {
    color: orange;
  }

</style>
</head>
<body>

<!-- الفيديو الخلفية -->
<video autoplay muted loop playsinline id="bg-video">
  <source src="video.mp4" type="video/mp4">
  Your browser does not support HTML5 video.
</video>

<!-- المحتوى -->
<div class="content">
  <h1>Hi I'm Rinad Alghamdi</h1>
  <p>Data Science Student | AI Enthusiast | Former IT Officer</p>

  <div class="badges">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
    <img src="https://img.shields.io/badge/Data%20Science-4B8BBE?style=for-the-badge">
    <img src="https://img.shields.io/badge/AI%20Developer-FF6F00?style=for-the-badge">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
  </div>

  <div class="section">
    <h2>About Me</h2>
    <ul>
      <li>Graduate in Computer Networks and Security From IAU</li>
      <li>Currently studying Data Science In SEU</li>
      <li>Passionate about Artificial Intelligence and its applications</li>
      <li>Former IT Officer in the healthcare sector</li>
      <li>Currently transitioning into AI Development</li>
    </ul>
  </div>

  <div class="section">
    <h2>Skills</h2>
    <ul>
      <li>Network Administration and Cybersecurity</li>
      <li>Data Analysis and Model Building</li>
      <li>AI Application Development</li>
      <li>Systems Management and IT Solutions</li>
    </ul>
  </div>

  <div class="section">
    <h2>Tools & Technologies</h2>
    <ul>
      <li>Programming: Python, HTML, CSS, JavaScript</li>
      <li>Data &amp; AI: Pandas, NumPy, Scikit-learn, TensorFlow</li>
      <li>Version Control: Git, GitHub</li>
      <li>Cloud &amp; IT: Microsoft Azure, Linux, Windows Server</li>
      <li>Others: Canva, Notion, Figma</li>
    </ul>
  </div>

  <div class="section">
    <h2>Featured Projects</h2>
    <table>
      <tr>
        <th>Project</th>
        <th>Description</th>
        <th>Link</th>
      </tr>
      <tr>
        <td>Interactive Website</td>
        <td>Building an interactive website experience</td>
        <td><a href="#">Link</a></td>
      </tr>
      <tr>
        <td>Mobile Application</td>
        <td>Developing a mobile application with interactive features</td>
        <td><a href="#">Link</a></td>
      </tr>
    </table>
  </div>

  <div class="section">
    <h2>Contact</h2>
    <p>
      <a href="https://www.linkedin.com/in/rinad-alghamdi-3967b1245/" target="_blank">LinkedIn</a> |
      <a href="https://mail.google.com/mail/?view=cm&fs=1&to=reenad18gh@gmail.com" target="_blank">Email Me on Gmail</a>
    </p>
  </div>

</div>

</body>
</html>
