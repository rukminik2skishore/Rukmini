<html>
<head>
  <title>🌟 Rukmini KS || FP&A Associate</title>
  <style>
   body 
    {
  background-image: url('Copilot_20260914_210938.png');
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  color: white;
  font-family: Arial, sans-serif;
  animation: fadeIn 2s ease-in
  ;}
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
      max-width: 800px;
      margin-left: auto;
      margin-right: auto;
    }
    .section.active {
      display: block; /* show when active */
      border-left: 4px solid #00aced;
      padding-left: 10px;
      background-color: #111;
    }
  </style>
</head>
<body>

<h1> Rukmini KS || FP&A Associate</h1>

<!-- Navigation Buttons -->
<div>
  <button class="nav-btn" onclick="showSection('about')">About Me</button>
  <button class="nav-btn" onclick="showSection('experience')">Experience</button>
  <button class="nav-btn" onclick="showSection('projects')">Demo Projects</button>
  <button class="nav-btn" onclick="showSection('education')">Education & Awards</button>
  <button class="nav-btn" onclick="showSection('skills')">Skills</button>
  <button class="nav-btn" onclick="showSection('contact')">Contact</button>
  <button class="nav-btn" onclick="showSection('resume')">Resume</button>
</div>

<!-- Sections -->


<div id="about" class="section active">
  <div style="display: flex; align-items: center;">
    <!-- Photo -->
    <img src="Profile Photo(1).png" alt="Profile Photo" 
         style="width:200px; height:auto; margin-right:20px; border-radius:8px;">
    <!-- Text -->
    <div>
      <h2>Rukmini KS</h2>
      <p>Associate – Business Finance (FP&A) at UST Global.</p>
      <p>Passionate about corporate finance, analytics, and automation.</p>
      <p>Skilled in turning complex data into actionable insights for stakeholders.</p>
    </div>
  </div>
</div> <!-- ✅ Properly closed About section -->


<div id="resume" class="section">
  <h2>📄 Resume</h2>
  <iframe src="Rukmini_KS_Resume_v3.pdf" 
          width="100%" 
          height="600px" 
          style="border:none;">
  </iframe>
  <p><a href="Rukmini_KS_Resume_v3.pdf" download>Download Resume</a></p>
</div>

<div id="experience" class="section">
  <h2>💼 Experience</h2>
  <h3>UST Global – Associate, Business Finance (FP&A)</h3>
  <ul>
    <li>Budgeting, Forecasting, Variance Analysis, and P&L Analysis</li>
    <li>Automated reporting workflows, reducing cycle time by 50%</li>
    <li>Partnered with stakeholders to deliver accurate and timely insights</li>
  </ul>
</div>

<div id="projects" class="section">
  <h2>📊 Demo Projects</h2>
  <p><strong>Power BI Dashboard</strong><br>
  <img src="dashboards/powerbi_dashboard.png" alt="Dashboard Screenshot"><br>
  Automated FP&A reporting with interactive visuals.</p>

  <p><strong>SQL Practice Database</strong><br>
  <a href="projects/sql_queries.sql" target="_blank">View SQL Scripts</a><br>
  Built sample queries for financial data analysis and reporting.</p>

  <p><strong>Excel FP&A Model</strong><br>
  <a href="projects/fpa_model.xlsx" target="_blank">View Excel Model</a><br>
  Variance analysis and forecasting using advanced Excel functions.</p>
</div>

<div id="education" class="section">
  <h2>🎓 Education & Awards</h2>
  <ul>
  <li>
    <strong>M.Com (Finance)</strong> – Govt. College for Women, Thiruvananthapuram
    <ul>
      <li><em>University Rank Holder</em></li>
      <li><em>Aspire Research Award</em></li>
    </ul>
  </li>
  <li>
    <strong>B.Com (Taxation)</strong> – KNM Govt. Arts & Science College
    <ul>
      <li><em>University 2nd Rank Holder</em></li>
      <li><em>Best Manager Competition Winner</em></li>
    </ul>
  </li>
</ul>
</div>

<div id="skills" class="section">
  <h2>🏆 Skills</h2>
  <ul>
    <li>Excel: Pivot Tables, XLOOKUP, INDEX-MATCH</li>
    <li>Power BI: Data Modeling, DAX, Power Query</li>
    <li>SQL: Beginner–Intermediate</li>
    <li>ERP Tools: SAP Concur, Tally ERP</li>
    <li>FP&A Expertise: Budgeting, Forecasting, Variance Analysis, P&L Analysis</li>
  </ul>
</div>

<div id="contact" class="section">
  <h2>📬 Contact</h2>
  <p>LinkedIn Profile: <a href="https://www.linkedin.com/in/rukmini-ks-98a13725a/" target="_blank">LinkedIn</a><br>
  Email: rukminik2skishsun20@gmail.com<br>
  Phone: +91-9148866329</p>
</div>

<script>
  function showSection(id) {
    // Hide all sections
    document.querySelectorAll('.section').forEach(sec => sec.classList.remove('active'));
    // Show the clicked section
    document.getElementById(id).classList.add('active');
  }
</script>

</body>
</html>
