# LeetCode AI Solver

AI-assisted LeetCode practice lab. Submit a problem, get a full solution workflow — or bring your own solution and refine it.

## About

LeetCode AI Solver turns each problem into a complete, submit-ready package: solution code, explanation, and an animated HTML dry-run visualization showing how the algorithm works step by step.

## Two Modes

### 1. Submit Your Own — Refine Mode
Submit your own solution. The AI reviews it, fixes edge cases, optimizes complexity, and keeps your approach.

### 2. Same Problem — Generate Mode
Submit the same problem to the app to create a fresh solution from scratch, ready for LeetCode.

## Pre-Submit Step: Animated Dry-Run

Before submitting, the solution MD file is augmented with an HTML animation — a step-by-step visual dry-run showing the algorithm's execution on the problem's example inputs.

## Quick Start

1. Drop a problem (statement + examples) into `problems/` or run the app prompt
2. Choose mode: **Refine** (your code) or **Generate** (fresh solution)
3. Review the solution + animated dry-run HTML
4. Copy the solution to LeetCode

## Layout

```
leetcode-ai-solver/
├── problems/        # problem statements + examples
├── solutions/       # refined / generated solutions (.md + .html dry-run)
└── README.md
```

## Skills

Works with the [`gh` agent skill](https://github.com/cli/cli) — `gh skill install cli/cli gh --scope user` — for driving GitHub CLI from coding agents (structured `--json` output, pagination, `gh api` fallback).

## License

MIT
