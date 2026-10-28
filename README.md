<h1 align="center">Josh</h1>

<p align="center">
I build things that have to be measured: robots, circuit tools, vision systems, desktop apps and market research.<br>
Most of what I write is Python, with C++, Rust and TypeScript when the job needs them.
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-1f2937?style=flat-square&logo=python&logoColor=white">
  <img alt="C++" src="https://img.shields.io/badge/C++-1f2937?style=flat-square&logo=cplusplus&logoColor=white">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-1f2937?style=flat-square&logo=rust&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-1f2937?style=flat-square&logo=typescript&logoColor=white">
  <img alt="KiCad" src="https://img.shields.io/badge/KiCad-1f2937?style=flat-square&logo=kicad&logoColor=white">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-1f2937?style=flat-square&logo=pytorch&logoColor=white">
  <img alt="Fusion" src="https://img.shields.io/badge/Fusion-1f2937?style=flat-square&logo=autodesk&logoColor=white">
</p>

## Projects

### Hardware and robotics

| Project | What it is |
|---|---|
| [**Kairo**](https://github.com/JoshChomps/Kairo) | An MCP server that turns a described circuit into a checked KiCad schematic. Every voltage and current is worked out twice, by cited formulas and by ngspice/Xyce simulation, and anything unchecked is marked unverified. |
| [**7_DOF_Arm**](https://github.com/JoshChomps/7_DOF_Arm) | A mostly 3D-printed, 7-axis desk arm with swappable end effectors. Modelled and checked in Fusion by script, with a software digital twin running in simulation. |

### Vision

| Project | What it is |
|---|---|
| [**Drone-Detection**](https://github.com/JoshChomps/Drone-Detection) | A ground camera looking up, a YOLO detector on motion-cued crops, a tracker and a decision layer. Every cited paper was checked against arXiv and Crossref. |
| [**Drone-to-Drone**](https://github.com/JoshChomps/Drone-to-Drone) | Drones that locate each other from the air and share positions: a five-on-five tracker and teammate cueing, with measured results in the build log. |

### Software

| Project | What it is |
|---|---|
| [**Stupefinity**](https://github.com/JoshChomps/stupefinity) | A native, lightweight Windows 11 music player for Spotify Premium, written in Rust. The whole app runs in under 10 MB of memory. |
| [**Scraper**](https://github.com/JoshChomps/Scraper) | A self-hosted extraction tool that reads REIT financial statements out of annual-report PDFs, one record per figure, each checked against the page's own arithmetic. |
| [**Job-hunter**](https://github.com/JoshChomps/Job-hunter) | Pulls job postings from boards and company ATS feeds into one database, filters them hard, checks visa sponsorship rules, and tracks applications. |
| [**AI_Library**](https://github.com/JoshChomps/AI_Library) | Kinesis, a low-level C++20 maths and ML engine aimed at fixed-latency work. CPU kernels exist; the domain modules are planned. |
| [**CUDA_Translator**](https://github.com/JoshChomps/CUDA_Translator) | A prototype that translates PTX into an intermediate representation and lowers it to AMD ROCm and Vulkan SPIR-V. |

### Markets and research

| Project | What it is |
|---|---|
| [**copytrading**](https://github.com/JoshChomps/copytrading) | Tests how much of a disclosed trader's edge survives the filing delay and real costs, with strict point-in-time rules. |
| [**Finance_using_DSP**](https://github.com/JoshChomps/Finance_using_DSP) | Splits price action into frequency components with wavelets to cut indicator lag. |

### Simulation

| Project | What it is |
|---|---|
| [**Gravity-well-sim**](https://github.com/JoshChomps/Gravity-well-sim) | 3D planetary simulation where gravity is drawn as wells. Also a [WebGL version](https://github.com/JoshChomps/Gravity-well-sim-web) and a [3D grid version](https://github.com/JoshChomps/Gravity-sim-3D-grid). |

Anything not listed here is experimentation and fluff of my own machinations.

## How I work

- I write down what a result would have to look like before I run the test, then report the result either way.
- Numbers get a source or a measurement. If I could not check something, the docs say so.
- Small, readable code over clever code.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=JoshChomps&show_icons=true&hide_border=true&theme=transparent&title_color=9ca3af&text_color=9ca3af&icon_color=9ca3af">
    <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=JoshChomps&show_icons=true&hide_border=true&theme=transparent&title_color=4b5563&text_color=4b5563&icon_color=4b5563">
  </picture>
</p>
