# port-check

A small utility that checks TCP reachability with configurable timeouts.

## Why

Mostly written for my own projects, but it may be useful to someone else.

## Install

```bash
pip install port-check
```

## Usage

```python
from port_check import portCheck

result = portCheck("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
