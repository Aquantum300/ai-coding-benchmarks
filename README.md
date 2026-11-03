# AI Coding Benchmark Suite

A repository for testing and evaluating LLM-driven code repair. This suite focuses on building deterministic verifiers to ensure AI-generated code is both accurate and robust.

## Overview
This repository provides:
- Intentional buggy code snippets.
- Unit test suites that act as deterministic verifiers.
- Golden reference solutions for evaluation.

## How to use
1. Run the verifier against a candidate's solution:
   python3 verifier.py --candidate path/to/solution.py

## Challenges
Each folder under /challenges represents a unique technical hurdle (bug fixing, refactoring, or feature implementation).

## Contribution
Designed for AI training data generation and automated coding challenge validation.
