# pycounts_my_at

This package will be used to calculate word counts from a text file.

## Installation

```bash
$ pip install pycounts_my_at
```

## Usage

`pycounts` can be used to count words in a text file and plot results
as follows:

```python
from pycounts_my_at.pycounts_my_at import count_words
from pycounts_my_at.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_my_at` was created by Abeba N. Turi. It is licensed under the terms of the MIT license.

## Credits

`pycounts_my_at` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
