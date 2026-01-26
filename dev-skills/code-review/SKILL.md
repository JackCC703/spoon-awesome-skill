---
name: code-review
description: Automated code review and quality analysis. Use for reviewing PRs, checking code style, detecting vulnerabilities, and suggesting improvements.
version: 0.1.0
author: Community
tags: [code-review, quality, security, linting, pr-review]
status: placeholder
---

# Code Review

> **Status**: 🟡 Placeholder - Contributions Welcome!

Automated code review capabilities for SpoonOS agents.

## Planned Features

- [ ] Style and convention checking
- [ ] Security vulnerability detection
- [ ] Performance anti-pattern detection
- [ ] Code complexity analysis
- [ ] PR review automation
- [ ] Suggestion generation

## Quick Start (Planned)

```python
from dev_skills.code_review.scripts.reviewer import CodeReviewTool

tool = CodeReviewTool()
result = await tool.execute(
    files=["src/main.py", "src/utils.py"],
    checks=["style", "security", "performance"]
)
```

## How to Contribute

See [CONTRIBUTING.md](../../CONTRIBUTING.md) for guidelines.

## Scripts Needed

| Script | Priority | Description |
|--------|----------|-------------|
| `reviewer.py` | High | Main review tool |
| `security_scanner.py` | High | Security checks |
| `style_checker.py` | Medium | Style analysis |
| `complexity_analyzer.py` | Medium | Complexity metrics |

## Environment Variables (Planned)

| Variable | Required | Description |
|----------|----------|-------------|
| `REVIEW_STRICTNESS` | No | low/medium/high |
| `IGNORE_PATTERNS` | No | Files to ignore |
