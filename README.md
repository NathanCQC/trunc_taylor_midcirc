# trunctaylor-midcirc: Truncated Taylor Series using Mid-Circuit Measurements in guppy

This repository accompanies our research paper on implementing truncated Taylor series using mid-circuit measurements,featuring its application in the [guppy](https://github.com/CQCL/guppylang) framework. The paper discusses a novel computational technique ......
## Repository Overview

The codebase provided within this repository serves as the practical implementation that complements the theoretical exposition of the paper. It supports reproducibility ...

## Installation

To replicate our experimental results, follow these steps to set up your project environment:

1. Open your terminal and navigate to the project directory.
2. Execute the following commands to create and synchronize the virtual environment:

```bash
uv venv .venv
uv sync
```

These commands will install the necessary dependencies, including the trunctaylor package, ensuring that all computational experiments run seamlessly.

## Examples

For a detailed demonstration of the projector in action—specifically within the Hubbard model framework—please refer to the accompanying Jupyter notebook:

[something.ipynb](https://github.com/NathanCQC/wall_chebyshev/blob/main/examples/something.ipynb)



## Citation

If you find this work helpful in your research, please consider citing our paper:

    @article{trunctaylor2023,
      title={Truncated Taylor Series using Mid-Circuit Measurements in guppy},
      author={Your Name and Collaborators},
      journal={Journal of Computational Methods},
      year={2023},
    }

