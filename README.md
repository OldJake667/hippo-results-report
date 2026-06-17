# HiPPO Benchmark Report

This is the write-up for my HiPPO sequence-model experiments. I separated it from the main code repository because the report is easier to read on its own, especially for someone who wants the motivation, setup, and results without opening the whole training codebase.

The report summarizes experiments with MNIST, adding, and copying tasks, with a focus on comparing recurrent, convolutional, attention, and HiPPO/LegS-style approaches.

## What Is Included

- `RUN_REPORT.md` is the readable Markdown version.
- `RUN_REPORT.tex` is the LaTeX source.
- `RUN_REPORT.pdf` is the compiled report.
- `benchmark_outputs/` contains the selected copying-task benchmark summary.

## Background

I prepared this report while working through sequence models and state-space memory methods. The goal was not only to get final numbers, but also to understand what each model family is good at and where the tradeoffs appear in practice.
