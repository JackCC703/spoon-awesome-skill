---
name: documentation
description: Generate and maintain documentation. Use for README generation, API docs, changelogs, and code comments.
version: 0.1.0
author: Community
tags: [documentation, readme, api-docs, changelog, comments]
status: placeholder
---

# Documentation Generation

> **Status**: 🟡 Placeholder - Contributions Welcome!

Documentation generation and maintenance for SpoonOS agents.

## Planned Features

- [ ] README generation
- [ ] API documentation
- [ ] Changelog generation
- [ ] Code comment generation
- [ ] Architecture diagrams
- [ ] Usage examples

## Quick Start (Planned)

```python
from dev_skills.documentation.scripts.doc_generator import DocGeneratorTool

tool = DocGeneratorTool()
result = await tool.execute(
    source_dir="src/",
    output="docs/",
    format="markdown"
)
```

## How to Contribute

See [CONTRIBUTING.md](../../CONTRIBUTING.md) for guidelines.

## Scripts Needed

| Script | Priority | Description |
|--------|----------|-------------|
| `doc_generator.py` | High | Main doc generator |
| `readme_builder.py` | High | README creation |
| `changelog_generator.py` | Medium | Changelog from commits |
| `api_documenter.py` | Medium | API reference docs |

## Environment Variables (Planned)

| Variable | Required | Description |
|----------|----------|-------------|
| `DOC_FORMAT` | No | markdown/rst/html |
| `DOC_TEMPLATE` | No | Custom template path |
