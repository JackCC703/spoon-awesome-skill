---
name: refactoring
description: Code refactoring patterns and automation. Use for extracting functions, renaming, removing dead code, and pattern migration.
version: 0.1.0
author: Community
tags: [refactoring, clean-code, patterns, migration, optimization]
status: placeholder
---

# Code Refactoring

> **Status**: 🟡 Placeholder - Contributions Welcome!

Code refactoring automation for SpoonOS agents.

## Planned Features

- [ ] Extract function/class
- [ ] Rename across codebase
- [ ] Dead code removal
- [ ] Import optimization
- [ ] Pattern migration
- [ ] Code deduplication

## Quick Start (Planned)

```python
from dev_skills.refactoring.scripts.refactor_tool import RefactorTool

tool = RefactorTool()
result = await tool.execute(
    action="extract_function",
    file="src/main.py",
    lines=(10, 25),
    function_name="process_data"
)
```

## How to Contribute

See [CONTRIBUTING.md](../../CONTRIBUTING.md) for guidelines.

## Scripts Needed

| Script | Priority | Description |
|--------|----------|-------------|
| `refactor_tool.py` | High | Main refactoring tool |
| `rename_tool.py` | High | Rename across files |
| `dead_code_finder.py` | Medium | Find unused code |
| `import_optimizer.py` | Low | Organize imports |

## Environment Variables (Planned)

| Variable | Required | Description |
|----------|----------|-------------|
| `BACKUP_BEFORE_REFACTOR` | No | Create backups (default: true) |
| `DRY_RUN` | No | Preview changes only |
