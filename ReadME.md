# Day 27 - Hands On: Git Branching Strategies

## Overview
This repository demonstrates Git branching strategies and collaborative workflows.

## Project Structure
- `main` — stable production-ready code
- `feature/*` — feature development branches
- `release/*` — release preparation branches

## Getting Started
Clone the repository and follow the branching workflow described below.

## Branching Strategy
This project follows trunk-based development principles:
1. Short-lived feature branches are created from `main`
2. Changes are reviewed via pull requests before merging
3. Releases are tagged from dedicated release branches
