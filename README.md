<html>
<head>
  <title>🌟 Rukmini KS || FP&A Associate</title>
  <style>
    body {
      background-image: url('Copilot_20260914_210938.png');
      background-size: cover;
      background-repeat: no-repeat;
      background-attachment: fixed;
      background-position: center;
      color: white;
      font-family: Arial, sans-serif;
      animation: fadeIn 2s ease-in;
    }

    /* Header layout */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 20px;
    }

    h1 {
      color: #00aced; /* Blue name */
      margin: 0;
    }

    .nav-btn {
      display: inline-block;
      background-color: #00aced;
      color: white;
      padding: 10px 20px;
      margin: 5px;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }

    .nav-btn:hover {
      background-color: #0077b5;
    }

    .section {
      display: none; /* hidden by default */
      margin-top: 20px;
      text-align: left;
      max-width: 1000px; /* expanded horizon */
      margin-left: auto;
      margin-right: auto;
      line-height: 1.6; /* better readability */
    }

    .section.active {
      display: block; /* show when active */
      border-left: 4px solid #00aced;
      padding-left: 15px;
      background-color: #111;
    }
  </style>
</head>
<body>

<!-- Header with name left, buttons right -->
<header>
  <h1>Rukmini KS || FP&A Associate</h1>
  <div>
    <button class="nav-btn" onclick="showSection('about')">About Me</button>
    <button class="nav-btn" onclick="showSection('experience')">Experience</button>
    <button class="nav-btn" onclick="showSection('projects')">Demo Projects</button>
    <button class="nav-btn" onclick="showSection('education')">Education & Awards</button>
    <button class="nav-btn" onclick="showSection('skills')">Skills</button>
    <button class="nav-btn" onclick="showSection('contact')">Contact</button>
    <button class="nav-btn" onclick="showSection('resume')">Resume</button>
  </div>
</header>

<!-- Sections remain the same -->
<div id="about" class="section active">
  <div style="display: flex; align-items: center;">
    <img src="Profile Photo(1).png" alt="Profile Photo" 
         style="width:200px; height:auto; margin-right:20px; border-radius:8px;">
    <div>
      <h2 style="color:#00aced;">Rukmini KS</h2>
      <p>Associate – Business Finance (FP&A) at UST Global.</p>
      <p>Passionate about corporate finance, analytics, and automation.</p>
      <p>Skilled in turning complex data into actionable insights for stakeholders.</p>
    </div>
  </div>
</div>

<script>
  function showSection(id) {
    document.querySelectorAll('.section').forEach(sec => sec.classList.remove('active'));
    document.getElementById(id).classList.add('active');
  }
</script>

</body>
</html>
