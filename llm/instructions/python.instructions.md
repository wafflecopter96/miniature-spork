---
applyTo: "**/*.py"
description: "Python coding conventions and style"
---

# Python Instructions

- Follow PEP 8 and PEP 484 (type hints on all public functions)
- Use `pathlib` over `os.path` for path manipulation
- Prefer f-strings over `%` or `.format()`
- Use `dataclasses` for simple data containers
- Use `enum.StrEnum` for string enums
- Use `zoneinfo` not `pytz` for timezone handling (Python 3.9+)
- Use `|` union syntax over `Optional` / `Union` (Python 3.10+)
- Use `except ...` with specific exception types, never bare `except:`
- Write `async def` for I/O-bound functions; use `asyncio` or `anyio`
- Test files go in `tests/` mirroring the source tree, suffixed `_test.py`
