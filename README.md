<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:1e293b&height=200&section=header&text=Yousef%20Ali%20Aicha&fontSize=42&fontColor=e2e8f0&animation=fadeIn&fontAlignY=38&desc=Systems%20%2F%20Embedded%20%2F%20ML%20Engineering&descAlignY=58&descSize=18&descColor=94a3b8" />

<img src="https://readme-typing-svg.demolab.com/?lines=Embedded+Systems+%26+Firmware;Simulation+%26+Monte+Carlo+Methods;Machine+Learning+%2F+ML+Systems;Hardware-Software+Integration&font=Fira+Code&center=true&width=600&height=40&color=94A3B8&vCenter=true&size=18&pause=1800" />

</div>

<br>

## About

Yousef Ali Aicha — CSAI student at IE University, second year. I build systems where a PCB
and firmware on one end feed a model or dashboard on the other — usually
in the same project. Interested in defense, robotics, and simulation work
where the hardware layer is the hard part.

<br>

## Stack

<div align="center">

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-4B8BBE?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

<br>

## Flagship projects

| Project | What it is |
| --- | --- |
| **[Ballista](https://github.com/YousefAliAicha/ballista)** | C++17 Monte Carlo ballistics sim — RK4 integration, Mach-dependent drag, altitude-coupled wind. Validated against closed-form solutions (0.00000m error on zero-drag range, RK4 convergence ratio 16.01 vs theoretical 16×) and stress-tested across 100 independent RNG seeds (CEP std dev 1.48% of mean). |
| **[AEGIS](https://github.com/YousefAliAicha/aegis-embedded-system)** | ESP32-S3 rotating ultrasonic radar. Custom KiCad PCB, non-blocking firmware, dashboard served from the board's own flash with WebSocket telemetry and click-to-steer control. Falls back to local-only operation if Wi-Fi drops — the sensing loop never depends on the network. |
| **[Raycaster-Engine](https://github.com/YousefAliAicha/Raycaster-Engine)** + **[Rayborn](https://github.com/YousefAliAicha/Rayborn)** | Wolfenstein-style 2.5D engine, twice: first vectorized in Python/NumPy (32 headless tests, hand-rolled Taylor-series trig with two documented and regression-tested bug fixes), then rewritten — not ported — in zero-dependency JavaScript/Canvas for real-time browser play. |

<br>

## Other projects

| Project | Description |
| --- | --- |
| **[SENTINEL](https://github.com/YousefAliAicha/sentinel-arduino-firmware)** | Bare ATmega328P traffic-light FSM, zero libraries. Pedestrian preemption, LDR-gated night mode with vehicle detection, 74HC595-driven 7-segment countdown, no `delay()` in the main loop. Own KiCad PCB. |
| **[Splice-Engine](https://github.com/YousefAliAicha/splice-engine)** | MovieLens recommender: cold-start genre scoring → item-KNN → stacked LightGBM ensemble, hybridized with FAISS content embeddings. SVD++ was implemented, benchmarked, and dropped after it underperformed simpler tiers. Test RMSE 0.90 (100k) / 0.85 (1M). Streamlit dashboard with a live feedback loop. |
| **[GRAVITAS](https://yousefaliaicha.me/)** | Portfolio site — three recruiter-facing tracks (Systems / Creative Tech / Startup), Three.js excavation-themed landing scene, single-source project data model driving tracks, archive, and routing. |

<br>

## Currently building

| Project | What it is | Target |
| --- | --- | --- |
| **NoorMap** | Real-time disaster/weather map for Syria on NASA EONET/FIRMS feeds — scoped for eventual handoff to a non-technical stakeholder, documentation-first | Aug 2026 |
| **Principia** | Interactive classical mechanics sandbox for IE's physics department — forces/motion/energy as live adjustable parameters | 2026 |
| **Predictive Object Tracking** | ESP32 dual-stream (camera + IMU) feeding a Kalman-filtered YOLOv8n tracker — IMU angular rates compensate the prediction step so tracks survive platform motion | 2026 |
| **NullShell** | POSIX shell/REPL in C++ from scratch — fork/exec, pipes, job control | TBD |
| **Genesis** | SDL2 engine scaffold — window, render loop, input | TBD |

<br>

## GitHub Stats

<div align="center">

<img width="480" src="https://streak-stats.demolab.com?user=YousefAliAicha&theme=dark&hide_border=true" />

</div>

<br>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge)](https://www.linkedin.com/in/yousefaliaicha)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:1e293b&height=100&section=footer" />
