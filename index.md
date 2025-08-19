<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mohamad Ali Jarkas — Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Share Tech Mono', monospace;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #1a1a1a;
      line-height: 1.6;
    }
    .container {
      max-width: 900px;
      margin: auto;
      padding: 50px 20px;
    }
    header {
      text-align: center;
      margin-bottom: 50px;
    }
    h1 {
      font-size: 3rem;
      color: #2a2a2a;
      margin: 0;
    }
    .role {
      font-size: 1.3rem;
      color: #555;
      margin-top: 10px;
    }
    section {
      margin-bottom: 40px;
    }
    h2 {
      cursor: pointer;
      font-size: 1.6rem;
      color: #222;
      border-bottom: 1px solid #ccc;
      padding-bottom: 6px;
      transition: color 0.2s;
      position: relative;
    }
    h2::after {
      content: '\25B6';
      position: absolute;
      right: 0;
      transition: transform 0.3s;
    }
    h2.active::after {
      transform: rotate(90deg);
    }
    h2:hover { color: #0077cc; }
    .content {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.5s ease, padding 0.5s ease;
      padding-left: 10px;
      margin-top: 10px;
      border-left: 2px solid #ccc;
    }
    .content.open {
      max-height: 3000px;
      padding-top: 10px;
    }
    .chip {
      display: inline-block;
      background: #e0e0e0;
      color: #333;
      padding: 5px 12px;
      border-radius: 5px;
      margin: 3px;
      font-size: 0.9rem;
      border: 1px solid #ccc;
    }
    ul {
      padding-left: 20px;
      margin: 10px 0;
    }
    li { margin-bottom: 6px; }
    footer {
      text-align: center;
      margin-top: 60px;
      color: #555;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Mohamad Ali Jarkas</h1>
      <div class="role">AI / ML · Signal Processing · Embedded Systems</div>
    </header>

    <section>
      <h2>AI / ML</h2>
      <div class="content">
        <ul>
          <li>Researched different architectures for LLM classification tasks by lmsys.</li>
          <li>Suggested a new <strong>parallel BERT architecture</strong> to increase context window and allow more input tokens.</li>
          <li>Technologies used: <span class="chip">PyTorch</span> <span class="chip">CUDA</span> <span class="chip">Transformers</span> <span class="chip">oLlama</span> <span class="chip">Python</span> <span class="chip">Linux</span></li>
        </ul>
      </div>
    </section>

    <section>
      <h2>Signal Processing</h2>
      <div class="content">
        <ul>
          <li>Designed and implemented an <strong>AWGN codebase in C++</strong> to simulate different coding and decoding techniques, including polar codes.</li>
          <li>Code written with focus on proper abstraction, organization, and minimization of technical debt.</li>
          <li>Biggest codebase written (~3500 LOC).</li>
          <li>Technologies used: <span class="chip">C++</span> <span class="chip">CMake</span> <span class="chip">Make</span> <span class="chip">Neovim</span> <span class="chip">Ubuntu</span> <span class="chip">WSL2</span> <span class="chip">Gitea & Git</span> <span class="chip">Linux</span></li>
        </ul>
      </div>
    </section>

    <section>
      <h2>Internships & Work</h2>
      <div class="content">
        <h3>Arkalumen</h3>
        <ul>
          <li>Designed and implemented a <strong>Windows app</strong> in C# and .NET for CCT interpolation using cubic spline interpolation.</li>
          <li>Implemented OS concepts such as mutexes.</li>
          <li>Designed and implemented a <strong>USB Type-C PD compliant PCB</strong> for MCU programming/debugging.</li>
          <li>Switched between DEBUG mode (ICSP pins connected to USB) and regular USB 2.0 operation.</li>
          <li>Debugged LED controller PCBs and firmware.</li>
          <li>Developed <strong>ESP32 firmware</strong> in C for BLE communication, PWM signal generation, ADC current sensing for feedback loops.</li>
          <li>Conducted experiments measuring thermal efficiency and effect of heat on capacitor degradation.</li>
          <li>Represented Arkalumen in communications with international partners.</li>
          <li>Technologies: <span class="chip">C#</span> <span class="chip">.NET</span> <span class="chip">C</span> <span class="chip">Python</span> <span class="chip">KiCad</span> <span class="chip">Oscilloscope</span> <span class="chip">Multimeter</span> <span class="chip">Soldering</span> <span class="chip">Hot Air Solder</span> <span class="chip">Thermal Camera</span> <span class="chip">VS/Code</span></li>
        </ul>

        <h3>Cisco Systems</h3>
        <ul>
          <li>Software development internship.</li>
          <li>Learned OS concepts, Linux signaling libraries, synchronous/asynchronous callbacks.</li>
          <li>Developed a feature for Cisco IOS-XE: overhauled critical real-time operation, trimmed codebase, increased speed, migrated from custom to native Linux libraries.</li>
          <li>Technologies: <span class="chip">C</span> <span class="chip">Bash</span> <span class="chip">Python</span> <span class="chip">VSCode</span> <span class="chip">Git</span> <span class="chip">Linux</span></li>
        </ul>

        <h3>Rianta Solutions (pre-Marvell)</h3>
        <ul>
          <li>Learned business side: acquisitions, transition periods.</li>
          <li>Technical work: SystemVerilog + UVM testbench, functional coverage, integrated/debugged Ethernet IP RTL wrapper.</li>
          <li>Technologies: <span class="chip">SystemVerilog</span> <span class="chip">UVM</span> <span class="chip">Bash</span> <span class="chip">Vim</span> <span class="chip">Linux</span></li>
        </ul>

        <h3>MATE ROV (Kelpie Team)</h3>
        <ul>
          <li>Founding member, later Electrical Team Lead.</li>
          <li>Designed original power distribution system for ROV.</li>
          <li>Wrote and implemented PMBus library (I²C) to communicate with DC step-down converter.</li>
          <li>Learned importance of documentation for production-ready products.</li>
          <li>Technologies: <span class="chip">Arduino IDE</span> <span class="chip">C</span> <span class="chip">Espressif VSCode</span> <span class="chip">KiCad</span> <span class="chip">Fusion360</span> <span class="chip">Power Tools</span></li>
        </ul>

        <h3>University of Ottawa Research</h3>
        <ul>
          <li>Debugged ESP32 controllers using BLE and LoRa.</li>
          <li>Drone experiments, designed experiments, created professional figures.</li>
          <li>Co-published first research paper.</li>
          <li>Literature and commercial review of haptic jackets.</li>
          <li>Designed/implemented haptic jacket prototype using PWM motors and NVIDIA Jetson.</li>
          <li>Technologies: <span class="chip">Arduino IDE</span> <span class="chip">C</span> <span class="chip">Java</span> <span class="chip">Inkscape</span></li>
        </ul>
      </div>
    </section>

    <section>
      <h2>Skills</h2>
      <div class="content">
        <span class="chip">C</span> <span class="chip">C++</span> <span class="chip">Python</span> <span class="chip">PyTorch</span> <span class="chip">CUDA</span> <span class="chip">Transformers</span> <span class="chip">ESP32</span> <span class="chip">BLE</span> <span class="chip">LoRa</span> <span class="chip">UVM</span> <span class="chip">SystemVerilog</span> <span class="chip">VHDL</span> <span class="chip">Java</span> <span class="chip">CMake</span> <span class="chip">Make</span> <span class="chip">Git</span> <span class="chip">Linux</span> <span class="chip">Windows</span> <span class="chip">PCB Design</span>
      </div>
    </section>

    <footer>Last updated: 2025-08-18</footer>
  </div>

  <script>
    document.querySelectorAll('h2').forEach(header => {
      header.addEventListener('click', () => {
        header.classList.toggle('active');
        header.nextElementSibling.classList.toggle('open');
      });
    });
  </script>
</body>
</html>
