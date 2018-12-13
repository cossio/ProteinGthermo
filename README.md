# Biophysical inference of epistasis and the effects of mutations on protein stability and function

This repository contains a jupyter notebook with julia code with all of the analysis presented in "Biophysical inference of epistasis and the effects of mutations on protein stability and function"

## Additional setup

We need `RCall.jl` to be able to run some of the Jupyter notebooks.
Here is how to set it up.

* Set `ENV["R_HOME"] = "*"`, then `add RCall` (RCall will install its own version of R). 
* add `Conda`. Then `using Conda; Conda.add("gxx_linux-64")`, to be able to build R dependencies.
* Add `$JULIA_DEPOT_PATH/conda/3/bin` to the environment `PATH` variable.
* `using RCall; R"""install.packages(c("tidyverse", "cowplot", "stringr", "forcats", "ggplot2"), repos="https://cloud.r-project.org")"""`
