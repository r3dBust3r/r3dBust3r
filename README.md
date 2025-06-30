<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>r3dBust3r | GitHub Bio</title>
  <style>
    body {
      background: #181c20;
      color: #f3f3f3;
      font-family: 'Segoe UI', Arial, sans-serif;
      margin: 0;
      padding: 0;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .container {
      background: rgba(30, 34, 40, 0.95);
      border-radius: 18px;
      box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
      padding: 2.5rem 2rem;
      max-width: 600px;
      width: 100%;
      animation: fadeIn 1.2s ease;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }
    h1 {
      font-size: 2.6rem;
      margin-bottom: 2rem;
    }
    .section {
      margin-top: 1.5rem;
      animation: fadeInUp 1s ease;
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .section-title {
      font-size: 1.2rem;
      color: #1fa2ff;
      margin-bottom: 0.5rem;
      letter-spacing: 0.5px;
      font-weight: 600;
    }
    ul.tech-list, ul.tools-list {
      list-style: none;
      padding: 0;
      margin: 0;
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem 1rem;
    }
    ul.tech-list li, ul.tools-list li {
      background: rgba(255,255,255,0.07);
      border-radius: 8px;
      padding: 0.3rem 0.8rem;
      font-size: 1rem;
      margin-bottom: 0.3rem;
      transition: background 0.3s;
      box-shadow: 0 2px 8px 0 rgba(31, 38, 135, 0.07);
      animation: popIn 0.7s cubic-bezier(.68,-0.55,.27,1.55) both;
    }
    @keyframes popIn {
      0% { opacity: 0; transform: scale(0.7); }
      100% { opacity: 1; transform: scale(1); }
    }
    .bio {
      font-size: 1.1rem;
      line-height: 1.7;
      margin-bottom: 1.2rem;
    }
    .emoji {
      font-size: 1.2em;
      vertical-align: middle;
      margin-right: 0.3em;
    }
    @media (max-width: 700px) {
      .container { padding: 1.2rem 0.5rem; }
      h1 { font-size: 1.5rem; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Hi, I'm <b>r3dBust3r</b> from Morocco</h1>
    <div class="bio">
        <span class="emoji">🔌</span> Background in <b>Networking & System Administration (Client/Server)</b><br>
        <span class="emoji">💻</span> Former <b>Web Developer</b><br>
        <span class="emoji">🛡️</span> Currently diving deep into <b>Cybersecurity</b><br>
        <span class="emoji">🚀</span> Passionate about <b>Hacking and Cyber Security</b>.
    </div>
    <img src="./animated-image.webp" style="display: block; width: 100%;">
    <div class="section">
      <div class="section-title">Web Technologies</div>
      <ul class="tech-list">
        <li title="HTML">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align:middle;"><path d="M3.5 2l1.7 19.1L12 22l6.8-0.9L20.5 2H3.5zm13.1 4.2l-0.1 1.5-0.1 1.3H7.6l0.1 1.5h7.5l-0.1 1.3-0.1 1.5H8.1l0.1 1.5h7.1l-0.1 1.3-0.1 1.5-3.1 0.4-3.1-0.4-0.2-2.2h1.5l0.1 1.1 1.7 0.2 1.7-0.2 0.1-1.1h1.5l-0.2 2.2-3.1 0.4-3.1-0.4L5.7 4.2h12.6z" fill="#E44D26"/></svg>
          HTML
        </li>
        <li title="CSS">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align:middle;"><path d="M3.5 2l1.7 19.1L12 22l6.8-0.9L20.5 2H3.5zm13.1 4.2l-0.1 1.5-0.1 1.3H7.6l0.1 1.5h7.5l-0.1 1.3-0.1 1.5H8.1l0.1 1.5h7.1l-0.1 1.3-0.1 1.5-3.1 0.4-3.1-0.4-0.2-2.2h1.5l0.1 1.1 1.7 0.2 1.7-0.2 0.1-1.1h1.5l-0.2 2.2-3.1 0.4-3.1-0.4L5.7 4.2h12.6z" fill="#1572B6"/></svg>
          CSS
        </li>
        <li title="SASS">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="10" fill="#CD6799"/><text x="12" y="16" text-anchor="middle" font-size="10" fill="#fff" font-family="Arial">SASS</text></svg>
          SASS
        </li>
        <li title="Tailwind">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align:middle;"><path d="M12 6.5c-2.5 0-4.1 1.3-4.8 3.8 1-1.3 2-1.8 3.1-1.8 1.1 0 1.8 0.6 2.2 1.7 0.4 1.1 1.1 1.7 2.2 1.7 1.1 0 2.1-0.6 3.1-1.8-0.7-2.5-2.3-3.6-4.8-3.6zm-4.8 5.7c-2.5 0-4.1 1.3-4.8 3.8 1-1.3 2-1.8 3.1-1.8 1.1 0 1.8 0.6 2.2 1.7 0.4 1.1 1.1 1.7 2.2 1.7 1.1 0 2.1-0.6 3.1-1.8-0.7-2.5-2.3-3.6-4.8-3.6z" fill="#38BDF8"/></svg>
          Tailwind
        </li>
        <li title="Bootstrap">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align:middle;"><rect width="24" height="24" rx="6" fill="#7952B3"/><text x="12" y="17" text-anchor="middle" font-size="13" fill="#fff" font-family="Arial">B</text></svg>
          Bootstrap
        </li>
        <li title="Javascript">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align:middle;"><rect width="24" height="24" rx="4" fill="#F7DF1E"/><text x="12" y="17" text-anchor="middle" font-size="13" fill="#000" font-family="Arial">JS</text></svg>
          Javascript
        </li>
        <li title="jQuery">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="10" fill="#0769AD"/><text x="12" y="16" text-anchor="middle" font-size="10" fill="#fff" font-family="Arial">jQ</text></svg>
          jQuery
        </li>
        <li title="PHP">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="10" fill="#777BB4"/><text x="12" y="16" text-anchor="middle" font-size="10" fill="#fff" font-family="Arial">PHP</text></svg>
          PHP
        </li>
        <li title="Laravel">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align:middle;"><rect width="24" height="24" rx="6" fill="#FF2D20"/><text x="12" y="17" text-anchor="middle" font-size="10" fill="#fff" font-family="Arial">L</text></svg>
          Laravel
        </li>
        <li title="MySQL">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="10" fill="#4479A1"/><text x="12" y="16" text-anchor="middle" font-size="10" fill="#fff" font-family="Arial">SQL</text></svg>
          MySQL
        </li>
        <li title="Python">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align:middle;"><rect width="24" height="24" rx="6" fill="#3776AB"/><text x="12" y="17" text-anchor="middle" font-size="10" fill="#FFD43B" font-family="Arial">Py</text></svg>
          Python
        </li>
        <li title="Bash">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align:middle;"><rect width="24" height="24" rx="6" fill="#4EAA25"/><text x="12" y="17" text-anchor="middle" font-size="10" fill="#fff" font-family="Arial">sh</text></svg>
          Bash
        </li>
      </ul>
    </div>
    <div class="section">
      <div class="section-title">Security Technologies and Tools</div>
      <ul class="tools-list">
        <li title="Nmap">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><circle cx="12" cy="12" r="10" fill="#4682B4"/><circle cx="12" cy="12" r="7" fill="none" stroke="#fff" stroke-width="1.5"/><line x1="12" y1="12" x2="19" y2="12" stroke="#fff" stroke-width="1.5" stroke-linecap="round"><animateTransform attributeName="transform" type="rotate" from="0 12 12" to="360 12 12" dur="2s" repeatCount="indefinite"/></line></svg>
          Nmap
        </li>
        <li title="Masscan">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><rect x="4" y="4" width="16" height="16" rx="4" fill="#7B1FA2"/><path d="M8 12h8" stroke="#fff" stroke-width="2" stroke-linecap="round"/><circle cx="12" cy="12" r="2" fill="#fff"/></svg>
          Masscan
        </li>
        <li title="Sublist3r">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#009688"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">Sub</text></svg>
          Sublist3r
        </li>
        <li title="theHarvester">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#607D8B"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">Hrv</text></svg>
          theHarvester
        </li>
        <li title="Shodan">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><circle cx="12" cy="12" r="10" fill="#F44336"/><circle cx="12" cy="12" r="4" fill="#fff"/></svg>
          Shodan
        </li>
        <li title="Nikto">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><rect x="4" y="4" width="16" height="16" rx="4" fill="#FF9800"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">N</text></svg>
          Nikto
        </li>
        <li title="Gobuster">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><rect x="4" y="4" width="16" height="16" rx="4" fill="#8BC34A"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">Go</text></svg>
          Gobuster
        </li>
        <li title="FFUF">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#FFC107"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">FF</text></svg>
          FFUF
        </li>
        <li title="Burp Suite">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><rect x="4" y="4" width="16" height="16" rx="4" fill="#FF5722"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">B</text></svg>
          Burp Suite
        </li>
        <li title="OWASP ZAP">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><polygon points="12,4 20,20 4,20" fill="#1976D2"/><text x="12" y="17" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">Z</text></svg>
          OWASP ZAP
        </li>
        <li title="OpenVAS">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#43A047"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">OV</text></svg>
          OpenVAS
        </li>
        <li title="Nuclei">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><circle cx="12" cy="12" r="10" fill="#00BCD4"/><circle cx="12" cy="12" r="4" fill="#fff"/><circle cx="12" cy="6" r="2" fill="#fff"/><circle cx="12" cy="18" r="2" fill="#fff"/></svg>
          Nuclei
        </li>
        <li title="Metasploit">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><rect x="4" y="4" width="16" height="16" rx="4" fill="#3F51B5"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">M</text></svg>
          Metasploit
        </li>
        <li title="SQLmap">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#FFEB3B"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#000" font-family="Arial">SQL</text></svg>
          SQLmap
        </li>
        <li title="ExploitDB">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><rect x="4" y="4" width="16" height="16" rx="4" fill="#E65100"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">EDB</text></svg>
          ExploitDB
        </li>
        <li title="John the Ripper">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#616161"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">JtR</text></svg>
          John the Ripper
        </li>
        <li title="Hashcat">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#9C27B0"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">HC</text></svg>
          Hashcat
        </li>
        <li title="Hydra">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#00C853"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">Hy</text></svg>
          Hydra
        </li>
        <li title="Medusa">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#00B8D4"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">Me</text></svg>
          Medusa
        </li>
        <li title="Aircrack-ng">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><polygon points="12,4 20,20 4,20" fill="#607D8B"/><text x="12" y="17" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">A</text></svg>
          Aircrack-ng
        </li>
        <li title="Wifite">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#C51162"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">Wi</text></svg>
          Wifite
        </li>
        <li title="Bettercap">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><rect x="4" y="4" width="16" height="16" rx="4" fill="#263238"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">Bc</text></svg>
          Bettercap
        </li>
        <li title="Setoolkit">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><rect x="4" y="4" width="16" height="16" rx="4" fill="#FF1744"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">ST</text></svg>
          Setoolkit
        </li>
        <li title="Mimikatz">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#FFD600"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#000" font-family="Arial">Mk</text></svg>
          Mimikatz
        </li>
        <li title="Ghidra">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><rect x="4" y="4" width="16" height="16" rx="4" fill="#FF6F00"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">Gh</text></svg>
          Ghidra
        </li>
        <li title="tcpdump">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#00BFAE"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">TD</text></svg>
          tcpdump
        </li>
        <li title="Wireshark">
          <svg width="24" height="24" viewBox="0 0 24 24" style="vertical-align:middle;"><ellipse cx="12" cy="12" rx="10" ry="8" fill="#0288D1"/><text x="12" y="16" text-anchor="middle" font-size="8" fill="#fff" font-family="Arial">WS</text></svg>
          Wireshark
        </li>
      </ul>
    </div>
  </div>
</body>
</html> 