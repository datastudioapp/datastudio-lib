# DataStudio Python library

This library contains low-level functions used by [datastudio-cli](https://github.com/datastudioapp/datastudio-cli) to interact with datakits.

## Development

### Deploying to PyPI

```bash
python -m build  # Generate distribution archives
python -m twine upload --repository pypi dist/*  # Upload distribution archives
```
