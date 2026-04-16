<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>UP Board Class 10 Computer – Questions & Answers 2026</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800;900&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#0f1117;--surface:#161b27;--surface2:#1e2536;--border:#2a3148;
  --text:#e2e8f8;--muted:#6b7a9f;
  --c1:#f97316;--c2:#06b6d4;--c3:#8b5cf6;--c4:#10b981;--c5:#ef4444;
  --c6:#3b82f6;--c7:#f59e0b;--c8:#ec4899;--c9:#14b8a6;--star:#fbbf24;
  --ans-bg:rgba(16,185,129,0.06);--ans-border:rgba(16,185,129,0.25);
  --code-bg:#0d1117;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--text);font-family:'Poppins',sans-serif;min-height:100vh;overflow-x:hidden}
body::before{content:'';position:fixed;inset:0;z-index:0;pointer-events:none;
  background-image:linear-gradient(rgba(99,102,241,.04) 1px,transparent 1px),linear-gradient(90deg,rgba(99,102,241,.04) 1px,transparent 1px);
  background-size:48px 48px;}

/* HEADER */
header{position:relative;z-index:10;background:linear-gradient(135deg,#111827 0%,#1e1b4b 50%,#0f172a 100%);border-bottom:1px solid var(--border);overflow:hidden;}
header::after{content:'';position:absolute;inset:0;background:radial-gradient(ellipse 80% 80% at 50% -20%,rgba(99,102,241,.35),transparent);pointer-events:none;}
.header-inner{position:relative;z-index:2;max-width:1200px;margin:0 auto;padding:50px 24px 42px;display:flex;flex-direction:column;align-items:center;text-align:center;}
.up-pill{display:inline-flex;align-items:center;gap:8px;background:rgba(99,102,241,.18);border:1px solid rgba(99,102,241,.4);color:#a5b4fc;font-size:11px;font-weight:700;letter-spacing:3px;text-transform:uppercase;padding:6px 18px;border-radius:50px;margin-bottom:22px;}
header h1{font-size:clamp(2rem,5vw,3.6rem);font-weight:900;line-height:1.1;background:linear-gradient(135deg,#fff 0%,#c7d2fe 60%,#818cf8 100%);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;margin-bottom:10px;}
header h1 span{background:linear-gradient(135deg,#f97316,#fbbf24);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.header-sub{color:var(--muted);font-size:.9rem;max-width:580px;line-height:1.7;margin-bottom:32px;}
.hstats{display:flex;gap:2px;border:1px solid var(--border);border-radius:12px;overflow:hidden;background:rgba(0,0,0,.25);}
.hstat{padding:14px 22px;text-align:center;border-right:1px solid var(--border);}
.hstat:last-child{border-right:none;}
.hstat-n{display:block;font-family:'JetBrains Mono',monospace;font-size:1.6rem;font-weight:700;color:#818cf8;}
.hstat-l{display:block;font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--muted);margin-top:2px;}

/* MARQUEE */
.marquee-wrap{background:linear-gradient(90deg,#312e81,#1e1b4b,#312e81);border-top:1px solid rgba(99,102,241,.3);border-bottom:1px solid rgba(99,102,241,.3);padding:9px 0;overflow:hidden;white-space:nowrap;}
.marquee-track{display:inline-block;animation:marquee 35s linear infinite;font-size:12px;font-weight:600;letter-spacing:1.5px;color:#a5b4fc;}
@keyframes marquee{from{transform:translateX(100vw)}to{transform:translateX(-100%)}}

/* LAYOUT */
.layout{max-width:1200px;margin:0 auto;padding:32px 18px 100px;display:grid;grid-template-columns:256px 1fr;gap:26px;position:relative;z-index:2;}

/* SIDEBAR */
.sidebar{position:sticky;top:18px;align-self:start;}
.scard{background:var(--surface);border:1px solid var(--border);border-radius:14px;padding:18px;margin-bottom:14px;}
.scard-title{font-size:10px;font-weight:700;letter-spacing:3px;text-transform:uppercase;color:var(--muted);margin-bottom:12px;padding-bottom:10px;border-bottom:1px solid var(--border);}
.nav-item{display:flex;align-items:center;gap:9px;padding:8px 11px;border-radius:8px;margin-bottom:3px;text-decoration:none;color:var(--text);font-size:.81rem;font-weight:500;border:1px solid transparent;transition:all .18s;cursor:pointer;}
.nav-item:hover{background:var(--surface2);border-color:var(--border);}
.nav-dot{width:8px;height:8px;border-radius:50%;flex-shrink:0;}
.nav-badge{margin-left:auto;font-family:'JetBrains Mono',monospace;font-size:10px;color:var(--muted);background:var(--surface2);padding:2px 7px;border-radius:8px;}
.search-box{display:flex;align-items:center;gap:9px;background:var(--surface2);border:1px solid var(--border);border-radius:10px;padding:10px 13px;margin-bottom:26px;}
.search-box input{flex:1;background:none;border:none;outline:none;font-family:'Poppins',sans-serif;font-size:.85rem;color:var(--text);}
.search-box input::placeholder{color:var(--muted);}
.ep-grid{display:grid;grid-template-columns:1fr 1fr 1fr;gap:7px;margin-bottom:11px;}
.ep-box{background:var(--surface2);border:1px solid var(--border);border-radius:8px;padding:9px 5px;text-align:center;}
.ep-n{font-family:'JetBrains Mono',monospace;font-size:1rem;font-weight:700;}
.ep-l{font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:1px;margin-top:3px;}
.tip{background:rgba(251,191,36,.06);border:1px solid rgba(251,191,36,.22);border-radius:8px;padding:12px 13px;font-size:.76rem;line-height:1.7;color:#d4b96a;}
.tip strong{color:var(--star);}
.prog-pill{background:var(--surface2);border:1px solid var(--border);border-radius:8px;padding:11px 13px;display:flex;align-items:center;justify-content:space-between;}
.prog-label{font-size:.76rem;color:var(--muted);}
.prog-value{font-family:'JetBrains Mono',monospace;font-size:.95rem;font-weight:700;color:#818cf8;}
.prog-bar{height:4px;background:var(--border);border-radius:4px;margin-top:8px;overflow:hidden;}
.prog-fill{height:100%;background:linear-gradient(90deg,#818cf8,#06b6d4);border-radius:4px;transition:width .4s;width:0%;}

/* CHAPTER */
.chapter{background:var(--surface);border:1px solid var(--border);border-radius:16px;margin-bottom:22px;overflow:hidden;animation:fadeUp .4s ease both;}
@keyframes fadeUp{from{opacity:0;transform:translateY(16px)}to{opacity:1;transform:translateY(0)}}
.ch-head{display:flex;align-items:center;gap:13px;padding:18px 22px;cursor:pointer;user-select:none;border-bottom:1px solid transparent;transition:border-color .3s;}
.chapter.open .ch-head{border-bottom-color:var(--border);}
.ch-num{font-family:'JetBrains Mono',monospace;font-size:10px;font-weight:700;color:#000;padding:4px 9px;border-radius:6px;flex-shrink:0;}
.ch-icon{font-size:22px;flex-shrink:0;}
.ch-info{flex:1;}
.ch-name{font-size:.97rem;font-weight:700;color:var(--text);line-height:1.3;}
.ch-sub{font-size:10px;color:var(--muted);margin-top:2px;}
.ch-marks{font-family:'JetBrains Mono',monospace;font-size:11px;font-weight:700;color:#fff;padding:4px 11px;border-radius:20px;flex-shrink:0;}
.ch-arrow{color:var(--muted);font-size:12px;transition:transform .3s;flex-shrink:0;}
.chapter.open .ch-arrow{transform:rotate(180deg);}
.ch-body{display:none;padding:0 22px 26px;}
.chapter.open .ch-body{display:block;}
.qtype{display:flex;align-items:center;gap:11px;font-size:10px;font-weight:700;letter-spacing:2.5px;text-transform:uppercase;color:var(--muted);margin:22px 0 9px;}
.qtype::before,.qtype::after{content:'';flex:1;height:1px;background:var(--border);}

/* QUESTION ITEM */
.q-wrap{margin-bottom:9px;}
.q-item{display:flex;align-items:flex-start;gap:11px;padding:12px 14px;border-radius:10px;border:1px solid var(--border);background:var(--bg);cursor:pointer;transition:all .15s;position:relative;overflow:hidden;}
.q-item::before{content:'';position:absolute;left:0;top:0;bottom:0;width:3px;background:var(--item-color,#818cf8);opacity:0;transition:opacity .2s;}
.q-item:hover{border-color:rgba(255,255,255,.1);transform:translateX(2px);}
.q-item:hover::before{opacity:1;}
.q-item.done{background:rgba(16,185,129,.07);border-color:rgba(16,185,129,.3);}
.q-item.hot::after{content:'★ HOT';position:absolute;top:7px;right:-1px;background:var(--star);color:#000;font-size:9px;font-weight:800;letter-spacing:1px;padding:2px 8px 2px 6px;border-radius:4px 0 0 4px;}
.q-num{font-family:'JetBrains Mono',monospace;font-size:10px;font-weight:700;color:#000;padding:3px 7px;border-radius:5px;flex-shrink:0;margin-top:1px;min-width:36px;text-align:center;}
.q-text{font-size:.85rem;line-height:1.6;color:var(--text);flex:1;font-weight:500;}
.q-text em{font-style:normal;font-weight:700;}
.q-right{display:flex;flex-direction:column;align-items:flex-end;gap:6px;flex-shrink:0;}
.q-marks{font-family:'JetBrains Mono',monospace;font-size:10px;color:var(--muted);background:var(--surface2);border:1px solid var(--border);padding:2px 7px;border-radius:8px;}
.show-ans-btn{font-size:10px;font-weight:700;padding:4px 11px;border-radius:6px;border:none;cursor:pointer;letter-spacing:.5px;transition:all .15s;white-space:nowrap;}

/* ANSWER BOX */
.ans-box{display:none;background:var(--ans-bg);border:1px solid var(--ans-border);border-radius:0 0 10px 10px;padding:16px 18px;margin-top:-1px;animation:slideDown .25s ease;}
.ans-box.show{display:block;}
@keyframes slideDown{from{opacity:0;transform:translateY(-6px)}to{opacity:1;transform:translateY(0)}}
.ans-label{font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:#10b981;margin-bottom:10px;display:flex;align-items:center;gap:7px;}
.ans-label::after{content:'';flex:1;height:1px;background:rgba(16,185,129,.2);}
.ans-text{font-size:.83rem;line-height:1.8;color:#c8d8c0;}
.ans-text strong{color:#6ee7b7;font-weight:700;}
.ans-text ul{margin:8px 0 8px 20px;}
.ans-text ul li{margin-bottom:4px;}
.ans-text ol{margin:8px 0 8px 20px;}
.ans-text ol li{margin-bottom:4px;}
pre.code{background:var(--code-bg);border:1px solid var(--border);border-left:3px solid #10b981;border-radius:6px;padding:14px 16px;font-family:'JetBrains Mono',monospace;font-size:.76rem;line-height:1.75;color:#a5f3d0;overflow-x:auto;white-space:pre;margin:10px 0;}
.diff-table{width:100%;border-collapse:collapse;margin:10px 0;font-size:.8rem;}
.diff-table th{background:rgba(16,185,129,.15);color:#6ee7b7;padding:7px 12px;text-align:left;border:1px solid rgba(16,185,129,.2);}
.diff-table td{padding:6px 12px;border:1px solid rgba(255,255,255,.07);color:#c8d8c0;vertical-align:top;}
.diff-table tr:nth-child(even) td{background:rgba(255,255,255,.02);}
.key-point{background:rgba(251,191,36,.07);border-left:3px solid var(--star);border-radius:0 6px 6px 0;padding:8px 12px;margin:8px 0;font-size:.8rem;color:#fde68a;}

/* FLOAT */
.float-tracker{position:fixed;bottom:22px;right:22px;z-index:999;background:var(--surface);border:1px solid var(--border);border-radius:14px;padding:13px 18px;box-shadow:0 8px 40px rgba(0,0,0,.5);display:flex;flex-direction:column;align-items:center;gap:5px;min-width:128px;}
.ft-label{font-size:10px;color:var(--muted);letter-spacing:2px;text-transform:uppercase;}
.ft-num{font-family:'JetBrains Mono',monospace;font-size:1.9rem;font-weight:700;color:#818cf8;line-height:1;}
.ft-total{font-size:11px;color:var(--muted);}
.ft-btn{background:linear-gradient(135deg,#818cf8,#06b6d4);border:none;color:#000;font-family:'Poppins',sans-serif;font-size:11px;font-weight:700;padding:5px 15px;border-radius:20px;cursor:pointer;margin-top:3px;}

@media(max-width:820px){.layout{grid-template-columns:1fr}.sidebar{position:static}.hstats{flex-wrap:wrap}.hstat{flex:1 1 40%;border-right:none;border-bottom:1px solid var(--border)}}
</style>
</head>
<body>

<header>
  <div class="header-inner">
    <div class="up-pill">🎓 UPMSP · UP Board · Class 10 · 2025–26</div>
    <h1>Computer Science<br><span>Questions & Answers 2026</span></h1>
    <p class="header-sub">Chapter-wise most important Q&A for UP Board Exam 2026 — C Language, Arrays, Functions, Structures, Pointers, AI, Drone, E-Commerce, Cyber Security. Click any question to see the answer!</p>
    <div class="hstats">
      <div class="hstat"><span class="hstat-n">87+</span><span class="hstat-l">Questions</span></div>
      <div class="hstat"><span class="hstat-n">9</span><span class="hstat-l">Chapters</span></div>
      <div class="hstat"><span class="hstat-n">✅</span><span class="hstat-l">With Answers</span></div>
      <div class="hstat"><span class="hstat-n">70</span><span class="hstat-l">Theory Marks</span></div>
    </div>
  </div>
</header>
<div class="marquee-wrap"><span class="marquee-track">★ HOT = Appeared 3+ times in previous UP Board exams &nbsp;|&nbsp; Click any question to reveal its answer &nbsp;|&nbsp; C Language · Arrays · Functions · Structures · Pointers · File Handling · AI · Drone · E-Commerce · E-Governance · Cyber Security &nbsp;|&nbsp; 70 Marks Theory + 30 Marks Practical &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></div>

<div class="layout">

<!-- SIDEBAR -->
<aside class="sidebar">
  <div class="scard">
    <div class="scard-title">📚 Jump to Chapter</div>
    <div class="nav-item" onclick="openCh('ch1')"><span class="nav-dot" style="background:var(--c1)"></span>Ch 1 · Introduction to C<span class="nav-badge">12M</span></div>
    <div class="nav-item" onclick="openCh('ch2')"><span class="nav-dot" style="background:var(--c2)"></span>Ch 2 · Arrays<span class="nav-badge">10M</span></div>
    <div class="nav-item" onclick="openCh('ch3')"><span class="nav-dot" style="background:var(--c3)"></span>Ch 3 · Functions<span class="nav-badge">10M</span></div>
    <div class="nav-item" onclick="openCh('ch4')"><span class="nav-dot" style="background:var(--c4)"></span>Ch 4 · Structure & Union<span class="nav-badge">8M</span></div>
    <div class="nav-item" onclick="openCh('ch5')"><span class="nav-dot" style="background:var(--c5)"></span>Ch 5 · Pointers & Files<span class="nav-badge">10M</span></div>
    <div class="nav-item" onclick="openCh('ch6')"><span class="nav-dot" style="background:var(--c6)"></span>Ch 6 · AI<span class="nav-badge">8M</span></div>
    <div class="nav-item" onclick="openCh('ch7')"><span class="nav-dot" style="background:var(--c7)"></span>Ch 7 · Drone Technology<span class="nav-badge">5M</span></div>
    <div class="nav-item" onclick="openCh('ch8')"><span class="nav-dot" style="background:var(--c8)"></span>Ch 8 · E-Commerce & Gov<span class="nav-badge">5M</span></div>
    <div class="nav-item" onclick="openCh('ch9')"><span class="nav-dot" style="background:var(--c9)"></span>Ch 9 · Cyber Security<span class="nav-badge">5M</span></div>
  </div>
  <div class="scard">
    <div class="scard-title">📝 Exam Pattern</div>
    <div class="ep-grid">
      <div class="ep-box"><div class="ep-n" style="color:var(--c1)">1M</div><div class="ep-l">Objective</div></div>
      <div class="ep-box"><div class="ep-n" style="color:var(--c3)">2M</div><div class="ep-l">Short Ans</div></div>
      <div class="ep-box"><div class="ep-n" style="color:var(--c6)">5M</div><div class="ep-l">Long Ans</div></div>
    </div>
    <div class="tip"><strong>💡 Tip:</strong> Click <strong>"Show Answer"</strong> on any question to read the full answer. Mark questions ✓ to track your revision!</div>
  </div>
  <div class="scard">
    <div class="scard-title">📊 My Progress</div>
    <div class="prog-pill"><span class="prog-label">Questions Revised</span><span class="prog-value" id="prog-val">0/87</span></div>
    <div class="prog-bar"><div class="prog-fill" id="prog-fill"></div></div>
  </div>
</aside>

<!-- MAIN CONTENT -->
<main>
<div class="search-box">
  <span style="color:var(--muted);font-size:17px">🔍</span>
  <input type="text" placeholder="Search questions… e.g. 'pointer', 'array', 'AI', 'drone'" oninput="searchQ(this.value)">
</div>

<!-- ═══════════════════════════════════
     CHAPTER 1 — INTRODUCTION TO C
═══════════════════════════════════ -->
<div class="chapter open" id="ch1">
  <div class="ch-head" onclick="toggle('ch1')" style="border-left:4px solid var(--c1)">
    <span class="ch-num" style="background:var(--c1)">CH 01</span>
    <span class="ch-icon">🖥️</span>
    <div class="ch-info"><div class="ch-name">Introduction to C Language</div><div class="ch-sub">History · Data Types · Variables · Operators · Control Statements · Loops</div></div>
    <span class="ch-marks" style="background:var(--c1)">12 Marks</span>
    <span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">

    <div class="qtype">🔵 Objective — 1 Mark</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q1</span>
        <span class="q-text">What is C language and who developed it? Name the year.</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a1')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a1">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>C Language</strong> is a general-purpose, high-level programming language. It was developed by <strong>Dennis Ritchie</strong> at Bell Laboratories, USA in <strong>1972</strong>. It was developed for the UNIX operating system. C is called the "Mother of all Programming Languages."</div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q2</span>
        <span class="q-text">What are <em>keywords</em> in C? Give two examples.</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a2')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a2">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>Keywords</strong> are reserved words in C language that have a fixed meaning and cannot be used as variable names. There are <strong>32 keywords</strong> in C.<br><br>Examples: <strong>int, float, char, return, if, else, while, for, do, void, struct, break, continue, switch</strong></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q3</span>
        <span class="q-text">Name the four basic <em>data types</em> in C language.</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a3')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a3">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">The four basic data types in C are:<br><ul>
          <li><strong>int</strong> — Integer (whole numbers), e.g. 5, -3, 100 (2 or 4 bytes)</li>
          <li><strong>float</strong> — Floating point (decimal numbers), e.g. 3.14 (4 bytes)</li>
          <li><strong>char</strong> — Character, e.g. 'A', 'z' (1 byte)</li>
          <li><strong>double</strong> — Double precision float, e.g. 3.14159265 (8 bytes)</li>
        </ul></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q4</span>
        <span class="q-text">What is the use of <em>#include &lt;stdio.h&gt;</em> in a C program?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a4')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a4">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>#include &lt;stdio.h&gt;</strong> is a preprocessor directive. It tells the compiler to include the <strong>Standard Input Output Header file</strong> (stdio.h) before compilation. It is required to use functions like <strong>printf()</strong> and <strong>scanf()</strong>. Without it, these functions would not work.</div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q5</span>
        <span class="q-text">What is the difference between <em>++i</em> (pre-increment) and <em>i++</em> (post-increment)?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a5')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a5">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>++i (Pre-increment)</th><th>i++ (Post-increment)</th></tr>
            <tr><td>Value is incremented <strong>first</strong>, then used</td><td>Value is used <strong>first</strong>, then incremented</td></tr>
            <tr><td>If i=5, then ++i gives 6</td><td>If i=5, then i++ gives 5 (then i becomes 6)</td></tr>
          </table>
          <pre class="code">int i=5;
printf("%d", ++i); // Output: 6
int j=5;
printf("%d", j++); // Output: 5</pre>
        </div>
      </div>
    </div>

    <div class="qtype">📝 Short Answer — 2 Marks</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q6</span>
        <span class="q-text">What is <em>printf()</em> and <em>scanf()</em>? Write their syntax with one example each.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a6')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a6">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <strong>printf()</strong> — Used to <strong>display output</strong> on the screen.<br>
          Syntax: <code style="color:#a5f3d0">printf("format string", variable_list);</code><br><br>
          <strong>scanf()</strong> — Used to <strong>take input</strong> from the user.<br>
          Syntax: <code style="color:#a5f3d0">scanf("format string", &variable_list);</code><br>
          <pre class="code">#include&lt;stdio.h&gt;
int main(){
    int a;
    printf("Enter a number: ");  // Output
    scanf("%d", &a);              // Input
    printf("You entered: %d", a); // Output
    return 0;
}</pre>
          <div class="key-point">💡 Note: & (address-of operator) is used with scanf() to store value at the variable's memory address.</div>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q7</span>
        <span class="q-text">Differentiate between <em>while loop</em> and <em>do-while loop</em> in C with syntax.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a7')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a7">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>while loop</th><th>do-while loop</th></tr>
            <tr><td>Condition checked <strong>before</strong> execution</td><td>Condition checked <strong>after</strong> execution</td></tr>
            <tr><td>May execute <strong>0 times</strong> if condition false</td><td>Executes at least <strong>1 time</strong></td></tr>
            <tr><td>Entry-controlled loop</td><td>Exit-controlled loop</td></tr>
          </table>
          <pre class="code">// while loop
while(condition){
    // statements
}

// do-while loop
do{
    // statements
} while(condition);</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q8</span>
        <span class="q-text">What are <em>relational operators</em> in C? List all of them.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a8')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a8">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">Relational operators are used to <strong>compare two values</strong>. They return either <strong>true (1)</strong> or <strong>false (0)</strong>.
          <table class="diff-table">
            <tr><th>Operator</th><th>Meaning</th><th>Example</th></tr>
            <tr><td>==</td><td>Equal to</td><td>5==5 → true</td></tr>
            <tr><td>!=</td><td>Not equal to</td><td>5!=3 → true</td></tr>
            <tr><td>&gt;</td><td>Greater than</td><td>7&gt;3 → true</td></tr>
            <tr><td>&lt;</td><td>Less than</td><td>3&lt;7 → true</td></tr>
            <tr><td>&gt;=</td><td>Greater than or equal</td><td>5&gt;=5 → true</td></tr>
            <tr><td>&lt;=</td><td>Less than or equal</td><td>3&lt;=5 → true</td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q9</span>
        <span class="q-text">Explain <em>if-else</em> and <em>if-else if-else</em> with syntax and example.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a9')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a9">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <strong>if-else:</strong> Executes one block if condition is true, otherwise another block.<pre class="code">if(condition){
    // executed if true
} else {
    // executed if false
}</pre>
          <strong>if-else if-else:</strong> Used to check multiple conditions.<pre class="code">if(marks >= 75)
    printf("Distinction");
else if(marks >= 60)
    printf("First Division");
else if(marks >= 45)
    printf("Second Division");
else
    printf("Fail");</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q10</span>
        <span class="q-text">What is the difference between <em>local variable</em> and <em>global variable</em>?</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a10')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a10">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>Local Variable</th><th>Global Variable</th></tr>
            <tr><td>Declared <strong>inside</strong> a function</td><td>Declared <strong>outside</strong> all functions</td></tr>
            <tr><td>Accessible only within that function</td><td>Accessible in <strong>all functions</strong> of program</td></tr>
            <tr><td>Created when function is called, destroyed when it ends</td><td>Exists throughout the program execution</td></tr>
            <tr><td>Example: int a; inside main()</td><td>Example: int a; before main()</td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q11</span>
        <span class="q-text">Explain the use of <em>switch-case</em> statement in C with syntax and example.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a11')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a11">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">The <strong>switch-case</strong> statement is used to execute one block from multiple options based on the value of a variable.
          <pre class="code">switch(variable){
    case 1: printf("One"); break;
    case 2: printf("Two"); break;
    case 3: printf("Three"); break;
    default: printf("Other");
}</pre>
          <div class="key-point">💡 break statement is used to exit the switch block. Without break, all cases after the matching case will execute (fall-through).</div>
        </div>
      </div>
    </div>

    <div class="qtype">📖 Programs — 5 Marks</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q12</span>
        <span class="q-text">Write a C program to find the <em>factorial of a number</em> using for loop.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a12')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a12">
        <div class="ans-label">✅ Answer — C Program</div>
        <div class="ans-text">
          <strong>Algorithm:</strong> Factorial of n = n × (n-1) × (n-2) × ... × 1. Factorial of 0 = 1.
          <pre class="code">#include&lt;stdio.h&gt;
int main(){
    int n, i;
    long int fact = 1;
    printf("Enter a number: ");
    scanf("%d", &n);
    if(n < 0)
        printf("Factorial not defined for negative numbers");
    else{
        for(i = 1; i &lt;= n; i++){
            fact = fact * i;
        }
        printf("Factorial of %d = %ld", n, fact);
    }
    return 0;
}
// Output: Enter a number: 5
// Factorial of 5 = 120</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q13</span>
        <span class="q-text">Write a C program to check whether a given number is <em>Prime or Not</em>.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a13')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a13">
        <div class="ans-label">✅ Answer — C Program</div>
        <div class="ans-text">
          <strong>Prime Number:</strong> A number divisible only by 1 and itself. e.g. 2, 3, 5, 7, 11...
          <pre class="code">#include&lt;stdio.h&gt;
int main(){
    int n, i, flag = 0;
    printf("Enter a number: ");
    scanf("%d", &n);
    if(n &lt;= 1){
        printf("%d is not prime", n);
    } else {
        for(i = 2; i &lt;= n/2; i++){
            if(n % i == 0){
                flag = 1;
                break;
            }
        }
        if(flag == 0)
            printf("%d is a PRIME number", n);
        else
            printf("%d is NOT a prime number", n);
    }
    return 0;
}
// Output: Enter a number: 7
// 7 is a PRIME number</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q14</span>
        <span class="q-text">Write a C program to print the <em>Fibonacci Series</em> up to n terms.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a14')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a14">
        <div class="ans-label">✅ Answer — C Program</div>
        <div class="ans-text">
          <strong>Fibonacci Series:</strong> 0, 1, 1, 2, 3, 5, 8, 13... Each term = sum of previous two terms.
          <pre class="code">#include&lt;stdio.h&gt;
int main(){
    int n, i, a=0, b=1, c;
    printf("Enter number of terms: ");
    scanf("%d", &n);
    printf("Fibonacci Series: ");
    for(i = 1; i &lt;= n; i++){
        printf("%d ", a);
        c = a + b;
        a = b;
        b = c;
    }
    return 0;
}
// Output: Enter number of terms: 7
// Fibonacci Series: 0 1 1 2 3 5 8</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q15</span>
        <span class="q-text">Explain the <em>structure of a C program</em> with all sections.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a15')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a15">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">A C program has the following sections:
          <pre class="code">// 1. Documentation Section (Comments)
/* Program to add two numbers */

// 2. Preprocessor / Link Section
#include&lt;stdio.h&gt;
#include&lt;conio.h&gt;

// 3. Global Variable Declaration
int globalVar = 10;

// 4. main() Function
int main(){
    // 5. Local Variable Declaration
    int a, b, sum;

    // 6. Executable Statements
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);
    sum = a + b;
    printf("Sum = %d", sum);

    // 7. Return Statement
    return 0;
}</pre>
          <div class="key-point">💡 main() is mandatory — every C program must have exactly one main() function.</div>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c1)">
        <span class="q-num" style="background:var(--c1)">Q16</span>
        <span class="q-text">Write a C program to find the <em>largest of three numbers</em> using if-else.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(249,115,22,.15);color:var(--c1);border:1px solid rgba(249,115,22,.3)" onclick="showAns(event,'a16')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a16">
        <div class="ans-label">✅ Answer — C Program</div>
        <div class="ans-text"><pre class="code">#include&lt;stdio.h&gt;
int main(){
    int a, b, c;
    printf("Enter three numbers: ");
    scanf("%d %d %d", &a, &b, &c);
    if(a >= b && a >= c)
        printf("Largest = %d", a);
    else if(b >= a && b >= c)
        printf("Largest = %d", b);
    else
        printf("Largest = %d", c);
    return 0;
}
// Output: Enter three numbers: 10 25 18
// Largest = 25</pre>
        </div>
      </div>
    </div>

  </div>
</div>

<!-- ═══════════════════════════════════
     CHAPTER 2 — ARRAYS
═══════════════════════════════════ -->
<div class="chapter" id="ch2">
  <div class="ch-head" onclick="toggle('ch2')" style="border-left:4px solid var(--c2)">
    <span class="ch-num" style="background:var(--c2);color:#000">CH 02</span>
    <span class="ch-icon">📋</span>
    <div class="ch-info"><div class="ch-name">Arrays</div><div class="ch-sub">1D Arrays · 2D Arrays · Traversal · Sorting · Searching</div></div>
    <span class="ch-marks" style="background:var(--c2);color:#000">10 Marks</span>
    <span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">

    <div class="qtype">🔵 Objective — 1 Mark</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c2)">
        <span class="q-num" style="background:var(--c2);color:#000">Q17</span>
        <span class="q-text">What is an <em>Array</em> in C? What is its declaration syntax?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(6,182,212,.15);color:var(--c2);border:1px solid rgba(6,182,212,.3)" onclick="showAns(event,'a17')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a17">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">An <strong>Array</strong> is a collection of elements of the <strong>same data type</strong> stored in <strong>contiguous memory locations</strong>.<br><br>
        Syntax: <code style="color:#a5f3d0">data_type array_name[size];</code><br>
        Example: <code style="color:#a5f3d0">int marks[10];</code> — stores 10 integers<br><br>
        Array index starts from <strong>0</strong> and goes up to <strong>size-1</strong>.</div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item" onclick="markQ(this)" style="--item-color:var(--c2)">
        <span class="q-num" style="background:var(--c2);color:#000">Q18</span>
        <span class="q-text">What is the <em>index</em> of an array? What is the index of the first element?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(6,182,212,.15);color:var(--c2);border:1px solid rgba(6,182,212,.3)" onclick="showAns(event,'a18')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a18">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">The <strong>index</strong> (also called subscript) is the position number used to access an element of an array. In C, array indexing starts from <strong>0</strong>.<br><br>
        For array <code style="color:#a5f3d0">int a[5]</code>: elements are a[0], a[1], a[2], a[3], a[4]<br>
        The <strong>first element</strong> has index <strong>0</strong>.<br>
        The <strong>last element</strong> has index <strong>size-1</strong> (here, 4).</div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c2)">
        <span class="q-num" style="background:var(--c2);color:#000">Q19</span>
        <span class="q-text">What is the difference between a <em>1D array</em> and a <em>2D array</em>?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(6,182,212,.15);color:var(--c2);border:1px solid rgba(6,182,212,.3)" onclick="showAns(event,'a19')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a19">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>1D Array</th><th>2D Array</th></tr>
            <tr><td>Single row of elements</td><td>Multiple rows and columns (like a table/matrix)</td></tr>
            <tr><td>One subscript: a[i]</td><td>Two subscripts: a[i][j]</td></tr>
            <tr><td>Example: int a[5];</td><td>Example: int a[3][3];</td></tr>
            <tr><td>Used for simple lists</td><td>Used for matrices, tables</td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="qtype">📝 Short Answer — 2 Marks</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c2)">
        <span class="q-num" style="background:var(--c2);color:#000">Q20</span>
        <span class="q-text">How do you <em>declare, initialize, and access</em> elements of an array in C?</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(6,182,212,.15);color:var(--c2);border:1px solid rgba(6,182,212,.3)" onclick="showAns(event,'a20')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a20">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><pre class="code">// Declaration
int marks[5];

// Initialization at declaration
int marks[5] = {90, 85, 78, 92, 88};

// Accessing elements
printf("%d", marks[0]); // First element = 90
printf("%d", marks[4]); // Last element = 88

// Input elements using loop
for(int i=0; i&lt;5; i++)
    scanf("%d", &marks[i]);

// Print elements using loop
for(int i=0; i&lt;5; i++)
    printf("%d ", marks[i]);</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c2)">
        <span class="q-num" style="background:var(--c2);color:#000">Q21</span>
        <span class="q-text">Write a C code to find the <em>sum and average</em> of N numbers stored in an array.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(6,182,212,.15);color:var(--c2);border:1px solid rgba(6,182,212,.3)" onclick="showAns(event,'a21')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a21">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><pre class="code">#include&lt;stdio.h&gt;
int main(){
    int n, i;
    float sum=0, avg;
    int a[100];
    printf("Enter N: ");
    scanf("%d", &n);
    for(i=0; i&lt;n; i++){
        printf("Enter element %d: ", i+1);
        scanf("%d", &a[i]);
        sum += a[i];
    }
    avg = sum / n;
    printf("Sum = %.2f\n", sum);
    printf("Average = %.2f", avg);
    return 0;
}</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item" onclick="markQ(this)" style="--item-color:var(--c2)">
        <span class="q-num" style="background:var(--c2);color:#000">Q22</span>
        <span class="q-text">What is <em>Linear Search</em>? Write its algorithm.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(6,182,212,.15);color:var(--c2);border:1px solid rgba(6,182,212,.3)" onclick="showAns(event,'a22')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a22">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>Linear Search</strong> is the simplest searching method. It searches for an element by checking <strong>each element one by one</strong> from the beginning.<br><br>
          <strong>Algorithm:</strong>
          <ol><li>Start from the first element</li><li>Compare each element with the search key</li><li>If match found, return index</li><li>If no match found till end, return -1 (not found)</li></ol>
          <pre class="code">for(i=0; i&lt;n; i++){
    if(a[i] == key){
        printf("Found at index %d", i);
        break;
    }
}</pre>
          <div class="key-point">💡 Time Complexity: O(n) — worst case checks all n elements</div>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c2)">
        <span class="q-num" style="background:var(--c2);color:#000">Q23</span>
        <span class="q-text">Explain <em>Bubble Sort</em> algorithm. How does it sort an array?</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(6,182,212,.15);color:var(--c2);border:1px solid rgba(6,182,212,.3)" onclick="showAns(event,'a23')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a23">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>Bubble Sort</strong> repeatedly compares <strong>adjacent elements</strong> and swaps them if they are in the wrong order. After each pass, the largest unsorted element "bubbles up" to its correct position.<br><br>
          <strong>Example:</strong> Array: 5, 3, 8, 1<br>
          Pass 1: 3,5,1,8 → Pass 2: 3,1,5,8 → Pass 3: 1,3,5,8 ✓<br>
          <pre class="code">for(i=0; i&lt;n-1; i++){
    for(j=0; j&lt;n-i-1; j++){
        if(a[j] > a[j+1]){
            temp=a[j]; a[j]=a[j+1]; a[j+1]=temp;
        }
    }
}</pre>
        </div>
      </div>
    </div>

    <div class="qtype">📖 Programs — 5 Marks</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c2)">
        <span class="q-num" style="background:var(--c2);color:#000">Q24</span>
        <span class="q-text">Write a C program to sort an array of <em>10 numbers in ascending order</em> using Bubble Sort.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(6,182,212,.15);color:var(--c2);border:1px solid rgba(6,182,212,.3)" onclick="showAns(event,'a24')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a24">
        <div class="ans-label">✅ Answer — C Program</div>
        <div class="ans-text"><pre class="code">#include&lt;stdio.h&gt;
int main(){
    int a[10], i, j, temp;
    printf("Enter 10 numbers:\n");
    for(i=0; i&lt;10; i++)
        scanf("%d", &a[i]);

    // Bubble Sort
    for(i=0; i&lt;9; i++){
        for(j=0; j&lt;9-i; j++){
            if(a[j] > a[j+1]){
                temp = a[j];
                a[j] = a[j+1];
                a[j+1] = temp;
            }
        }
    }
    printf("Sorted Array (Ascending): ");
    for(i=0; i&lt;10; i++)
        printf("%d ", a[i]);
    return 0;
}
// Output: 2 5 8 12 15 18 20 25 30 45</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c2)">
        <span class="q-num" style="background:var(--c2);color:#000">Q25</span>
        <span class="q-text">Write a C program to input and display a <em>2D matrix (3×3)</em>.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(6,182,212,.15);color:var(--c2);border:1px solid rgba(6,182,212,.3)" onclick="showAns(event,'a25')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a25">
        <div class="ans-label">✅ Answer — C Program</div>
        <div class="ans-text"><pre class="code">#include&lt;stdio.h&gt;
int main(){
    int a[3][3], i, j;
    printf("Enter 9 elements of 3x3 matrix:\n");
    for(i=0; i&lt;3; i++)
        for(j=0; j&lt;3; j++)
            scanf("%d", &a[i][j]);

    printf("\nMatrix:\n");
    for(i=0; i&lt;3; i++){
        for(j=0; j&lt;3; j++)
            printf("%d\t", a[i][j]);
        printf("\n");
    }
    return 0;
}
// Output:
// 1  2  3
// 4  5  6
// 7  8  9</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item" onclick="markQ(this)" style="--item-color:var(--c2)">
        <span class="q-num" style="background:var(--c2);color:#000">Q26</span>
        <span class="q-text">Write a C program to find the <em>largest and smallest element</em> in an array.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(6,182,212,.15);color:var(--c2);border:1px solid rgba(6,182,212,.3)" onclick="showAns(event,'a26')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a26">
        <div class="ans-label">✅ Answer — C Program</div>
        <div class="ans-text"><pre class="code">#include&lt;stdio.h&gt;
int main(){
    int a[100], n, i, max, min;
    printf("Enter number of elements: ");
    scanf("%d", &n);
    for(i=0; i&lt;n; i++)
        scanf("%d", &a[i]);
    max = min = a[0];
    for(i=1; i&lt;n; i++){
        if(a[i] > max) max = a[i];
        if(a[i] &lt; min) min = a[i];
    }
    printf("Largest = %d\n", max);
    printf("Smallest = %d", min);
    return 0;
}</pre>
        </div>
      </div>
    </div>

  </div>
</div>

<!-- ═══════════════════════════════════
     CHAPTER 3 — FUNCTIONS
═══════════════════════════════════ -->
<div class="chapter" id="ch3">
  <div class="ch-head" onclick="toggle('ch3')" style="border-left:4px solid var(--c3)">
    <span class="ch-num" style="background:var(--c3)">CH 03</span>
    <span class="ch-icon">🔧</span>
    <div class="ch-info"><div class="ch-name">Functions / Subroutines</div><div class="ch-sub">User-defined · Call by Value · Call by Reference · Recursion · Library Functions</div></div>
    <span class="ch-marks" style="background:var(--c3)">10 Marks</span>
    <span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">

    <div class="qtype">🔵 Objective — 1 Mark</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c3)">
        <span class="q-num" style="background:var(--c3)">Q27</span>
        <span class="q-text">What is a <em>function</em> in C? What are the advantages of using functions?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(139,92,246,.15);color:var(--c3);border:1px solid rgba(139,92,246,.3)" onclick="showAns(event,'a27')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a27">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">A <strong>function</strong> is a self-contained block of code that performs a specific task. It can be called multiple times from different parts of a program.<br><br>
          <strong>Advantages:</strong>
          <ul><li>Code reusability — write once, use many times</li><li>Makes program easier to read and debug</li><li>Reduces code length</li><li>Supports modular programming</li></ul>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item" onclick="markQ(this)" style="--item-color:var(--c3)">
        <span class="q-num" style="background:var(--c3)">Q28</span>
        <span class="q-text">What is a <em>return type</em> of a function? What does <em>void</em> mean?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(139,92,246,.15);color:var(--c3);border:1px solid rgba(139,92,246,.3)" onclick="showAns(event,'a28')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a28">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">The <strong>return type</strong> specifies what type of value a function will return after execution. Example: <code style="color:#a5f3d0">int add()</code> returns an integer.<br><br>
          <strong>void</strong> means the function does <strong>not return any value</strong>. It simply performs a task and exits.<br>
          Example: <code style="color:#a5f3d0">void display(){ printf("Hello"); }</code></div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c3)">
        <span class="q-num" style="background:var(--c3)">Q29</span>
        <span class="q-text">What is the difference between <em>function declaration</em> and <em>function definition</em>?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(139,92,246,.15);color:var(--c3);border:1px solid rgba(139,92,246,.3)" onclick="showAns(event,'a29')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a29">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>Function Declaration (Prototype)</th><th>Function Definition</th></tr>
            <tr><td>Tells compiler about function name, return type, parameters</td><td>Actual body of the function with statements</td></tr>
            <tr><td>Written before main()</td><td>Written after main() or in a separate file</td></tr>
            <tr><td>Example: <code>int add(int, int);</code></td><td>Example: <code>int add(int a, int b){ return a+b; }</code></td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="qtype">📝 Short Answer — 2 Marks</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c3)">
        <span class="q-num" style="background:var(--c3)">Q30</span>
        <span class="q-text">Differentiate between <em>Call by Value</em> and <em>Call by Reference</em> with example.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(139,92,246,.15);color:var(--c3);border:1px solid rgba(139,92,246,.3)" onclick="showAns(event,'a30')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a30">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>Call by Value</th><th>Call by Reference</th></tr>
            <tr><td>A <strong>copy</strong> of the value is passed</td><td>The <strong>address</strong> of the variable is passed</td></tr>
            <tr><td>Changes in function do NOT affect original</td><td>Changes in function <strong>DO affect</strong> original</td></tr>
            <tr><td>Uses normal variables</td><td>Uses pointers (*)</td></tr>
          </table>
          <pre class="code">// Call by Value
void show(int x){ x = 100; }  // original unchanged

// Call by Reference
void show(int *x){ *x = 100; } // original changed
// Call: show(&a);</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c3)">
        <span class="q-num" style="background:var(--c3)">Q31</span>
        <span class="q-text">What is a <em>Recursive Function</em>? Write a recursive C program to find factorial of n.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(139,92,246,.15);color:var(--c3);border:1px solid rgba(139,92,246,.3)" onclick="showAns(event,'a31')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a31">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">A <strong>Recursive Function</strong> is a function that calls <strong>itself</strong> until a base condition is met.<br><br>
          <pre class="code">int factorial(int n){
    if(n == 0 || n == 1)
        return 1;           // Base condition
    else
        return n * factorial(n-1); // Recursive call
}
// factorial(5) = 5*4*3*2*1 = 120</pre>
          <div class="key-point">💡 Every recursive function must have a base condition to stop recursion, otherwise it causes infinite recursion (stack overflow).</div>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item" onclick="markQ(this)" style="--item-color:var(--c3)">
        <span class="q-num" style="background:var(--c3)">Q32</span>
        <span class="q-text">Name any five <em>library functions</em> from &lt;math.h&gt; and &lt;string.h&gt; with their use.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(139,92,246,.15);color:var(--c3);border:1px solid rgba(139,92,246,.3)" onclick="showAns(event,'a32')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a32">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <strong>From &lt;math.h&gt;:</strong>
          <table class="diff-table">
            <tr><th>Function</th><th>Use</th></tr>
            <tr><td>sqrt(x)</td><td>Square root of x</td></tr>
            <tr><td>pow(x,y)</td><td>x raised to power y</td></tr>
            <tr><td>abs(x)</td><td>Absolute value of x</td></tr>
          </table>
          <strong>From &lt;string.h&gt;:</strong>
          <table class="diff-table">
            <tr><th>Function</th><th>Use</th></tr>
            <tr><td>strlen(s)</td><td>Length of string s</td></tr>
            <tr><td>strcpy(s1,s2)</td><td>Copy s2 into s1</td></tr>
            <tr><td>strcmp(s1,s2)</td><td>Compare two strings</td></tr>
            <tr><td>strcat(s1,s2)</td><td>Concatenate s2 to s1</td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="qtype">📖 Programs — 5 Marks</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c3)">
        <span class="q-num" style="background:var(--c3)">Q33</span>
        <span class="q-text">Write a C program with function to find the <em>sum of two numbers</em> and return the result.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(139,92,246,.15);color:var(--c3);border:1px solid rgba(139,92,246,.3)" onclick="showAns(event,'a33')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a33">
        <div class="ans-label">✅ Answer — C Program</div>
        <div class="ans-text"><pre class="code">#include&lt;stdio.h&gt;

// Function Declaration
int add(int a, int b);

int main(){
    int x, y, result;
    printf("Enter two numbers: ");
    scanf("%d %d", &x, &y);
    result = add(x, y);   // Function call
    printf("Sum = %d", result);
    return 0;
}

// Function Definition
int add(int a, int b){
    return a + b;
}
// Output: Enter two numbers: 10 20
// Sum = 30</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c3)">
        <span class="q-num" style="background:var(--c3)">Q34</span>
        <span class="q-text">Explain <em>Recursion</em> with a C program for <em>Fibonacci Series</em> using recursion.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(139,92,246,.15);color:var(--c3);border:1px solid rgba(139,92,246,.3)" onclick="showAns(event,'a34')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a34">
        <div class="ans-label">✅ Answer — C Program</div>
        <div class="ans-text"><strong>Recursion</strong> = A function calling itself. Each call reduces the problem until a base case is reached.<br>
          <pre class="code">#include&lt;stdio.h&gt;

int fibonacci(int n){
    if(n == 0) return 0;   // Base case 1
    if(n == 1) return 1;   // Base case 2
    return fibonacci(n-1) + fibonacci(n-2); // Recursive call
}

int main(){
    int n, i;
    printf("Enter number of terms: ");
    scanf("%d", &n);
    printf("Fibonacci Series: ");
    for(i=0; i&lt;n; i++)
        printf("%d ", fibonacci(i));
    return 0;
}
// Output: 0 1 1 2 3 5 8 13 ...</pre>
        </div>
      </div>
    </div>

  </div>
</div>

<!-- ═══════════════════════════════════
     CHAPTER 4 — STRUCTURE AND UNION
═══════════════════════════════════ -->
<div class="chapter" id="ch4">
  <div class="ch-head" onclick="toggle('ch4')" style="border-left:4px solid var(--c4)">
    <span class="ch-num" style="background:var(--c4)">CH 04</span>
    <span class="ch-icon">🗂️</span>
    <div class="ch-info"><div class="ch-name">Structure and Union</div><div class="ch-sub">Structure Definition · Members · Array of Structure · Union · typedef</div></div>
    <span class="ch-marks" style="background:var(--c4)">8 Marks</span>
    <span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">

    <div class="qtype">🔵 Objective / Short Answer</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c4)">
        <span class="q-num" style="background:var(--c4)">Q35</span>
        <span class="q-text">What is a <em>Structure</em> in C? Write syntax to declare it.</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(16,185,129,.15);color:var(--c4);border:1px solid rgba(16,185,129,.3)" onclick="showAns(event,'a35')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a35">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">A <strong>Structure</strong> is a user-defined data type that groups different types of data under one name. It is defined using the keyword <strong>struct</strong>.<br><br>
          <pre class="code">struct Student {
    int rollno;
    char name[50];
    float marks;
};
// Creating a variable
struct Student s1;</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c4)">
        <span class="q-num" style="background:var(--c4)">Q36</span>
        <span class="q-text">What is the main difference between <em>Structure</em> and <em>Union</em> in C?</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(16,185,129,.15);color:var(--c4);border:1px solid rgba(16,185,129,.3)" onclick="showAns(event,'a36')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a36">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>Structure</th><th>Union</th></tr>
            <tr><td>Keyword: <strong>struct</strong></td><td>Keyword: <strong>union</strong></td></tr>
            <tr><td>Each member has its <strong>own memory</strong></td><td>All members <strong>share same memory</strong></td></tr>
            <tr><td>Memory = sum of all members</td><td>Memory = size of largest member</td></tr>
            <tr><td>All members accessible simultaneously</td><td>Only one member can be used at a time</td></tr>
            <tr><td>struct S{int a; float b;} → 6 bytes</td><td>union U{int a; float b;} → 4 bytes</td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c4)">
        <span class="q-num" style="background:var(--c4)">Q37</span>
        <span class="q-text">How do you <em>access members</em> of a structure? Explain dot (.) and arrow (->) operator.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(16,185,129,.15);color:var(--c4);border:1px solid rgba(16,185,129,.3)" onclick="showAns(event,'a37')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a37">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <strong>Dot Operator (.)</strong> — Used to access members using a <strong>structure variable</strong>.<br>
          <strong>Arrow Operator (→)</strong> — Used to access members using a <strong>pointer to structure</strong>.
          <pre class="code">struct Student s1;
s1.rollno = 101;         // Dot operator
s1.marks = 85.5;

struct Student *ptr = &s1;
ptr->rollno = 101;       // Arrow operator
ptr->marks = 85.5;</pre>
        </div>
      </div>
    </div>

    <div class="qtype">📖 Programs — 5 Marks</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c4)">
        <span class="q-num" style="background:var(--c4)">Q38</span>
        <span class="q-text">Write a C program using <em>structure</em> to store and display student record (name, rollno, marks) and calculate grade.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(16,185,129,.15);color:var(--c4);border:1px solid rgba(16,185,129,.3)" onclick="showAns(event,'a38')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a38">
        <div class="ans-label">✅ Answer — C Program</div>
        <div class="ans-text"><pre class="code">#include&lt;stdio.h&gt;
struct Student {
    int rollno;
    char name[50];
    float marks;
};

int main(){
    struct Student s;
    printf("Enter Roll No: ");
    scanf("%d", &s.rollno);
    printf("Enter Name: ");
    scanf("%s", s.name);
    printf("Enter Marks (out of 100): ");
    scanf("%f", &s.marks);

    printf("\n--- Student Record ---\n");
    printf("Roll No: %d\n", s.rollno);
    printf("Name: %s\n", s.name);
    printf("Marks: %.2f\n", s.marks);

    if(s.marks >= 75) printf("Grade: A");
    else if(s.marks >= 60) printf("Grade: B");
    else if(s.marks >= 45) printf("Grade: C");
    else printf("Grade: F (Fail)");
    return 0;
}</pre>
        </div>
      </div>
    </div>

  </div>
</div>

<!-- ═══════════════════════════════════
     CHAPTER 5 — POINTERS & FILE HANDLING
═══════════════════════════════════ -->
<div class="chapter" id="ch5">
  <div class="ch-head" onclick="toggle('ch5')" style="border-left:4px solid var(--c5)">
    <span class="ch-num" style="background:var(--c5)">CH 05</span>
    <span class="ch-icon">📂</span>
    <div class="ch-info"><div class="ch-name">Pointers and File Handling</div><div class="ch-sub">Pointer Basics · Arithmetic · fopen · fclose · fread · fwrite · fprintf · fscanf</div></div>
    <span class="ch-marks" style="background:var(--c5)">10 Marks</span>
    <span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">

    <div class="qtype">🔵 Objective — 1 Mark</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c5)">
        <span class="q-num" style="background:var(--c5)">Q39</span>
        <span class="q-text">What is a <em>Pointer</em> in C? Write its declaration syntax.</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(239,68,68,.15);color:var(--c5);border:1px solid rgba(239,68,68,.3)" onclick="showAns(event,'a39')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a39">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">A <strong>Pointer</strong> is a variable that stores the <strong>memory address</strong> of another variable.<br><br>
          <strong>Syntax:</strong> <code style="color:#a5f3d0">data_type *pointer_name;</code><br><br>
          <pre class="code">int a = 10;
int *p;      // Pointer declaration
p = &a;      // p stores address of a
printf("%d", *p); // *p gives value = 10</pre>
          <div class="key-point">💡 * = dereference (get value) &nbsp;|&nbsp; & = address-of operator</div>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c5)">
        <span class="q-num" style="background:var(--c5)">Q40</span>
        <span class="q-text">What do the operators <em>*</em> (dereference) and <em>&amp;</em> (address-of) do in C?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(239,68,68,.15);color:var(--c5);border:1px solid rgba(239,68,68,.3)" onclick="showAns(event,'a40')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a40">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>Operator</th><th>Name</th><th>Function</th></tr>
            <tr><td><strong>&</strong></td><td>Address-of</td><td>Returns the memory address of a variable. Example: &a gives address of a</td></tr>
            <tr><td><strong>*</strong></td><td>Dereference</td><td>Accesses the value stored at a memory address. Example: *p gives value at address p</td></tr>
          </table>
          <pre class="code">int a = 50;
int *p = &a;
printf("%d", a);   // 50  (value)
printf("%p", &a);  // address of a
printf("%d", *p);  // 50  (value via pointer)</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item" onclick="markQ(this)" style="--item-color:var(--c5)">
        <span class="q-num" style="background:var(--c5)">Q41</span>
        <span class="q-text">Name any two <em>file-opening modes</em> in C with their meaning.</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(239,68,68,.15);color:var(--c5);border:1px solid rgba(239,68,68,.3)" onclick="showAns(event,'a41')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a41">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>Mode</th><th>Meaning</th></tr>
            <tr><td>"r"</td><td>Open for <strong>reading</strong>. File must exist.</td></tr>
            <tr><td>"w"</td><td>Open for <strong>writing</strong>. Creates new or overwrites existing file.</td></tr>
            <tr><td>"a"</td><td>Open for <strong>appending</strong>. Adds data at end of file.</td></tr>
            <tr><td>"r+"</td><td>Open for both <strong>reading and writing</strong></td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="qtype">📝 Short Answer — 2 Marks</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c5)">
        <span class="q-num" style="background:var(--c5)">Q42</span>
        <span class="q-text">What is the use of <em>fopen()</em> and <em>fclose()</em>? Write their syntax.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(239,68,68,.15);color:var(--c5);border:1px solid rgba(239,68,68,.3)" onclick="showAns(event,'a42')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a42">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <strong>fopen()</strong> — Opens a file. Returns a file pointer (FILE*). If file cannot be opened, returns NULL.<br>
          Syntax: <code style="color:#a5f3d0">FILE *fp = fopen("filename.txt", "mode");</code><br><br>
          <strong>fclose()</strong> — Closes an open file and saves all changes.<br>
          Syntax: <code style="color:#a5f3d0">fclose(fp);</code><br>
          <pre class="code">FILE *fp;
fp = fopen("data.txt", "w");  // Open for writing
if(fp == NULL){
    printf("Error opening file!");
}
// ... write to file ...
fclose(fp);  // Always close the file</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c5)">
        <span class="q-num" style="background:var(--c5)">Q43</span>
        <span class="q-text">Differentiate between <em>Text File</em> and <em>Binary File</em> in C.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(239,68,68,.15);color:var(--c5);border:1px solid rgba(239,68,68,.3)" onclick="showAns(event,'a43')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a43">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>Text File</th><th>Binary File</th></tr>
            <tr><td>Stores data in <strong>readable text</strong> form (ASCII)</td><td>Stores data in <strong>binary</strong> (0s and 1s) form</td></tr>
            <tr><td>Can be opened in Notepad</td><td>Not human-readable</td></tr>
            <tr><td>Uses fprintf(), fscanf()</td><td>Uses fwrite(), fread()</td></tr>
            <tr><td>Extension: .txt</td><td>Extension: .bin, .dat</td></tr>
            <tr><td>Slower but human-friendly</td><td>Faster and compact</td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="qtype">📖 Programs — 5 Marks</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c5)">
        <span class="q-num" style="background:var(--c5)">Q44</span>
        <span class="q-text">Write a C program to <em>write data to a file</em> and then <em>read and display</em> it using fprintf() and fscanf().</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(239,68,68,.15);color:var(--c5);border:1px solid rgba(239,68,68,.3)" onclick="showAns(event,'a44')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a44">
        <div class="ans-label">✅ Answer — C Program</div>
        <div class="ans-text"><pre class="code">#include&lt;stdio.h&gt;
int main(){
    FILE *fp;
    char name[50];
    int age;

    // WRITE to file
    fp = fopen("student.txt", "w");
    if(fp == NULL){ printf("Error!"); return 1; }
    printf("Enter name: "); scanf("%s", name);
    printf("Enter age: ");  scanf("%d", &age);
    fprintf(fp, "%s %d\n", name, age);
    fclose(fp);
    printf("Data written successfully!\n");

    // READ from file
    fp = fopen("student.txt", "r");
    if(fp == NULL){ printf("Error!"); return 1; }
    printf("\n--- File Contents ---\n");
    while(fscanf(fp, "%s %d", name, &age) != EOF){
        printf("Name: %s, Age: %d\n", name, age);
    }
    fclose(fp);
    return 0;
}</pre>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c5)">
        <span class="q-num" style="background:var(--c5)">Q45</span>
        <span class="q-text">Write a C program to <em>swap two numbers</em> using pointers (Call by Reference).</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(239,68,68,.15);color:var(--c5);border:1px solid rgba(239,68,68,.3)" onclick="showAns(event,'a45')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a45">
        <div class="ans-label">✅ Answer — C Program</div>
        <div class="ans-text"><pre class="code">#include&lt;stdio.h&gt;

void swap(int *x, int *y){
    int temp;
    temp = *x;
    *x = *y;
    *y = temp;
}

int main(){
    int a, b;
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);
    printf("Before swap: a=%d, b=%d\n", a, b);
    swap(&a, &b);   // Passing addresses
    printf("After swap:  a=%d, b=%d", a, b);
    return 0;
}
// Output:
// Before swap: a=10, b=20
// After swap:  a=20, b=10</pre>
        </div>
      </div>
    </div>

  </div>
</div>

<!-- ═══════════════════════════════════
     CHAPTER 6 — ARTIFICIAL INTELLIGENCE
═══════════════════════════════════ -->
<div class="chapter" id="ch6">
  <div class="ch-head" onclick="toggle('ch6')" style="border-left:4px solid var(--c6)">
    <span class="ch-num" style="background:var(--c6)">CH 06</span>
    <span class="ch-icon">🤖</span>
    <div class="ch-info"><div class="ch-name">Artificial Intelligence</div><div class="ch-sub">Definition · ML · Deep Learning · NLP · Expert Systems · Applications</div></div>
    <span class="ch-marks" style="background:var(--c6)">8 Marks</span>
    <span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">

    <div class="qtype">🔵 Objective — 1 Mark</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c6)">
        <span class="q-num" style="background:var(--c6)">Q46</span>
        <span class="q-text">What is <em>Artificial Intelligence (AI)</em>? Who coined the term?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(59,130,246,.15);color:var(--c6);border:1px solid rgba(59,130,246,.3)" onclick="showAns(event,'a46')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a46">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>Artificial Intelligence (AI)</strong> is the simulation of human intelligence in machines so that they can think, learn, and solve problems like humans.<br><br>
          The term "Artificial Intelligence" was coined by <strong>John McCarthy</strong> in <strong>1956</strong> at the Dartmouth Conference.<br><br>
          Examples: Siri, Google Assistant, Chess-playing computers, Self-driving cars, ChatGPT.</div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c6)">
        <span class="q-num" style="background:var(--c6)">Q47</span>
        <span class="q-text">What is the full form of <em>NLP</em>? Give one example of NLP in daily life.</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(59,130,246,.15);color:var(--c6);border:1px solid rgba(59,130,246,.3)" onclick="showAns(event,'a47')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a47">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>NLP</strong> = <strong>Natural Language Processing</strong><br><br>
          NLP is a branch of AI that enables computers to understand, interpret, and generate <strong>human language</strong>.<br><br>
          <strong>Examples in daily life:</strong>
          <ul>
            <li>Google Translate — translating languages</li>
            <li>Voice assistants: Siri, Alexa, Google Assistant</li>
            <li>Spam email detection</li>
            <li>Auto-correct on smartphones</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="qtype">📝 Short Answer — 2 Marks</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c6)">
        <span class="q-num" style="background:var(--c6)">Q48</span>
        <span class="q-text">Differentiate between <em>AI</em>, <em>Machine Learning</em>, and <em>Deep Learning</em>.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(59,130,246,.15);color:var(--c6);border:1px solid rgba(59,130,246,.3)" onclick="showAns(event,'a48')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a48">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>AI</th><th>Machine Learning (ML)</th><th>Deep Learning (DL)</th></tr>
            <tr><td>Broad concept: machines mimicking human intelligence</td><td>Subset of AI: machines learn from data automatically</td><td>Subset of ML: uses neural networks with many layers</td></tr>
            <tr><td>Example: Chess game</td><td>Example: Email spam filter</td><td>Example: Face recognition, Self-driving cars</td></tr>
          </table>
          <div class="key-point">💡 Relationship: AI ⊃ Machine Learning ⊃ Deep Learning (DL is a part of ML which is a part of AI)</div>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c6)">
        <span class="q-num" style="background:var(--c6)">Q49</span>
        <span class="q-text">What is <em>Machine Learning</em>? Name its three types.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(59,130,246,.15);color:var(--c6);border:1px solid rgba(59,130,246,.3)" onclick="showAns(event,'a49')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a49">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>Machine Learning (ML)</strong> is a branch of AI where machines learn from <strong>data and experience</strong> without being explicitly programmed.<br><br>
          <strong>Three types of Machine Learning:</strong>
          <ol>
            <li><strong>Supervised Learning</strong> — Model trained on labelled data. Example: Email spam detection, Predicting house prices</li>
            <li><strong>Unsupervised Learning</strong> — Model trained on unlabelled data. Example: Customer segmentation, Netflix recommendation</li>
            <li><strong>Reinforcement Learning</strong> — Model learns by trial and error, rewarded for correct actions. Example: Game playing AI, Robotics</li>
          </ol>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c6)">
        <span class="q-num" style="background:var(--c6)">Q50</span>
        <span class="q-text">What are <em>Expert Systems</em>? Give two examples.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(59,130,246,.15);color:var(--c6);border:1px solid rgba(59,130,246,.3)" onclick="showAns(event,'a50')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a50">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>Expert Systems</strong> are AI programs that simulate the decision-making ability of a <strong>human expert</strong> in a specific domain. They use a knowledge base and inference engine.<br><br>
          <strong>Components:</strong> Knowledge Base + Inference Engine + User Interface<br><br>
          <strong>Examples:</strong>
          <ul>
            <li><strong>MYCIN</strong> — Medical expert system for diagnosing blood diseases</li>
            <li><strong>DENDRAL</strong> — Used in chemistry to identify chemical compounds</li>
            <li><strong>XCON</strong> — Used by DEC to configure computer systems</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="qtype">📖 Long Answer — 5 Marks</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c6)">
        <span class="q-num" style="background:var(--c6)">Q51</span>
        <span class="q-text">What is <em>Artificial Intelligence</em>? Explain its types, advantages, disadvantages, and applications.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(59,130,246,.15);color:var(--c6);border:1px solid rgba(59,130,246,.3)" onclick="showAns(event,'a51')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a51">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <strong>Definition:</strong> AI is the branch of computer science that enables machines to perform tasks that normally require human intelligence.<br><br>
          <strong>Types of AI:</strong>
          <ul>
            <li><strong>Narrow AI (Weak AI)</strong> — Performs specific tasks only. Example: Siri, Chess AI</li>
            <li><strong>General AI (Strong AI)</strong> — Can perform any intellectual task like a human (theoretical)</li>
            <li><strong>Super AI</strong> — Surpasses human intelligence in all areas (future concept)</li>
          </ul>
          <strong>Advantages:</strong>
          <ul>
            <li>Works 24×7 without rest or mistakes due to fatigue</li>
            <li>Handles repetitive tasks efficiently</li>
            <li>Makes accurate decisions using data</li>
            <li>Used in dangerous situations (mining, space exploration)</li>
          </ul>
          <strong>Disadvantages:</strong>
          <ul>
            <li>High cost of development</li>
            <li>May cause unemployment</li>
            <li>Lacks creativity and emotions</li>
            <li>Ethical concerns</li>
          </ul>
          <strong>Applications:</strong> Healthcare (disease diagnosis), Education (smart tutors), Transport (self-driving cars), Finance (fraud detection), Entertainment (gaming, OTT recommendation)
        </div>
      </div>
    </div>

  </div>
</div>

<!-- ═══════════════════════════════════
     CHAPTER 7 — DRONE TECHNOLOGY
═══════════════════════════════════ -->
<div class="chapter" id="ch7">
  <div class="ch-head" onclick="toggle('ch7')" style="border-left:4px solid var(--c7)">
    <span class="ch-num" style="background:var(--c7);color:#000">CH 07</span>
    <span class="ch-icon">🚁</span>
    <div class="ch-info"><div class="ch-name">Drone Technology</div><div class="ch-sub">Definition · Types · Components · Uses · Advantages · Rules in India</div></div>
    <span class="ch-marks" style="background:var(--c7);color:#000">5 Marks</span>
    <span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">

    <div class="qtype">🔵 Objective / Short Answer</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c7)">
        <span class="q-num" style="background:var(--c7);color:#000">Q52</span>
        <span class="q-text">What is a <em>Drone</em>? What is its other name (UAV)?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(245,158,11,.15);color:var(--c7);border:1px solid rgba(245,158,11,.3)" onclick="showAns(event,'a52')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a52">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">A <strong>Drone</strong> is an <strong>unmanned aerial vehicle (UAV)</strong> — an aircraft that flies without a human pilot on board. It is controlled remotely by a human operator or autonomously using pre-programmed flight plans.<br><br>
          Full form of <strong>UAV</strong> = <strong>Unmanned Aerial Vehicle</strong><br>
          Also called <strong>UAS</strong> = Unmanned Aircraft System</div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c7)">
        <span class="q-num" style="background:var(--c7);color:#000">Q53</span>
        <span class="q-text">What are the main <em>components of a Drone</em>? Name at least four.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(245,158,11,.15);color:var(--c7);border:1px solid rgba(245,158,11,.3)" onclick="showAns(event,'a53')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a53">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">Main components of a drone:
          <ul>
            <li><strong>Frame</strong> — The body/structure of the drone</li>
            <li><strong>Propellers/Rotors</strong> — Blades that create lift and thrust</li>
            <li><strong>Motors</strong> — Drive the propellers</li>
            <li><strong>Battery</strong> — Power source (usually Li-Po battery)</li>
            <li><strong>Flight Controller</strong> — The "brain" of the drone; controls flight</li>
            <li><strong>GPS Module</strong> — For navigation and positioning</li>
            <li><strong>Camera</strong> — For photography or surveillance</li>
            <li><strong>Remote Controller</strong> — Operator uses this to control the drone</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c7)">
        <span class="q-num" style="background:var(--c7);color:#000">Q54</span>
        <span class="q-text">Write any four <em>uses of Drone Technology</em> in different fields.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(245,158,11,.15);color:var(--c7);border:1px solid rgba(245,158,11,.3)" onclick="showAns(event,'a54')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a54">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>Field</th><th>Use of Drone</th></tr>
            <tr><td><strong>Agriculture</strong></td><td>Spraying pesticides and fertilizers on crops efficiently</td></tr>
            <tr><td><strong>Military / Defence</strong></td><td>Surveillance, reconnaissance, and strikes in war zones</td></tr>
            <tr><td><strong>Delivery</strong></td><td>Amazon Prime Air for package delivery</td></tr>
            <tr><td><strong>Disaster Management</strong></td><td>Search and rescue operations in floods/earthquakes</td></tr>
            <tr><td><strong>Photography</strong></td><td>Aerial photography and videography for films</td></tr>
            <tr><td><strong>Healthcare</strong></td><td>Delivering medicines/blood to remote areas</td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c7)">
        <span class="q-num" style="background:var(--c7);color:#000">Q55</span>
        <span class="q-text">What is <em>Drone Technology</em>? Explain its types, components, applications, advantages, and limitations.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(245,158,11,.15);color:var(--c7);border:1px solid rgba(245,158,11,.3)" onclick="showAns(event,'a55')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a55">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <strong>Definition:</strong> Drone technology refers to unmanned aerial vehicles (UAVs) controlled remotely or autonomously.<br><br>
          <strong>Types of Drones:</strong>
          <ul>
            <li><strong>Multi-rotor</strong> (Quadcopter) — Most common, 4 rotors, used for photography</li>
            <li><strong>Fixed-wing</strong> — Like an airplane, used for long distances</li>
            <li><strong>Single Rotor</strong> (Helicopter type) — More efficient, used in military</li>
            <li><strong>Hybrid</strong> — Combines fixed-wing and multi-rotor</li>
          </ul>
          <strong>Advantages:</strong>
          <ul>
            <li>Can reach inaccessible areas</li>
            <li>Saves time and human effort</li>
            <li>Reduces cost in agriculture and delivery</li>
            <li>No risk to human life in dangerous missions</li>
          </ul>
          <strong>Limitations:</strong>
          <ul>
            <li>Limited battery life (20–40 minutes)</li>
            <li>Privacy concerns</li>
            <li>Can be misused for illegal surveillance</li>
            <li>Affected by bad weather</li>
            <li>Restricted in many areas (near airports)</li>
          </ul>
          <strong>India Drone Rules:</strong> In India, drones are regulated by <strong>DGCA (Directorate General of Civil Aviation)</strong>. Drone flights above 400 feet require permission.
        </div>
      </div>
    </div>

  </div>
