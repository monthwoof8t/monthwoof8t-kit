# monthwoof8t-kit

Sort a folder of files into per-type subfolders.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m monthwoof8t_kit.cli --help
```

```python
from monthwoof8t_kit.core import Monthwoof8tTool

tool = Monthwoof8tTool()
print(tool)
```

## Layout

```
monthwoof8t_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 monthwoof8t
