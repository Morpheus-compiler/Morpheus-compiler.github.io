---
layout: page
title: Domain Specific Run Time Optimization for Software Data Planes
permalink: /
---


[![Morpheus DUT Build](https://github.com/Morpheus-compiler/Morpheus/actions/workflows/morpheus-build.yml/badge.svg)](https://github.com/Morpheus-compiler/Morpheus/actions/workflows/morpheus-build.yml)
[![Morpheus Packet Generator Build](https://github.com/Morpheus-compiler/Morpheus/actions/workflows/morpheus-pktgen-build.yml/badge.svg)](https://github.com/Morpheus-compiler/Morpheus/actions/workflows/morpheus-pktgen-build.yml)

Morpheus is a system working alongside static compilers that continuously optimizes the targeted networking code. 
It introduces a number of new techniques, from static code analysis to adaptive code instrumentation, together with a toolbox of domain specific optimizations used to manipulate the code on-the-fly depending on runtime traffic patterns and control plane configurations.

<p align="center">
<img src="https://raw.githubusercontent.com/Morpheus-compiler/Morpheus/main/morpheus-logo.svg"  alt="Morpheus" width="80%">
</p>
<p align="center">
<sub>Morpheus compilation pipeline.</sub>
</p>

The Morpheus core exploits the **LLVM compiler** toolchain (v10.0.1) for code manipulation and run-time code generation. It works at the *intermediate representation* (IR) level as it allows to reason about the running code using a relatively high-level language framework without compromising on code generation time.

The Morpheus compilation pipeline is characterized of three main steps:
1. **Code Analysis**: In the first pass, Morpheus uses ***static code analysis*** to identify all map access sites in
the code, understand whether a particular access is a read or a write operation, and reason about the way the result is
used later in the code. In particular, signature-based call site analysis is used to track map lookup and update calls, and then a combination of ***memory dependency analysis*** and ***alias analysis*** is performed to match map lookups to map updates.
2. **Instrumentation**: In the second pass, Morpheus profiles the dynamics of the input traffic by generating ***heatmaps*** of the maps’ access patterns, so that the collected statistics can then be used to drive the subsequent optimization passes.
3. **Optimization Passes**: The third step of the compilation pipeline is where all online code transformations are applied (e.g., *JIT compilation*, *Dead code elimination*, *Constant Propagation*, *Guard Elision*). 

For more information, please read the Morpheus's [paper](https://sebymiano.github.io/publication/2022-morpheus/2022-morpheus.pdf) and the [extended abstract](https://sebymiano.github.io/publication/2022-morpheus/2022-morpheus_abstract.pdf) accepted to [ASPLOS '22](https://asplos-conference.org/2022/).
