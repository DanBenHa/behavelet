behavelet: a normalized Morlet wavelet transform for behavioral mapping
============

behavelet is a Python implementation of the normalized Morlet wavelet transform for behavioral mapping from [Berman et al. (2014)](https://doi.org/10.1098/rsif.2014.0672). It runs on the CPU using numpy and multiprocessing or on the GPU using [CuPy](https://github.com/cupy/cupy). 

Citation
---------

If you use behavelet for you research, please cite our DOI:

[placeholder]

for the original description of the normalized Morlet wavelet transform see the paper from [Berman et al. (2014)](https://doi.org/10.1098/rsif.2014.0672):

    @article{berman2014mapping,
             title={Mapping the stereotyped behaviour of freely moving fruit flies},
             author={Berman, Gordon J and Choi, Daniel M and Bialek, William and Shaevitz, Joshua W},
             journal={Journal of The Royal Society Interface},
             volume={11},
             number={99},
             pages={20140672},
             year={2014},
             publisher={The Royal Society}
             }

Installation
------------

If you wish to use the GPU version, you may need to [install CuPy manually](https://github.com/cupy/cupy#installation).

Install the development version with pip:
```bash
pip install git+https://www.github.com/jgraving/behavelet.git
```

You can also install from within Python rather than using the command line, either from within Jupyter or another IDE, to ensure it is installed in the correct working environment:
```python
import sys
!{sys.executable} -m pip install git+https://www.github.com/jgraving/behavelet.git
```

Development
-------------
Please submit bugs or feature requests to the [GitHub issue tracker](https://github.com/jgraving/behavelet/issues/new). Please limit reported issues to the behavelet codebase and provide as much detail as you can with a minimal working example if possible. 

If you experience problems with [CuPy](https://github.com/cupy/cupy), such as installing CUDA or other dependencies, then please direct issues to their development team.

Contributors
------------
behavelet was developed by [Jake Graving](https://github.com/jgraving), and is still being actively developed. Public contributions are welcome. If you wish to contribute, please [fork the repository](https://help.github.com/en/articles/fork-a-repo) to make your modifications and [submit a pull request](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork).

License
------------
Released under a Apache 2.0 License. See [LICENSE](https://github.com/jgraving/behavelet/blob/master/LICENSE) for details.
