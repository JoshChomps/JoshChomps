<h1 align="center">Josh</h1>

<p align="center">
I build things that have to be measured: robots, circuit tools, vision systems and market research.<br>
Based in Vancouver, BC. Most of what I write is Python, with C++ and TypeScript when the job needs them.
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-1f2937?style=flat-square&logo=python&logoColor=white">
  <img alt="C++" src="https://img.shields.io/badge/C++-1f2937?style=flat-square&logo=cplusplus&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-1f2937?style=flat-square&logo=typescript&logoColor=white">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-1f2937?style=flat-square&logo=rust&logoColor=white">
  <img alt="KiCad" src="https://img.shields.io/badge/KiCad-1f2937?style=flat-square&logo=kicad&logoColor=white">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-1f2937?style=flat-square&logo=pytorch&logoColor=white">
  <img alt="Fusion" src="https://img.shields.io/badge/Fusion-1f2937?style=flat-square&logo=autodesk&logoColor=white">
</p>

## What I work on

| Area | Project | What it is |
|---|---|---|
| Circuits | **Kairo** | An MCP server that turns a described circuit into a checked KiCad schematic. Every voltage and current is worked out twice, by cited formulas and by ngspice/Xyce simulation, and anything unchecked is marked unverified. |
| Robotics | **7-DOF desk arm** | A mostly 3D-printed, 7-axis arm with swappable end effectors. Modelled and checked in Fusion by script, with a software digital twin running in simulation. Parts are bought; printing starts with tolerance coupons. |
| Vision | **Drone detection** | A ground camera looking up, a YOLO detector on motion-cued crops, a tracker and a decision layer. Backed by a reference list where every citation was checked against arXiv and Crossref. |
| Vision | **Drone to drone** | Drones that locate each other from the air and share positions. A five-on-five tracker and teammate cueing, with measured results in the build log. |
| Data | **Scraper** | A self-hosted extraction tool that reads REIT financial statements out of annual-report PDFs, one record per figure, each checked against the page's own arithmetic. |
| Research | **Singapore REITs** | Verified fundamentals for 40+ listed REITs, pre-registered indicator studies, and a record of what did not work. |
| Research | **Copytrade** | Tests how much of a disclosed trader's edge survives the filing delay and real costs, with strict point-in-time rules. |

Most of these repositories are private for now.

## Public repositories

| Repository | Description |
|---|---|
| [**AI_Library**](https://github.com/JoshChomps/AI_Library) | Kinesis, a low-level C++20 maths and ML engine aimed at fixed-latency work. CPU kernels exist; the domain modules are planned. |
| [**CUDA_Translator**](https://github.com/JoshChomps/CUDA_Translator) | A prototype that translates PTX into an intermediate representation and lowers it to AMD ROCm and Vulkan SPIR-V. |
| [**Bias-Spotter**](https://github.com/JoshChomps/Bias-Spotter) | Finds persuasion techniques in text with a fine-tuned ModernBERT classifier, not a prompt to a chatbot. |
| [**Finance_using_DSP**](https://github.com/JoshChomps/Finance_using_DSP) | Splits price action into frequency components with wavelets to cut indicator lag. |
| [**Gravity-well-sim**](https://github.com/JoshChomps/Gravity-well-sim) | 3D planetary simulation where gravity is drawn as wells. Also a [WebGL version](https://github.com/JoshChomps/Gravity-well-sim-web). |

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
