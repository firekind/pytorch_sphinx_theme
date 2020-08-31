# Pytorch Sphinx Theme

forked from [pytorch sphinx theme](https://github.com/pytorch/pytorch_sphinx_theme). I really liked the theme so I made some changes to make it more generic for personal use.

## Installation

Clone this repo and run
```
$ python setup.py install
```

To install it. To use the theme, add the following to the `conf.py` file
```python
extensions = [
    ...
    "pytorch_sphinx_theme",
]

html_theme = "pytorch_sphinx_theme"
```

## Credits

All credits go to original authors.