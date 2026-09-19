<html>
<head>
  <title>🌟 Rukmini KS || FP&A Associate</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      background-image: url('Copilot_20260914_210938.png');
      background-size: cover;
      background-repeat: no-repeat;
      background-attachment: fixed;
      background-position: center;
      color: white;
      font-family: Arial, sans-serif;
      animation: fadeIn 2s ease-in;
      margin: 0;
      padding: 25px 35px;
    }

    /* Header layout */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      width: 100%;
      margin-bottom: 25px;
      gap: 20px;
    }

    /* Name on the left */
    h1 {
      color: #00aced;
      margin: 0;
      font-size: 28px;
      white-space: nowrap;
      flex-shrink: 0;
    }

    /* Navigation buttons on the right */
    header > div {
      display: flex;
      align-items: center;
      justify-content: flex-end;
      flex-wrap: nowrap;
      gap: 5px;
      white-space: nowrap;
    }

    .nav-btn {
      display: inline-block;
      background-color: #00aced;
      color: white;
      padding: 9px 13px;
      margin: 0;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
      font-size: 13px;
      white-space: nowrap;
    }

    .nav-btn:hover {
      background-color: #0077b5;
    }

    /* Wider content/data area */
    .section {
      display: none;
      margin-top: 20px;
      text-align: left;

      /* Increased width */
      width: 95%;
      max-width: 1400px;

      margin-left: auto;
      margin-right: auto;

      line-height: 1.6;
    }

    .section.active {
      display: block;
      border-left: 4px solid #00aced;
      padding: 20px 25px;

      /* Slightly transparent background */
      background-color: rgba(17, 17, 17, 0.90);

      border-radius: 5px;
    }

    /* About section */
    .about-container {
      display: flex;
      align-items: center;
    }

    .about-container img {
      width: 200px;
      height: auto;
      margin-right: 25px;
      border-radius: 8px;
    }

    /* Dashboard image */
    #projects img {
      max-width: 100%;
      height: auto;
      border-radius: 5px;
    }

    /* Links */
    a {
      color: #00aced;
      font-weight: bold;
    }

    a:hover {
      color: #66d9ff;
    }

    /* Resume */
    iframe {
      width: 100%;
      height: 650px;
      border: none;
    }

    /* Prevent navigation wrapping on smaller screens */
    @media (max-width: 1200px) {
      body {
        padding: 20px;
      }

      h1 {
        font-size: 23px;
      }

      .nav-btn {
        padding: 8px 9px;
        font-size: 11px;
      }
    }
  </style>
</head>

<body>

<!-- Header with name left and navigation buttons right -->
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


<!-- ABOUT -->
<div id="about" class="section active">

  <div class="about-container">
    <img src="Profile Photo(1).png"
         alt="Profile Photo">
    <div>
      <h2 style="color:#00aced;">Rukmini KS</h2>
      <p>Associate – Business Finance (FP&A) at UST Global.</p>
      <p>
        Passionate about corporate finance, analytics, and automation.
      </p>
      <p>
        Skilled in turning complex data into actionable insights
        for stakeholders.
      </p>
    </div>

  </div>

</div>


<!-- RESUME -->
<div id="resume" class="section">

  <h2>📄 Resume</h2>

  <iframe src="Rukmini_KS_Resume_v3.pdf"></iframe>

  <p>
    <a href="Rukmini_KS_Resume_v3.pdf" download>
      Download Resume
    </a>
  </p>

</div>


<!-- EXPERIENCE -->
<div id="experience" class="section">

  <h2>💼 Experience</h2>

  <h3>UST Global – Associate, Business Finance (FP&A)</h3>

  <ul>
    <li>Budgeting, Forecasting, Variance Analysis, and P&L Analysis</li>
    <li>
      Automated reporting workflows, reducing cycle time by 50%
    </li>
    <li>
      Partnered with stakeholders to deliver accurate and timely insights
    </li>
  </ul>

</div>


<!-- PROJECTS -->
<div id="projects" class="section">

  <h2>📊 Demo Projects</h2>

  <p>
    <strong>Power BI Dashboard</strong>
    <br>
    <img src="dashboards/powerbi_dashboard.png"
         alt="Dashboard Screenshot">
    <br>
    Automated FP&A reporting with interactive visuals.
  </p>


  <p>
    <strong>SQL Practice Database</strong>
    <br>
    <a href="projects/sql_queries.sql" target="_blank">
      View SQL Scripts
    </a>
    <br>
    Built sample queries for financial data analysis and reporting.
  </p>


  <p>
    <strong>Excel FP&A Model</strong>
    <br>
    <a href="projects/fpa_model.xlsx" target="_blank">
      View Excel Model
    </a>
    <br>
    Variance analysis and forecasting using advanced Excel functions.
  </p>

</div>


<!-- EDUCATION -->
<div id="education" class="section">

  <h2>🎓 Education & Awards</h2>

  <ul>
    <li>
      <strong>M.Com (Finance)</strong> –
      Govt. College for Women, Thiruvananthapuram
      <ul>
        <li><em>University Rank Holder</em></li>
        <li><em>Aspire Research Award</em></li>
      </ul>
    </li>
    <li>
      <strong>B.Com (Taxation)</strong> –
      KNM Govt. Arts & Science College
      <ul>
        <li><em>University 2nd Rank Holder</em></li>
        <li><em>Best Manager Competition Winner</em></li>
      </ul>
    </li>

  </ul>

</div>


<!-- SKILLS -->
<div id="skills" class="section">

  <h2>🏆 Skills</h2>

  <ul>
    <li>
      Excel: Pivot Tables, XLOOKUP, INDEX-MATCH
    </li>
    <li>
      Power BI: Data Modeling, DAX, Power Query
    </li>
    <li>
      SQL: Beginner–Intermediate
    </li>
    <li>
      ERP Tools: SAP Concur, Tally ERP
    </li>
    <li>
      FP&A Expertise: Budgeting, Forecasting,
      Variance Analysis, P&L Analysis
    </li>

  </ul>

</div>


<!-- CONTACT -->
<div id="contact" class="section">

  <h2>📬 Contact</h2>

  <p>
    LinkedIn Profile:
    <a href="https://www.linkedin.com/in/rukmini-ks-98a13725/"
       target="_blank">
      LinkedIn
    </a>
    <br><br>
    Email: rukminik2skishsun20@gmail.com
    <br><br>
    Phone: +91-9148866329
  </p>

</div>


<script>

  function showSection(id) {

    document
      .querySelectorAll('.section')
      .forEach(sec => sec.classList.remove('active'));

    document
      .getElementById(id)
      .classList.add('active');

  }

</script>

</body>
</html>
```

### What I changed

* **Name stays on the far left**.
* **All 7 navigation buttons stay on one line** on the right.
* Reduced button padding/font slightly so they fit better.
* Increased the content area from `1000px` to **1400px**.
* Made the content area **95% of the screen width**.
* Added more internal padding so the information doesn't look cramped.
* Made the background of the data area slightly transparent so your background image remains visible.
* Made the **Power BI dashboard automatically use the available wider space**.
* Increased the Resume viewer to **650px height**.
* Added a small responsive adjustment for narrower screens.

If your monitor is wide, this should give you a much more **professional portfolio/dashboard-style layout**, with the name on the left and the complete navigation bar on one line.
