# Get fourtytwo

A package with pyo3 bindings for testing pyo3-pack.

## Usage

```bash
pip install --index-url https://test.pypi.org/simple/ pyo3_pure
```

```python
import pyo3_pure
assert pyo3_pure.DummyClass.get_42() == 42
```

## Testing

Install tox:

```bash
pip install tox
```

Run it:

```bash
tox
```

The tests are in `test_get_gourtytwo.py`, while the configuration is in tox.ini