</div>

<!-- ═══════════════════════════════════
     CHAPTER 8 — E-COMMERCE & E-GOVERNANCE
═══════════════════════════════════ -->
<div class="chapter" id="ch8">
  <div class="ch-head" onclick="toggle('ch8')" style="border-left:4px solid var(--c8)">
    <span class="ch-num" style="background:var(--c8)">CH 08</span>
    <span class="ch-icon">🛒</span>
    <div class="ch-info"><div class="ch-name">E-Commerce and E-Governance</div><div class="ch-sub">B2B · B2C · C2C · Digital Payment · E-Gov Portals · Digital India</div></div>
    <span class="ch-marks" style="background:var(--c8)">5 Marks</span>
    <span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">

    <div class="qtype">🔵 Objective / Short Answer</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c8)">
        <span class="q-num" style="background:var(--c8)">Q56</span>
        <span class="q-text">What is <em>E-Commerce</em>? Give two examples of e-commerce websites in India.</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(236,72,153,.15);color:var(--c8);border:1px solid rgba(236,72,153,.3)" onclick="showAns(event,'a56')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a56">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>E-Commerce (Electronic Commerce)</strong> is the buying and selling of goods and services over the <strong>internet</strong>. It involves electronic transactions between buyers and sellers.<br><br>
          <strong>Indian examples:</strong> Flipkart, Amazon India, Snapdeal, Myntra, Meesho, OLX<br><br>
          <strong>Global examples:</strong> Amazon, eBay, Alibaba</div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c8)">
        <span class="q-num" style="background:var(--c8)">Q57</span>
        <span class="q-text">Differentiate between <em>B2B</em>, <em>B2C</em>, and <em>C2C</em> e-commerce.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(236,72,153,.15);color:var(--c8);border:1px solid rgba(236,72,153,.3)" onclick="showAns(event,'a57')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a57">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>Type</th><th>Full Form</th><th>Meaning</th><th>Example</th></tr>
            <tr><td><strong>B2B</strong></td><td>Business to Business</td><td>Transaction between two businesses</td><td>Amazon Wholesale, Alibaba</td></tr>
            <tr><td><strong>B2C</strong></td><td>Business to Consumer</td><td>Business sells directly to customer</td><td>Flipkart, Amazon, Myntra</td></tr>
            <tr><td><strong>C2C</strong></td><td>Consumer to Consumer</td><td>One consumer sells to another consumer</td><td>OLX, Quikr, eBay</td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c8)">
        <span class="q-num" style="background:var(--c8)">Q58</span>
        <span class="q-text">What is <em>E-Governance</em>? Explain its objectives, types, and Indian portals.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(236,72,153,.15);color:var(--c8);border:1px solid rgba(236,72,153,.3)" onclick="showAns(event,'a58')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a58">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <strong>E-Governance</strong> is the use of information and communication technology (ICT) by the government to deliver public services efficiently to citizens and businesses.<br><br>
          <strong>Objectives:</strong>
          <ul>
            <li>Provide easy and fast government services</li>
            <li>Reduce corruption and paperwork</li>
            <li>Make government transparent and accountable</li>
            <li>Include citizens in governance</li>
          </ul>
          <strong>Types of E-Governance:</strong>
          <table class="diff-table">
            <tr><th>Type</th><th>Meaning</th><th>Example</th></tr>
            <tr><td>G2C</td><td>Government to Citizen</td><td>Online ration card, e-District portal</td></tr>
            <tr><td>G2B</td><td>Government to Business</td><td>Online tax filing (GST), e-tendering</td></tr>
            <tr><td>G2G</td><td>Government to Government</td><td>Data sharing between departments</td></tr>
            <tr><td>G2E</td><td>Government to Employee</td><td>Online salary slips, leaves management</td></tr>
          </table>
          <strong>Important Indian E-Governance Portals:</strong>
          <ul>
            <li><strong>DigiLocker</strong> — Digital storage of documents (Aadhaar, marksheets)</li>
            <li><strong>UMANG</strong> — Unified Mobile Application for New-age Governance</li>
            <li><strong>e-District</strong> — State-level citizen services portal</li>
            <li><strong>MyGov</strong> — Citizens participate in government decision making</li>
            <li><strong>Digital India</strong> — Flagship scheme to make India digitally empowered</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c8)">
        <span class="q-num" style="background:var(--c8)">Q59</span>
        <span class="q-text">What are <em>Digital Payment</em> methods? Name any four with examples.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(236,72,153,.15);color:var(--c8);border:1px solid rgba(236,72,153,.3)" onclick="showAns(event,'a59')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a59">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>Digital Payment</strong> is the method of paying for goods and services electronically without using physical cash.<br><br>
          <strong>Methods:</strong>
          <ul>
            <li><strong>UPI (Unified Payments Interface)</strong> — Google Pay, PhonePe, Paytm</li>
            <li><strong>Internet Banking / Net Banking</strong> — SBI Net Banking, HDFC NetBanking</li>
            <li><strong>Debit/Credit Card</strong> — Visa, Mastercard, RuPay</li>
            <li><strong>Mobile Wallet</strong> — Paytm Wallet, Amazon Pay</li>
            <li><strong>NEFT/RTGS</strong> — Bank transfers</li>
            <li><strong>Aadhaar Pay</strong> — Payment using fingerprint/Aadhaar</li>
          </ul>
        </div>
      </div>
    </div>

  </div>
