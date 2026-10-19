<h1 align="center">Hi, I'm Alex 👋</h1>

<p align="center">
  <b>I build things that ship: web apps, tools and robots.</b><br>
  Student at TU Eindhoven · from Cluj, Romania · based in Eindhoven, NL
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/alexandru-ciornai"><img src="https://img.shields.io/badge/LinkedIn-alexandru--ciornai-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:alex24ciornai@gmail.com"><img src="https://img.shields.io/badge/Email-alex24ciornai%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## 🙋 About me

- I like problems with real users. I've built a security prototype for a company, live price calculators for an online store, and a bot that books my padel court.
- I co-founded two FIRST robotics teams. At FRC we were the **first Romanian team ever to win an award at the World Championship**.
- 🔨 **Right now:** getting ready for **Junction 2026** and maintaining the VIVODECOR calculators.
- Outside code, I drive our FRC robot, mentor FIRST LEGO League kids and play padel (hence the bot).

---

## 🚀 Featured projects

### 🛡️ Protection Studio · [live demo ↗](https://legendary-strudel-73ee63.netlify.app/)

<a href="https://legendary-strudel-73ee63.netlify.app/"><img src="assets/protection-studio.png" alt="Protection Studio: the Trade-off Studio cockpit, where you drag two cut-offs on the visitor-score distribution and see bots let through versus customers blocked" width="100%"></a>

A take-home assignment for **Securely**, a web application firewall company. It helps their customers move from *watching* attacks to *blocking* them without blocking real customers.
- **Three cockpits for three audiences** (leadership, manager, engineer), all driven by one pure policy simulator. It replays ~1.2M requests in ~12 ms, so dragging a cut-off updates the impact live.
- Canary rollout with a circuit breaker, replay against last week's traffic, and per-rule amendments instead of disabling a rule.
- Policy as code: every version exports as JSON and ModSecurity rules. 73 unit tests.
- **Built in 5 days.** React · TypeScript · Vite · Zustand · Vitest

### 🎾 [Padel Sniper](https://github.com/AlexandruCiornai/Padel-Sniper)

<img src="assets/padel-sniper.png" alt="Padel Sniper booking screen on a phone" width="230" align="right">

The courts in my town open for booking exactly 14 days ahead, and the evening slots are gone in seconds. So I built a bot.

- You pick a date and hour on your phone.
- A headless browser logs in 2 minutes early, waits on the calendar page, and clicks the slot at exactly `hh:mm:00`.
- Live status reaches the phone over Socket.IO, and the result arrives by email.
- The timing is DST-safe, and access is PIN-protected with lockout.

Python · Flask · Playwright · APScheduler · Socket.IO

<br clear="right">

### 🧮 [VIVODECOR calculators](https://github.com/vivodecor/calculatoare) · [live ↗](https://www.vivodecor.ro/calculator-gard-wpc)

<a href="https://www.vivodecor.ro/calculator-gard-wpc"><img src="assets/vivodecor-calculator.png" alt="VIVODECOR fence calculator: a to-scale drawing of the fence next to color, size and spacing options" width="100%"></a>

Price and quantity calculators for a Romanian store selling WPC fencing, cladding and decking. They run live on the store.
- They draw the fence to scale, with wood textures generated pixel by pixel and matched to product photos.
- Prices sync from the store, and customers can request a quote, send their configuration by WhatsApp or download a PDF.
- The store platform strips `<script>` tags, so the engines are served from GitHub via jsDelivr with versioned releases.
- Releases are checked by a jsdom regression suite. For the fence calculator, that means 88 configurations on desktop and mobile.

JavaScript · SVG/Canvas · Python build · Google Apps Script

---

## 🏆 Hackathons & robotics

- **Cluj Hackathon ×3 (2023, 2024, 2025).** Each time, a 48-hour AI startup prototype built from scratch with two friends and pitched to mentors and investors. The latest is an AI tool that validates business ideas from market and competitor data and writes the business plan for a loan application.
- **AlphaZ #11141 (FRC), co-founder.** I'm the driver, I wrote our custom driver-station dashboard, and I raised $61K+. Rookie All-Star at the **FIRST Championship 2026** in Houston, plus Rookie All-Star (Ankara) and the Quality Award (Başkent).
- **Alphatronic (FTC), co-founder and captain.** Inspire Award at Regional and National level, and the Design Award at the FTC World Championship. I raised $185K+ over two seasons.
- **Internships:** AROBS (web, embedded C on STM32, cybersecurity) and Bosch (electrical and pneumatics).

---

## 🧰 Tech I use

<p>
  <img src="https://skillicons.dev/icons?i=ts,react,vite,python,flask,java,cpp,threejs,git,linux,netlify" alt="TypeScript, React, Vite, Python, Flask, Java, C++, Three.js, Git, Linux, Netlify">
</p>

Also Playwright, Zustand, Vitest, jsdom, APScheduler, STM32 (Keil, CubeMX) and WPILib.
