# Project Overview

This project utilizes Claude Code for enhanced development processes, integrating multiple automated harnesses and agents to streamline code review and documentation.

## Harnesses

- **ClaudeCode**: Configuration located in `.claude/`
- **Codex**: Configuration referenced in `AGENTS.md`

## Stack

- **Node.js**: Build and test commands are handled through npm. Linting is managed using `eslint` for maintaining code quality.

## Workflow

- **Git-based**: We use a trunk-based development model with mandatory pull request reviews to ensure code quality.
- **Free items**: 트렁크 기반, PR 필수 리뷰

## Active Agents

- **code-reviewer**
- **doc-writer**

## Policy

Our policy maintains a balanced approach, allowing moderate permissions for tools while keeping necessary restrictions in place.
