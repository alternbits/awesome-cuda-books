# Awesome CUDA Books

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
> A curated list of **every major book** on CUDA programming — beginner to advanced, C++/Python, architecture, optimization, and the latest 2024–2026 releases.  
> Focused on practical, high-quality resources for NVIDIA GPU parallel computing.

**Last updated:** May 2026  
**Contributions welcome!** See [Contributing](#contributing).

## Contents

- [Beginner / Getting Started](#beginner--getting-started)
- [Core Architecture & Parallel Programming](#core-architecture--parallel-programming)
- [Practical & Hands-on Guides](#practical--hands-on-guides)
- [Advanced / Optimization / Reference](#advanced--optimization--reference)
- [Python & High-Level CUDA](#python--high-level-cuda)
- [Modern & Recent Releases (2022–2026)](#modern--recent-releases-2022-2026)
- [Contributing](#contributing)
- [Related Awesome Lists](#related-awesome-lists)

## Beginner / Getting Started

- **[CUDA by Example: An Introduction to General-Purpose GPU Programming](https://www.amazon.com/CUDA-Example-Introduction-General-Purpose-Programming/dp/0131387685)**  
  *Jason Sanders & Edward Kandrot (2010, Addison-Wesley)*  
  The timeless classic. Short, example-driven, perfect first book.

- **[Learn CUDA Programming](https://www.packtpub.com/product/learn-cuda-programming/9781788996242)**  
  *Jaegeun Han & Bharatkumar Sharma (2019, Packt)*  
  Modern beginner-to-intermediate with CUDA 10+ examples and GitHub repo.

- **[CUDA for Engineers: An Introduction to High-Performance Parallel Computing](https://www.amazon.com/CUDA-Engineers-Introduction-High-Performance-Computing/dp/013417741X)**  
  *Mete Yurtoglu & Duane Storti (2016, Addison-Wesley)*  
  Engineer-focused, hands-on projects for scientists and non-CS folks.

## Core Architecture & Parallel Programming

- **[Programming Massively Parallel Processors: A Hands-on Approach (3rd Edition)](https://www.amazon.com/Programming-Massively-Parallel-Processors-Hands/dp/0323912311)**  
  *David B. Kirk & Wen-mei W. Hwu (2022)*  
  **The definitive GPU architecture bible.** Used in universities worldwide.

## Practical & Hands-on Guides

- **[Programming in Parallel with CUDA: A Practical Guide](https://www.cambridge.org/core/books/programming-in-parallel-with-cuda/9781108855273)**  
  *Richard Ansorge (2022, Cambridge University Press)*  
  Real-world scientific examples (stencils, Monte Carlo, imaging). Excellent modern C++ coverage.

- **[Professional CUDA C Programming](https://www.amazon.com/Professional-CUDA-Programming-John-Cheng/dp/1118737636)**  
  *John Cheng, Max Grossman & Ty McKercher (2014, Wrox)*  
  Production-level: multi-GPU, streams, libraries, and performance pitfalls.

- **[GPU Parallel Program Development Using CUDA](https://www.routledge.com/GPU-Parallel-Program-Development-Using-CUDA/Soyata/p/book/9780367572242)**  
  *Tolga Soyata (2018, Chapman & Hall/CRC)*  
  Strong on libraries (cuBLAS, cuFFT, Thrust, NPP) and OpenCL comparison.

- **[CUDA for Deep Learning](https://www.manning.com/books/cuda-for-deep-learning)**
  *Elliot Arledge (2025, Manning)*
  From first kernels to Flash Attention — teaches hands-on CUDA optimization for deep learning with Nsight Compute profiling.

## Advanced / Optimization / Reference

- **[The CUDA Handbook: A Comprehensive Guide to GPU Programming](https://www.amazon.com/CUDA-Handbook-Comprehensive-Guide-Programming/dp/0134852745)**  
  *Nicholas Wilt (2013)*  
  The deep-dive reference. Every API detail and low-level trick.

- **[CUDA Programming: A Developer's Guide to Parallel Computing with GPUs](https://www.elsevier.com/books/cuda-programming/cook/978-0-12-415933-4)**  
  *Shane Cook (2013, Morgan Kaufmann)*  
  Parallel algorithms, optimization patterns, and best practices.

- **[CUDA Application Design and Development](https://www.elsevier.com/books/cuda-application-design-and-development/farber/978-0-12-388426-8)**  
  *Rob Farber (2011, Morgan Kaufmann)*  
  Real research applications and scalable design.

## Python & High-Level CUDA

- **[Hands-On GPU Programming with Python and CUDA](https://www.amazon.com/Hands-Programming-Python-CUDA-high-performance/dp/1788993918)**  
  *Brian Tuomanen (2018, Packt)*  
  Best for Python users — Numba, CuPy, and raw bindings.

- **[GPU Programming with C++ and CUDA](https://www.packtpub.com/product/gpu-programming-with-c-and-cuda/9781805124542)** (or 9781805128823 variant)  
  *Paulo Motta (2024, Packt)*  
  Modern C++20 + Python interop (pybind11).

## Modern & Recent Releases (2022–2026)

- **Programming in Parallel with CUDA** (Ansorge, 2022) — see above
- **Programming Massively Parallel Processors (3rd Ed.)** (Kirk & Hwu, 2022) — see above
- **GPU Programming with C++ and CUDA** (Motta, 2024) — see above

- **CUDA for Deep Learning** (Arledge, 2025, Manning) — see above

**Notable 2024–2026 titles** (mostly specialized or self-published but frequently appearing in searches):
- *CUDA C++ Optimization* – David Spuler (2024) — kernel performance & memory tuning
- *CUDA C++ Debugging* – Dr. David Spuler (2024) — error checking & Nsight
- *CUDA Programming from Basics to Advanced* – Finbarrs Oketunji (2024, covers CUDA 12.6)
- *CUDA Mastery* – Elbert Gale (2024) — scientific simulations & CUDA-X
- *CUDA in Action* – Leon Chapman (2024) — Tensor Cores & multi-GPU
- *Mastering CUDA C++ Programming* – Brett Neutreon (2024) / Toby Webber (2025) — comprehensive C++ guides
- *High-Performance Computing with C++26 and CUDA 13* – William M. Crutcher (2026)

> **Pro tip:** CUDA changes fast. Always pair books with the free official **[CUDA C++ Programming Guide (v13.x, 2026)](https://docs.nvidia.com/cuda/cuda-c-programming-guide/)**.

## Contributing

- Add a new high-quality book? Open a PR with title, authors, year, short description, and link.
- Preference for books **post-2018** or still relevant classics.
- Only include books with substantial code/examples and good reviews.

## Related Awesome Lists

- [awesome-cuda](https://github.com/vincentherrmann/awesome-cuda) — tools & libraries
- [awesome-gpu](https://github.com/antonmks/awesome-gpu)
- [awesome-parallel-computing](https://github.com/rossant/awesome-parallel-computing)

---

**Star the repo** if this helps you write faster kernels! 🚀  
Fully expanded after a full web search — this is now the most complete public CUDA books list.
