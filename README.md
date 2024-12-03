
## Installation

The instructions below were tested on Ubuntu 22.04. It is assumed that you have miniconda installed.

### Manual steps
1. `conda create -n sgn python=3.8`
2. `conda activate sgn`
3. `pip install -r requirements.txt`
4. `pip install "git+https://github.com/google/uncertainty-baselines.git@0895e0e#egg=uncertainty_baselines" --no-deps`
5. `conda install cudatoolkit cudnn`

### (Experimental) Conda environment file
1. `conda env create -f environment.yml`
2. `conda activate sgn`

See [original README](SGN-main/README.md) for project-specific details and scripts.