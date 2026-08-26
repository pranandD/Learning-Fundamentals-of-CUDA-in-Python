<div align="center">

# Fundamentals of Accelerated Computing with CUDA Python

[![NVIDIA DLI](https://img.shields.io/badge/NVIDIA-DLI%20Course-76B900?style=for-the-badge&logo=nvidia&logoColor=white)](https://www.nvidia.com/en-us/training/)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![CUDA](https://img.shields.io/badge/CUDA-Numba-76B900?style=for-the-badge&logo=nvidia&logoColor=white)](https://numba.readthedocs.io/en/stable/cuda/index.html)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

*Coursework and exercises from NVIDIA's Deep Learning Institute (DLI) course on GPU-accelerated computing using CUDA Python and Numba.*

</div>

---

## About

This repository contains my work from the **NVIDIA DLI — Fundamentals of Accelerated Computing with CUDA Python** course. It covers the core concepts of GPU programming in Python using the Numba compiler, progressing from basic GPU compilation to advanced memory optimization techniques.

## Course Sections

| Section | Topic | Description |
|---------|-------|-------------|
| [`section1/`](section1/) | **Introduction to CUDA Python with Numba** | GPU vs CPU compilation, writing and launching CUDA kernels, thread and block hierarchy |
| [`section2/`](section2/) | **Custom CUDA Kernels in Python with Numba** | Custom kernel development, grid-stride loops, multi-dimensional grids, debugging GPU code |
| [`section3/`](section3/) | **Effective Memory Use** | Coalesced memory access, shared memory, optimizing GPU throughput |

## Supplementary Notes

The [`notes/`](notes/) directory contains reference material on key GPU computing concepts:

| # | Topic |
|---|-------|
| 1 | GPU-Accelerated vs. CPU-Only Applications |
| 2 | Grid-Stride Loops |
| 3 | Memory Coalescing |
| 4 | Using Shared Memory to Support Coalesced Access |
| 5 | Shared Memory Bank Conflicts |

## Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3** | Primary language |
| **Numba** | JIT compiler for CUDA kernel development |
| **Jupyter Notebook** | Interactive development environment |
| **NVIDIA CUDA** | GPU computing platform |

## References

- [NVIDIA DLI — Fundamentals of Accelerated Computing with CUDA Python](https://www.nvidia.com/en-us/training/)
- [Numba CUDA Documentation](https://numba.readthedocs.io/en/stable/cuda/index.html)
- [CUDA Programming Guide](https://docs.nvidia.com/cuda/cuda-c-programming-guide/)

---

