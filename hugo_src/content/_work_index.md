+++
title = "work"
menu = "main"
+++

---
*about*

A summary of where I've worked, what I've built, and what I've led.

EXPERIENCE
---

**Computer Engineering Intern** | Kinectrics, Nuclear Equipment Solutions — *September 2025 – September 2026*
- Owned the full software stack (PLC control logic, HMI, and database) for a medical isotope production system; absorbed all remaining development as the team shrank from 3 developers to 1 and carried the build to release.
- Automated 7 operator-controlled sequences (target loading, target unloading, in-system leak testing) in Structured Text and JavaScript on Beckhoff TwinCAT 3, replacing 4–5 manual procedures per sequence with a single operator input.
- Built a standalone I/O simulator on a secondary PLC emulating field devices (14 valves, 3 analog inputs, 3 analog outputs, and additional I/O), interlocks, and fault conditions across all 7 sequences, enabling reproducible full-scope QA without physical plant hardware.
- Engineered 8 custom unit operations for DWSIM (open-source chemical process simulator) in VB.NET, translating Engineering Equation Solver (EES) models into production software used to evaluate tritium extraction in CANDU reactors.
- Wrote CLAUDE.md guidelines and custom Claude skills that codify the DWSIM editor architecture (VB.NET WinForms): a single top-down refresh lifecycle, connection handling, and results grids, so AI-generated code followed one consistent pattern across every unit operation.
- Used those skills to scaffold unit-operation editor UIs and result charts far faster than hand-building each form, reviewing every generated editor against the simulation results before release.

**Freelance Software Developer** | Item Trading Platform for Rust (the game) — *May 2023 – January 2024*
- Built a FastAPI and WebSockets backend synchronizing schema models between users and bots for real-time in-game trades, and cut infrastructure spend by 86% with 3 containerized (Docker) DigitalOcean droplets distributing requests across IP addresses.
- Reduced external API call volume by 50% by adding a caching layer to an open-source bot framework.

PROJECTS
---

**Engine: AI-Assisted Real-Time Audio Capture** | C++20, WASAPI, libsamplerate, libopus, pi-agent
- Built a per-app audio isolation engine (mic plus Discord/loopback, drift-corrected multi-track recording) with pi-agent, using custom skills I wrote to run a plan-then-implement workflow that delivered 15+ scoped tasks, while personally owning architecture, technology tradeoffs, and hardware validation.
- Set the boundaries the agent worked within: a signal-only engine with judgment deferred to an offline local-only pass, and a two-sidecar-log model for cross-track event correlation. Chose C++/WASAPI over Python to meet a ~10 ms zero-allocation capture deadline.
- Designed 3 validation gates an agent couldn't run: FFT-measured 76 dB per-app isolation, a 10-minute live mic acceptance run, and a 2-hour soak test, which caught a test flaw where a local clock pair passed with drift correction disabled.

**[Video Content Pipeline](https://github.com/andysit1/Video-Content-Pipeline)** | Python, OpenCV
- Built a pipeline that selects and stitches clips from long-form Twitch and YouTube streams into a single video, cutting manual clip-hunting and editing time by 90%.
- Cut processing time for a 6-hour stream from 2 hours to 30 minutes, with lower memory use, using OpenCV routines for colour-format and resolution conversion.

EDUCATION
---

**University of Western Ontario** — *September 2022 – April 2027 (expected)*
Bachelor of Science | Major in Computer Science (Co-op)
Major GPA: 3.79/4.0 | Dean's Honor List (2022–23, 2024–25) | Western Admission Scholarship

LEADERSHIP
---

**Vice President of Production** | Western Esports & Gaming, UWO — *September 2023 – April 2025*
- Led a 5-person executive team producing live streams for 12 esports teams; raised over $1,200 for UNICEF by directing a flagship 24-hour livestream.

TECHNOLOGIES
---

**AI-Assisted Development:** Claude (CLAUDE.md, custom skills), pi-agent, plan-then-implement workflows
**Backend & Systems:** FastAPI, WebSockets, MySQL, Docker, Linux/Unix, FreeBSD, Git, DigitalOcean
**Media & Simulation:** OpenCV, WASAPI, Beckhoff TwinCAT 3, hardware-in-the-loop testing, DWSIM

---

Reach me at [andysit173@gmail.com](mailto:andysit173@gmail.com), on [LinkedIn](https://linkedin.com/in/andy-sit), or on [GitHub](https://github.com/andysit1).
