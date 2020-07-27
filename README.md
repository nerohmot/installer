# conda-forge-installer

The best way to setup `conda` for `conda-forge` is via [miniforge](https://github.com/conda-forge/miniforge), however, the installers you find there are made for 'purists' iow, this is the `conda-forge` equivalent for `miniconda`, and what about the `conda-forge` equivalent for `anaconda`? And what if we want a lean, yet comfortable `base` envirionment? (read: with for example [mamba](https://github.com/TheSnakePit/mamba) in the base environment) And what if we want to install `conda` for [all users on a system](https://docs.anaconda.com/anaconda/install/multi-user/)?

[conda-forge-installer]() is a 'top level' installer script for both `Linux` and `macOS` that makes installing `conda` for/from `conda-forge` easy and straightforward for all use-cases.

It will :
  1. Figure out what OS you are running
  2. Figure out what CPU you have 
  3. Look what 'size' you want to install
  4. Look 
  
# sizes

There are basically 3 sizes you can chose from:
  - minimal ➜ this is the miniconda installation.
  - nominal ➜ this is the `minimal` installation, but with some good to have goodies in the `base`
  - maximal ➜ this is the `nominal` installation, extended with the `conda-forge` variant of `anaconda`
  
  
