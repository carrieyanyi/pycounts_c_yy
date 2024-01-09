# pycounts_c_yy

Calculate word counts in text files.

## Installation

``` bash
$ pip install pycounts_c_yy
```

## Usage

`pycounts` can be used to count words in a text file and plot results as follows:

``` python
from pycounts_c_yy.pycounts_c_yy import count_words 
from pycounts_c_yy.plotting_c_yy import plot_words 
import matplotlib.pyplot as plt

file_path = "test.txt"  
counts = count_words(file_path) 
fig = plot_words(counts, n=10) 
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_c_yy` was created by Carrie Yan. It is licensed under the terms of the BSD 3-Clause and MIT license.

## Credits

`pycounts_c_yy` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
