---

title: "Mohamad Ali Jarkas — Resume"
layout: null
permalink: /
------------

<style>
  :root {
    --bg: #0b0f14;
    --card: #111827;
    --text: #e5e7eb;
    --muted: #9ca3af;
    --accent: #60a5fa;
    --chip: #1f2937;
    --link: #93c5fd;
    --border: #1f2937;
  }
  @media (prefers-color-scheme: light) {
    :root {
      --bg: #f8fafc;
      --card: #ffffff;
      --text: #0b1220;
      --muted: #475569;
      --accent: #1d4ed8;
      --chip: #f1f5f9;
      --link: #1d4ed8;
      --border: #e2e8f0;
    }
  }
  * { box-sizing: border-box; }
  body {
    margin: 0;
    font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans", "Apple Color Emoji", "Segoe UI Emoji";
    background: var(--bg);
    color: var(--text);
    line-height: 1.6;
  }
  a { color: var(--link); text-decoration: none; }
  a:hover { text-decoration: underline; }
  .container { max-width: 980px; margin: 0 auto; padding: 28px 20px 64px; }
  .header { display: grid; grid-template-columns: 1fr auto; gap: 16px; align-items: center; }
  .name { font-size: clamp(28px, 4vw, 40px); font-weight: 800; letter-spacing: -0.02em; }
  .role { color: var(--muted); font-size: 1.05rem; }
  .meta { color: var(--muted); font-size: 0.98rem; margin-top: 4px; }
  .btn { display: inline-block; border: 1px solid var(--border); padding: 10px 14px; border-radius: 12px; background: linear-gradient(180deg, #1f2937, #111827); color: var(--text); font-weight: 600; }
  .btn:hover { filter: brightness(1.05); }
  .pill { display:inline-block; padding: 4px 10px; border-radius: 999px; border:1px solid var(--border); background: var(--chip); font-size: 0.9rem; color: var(--muted); }
  .grid-2 { display: grid; gap: 16px; }
  @media (min-width: 820px) { .grid-2 { grid-template-columns: 1fr 1fr; } }
  .section { background: var(--card); border: 1px solid var(--border); border-radius: 16px; padding: 18px 20px; margin-top: 16px; }
  .section h2 { margin: 0 0 10px 0; font-size: 1.25rem; letter-spacing: -0.01em; }
  .section h3 { margin: 8px 0 2px 0; font-size: 1.05rem; }
  .list { padding-left: 1.05rem; margin: 6px 0 0 0; }
  .list > li { margin: 6px 0; }
  .chips { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 8px; }
  .chip { padding: 6px 10px; background: var(--chip); border: 1px solid var(--border); border-radius: 999px; font-size: 0.9rem; }
  .small { color: var(--muted); font-size: 0.95rem; }
  hr { border: 0; border-top: 1px solid var(--border); margin: 16px 0; }
  .footer { color: var(--muted); text-align: center; margin-top: 24px; font-size: 0.95rem; }
  .nav { display:flex; gap:10px; flex-wrap:wrap; margin-top: 8px; }
  .nav a { border:1px solid var(--border); padding:6px 10px; border-radius:10px; background: var(--chip); }
  .print-hide { display: inline-block; }
  @media print {
    body { background: #fff; color: #000; }
    .section { border: 0; background: #fff; padding: 0; margin: 14px 0; }
    .print-hide, .nav { display:none; }
    a { color: #000; text-decoration: underline; }
    .chip { border: 1px solid #777; background: #fff; }
  }
</style>

<div class="container">
  <header class="header">
    <div>
      <div class="name">Mohamad Ali Jarkas</div>
      <div class="role">AI/ML · Signal Processing · Embedded Systems</div>
      <div class="meta">Ottawa, Canada · <a href="mailto:YOUR_EMAIL@example.com">YOUR_EMAIL@example.com</a> · <a href="https://github.com/YOUR_GITHUB" target="_blank" rel="noopener">GitHub</a> · <a href="https://www.linkedin.com/in/YOUR_LINKEDIN" target="_blank" rel="noopener">LinkedIn</a></div>
      <div class="nav small">
        <a href="#aiml">AI/ML</a>
        <a href="#signal">Signal Processing</a>
        <a href="#experience">Experience</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
      </div>
    </div>
    <div class="print-hide">
      <a class="btn" href="/assets/Mohamad_Ali_Jarkas_Resume.pdf" download>Download PDF</a>
    </div>
  </header>

  <section class="section" id="summary">
    <h2>Summary</h2>
    <p>
      Electrical/Software engineer working across <strong>machine learning</strong>, <strong>signal processing</strong>, and <strong>embedded systems</strong>. Practical experience from low-level C/C++ firmware and PCB design to PyTorch-based LLM research. Built an <strong>AWGN simulation codebase</strong> in modern C++ (≈3.5k LOC) and delivered production features at Cisco. Comfortable shipping on Linux and Windows, and cleaning up legacy code without breaking real-time constraints.
    </p>
  </section>

  <section class="section" id="aiml">
    <h2>AI / ML</h2>
    <ul class="list">
      <li>Researched architectures for LLM classification tasks with <strong>lmsys</strong>.</li>
      <li>Proposed a <strong>parallel BERT</strong> variant to extend effective context and handle more input tokens.</li>
      <li><span class="small">Tech:</span> <span class="chip">PyTorch</span> <span class="chip">CUDA</span> <span class="chip">Hugging Face Transformers</span> <span class="chip">oLlama</span> <span class="chip">Python</span> <span class="chip">Linux</span></li>
    </ul>
  </section>

  <section class="section" id="signal">
    <h2>Signal Processing</h2>
    <ul class="list">
      <li>Designed and implemented an <strong>AWGN codebase in C++</strong> to simulate coding/decoding techniques including <strong>polar codes</strong>.</li>
      <li>Focus on abstraction, organization, and minimizing technical debt; current size ≈ <strong>3500 LOC</strong>.</li>
      <li><span class="small">Tech:</span> <span class="chip">C++</span> <span class="chip">CMake</span> <span class="chip">Make</span> <span class="chip">Neovim</span> <span class="chip">Ubuntu</span> <span class="chip">WSL2</span> <span class="chip">Gitea</span> <span class="chip">Git</span> <span class="chip">Linux</span></li>
    </ul>
  </section>

  <section class="section" id="experience">
    <h2>Experience</h2>

```
<h3>Arkalumen — Intern</h3>
<div class="small">Embedded · Firmware · Desktop</div>
<ul class="list">
  <li>Built a <strong>Windows C#/.NET</strong> app for CCT interpolation (cubic spline), applying OS primitives (mutexes).</li>
  <li>Designed a <strong>USB Type‑C PD compliant PCB</strong> enabling MCU programming/debug over a single port; switched between <em>DEBUG</em> (ICSP pins mapped to USB) and standard USB 2.0 operation.</li>
  <li>Debugged LED controller PCBs and firmware.</li>
  <li>Developed <strong>ESP32 firmware</strong> (C) for BLE comms, PWM LED driving, and ADC current sensing loops.</li>
  <li>Ran experiments on <strong>thermal efficiency</strong> and <strong>ceramic capacitor heat‑induced degradation</strong> (&lt;1206 footprint).</li>
  <li>Represented the company in communications with international partners.</li>
  <li><span class="small">Tech:</span> <span class="chip">C#</span> <span class="chip">.NET</span> <span class="chip">C</span> <span class="chip">Python</span> <span class="chip">KiCad</span> <span class="chip">Oscilloscope</span> <span class="chip">Multimeter</span> <span class="chip">Soldering</span> <span class="chip">Hot Air</span> <span class="chip">Thermal Camera</span> <span class="chip">VS Code</span> <span class="chip">Linux</span></li>
</ul>
<hr>

<h3>Cisco Systems — Software Engineering Intern</h3>
<div class="small">Systems · Networking</div>
<ul class="list">
  <li>Delivered a feature for <strong>Cisco IOS‑XE</strong>: overhauled a critical real‑time operation, simplified code paths, and improved performance.</li>
  <li>Reduced reliance on custom libs by migrating to <strong>native Linux</strong> facilities; set groundwork for future work.</li>
  <li>Learned and used Linux signaling, sync/async callbacks, and OS‑level concepts.</li>
  <li><span class="small">Tech:</span> <span class="chip">C</span> <span class="chip">Bash</span> <span class="chip">Python</span> <span class="chip">VS Code</span> <span class="chip">Git</span> <span class="chip">Linux</span></li>
</ul>
<hr>

<h3>Rianta Solutions (acquired by Marvell) — Verification Intern</h3>
<div class="small">RTL Verification</div>
<ul class="list">
  <li>Built a <strong>UVM</strong> testbench with constrained‑random stimulus and <strong>functional coverage</strong>.</li>
  <li>Integrated, debugged, and simulated an <strong>Ethernet IP RTL wrapper</strong>.</li>
  <li><span class="small">Tech:</span> <span class="chip">SystemVerilog</span> <span class="chip">UVM</span> <span class="chip">Bash</span> <span class="chip">Vim</span> <span class="chip">Linux</span></li>
</ul>
<hr>

<h3>MATE ROV (Kelpie Team) — Founding Member → Electrical Team Lead</h3>
<div class="small">Robotics</div>
<ul class="list">
  <li>Designed the original <strong>ROV power distribution</strong> system.</li>
  <li>Wrote a <strong>PMBus (I²C) library</strong> for DC step‑down converter control.</li>
  <li>Drove team documentation standards for production readiness.</li>
  <li><span class="small">Tech:</span> <span class="chip">Arduino IDE</span> <span class="chip">C</span> <span class="chip">Espressif (VS Code)</span> <span class="chip">KiCad</span> <span class="chip">Fusion 360</span> <span class="chip">Power tools</span> <span class="chip">Linux</span></li>
</ul>
<hr>

<h3>University of Ottawa — Research</h3>
<div class="small">Haptics · Drones · Embedded</div>
<ul class="list">
  <li>Debugged <strong>ESP32</strong> controllers with BLE and LoRa comms; flew drones, designed experiments, and produced publication‑quality figures.</li>
  <li>Co‑published first research paper; second paper co‑authored (pending).</li>
  <li>Ran a literature + commercial review of <strong>haptic jackets</strong>.</li>
  <li>Designed a <strong>haptic jacket prototype</strong>: authored proposal, soldered PWM motors, and built a control stack on an <strong>NVIDIA Jetson</strong>.</li>
  <li><span class="small">Tech:</span> <span class="chip">Arduino IDE</span> <span class="chip">C</span> <span class="chip">Java</span> <span class="chip">Inkscape</span> <span class="chip">Linux</span></li>
</ul>
```

  </section>

  <section class="section" id="projects">
    <h2>Selected Projects</h2>
    <ul class="list">
      <li><strong>AWGN Simulation Suite (C++)</strong> — modular, extensible codebase for coding/decoding (incl. polar codes); designed for clarity and low technical debt.</li>
      <li><strong>Parallel BERT Concept</strong> — exploration of parallel token processing to extend context without prohibitive compute growth.</li>
    </ul>
  </section>

  <section class="section" id="skills">
    <h2>Skills</h2>
    <div class="chips">
      <span class="chip">C</span>
      <span class="chip">C++</span>
      <span class="chip">Python</span>
      <span class="chip">PyTorch</span>
      <span class="chip">CUDA</span>
      <span class="chip">Transformers (HF)</span>
      <span class="chip">ESP32</span>
      <span class="chip">BLE</span>
      <span class="chip">LoRa</span>
      <span class="chip">UVM</span>
      <span class="chip">SystemVerilog</span>
      <span class="chip">CMake</span>
      <span class="chip">Make</span>
      <span class="chip">Git</span>
      <span class="chip">Linux</span>
      <span class="chip">Windows</span>
      <span class="chip">PCB Design (KiCad)</span>
      <span class="chip">Debug (Scope/Logic)</span>
    </div>
  </section>

  <div class="footer">
    Last updated: {{ site.time | date: "%B %d, %Y" }} · Print this page for a clean PDF, or use the button to download your uploaded resume.
  </div>
</div>

<!-- Optional structured data for better SEO -->

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Mohamad Ali Jarkas",
  "url": "https://YOUR_GITHUB.github.io/",
  "sameAs": [
    "https://github.com/YOUR_GITHUB",
    "https://www.linkedin.com/in/YOUR_LINKEDIN"
  ],
  "jobTitle": "Engineer (AI/ML, Signal Processing, Embedded)",
  "address": {"@type": "PostalAddress", "addressLocality": "Ottawa", "addressCountry": "CA"},
  "knowsAbout": ["Machine Learning", "Signal Processing", "Embedded Systems", "C++", "C", "Python", "PyTorch", "CUDA", "ESP32", "UVM", "SystemVerilog", "KiCad", "Linux"]
}
</script>
