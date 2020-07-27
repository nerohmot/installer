# conda-forge-installer

The way to setup `miniconda` for `conda-forge` is via [miniforge](https://github.com/conda-forge/miniforge), but as the name suggest, it is a minimalistic base installation that can be intimidating for some people.

Some use-cases that are not- or not easily foreseen in `miniconda` are:
  - I need the `conda-forge` equivalent of `anaconda`!
  - I need to install `conda` for [all users on a system](https://docs.anaconda.com/anaconda/install/multi-user/) and want to do it the right way with a single command. 
  - I want a **lean** `base` installation instead of the **anorexic** `base` install from miniconda.
  - I want any of the above but with a `PyPy` instead of a `CPython` implementation.
  - I need to install `conda` for/from `conda-forge`, but CPU ... no clue
  
With conda-forge-installer, you can do all of the above in a single command.