</div>

<!-- ═══════════════════════════════════
     CHAPTER 9 — CYBER SECURITY
═══════════════════════════════════ -->
<div class="chapter" id="ch9">
  <div class="ch-head" onclick="toggle('ch9')" style="border-left:4px solid var(--c9)">
    <span class="ch-num" style="background:var(--c9);color:#000">CH 09</span>
    <span class="ch-icon">🔐</span>
    <div class="ch-info"><div class="ch-name">Cyber Security and Cyber Crime</div><div class="ch-sub">Types of Threats · Hacking · Phishing · Malware · IT Act 2000 · Safety Tips</div></div>
    <span class="ch-marks" style="background:var(--c9);color:#000">5 Marks</span>
    <span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">

    <div class="qtype">🔵 Objective — 1 Mark</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c9)">
        <span class="q-num" style="background:var(--c9);color:#000">Q60</span>
        <span class="q-text">What is <em>Cyber Crime</em>? Give two examples.</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(20,184,166,.15);color:var(--c9);border:1px solid rgba(20,184,166,.3)" onclick="showAns(event,'a60')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a60">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>Cyber Crime</strong> is any illegal activity that involves computers, networks, or the internet as a tool, target, or place of the crime.<br><br>
          <strong>Examples:</strong>
          <ul>
            <li><strong>Hacking</strong> — Unauthorized access to a computer system</li>
            <li><strong>Phishing</strong> — Sending fake emails to steal passwords/bank info</li>
            <li><strong>Identity Theft</strong> — Stealing someone's personal information online</li>
            <li><strong>Cyberbullying</strong> — Harassing someone on social media</li>
            <li><strong>Online Fraud</strong> — Fake lottery scams, UPI fraud</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c9)">
        <span class="q-num" style="background:var(--c9);color:#000">Q61</span>
        <span class="q-text">What is <em>Phishing</em>? How do hackers use it?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(20,184,166,.15);color:var(--c9);border:1px solid rgba(20,184,166,.3)" onclick="showAns(event,'a61')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a61">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>Phishing</strong> is a cyber attack where hackers send <strong>fake emails or messages</strong> that appear to be from a legitimate source (like a bank) to trick users into revealing their <strong>passwords, credit card numbers, or personal information</strong>.<br><br>
          <strong>How it works:</strong>
          <ol>
            <li>Hacker sends a fake email pretending to be from "SBI Bank"</li>
            <li>Email says "Your account will be closed — click here to update details"</li>
            <li>Link goes to a fake website that looks like SBI</li>
            <li>User enters login credentials → hacker steals them</li>
          </ol>
          <div class="key-point">💡 Always check the URL before entering personal information. Real banks never ask for passwords via email.</div>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c9)">
        <span class="q-num" style="background:var(--c9);color:#000">Q62</span>
        <span class="q-text">What is <em>IT Act 2000</em>? What is its full form?</span>
        <div class="q-right"><span class="q-marks">1M</span><button class="show-ans-btn" style="background:rgba(20,184,166,.15);color:var(--c9);border:1px solid rgba(20,184,166,.3)" onclick="showAns(event,'a62')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a62">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>IT Act 2000</strong> = <strong>Information Technology Act, 2000</strong><br><br>
          It is an Indian law passed by Parliament to <strong>legalize e-commerce</strong> and provide a <strong>legal framework for cyber crime</strong> in India.<br><br>
          <strong>Key provisions:</strong>
          <ul>
            <li>Hacking a computer system — punishable up to 3 years jail / ₹5 lakh fine</li>
            <li>Sending offensive emails — punishable under Section 66A</li>
            <li>Identity theft — punishable up to 3 years / ₹1 lakh fine</li>
            <li>Cyberbullying and stalking — punishable offense</li>
            <li>Publishing obscene content online — punishable</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="qtype">📝 Short Answer — 2 Marks</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c9)">
        <span class="q-num" style="background:var(--c9);color:#000">Q63</span>
        <span class="q-text">What is <em>Malware</em>? Explain three types: Virus, Worm, Trojan Horse.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(20,184,166,.15);color:var(--c9);border:1px solid rgba(20,184,166,.3)" onclick="showAns(event,'a63')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a63">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>Malware</strong> (Malicious Software) is any software designed to <strong>damage, disrupt, or gain unauthorized access</strong> to a computer system.<br><br>
          <table class="diff-table">
            <tr><th>Type</th><th>Description</th></tr>
            <tr><td><strong>Virus</strong></td><td>Attaches itself to programs and spreads when infected files are opened. Corrupts data. Like biological virus — needs a host.</td></tr>
            <tr><td><strong>Worm</strong></td><td>Self-replicates and spreads across networks WITHOUT needing a host file. Slows down network. Example: ILOVEYOU worm</td></tr>
            <tr><td><strong>Trojan Horse</strong></td><td>Disguises itself as legitimate software. When run, it opens a backdoor for hackers. Example: Fake antivirus apps</td></tr>
            <tr><td><strong>Ransomware</strong></td><td>Encrypts victim's files and demands ransom payment to restore. Example: WannaCry</td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c9)">
        <span class="q-num" style="background:var(--c9);color:#000">Q64</span>
        <span class="q-text">What is <em>Cyber Security</em>? Name four measures to stay safe online.</span>
        <div class="q-right"><span class="q-marks">2M</span><button class="show-ans-btn" style="background:rgba(20,184,166,.15);color:var(--c9);border:1px solid rgba(20,184,166,.3)" onclick="showAns(event,'a64')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a64">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text"><strong>Cyber Security</strong> is the practice of protecting computers, networks, programs and data from <strong>unauthorized access, damage, or cyber attacks</strong>.<br><br>
          <strong>Measures to stay safe online:</strong>
          <ul>
            <li><strong>Strong Password</strong> — Use long passwords with letters, numbers and symbols. Change regularly.</li>
            <li><strong>Antivirus Software</strong> — Install and keep updated (Windows Defender, Kaspersky)</li>
            <li><strong>Firewall</strong> — Blocks unauthorized incoming/outgoing network traffic</li>
            <li><strong>Encryption</strong> — Converts data to unreadable code to protect it during transmission</li>
            <li><strong>Two-Factor Authentication (2FA)</strong> — Extra verification step (OTP on phone)</li>
            <li><strong>Regular Updates</strong> — Keep OS and software updated to patch security vulnerabilities</li>
            <li><strong>Avoid phishing</strong> — Don't click suspicious links in emails</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--c9)">
        <span class="q-num" style="background:var(--c9);color:#000">Q65</span>
        <span class="q-text">What is <em>Cyber Crime</em>? Explain its types — Hacking, Phishing, Identity Theft, Cyberbullying — and punishments under IT Act 2000.</span>
        <div class="q-right"><span class="q-marks">5M</span><button class="show-ans-btn" style="background:rgba(20,184,166,.15);color:var(--c9);border:1px solid rgba(20,184,166,.3)" onclick="showAns(event,'a65')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="a65">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <strong>Cyber Crime:</strong> Illegal activities involving computers or the internet.<br><br>
          <strong>Types of Cyber Crime:</strong>
          <ul>
            <li><strong>Hacking</strong> — Unauthorized access to someone's computer or account. Example: Stealing bank account details</li>
            <li><strong>Phishing</strong> — Sending fake emails to steal passwords and personal info</li>
            <li><strong>Identity Theft</strong> — Using someone else's personal information for fraud</li>
            <li><strong>Cyberbullying</strong> — Harassing, threatening, or humiliating someone on social media</li>
            <li><strong>Online Fraud</strong> — Fake lottery, job offers, UPI fraud calls</li>
            <li><strong>Ransomware</strong> — Encrypting files and demanding money</li>
            <li><strong>Child Pornography</strong> — Sharing obscene content involving children (most serious crime)</li>
          </ul>
          <strong>IT Act 2000 Punishments:</strong>
          <table class="diff-table">
            <tr><th>Cyber Crime</th><th>Punishment</th></tr>
            <tr><td>Hacking</td><td>Up to 3 years jail + ₹5 lakh fine (Section 66)</td></tr>
            <tr><td>Identity Theft</td><td>Up to 3 years jail + ₹1 lakh fine (Section 66C)</td></tr>
            <tr><td>Cyberbullying</td><td>Up to 3 years jail (Section 66A)</td></tr>
            <tr><td>Publishing obscene content</td><td>Up to 5 years jail + ₹10 lakh fine (Section 67)</td></tr>
          </table>
          <strong>Prevention:</strong> Use strong passwords, install antivirus, enable 2FA, avoid clicking suspicious links, report cyber crime at <strong>cybercrime.gov.in</strong> or call <strong>1930</strong>.
        </div>
      </div>
    </div>

  </div>
