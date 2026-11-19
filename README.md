# dustpancrusted1a-kit

Sort a folder of files into per-type subfolders.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m dustpancrusted1a_kit.cli --help
```

```python
from dustpancrusted1a_kit.core import Dustpancrusted1aTool

tool = Dustpancrusted1aTool()
print(tool)
```

## Layout

```
dustpancrusted1a_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 dustpancrusted1a
