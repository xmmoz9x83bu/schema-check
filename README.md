# schema-check

A small validator for a useful subset of JSON Schema.

## Why

I wanted something I could read in one sitting and vendor into a project if needed.

## Install

```bash
pip install schema-check
```

## Usage

```python
from schema_check import schemaCheck

result = schemaCheck("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