</div>

<!-- BONUS -->
<div class="chapter" id="ch10">
  <div class="ch-head" onclick="toggle('ch10')" style="border-left:4px solid var(--star)">
    <span class="ch-num" style="background:var(--star);color:#000">★</span>
    <span class="ch-icon">🔥</span>
    <div class="ch-info"><div class="ch-name">Bonus — Most Expected Definitions & Full Forms</div><div class="ch-sub">Quick Revision — Ask Every Year in Board Exam!</div></div>
    <span class="ch-marks" style="background:var(--star);color:#000">All Chapters</span>
    <span class="ch-arrow">▼</span>
  </div>
  <div class="ch-body">

    <div class="qtype">⚡ Always Asked — With Answers</div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--star)">
        <span class="q-num" style="background:var(--star);color:#000">B1</span>
        <span class="q-text">Important Full Forms for Board Exam</span>
        <div class="q-right"><span class="q-marks">1M each</span><button class="show-ans-btn" style="background:rgba(251,191,36,.15);color:var(--star);border:1px solid rgba(251,191,36,.3)" onclick="showAns(event,'ab1')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="ab1">
        <div class="ans-label">✅ Full Forms</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>Abbreviation</th><th>Full Form</th></tr>
            <tr><td>AI</td><td>Artificial Intelligence</td></tr>
            <tr><td>ML</td><td>Machine Learning</td></tr>
            <tr><td>NLP</td><td>Natural Language Processing</td></tr>
            <tr><td>UAV</td><td>Unmanned Aerial Vehicle</td></tr>
            <tr><td>IT Act</td><td>Information Technology Act</td></tr>
            <tr><td>UPI</td><td>Unified Payments Interface</td></tr>
            <tr><td>B2B</td><td>Business to Business</td></tr>
            <tr><td>B2C</td><td>Business to Consumer</td></tr>
            <tr><td>C2C</td><td>Consumer to Consumer</td></tr>
            <tr><td>DGCA</td><td>Directorate General of Civil Aviation</td></tr>
            <tr><td>GPS</td><td>Global Positioning System</td></tr>
            <tr><td>VPN</td><td>Virtual Private Network</td></tr>
            <tr><td>2FA</td><td>Two-Factor Authentication</td></tr>
            <tr><td>OTP</td><td>One Time Password</td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--star)">
        <span class="q-num" style="background:var(--star);color:#000">B2</span>
        <span class="q-text">C Language — Format Specifiers and Data Types Quick Reference</span>
        <div class="q-right"><span class="q-marks">1-2M</span><button class="show-ans-btn" style="background:rgba(251,191,36,.15);color:var(--star);border:1px solid rgba(251,191,36,.3)" onclick="showAns(event,'ab2')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="ab2">
        <div class="ans-label">✅ Answer</div>
        <div class="ans-text">
          <table class="diff-table">
            <tr><th>Data Type</th><th>Format Specifier</th><th>Size</th><th>Example</th></tr>
            <tr><td>int</td><td>%d</td><td>2 or 4 bytes</td><td>int a = 10;</td></tr>
            <tr><td>float</td><td>%f</td><td>4 bytes</td><td>float pi = 3.14;</td></tr>
            <tr><td>char</td><td>%c</td><td>1 byte</td><td>char ch = 'A';</td></tr>
            <tr><td>double</td><td>%lf</td><td>8 bytes</td><td>double d = 3.14159;</td></tr>
            <tr><td>long int</td><td>%ld</td><td>4 bytes</td><td>long int x;</td></tr>
            <tr><td>string (char array)</td><td>%s</td><td>variable</td><td>char name[50];</td></tr>
          </table>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--star)">
        <span class="q-num" style="background:var(--star);color:#000">B3</span>
        <span class="q-text">Most Important C Programs to Memorize for Board</span>
        <div class="q-right"><span class="q-marks">5M each</span><button class="show-ans-btn" style="background:rgba(251,191,36,.15);color:var(--star);border:1px solid rgba(251,191,36,.3)" onclick="showAns(event,'ab3')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="ab3">
        <div class="ans-label">✅ Must-Know Programs</div>
        <div class="ans-text">
          These programs are <strong>most frequently asked</strong> in UP Board Class 10 exam:<br><br>
          <ol>
            <li>✅ <strong>Factorial</strong> of a number (for loop)</li>
            <li>✅ <strong>Prime or Not</strong> check</li>
            <li>✅ <strong>Fibonacci Series</strong> (loop and recursion)</li>
            <li>✅ <strong>Largest of Three Numbers</strong> (if-else)</li>
            <li>✅ <strong>Bubble Sort</strong> (ascending order)</li>
            <li>✅ <strong>Sum and Average</strong> of array elements</li>
            <li>✅ <strong>Structure</strong> for student record</li>
            <li>✅ <strong>File Read/Write</strong> using fprintf/fscanf</li>
            <li>✅ <strong>Swap using Pointers</strong></li>
            <li>✅ <strong>Even or Odd</strong> using function</li>
            <li>✅ <strong>Reverse a Number</strong> (while loop)</li>
            <li>✅ <strong>Sum of Digits</strong> of a number</li>
          </ol>
          <div class="key-point">💡 Practice writing all these programs by hand — exam is written, not typed!</div>
        </div>
      </div>
    </div>

    <div class="q-wrap">
      <div class="q-item hot" onclick="markQ(this)" style="--item-color:var(--star)">
        <span class="q-num" style="background:var(--star);color:#000">B4</span>
        <span class="q-text">Key Differences to Remember for Board Exam</span>
        <div class="q-right"><span class="q-marks">2M each</span><button class="show-ans-btn" style="background:rgba(251,191,36,.15);color:var(--star);border:1px solid rgba(251,191,36,.3)" onclick="showAns(event,'ab4')">▶ Answer</button></div>
      </div>
      <div class="ans-box" id="ab4">
        <div class="ans-label">✅ Key Differences</div>
        <div class="ans-text">Most important differences asked in UP Board:
          <ul>
            <li>Structure vs Union → <em>memory allocation</em></li>
            <li>Call by Value vs Call by Reference → <em>original unchanged vs changed</em></li>
            <li>1D Array vs 2D Array → <em>subscripts</em></li>
            <li>while vs do-while → <em>condition checking position</em></li>
            <li>Text File vs Binary File → <em>human-readable vs machine format</em></li>
            <li>AI vs ML vs Deep Learning → <em>relationship: AI ⊃ ML ⊃ DL</em></li>
            <li>Hacker vs Cracker → <em>white hat vs black hat</em></li>
            <li>Virus vs Worm → <em>needs host vs self-replicates</em></li>
            <li>E-Commerce vs E-Governance → <em>business vs government services</em></li>
          </ul>
        </div>
      </div>
    </div>

  </div>
