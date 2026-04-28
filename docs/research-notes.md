# tmux for UITARS15_v2: Comparative Terminal Evaluation

## Purpose

This document records the research framing behind the static GitHub Pages site. The project studies how tmux can be adapted for UITARS15_v2 as a durable terminal substrate for agentic work.

## Research Question

Which controlled comparisons show whether tmux support improves UITARS15_v2 beyond simple terminal automation?

## Working Thesis

The evaluation compares pane-aware, pane-blind, and replay-assisted settings to isolate the value of terminal structure.

## Design Claims

- Tasks include pane navigation, concurrent logs, interrupted builds, and delayed output.
- Ablations remove segmentation, focus history, and replay memory.
- Analysis separates action selection, focus selection, and verification.

## Evaluation Lens

- Ablation sensitivity
- Concurrent-output resilience
- Verification accuracy after delayed feedback


## Threats to Validity

- Terminal state can be over-instrumented, causing an adapter to measure artifacts of the harness rather than real agent behavior.
- A final successful artifact may hide poor recovery behavior, repeated command attempts, or fragile focus management.
- Agent-specific adapters can become difficult to compare unless trace schemas remain explicit and documented.

## Hero Image Prompt Summary

A 700x500 academic technical illustration for tmux adaptation research with UITARS15_v2, emphasizing terminal panes, agent traces, reproducible evaluation, and a serious research discussion style. The generated image was copied into `docs/assets/hero.png` and normalized to 700x500 pixels.
