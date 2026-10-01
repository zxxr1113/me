---
layout: page
permalink: /cv/
title: CV
nav: true
description: Research, projects, and awards.
---

## Education

**University of Chinese Academy of Sciences (UCAS)** — B.Eng. in Computer Science and Technology, 2023–2027. GPA: 3.88/4.0; top 15%.

## Research and internship experience

### University of California, Berkeley

**Research Intern, Logic Synthesis and Formal Verification** · Summer 2026 · Advisor: Alan Mishchenko

Berkeley ABC is an open-source tool for optimizing and formally verifying digital circuits.

- **`&scorr2` — incremental signal correspondence.** Developed a new Berkeley ABC command that reuses SAT proofs, speculative-reduced-model state, and simulation signatures across refinement rounds. Achieved an 18.07× average speedup on two large industrial cases and 4.57× across 30 large academic cases over `&scorr`.
- **`&stran` — constructive signal correspondence.** Developed a new Berkeley ABC command using counterexample-guided synthesis, bounded transitive fanout, and formal proof. Reduced circuit size by a further 7% within 5× the runtime of `&scorr`; don't-care analysis raised the reduction to 10% at roughly 20× its runtime. Manuscript in preparation for submission.
- **`rewrite2` — incremental logic rewriting.** Developed a new Berkeley ABC command using incremental updates and lazy level computation. Ran 4.2× faster than `rewrite` on HWMCC benchmarks with identical optimization results on every case. Manuscript in preparation for submission.

### Institute of Software, Chinese Academy of Sciences (ISCAS)

**Research Intern, AI Agents, Formal Methods, and EDA** · Jan. 2025–present · Advisor: Xindi Zhang

- **Graph-augmented issue-resolution agent.** Integrated a code knowledge graph into SWE-agent and improved SWE-bench resolution by 10 percentage points with DeepSeek-V4.
- **Formal reasoning verification agent.** Built a typed state-transition DSL and hybrid checks for agent reasoning. With task-specific templates for DeepSeek-V4-Flash, raised BabyBench success from 20% to 65% (Small benchmark), 9% to 51% (Medium benchmark), and 11% to 46% (Large benchmark); improved AIME accuracy from 50% to 75% on 12 problems.
- **SAT and EDA optimization.** Improved CDCL search heuristics. Following the EDA Elite Challenge, developed algorithms that ran 2–10× faster than the previous state of the art across evaluated cases, while an iterative clustering framework reached 99.9% of a linear optimization solver's solution quality.

## Publications

- Manuscript under review at DATE 2027. Details withheld during double-blind review.

## Selected systems projects

- **End-to-end RISC-V processor** · [GitHub](https://github.com/zxxr1113/RISC-V-CPU-with-7-stage-pipeline) · Sep. 2024–Jun. 2025. Designed a seven-stage pipelined processor with local cache, booted it on FPGA, and validated it with 17 RISC-V workload programs in the UCAS automated simulation and FPGA flow.
- **Unix-like operating system for RISC-V** · [GitHub](https://github.com/zxxr1113/Operating-System-Project) · Sep. 2025–Jan. 2026. Implemented process scheduling, virtual memory, synchronization, and persistent storage; exercised six development stages with 50+ test programs for scheduling, multicore synchronization, paging, networking, and file-system operations.

## Honors and awards

- **Xinde Academic Scholarship**, UCAS, 2024 and 2025.
- **Academic Excellence Scholarship**, UCAS, 2024.

## Technical skills

- **Languages:** Python, C/C++, Verilog, SystemVerilog, Java, Shell, LaTeX.
- **Systems and EDA:** Berkeley ABC, SAT/CDCL, RISC-V, Vivado, GDB, QEMU, Linux, Git.
- **Agent and ML tools:** OpenAI SDK, Pydantic, PyYAML, Gymnasium, pytest, PyTorch.
