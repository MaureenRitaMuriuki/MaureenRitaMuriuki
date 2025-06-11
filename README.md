<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Maureen Rita | Cybersecurity Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      background: #fff0f5;
      color: #1a1a1a;
      line-height: 1.6;
      padding: 2rem;
    }
    h1, h2, h3 {
      text-align: center;
      margin-bottom: 1rem;
    }
    section {
      margin-bottom: 2rem;
      background: #ffffff;
      padding: 1.5rem;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
    }
    .projects, .certifications, .experience {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1rem;
    }
    .card {
      background: #fffafc;
      border: 1px solid #f9c6d0;
      padding: 1rem;
      border-radius: 10px;
    }
    .contact-form {
      max-width: 600px;
      margin: 0 auto;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background: #f8c8dc;
      border: none;
      padding: 0.75rem 2rem;
      border-radius: 5px;
      cursor: pointer;
    }
    img {
      max-width: 100%;
      border-radius: 8px;
    }
    .resume-link {
      text-align: center;
      margin-top: 1rem;
    }
    .resume-link a {
      display: inline-block;
      margin-top: 0.5rem;
      background: #f8c8dc;
      padding: 0.75rem 1.5rem;
      border-radius: 5px;
      text-decoration: none;
      color: #1a1a1a;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <h1>Maureen Rita</h1>
  <p align="center">
    <strong>Offensive Security Specialist | Red Team Operator | Threat Simulation Expert</strong><br>
    </p>

  <section>
    <h2>🫠 Professional Summary</h2>
    <p>Detail-oriented and passionate <strong>Cybersecurity Analyst</strong> with proven experience in <strong>penetration testing</strong>, <strong>threat detection</strong>, <strong>incident response</strong>, and <strong>vulnerability assessment</strong>. Skilled in using offensive security techniques across platforms like Hack The Box, Cyberspace CTFs, and simulated attack environments.</p>
    <p>Combines deep technical acumen with excellent communication and documentation skills to deliver impactful, actionable security insights. Excels in fast-paced environments that demand adaptability, critical thinking, and innovation.</p>
    <ul>
      <li><strong>Cyber Defense:</strong> Threat Intelligence | Incident Response | Splunk Dashboards | Risk Remediation</li>
      <li><strong>Offensive Security:</strong> OWASP Top 10 | Web App Exploits | Vulnerability Scanning | Ethical Hacking</li>
      <li><strong>Technical Stack:</strong> Wireshark | Python | Bash | Burp Suite | Nmap | MTR | DNS Spoofing</li>
      <li><strong>Communication:</strong> Security Reporting | Executive Briefings | Awareness Campaigns</li>
    </ul>
  </section>

  <section class="resume-link">
    <h2>📄 View My Resume</h2>
    <p><a href="MaureenRita_CV.pdf" target="_blank">Download PDF</a></p>
  </section>

  <section>
    <h2>📜 Certifications & Credentials</h2>
    <p align="center">
      <a href="https://cybergirls.cybersafefoundation.org/" target="_blank">CyberGirls Fellowship</a> |
      <a href="https://cybersafefoundation.org" target="_blank">CyberSafe Training</a> |
      <a href="https://skillsforall.com" target="_blank">Cisco Threat Analysis</a> |
      <a href="https://www.linkedin.com/learning/" target="_blank">LinkedIn Security Certs</a> |
      <a href="https://academy.hackthebox.com" target="_blank">Hack The Box Academy</a>
    </p>
    <div class="certifications">
      <div class="card">CyberGirls Fellowship – Practical training in ethical hacking and labs</div>
      <div class="card">CyberSafe Security Training – IAM & OWASP Fundamentals</div>
      <div class="card">Cisco Security Courses – Network Defense & Threat Analysis</div>
      <div class="card">LinkedIn Learning – Phishing, SOC Tools, Threat Modeling</div>
      <div class="card">Hack The Box Academy – Linux & Web Application Security</div>
    </div>
  </section>

  <section>
    <h2>🚀 Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>DVWA Pentest</h3>
        <p>Full penetration test using Kali Linux on DVWA. Covered XSS, SQLi, Command Injection. Documented with screenshots and recommendations.</p>
      </div>
      <div class="card">
        <h3>Nmap Vulnerability Scanner</h3>
        <p>Python wrapper for Nmap. Automated vulnerable port detection. Parsed outputs and created summary reports.</p>
      </div>
      <div class="card">
        <h3>DNS Spoofing & Analysis</h3>
        <p>Simulated DNS spoofing and captured traffic using Wireshark. Demonstrated MITM vulnerabilities.</p>
      </div>
      <div class="card">
        <h3>Network Path Mapping</h3>
        <p>Used mtr and traceroute for diagnostics. Visualized latency and packet loss to detect bottlenecks.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>💼 Experience</h2>
    <div class="experience">
      <div class="card">
        <h3>Freelance Developer & Analyst (2021 – Present)</h3>
        <p>Secured web apps, improved incident response by 40%, implemented secure APIs.</p>
      </div>
      <div class="card">
        <h3>Cybersecurity Attaché – Judiciary of Kenya (2023)</h3>
        <p>Secured judiciary networks, trained users, improved database access controls.</p>
      </div>
      <div class="card">
        <h3>CTF Participant – Cyberspace Foundation (2023)</h3>
        <p>Performed exploit research, cryptography, penetration testing, and network defense.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>🎓 Education</h2>
    <div class="card">
      <p><strong>BSc. Information Technology – Dedan Kimathi University of Technology</strong></p>
      <p>Relevant Coursework: Network Security | Secure Software Dev | Cybersecurity Fundamentals</p>
    </div>
  </section>

  <section>
    <h2>👩🏽‍💼 Leadership & Volunteering</h2>
    <div class="card">
      <p><strong>President – Model United Nations</strong>: Led policy talks on AI, digital sovereignty, cyber law.</p>
      <p><strong>UNDP Student Ambassador – 2023</strong>: Advocated cybersecurity and digital inclusion in Africa.</p>
    </div>
  </section>

  <section>
    <h2>🧪 Virtual Experience Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>AIG Shields Up</h3>
        <p>Simulated ransomware, brute-forced keys, drafted CISA vuln remediation reports.</p>
      </div>
      <div class="card">
        <h3>Commonwealth Bank</h3>
        <p>Created Splunk dashboards, detected fraud trends, built secure UX infographics.</p>
      </div>
      <div class="card">
        <h3>Mastercard</h3>
        <p>Trained staff on phishing threats, customized security awareness modules.</p>
      </div>
      <div class="card">
        <h3>TCS IAM Analyst</h3>
        <p>Aligned IAM strategy with org goals, delivered C-level security reports.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>🎀 Contact Me</h2>
    <form class="contact-form">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

</body>
</html>
