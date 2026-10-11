# py-config

Declarative configuration objects with validation and defaults.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

## Install

```bash
pip install py-config
```

## Usage

```python
from py_config import pyConfig

result = pyConfig("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
