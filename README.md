# evaluations

Reproducible, Swedish-first evaluations of AI models for public-sector education workflows.

This repo contains:
- **runs/**: raw run logs (inputs, outputs, pass/fail decisions)
- **templates/**: charter, weekly operating system, and run-log templates

## What “PASS/FAIL” means
This project uses strict, testable rules (groundedness, verbatim evidence quotes, deterministic “missing info” handling, and no extra text outside a required structure).  
A model can be strong and still fail—these tests target operational reliability.

## Current baseline
- **v0.1 — grounded Q&A (cloud baseline)**
  - Models: GPT-5.2 Thinking, Claude Opus 4.5, Gemini 3 Thinking
  - Run log: `runs/run_2026-01-05_v0.1_gqa_cloud.md`

## How to use
1. Open the latest run log in `runs/`
2. Read the task prompts and the three model outputs
3. See the scoring decision and the failure gallery

## License
MIT


