# Tangram for Python

- [Watch the Video](https://www.tangram.xyz)
- [Read the Docs](https://www.tangram.xyz/docs)

The Tangram Python library makes it easy to make predictions with your Tangram machine learning model from Python.

## Usage

```
$ pip install tangram
```

```python
import tangram

model = tangram.Model.from_path('./heart_disease.tangram')

input = {
  'age': 63,
  'gender': 'male',
  # ...
}

output = model.predict(input)
```

For more information, [read the docs](https://www.tangram.xyz/docs).

## Platform Support

Tangram for Python is currently supported on Linux, macOS, and Windows with ARM64 and AMD64 CPUs. Are you interested in another platform? [Open an issue](https://github.com/tangramxyz/tangram/issues/new) or send us an email at [help@tangram.xyz](mailto:help@tangram.xyz).

## Examples

The source for this package contains a number of examples in the `examples` directory. Each example has a `README.md` explaining how to run it.
