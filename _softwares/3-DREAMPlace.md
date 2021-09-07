---
title: "GPU-Accelerated VLSI Placement"
collection: softwares
type: "Softwares"
permalink: /softwares/3-DREAMPlace
date: 2021-09-03
---

We release **[DREAMPlace 3.0](https://github.com/limbo018/DREAMPlace)**, a Deep learning toolkit-enabled VLSI placement engine.
DREAMPlace 3.0 supports region constraints with multi-electrostatic fields and enhanced gradient descent optimization with quadratic density penalty and adaptive entropy injection.
With the analogy between nonlinear VLSI placement and deep learning training problem, this tool is developed with deep learning toolkit for flexibility and efficiency. The tool runs on both CPU and GPU. Over 30X speedup over the CPU implementation (RePlAce) is achieved in global placement and legalization on ISPD 2005 contest benchmarks with a Nvidia Tesla V100 GPU.
DREAMPlace also integrates a GPU-accelerated detailed placer, _ABCDPlace_, which can achieve around 16X speedup on million-size benchmarks over the widely-adopted sequential placer NTUPlace3 on CPU.

