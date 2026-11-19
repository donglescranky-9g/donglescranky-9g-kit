# donglescranky-9g-kit

Summarize numeric CSV columns (n / min / max / mean).

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m donglescranky_9g_kit.cli --help
```

```python
from donglescranky_9g_kit.core import Donglescranky9gTool

tool = Donglescranky9gTool()
print(tool)
```

## Layout

```
donglescranky_9g_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 donglescranky-9g
