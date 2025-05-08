<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>_root@enrico:~</title>
  <style>
    body {
      background-color: #0d0d0d;
      color: #33ff33;
      font-family: 'Courier New', Courier, monospace;
      padding: 2rem;
    }

    h1, h2, h3 {
      color: #00ff99;
      text-align: center;
    }

    a {
      color: #33ccff;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .section {
      margin-bottom: 2.5rem;
    }

    .intro, .skills {
      max-width: 800px;
      margin: 0 auto;
      line-height: 1.6;
    }

    .badge {
      display: inline-block;
      margin-top: 1rem;
      text-align: center;
    }

    .badge img {
      height: 30px;
    }

    table {
      margin-top: 1rem;
      width: 100%;
      max-width: 800px;
      margin-left: auto;
      margin-right: auto;
      border-collapse: collapse;
    }

    th, td {
      padding: 0.8rem;
      border-bottom: 1px solid #33ff33;
      text-align: left;
    }

    .cursor {
      font-weight: bold;
      font-size: 1.2rem;
      color: #33ff33;
      animation: blink 1s step-start infinite;
    }

    @keyframes blink {
      50% { opacity: 0; }
    }

    hr {
      border: none;
      border-top: 1px solid #33ff33;
      margin: 2rem auto;
      width: 80%;
    }
  </style>
</head>
<body>

  <h1>🛡️# 👋 Hello, I'm Enrico <span class="cursor">|</span></h1>
  <p style="text-align:center;"><i>Welcome to my repository</i></p>

  <div class="badge">
    <a href="https://linkedin.com/in/enrico-favaro-b57301196" target="_blank">
      <img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
    </a>
  </div>

  <div class="section intro">
    <p>
      I'm a career-changer with a diverse professional background spanning logistics, purchasing, and hospitality. Over the past few years, I’ve developed a growing passion for <strong>Cybersecurity</strong>, driven by curiosity, continuous learning, and a desire to solve real-world digital threats.
    </p>
    <p>
      While I don’t come from a traditional tech path, I bring a unique mix of discipline, problem-solving, and operational awareness from my previous roles — skills I now apply to labs, tools, and training environments focused on <strong>SOC operations</strong>, <strong>incident response</strong>, and <strong>automation</strong>.
    </p>
  </div>

  <hr>

  <div class="section">
    <h2>🎯 Objective</h2>
    <p class="intro">
      To join a dynamic SOC team as a <strong>Cybersecurity Analyst (Tier 1)</strong> and actively contribute to protecting organizational assets while continuously learning and growing within the field of cybersecurity.
    </p>
  </div>

  <hr>

  <div class="section">
    <h2>💡 Skills & Projects</h2>
    <table>
      <tr>
        <th>Skill</th>
        <th>Project Link</th>
      </tr>
      <tr>
        <td>Network Traffic Monitoring & Attack Detection<br>(SNORT + ZEEK)</td>
        <td><a href="https://github.com/Otacrob/Rilevare-e-risolvere-connessione-remota-non-autorizzata" target="_blank">Detection Lab</a></td>
      </tr>
      <tr>
        <td>Wazuh + Sysmon SIEM Lab – Windows Endpoint Monitoring</td>
        <td><a href="https://github.com/Otacrob/Wazuh_and_Sysmon_SIEM_Lab/blob/main/README.md" target="_blank">Detection Lab</a></td>
      </tr>
      <!-- Add more rows as you grow -->
    </table>
  </div>

</body>
</html>
