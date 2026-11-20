<div align="center">
  <h1>Hi, I'm Alex 👋</h1>
  <p><strong>Security Researcher · Reverse Engineer · Computer Vision Engineer</strong></p>
  <p>
    I build and study high-performance systems at the intersection of software security,
    native Windows development, and real-time computer vision.
  </p>
</div>

<p align="center">
  <a href="https://t.me/in_the_skyyy"><img src="https://img.shields.io/badge/Contact%20me-%40in__the__skyyy-2AABEE?style=for-the-badge&logo=telegram&logoColor=white" alt="Contact me on Telegram"></a>
  <a href="https://t.me/lunaraim"><img src="https://img.shields.io/badge/LunarAim-%40lunaraim-2548BB?style=for-the-badge&logo=telegram&logoColor=white" alt="LunarAim Telegram channel"></a>
  <a href="https://t.me/lunaraim2"><img src="https://img.shields.io/badge/LunarAim%202-%40lunaraim2-17C3E1?style=for-the-badge&logo=telegram&logoColor=white" alt="LunarAim 2 Telegram channel"></a>
</p>

<details>
<summary>Table of contents</summary>
<br>

- [About me](#about-me)
- [Focus areas](#focus-areas)
- [Core toolbox](#core-toolbox)
- [Featured project](#featured-project)
  - [LunarAim 2.2 — C++ redesign](#lunaraim-22--c-redesign)
  - [LunarEngine Open — Python predecessor](#lunarengine-open--python-predecessor)
- [How I work](#how-i-work)
- [Contact](#contact)

</details>

## About me

I am a Computer Security student at **HSE MIEM**, graduating in **2031**. My work combines reverse engineering, security testing, native systems programming, and applied machine learning.

I am especially interested in understanding how software behaves at the boundary between a high-level application, the operating system, hardware acceleration, and real-time data. I like taking a system apart, measuring what actually happens, and rebuilding the critical path with explicit performance and reliability constraints.

## Focus areas

- **Reverse engineering and security research** — binary analysis, software behavior analysis, Windows internals, and responsible vulnerability research.
- **Security testing** — binary-focused testing, forensics, and non-web network security testing.
- **Classical computer vision** — OpenCV pipelines, color-space segmentation, geometric reasoning, morphology, filtering, and high-throughput image processing.
- **Deep learning for vision** — YOLO-family detectors, Ultralytics workflows, dataset preparation, training, validation, experiment analysis, and inference integration.
- **Performance engineering** — profiling, debugging, latency analysis, pre-processing/inference/post-processing optimization, and minimizing end-to-end pipeline overhead.

## Core toolbox

<p align="center">
  <a href="https://isocpp.org/"><img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++"></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"></a>
  <a href="https://en.cppreference.com/w/c/language"><img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C"></a>
  <a href="https://en.wikipedia.org/wiki/Assembly_language"><img src="https://img.shields.io/badge/Assembly-525252?style=for-the-badge&logoColor=white" alt="Assembly"></a>
  <a href="https://opencv.org/"><img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"></a>
  <a href="https://pytorch.org/"><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"></a>
  <a href="https://github.com/ultralytics/ultralytics"><img src="https://img.shields.io/badge/Ultralytics%20YOLO-111F68?style=for-the-badge&logoColor=white" alt="Ultralytics YOLO"></a>
  <a href="https://developer.nvidia.com/tensorrt"><img src="https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="TensorRT"></a>
  <a href="https://learn.microsoft.com/en-us/windows/win32/"><img src="https://img.shields.io/badge/Win32-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Win32 API"></a>
  <a href="https://cmake.org/"><img src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white" alt="CMake"></a>
</p>

I write production-oriented code in **C++ and Python**, work comfortably in **C**, and use **Assembly** when low-level inspection or reasoning requires it. I also have hands-on experience with profiling, debugging, Windows-native APIs, GPU inference, and data pipelines for computer-vision models.

## Featured project

LunarAim is one long-running engineering project that can be viewed through two separate repositories and two technology generations:

<p align="center">
  <a href="https://github.com/lnTheSky/lunar_v2_showdown">
    <img src="https://raw.githubusercontent.com/lnTheSky/lunar_v2_showdown/main/assets/brand/lunar-aim-banner.png" alt="LunarAim 2.2 — C++ redesign" width="48%">
  </a>
  <a href="https://github.com/lnTheSky/LunarEngine_Open">
    <img src="https://raw.githubusercontent.com/lnTheSky/LunarEngine_Open/main/media/image.png" alt="LunarEngine Open — Python predecessor" width="48%">
  </a>
</p>

### LunarAim 2.2 — C++ redesign

[Open the LunarAim V2 showcase →](https://github.com/lnTheSky/lunar_v2_showdown)

The current generation is a **C++ native redesign** with an explicit runtime architecture and a structured frontend bridge. It is still being developed and is not an end-of-life project.

The project brings together:

- modular runtime orchestration and observable lifecycle state;
- a native UI bridge built around WebView2;
- Win32 Raw Input and DirectX-based desktop capture;
- replaceable detector, trigger, and mouse contracts;
- OpenCV/Colorbot and YOLO-based detection paths;
- CUDA/TensorRT integration with dynamic GPU-module boundaries;
- profiling, telemetry, and latency-focused pipeline design.

The public repository is a **technical showcase**. The production runtime and proprietary implementation remain private.

### LunarEngine Open — Python predecessor

[Open the archived LunarEngine repository →](https://github.com/lnTheSky/LunarEngine_Open)

The older generation is a **Python 3.11 research snapshot**. It documents the earlier experimental approach: Flet-based desktop UI, OpenCV color processing, model-assisted detection, configuration-heavy iteration, and several Windows input/output experiments.

It is preserved as an archive rather than a usable release. The repository explicitly states that the code is obsolete, unsupported, and not intended for operation or adaptation.

## How I work

My strongest projects combine low-level understanding with measurable system behavior:

1. **Understand the data path.** Reverse-engineer the relevant behavior, identify the real inputs and outputs, and define what can be measured.
2. **Build the smallest useful experiment.** Test an algorithm or integration point in isolation before embedding it into the larger runtime.
3. **Measure every stage.** Profile capture, pre-processing, inference, post-processing, control logic, and output separately.
4. **Learn from the data.** Prepare datasets, train models, inspect failures, compare experiments, and turn observations into concrete changes.
5. **Integrate end to end.** Carry the result into a working application with explicit boundaries, diagnostics, and a path for replacing implementations.

## Contact

For project discussions and collaboration, reach me at [@in_the_skyyy](https://t.me/in_the_skyyy). Project updates and related materials are shared through [@lunaraim](https://t.me/lunaraim) and [@lunaraim2](https://t.me/lunaraim2).

<br>

<div align="center">
  <sub>Security research · native systems · real-time computer vision</sub>
</div>