</div>

</main>
</div>

<!-- FLOATING TRACKER -->
<div class="float-tracker">
  <span class="ft-label">Revised</span>
  <span class="ft-num" id="ft-num">0</span>
  <span class="ft-total">of 87 questions</span>
  <button class="ft-btn" onclick="window.scrollTo({top:0,behavior:'smooth'})">⬆ Top</button>
</div>

<script>
const TOTAL = 87;
let done = 0;

function toggle(id){
  document.getElementById(id).classList.toggle('open');
}
function openCh(id){
  const el=document.getElementById(id);
  el.classList.add('open');
  setTimeout(()=>el.scrollIntoView({behavior:'smooth',block:'start'}),100);
}
function showAns(e, id){
  e.stopPropagation();
  const box = document.getElementById(id);
  const btn = e.target;
  box.classList.toggle('show');
  btn.textContent = box.classList.contains('show') ? '▼ Hide' : '▶ Answer';
}
function markQ(el){
  if(!el.classList.contains('done')){
    el.classList.add('done');
    done++;
  } else {
    el.classList.remove('done');
    done=Math.max(0,done-1);
  }
  document.getElementById('ft-num').textContent=done;
  document.getElementById('prog-val').textContent=done+'/'+TOTAL;
  document.getElementById('prog-fill').style.width=(done/TOTAL*100)+'%';
}
function searchQ(val){
  const q=val.toLowerCase();
  document.querySelectorAll('.q-wrap').forEach(wrap=>{
    const txt=wrap.querySelector('.q-text').textContent.toLowerCase();
    const show=!q||txt.includes(q);
    wrap.style.display=show?'block':'none';
    if(show&&q) wrap.closest('.chapter').classList.add('open');
  });
}
document.querySelectorAll('.chapter').forEach((ch,i)=>{ch.style.animationDelay=(i*55)+'ms';});
</script>
</body>
</html>
