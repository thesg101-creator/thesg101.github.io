<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Resume</title>
<style>
:root {
  --primary-color: #2c3e50;
  --accent-color: #3498db;
  --text-color: #333;
  --bg-color: #f4f6f9;
  --card-bg: #ffffff;
}

body { 
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
  line-height: 1.6; 
  margin: 0; 
  padding: 40px 20px; 
  background-color: var(--bg-color);
  color: var(--text-color);
}

.container {
  max-width: 800px;
  margin: 0 auto;
  background: var(--card-bg);
  padding: 40px;
  border-radius: 12px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.container:hover {
  transform: translateY(-5px);
}

header { 
  text-align: center;
  padding-bottom: 20px; 
  margin-bottom: 30px; 
  border-bottom: 2px solid var(--accent-color);
}

h1 { 
  margin: 0; 
  color: var(--primary-color);
  font-size: 2.5em;
}

.contact-info {
  color: #666;
  margin-top: 10px;
}

.section { 
  margin-bottom: 30px; 
  opacity: 0;
  animation: fadeIn 0.8s ease forwards;
}

.section-title { 
  font-weight: bold; 
  font-size: 1.5em;
  color: var(--primary-color);
  border-left: 4px solid var(--accent-color);
  padding-left: 10px; 
  margin-bottom: 15px; 
}

.job, .education {
  margin-bottom: 15px;
  padding: 15px;
  border-radius: 6px;
  background: #f9f9f9;
  transition: background 0.3s ease;
}

.job:hover, .education:hover {
  background: #f1f1f1;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>
</head>
<body>
<div class="container">
  <header>
    <h1>Your Name</h1>
    <p class="contact-info">Email: your.email@example.com | Phone: (123) 456-7890</p>
  </header>
  <div class="section">
    <div class="section-title">Experience</div>
    <div class="job">
      <p><strong>Job Title</strong> - Company Name (Year - Present)</p>
      <p>Description of your responsibilities and achievements.</p>
    </div>
  </div>
  <div class="section" style="animation-delay: 0.2s;">
    <div class="section-title">Education</div>
    <div class="education">
      <p><strong>Degree</strong> - University Name (Year)</p>
    </div>
  </div>
</div>
</body>
</html>
