<!DOCTYPE html>
<html>
<head>
<style>
.container {
  display: flex;
  flex-direction: row;
  width: 100%;
  height: 100vh;
}
.left, .right {
  width: 50%;
  padding: 20px;
  box-sizing: border-box;
  overflow-y: auto;
}
.left {
  border-right: 1px solid #ccc;
}
.right {
  border-left: 1px solid #ccc;
}
h2 {
  border-bottom: 2px solid #333;
  padding-bottom: 5px;
}
</style>
</head>
<body>

<div class="container">
  <div class="left">
    <h1>👋 Hello! I'm [Your Name]</h1>
    
    <h2>📍 Location</h2>
    <p>[Your City, Country]</p>
    
    <h2>📧 Contact</h2>
    <ul>
      <li>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></li>
      <li>LinkedIn: <a href="https://linkedin.com/in/yourprofile">linkedin.com/in/yourprofile</a></li>
      <li>GitHub: <a href="https://github.com/yourusername">github.com/yourusername</a></li>
    </ul>
    
    <h2>🧑‍💻 Programming Skills</h2>
    <p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript"/>
      <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white" alt="Java"/>
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white" alt="C++"/>
      <img src="https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white" alt="C#"/>
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" alt="Golang"/>
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat&logo=sqlite&logoColor=white" alt="SQL"/>
    </p>
    
    <h2>💼 Projects</h2>
    <p>
      <strong>🚀 <a href="https://github.com/yourusername/project-name">Project Name</a></strong><br>
      Description: A brief description of what the project does and its key features.<br>
      Technologies Used: Python, Django, PostgreSQL<br>
      Role: Lead Developer<br>
      Highlights: Successfully deployed using AWS, integrated with various third-party APIs, etc.
    </p>
    <p>
      <strong>📊 <a href="https://github.com/yourusername/another-project">Another Project</a></strong><br>
      Description: Description of this project and its features.<br>
      Technologies Used: JavaScript, React, Node.js<br>
      Role: Frontend Developer<br>
      Highlights: Improved user experience with a new UI/UX design, optimized performance, etc.
    </p>
  </div>
  
  <div class="right">
    <h2>🌟 Interests</h2>
    <ul>
      <li>Database Internals: Enthusiastic about understanding the inner workings of databases and optimization techniques.</li
