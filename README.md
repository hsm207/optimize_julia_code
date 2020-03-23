# Introduction

This repository contains code to accompany my Medium blog post titled [A Beginner's Guide To Optimizing Julia Code](https://medium.com/towards-artificial-intelligence/a-beginners-guide-to-optimizing-julia-code-148e3f2d69bd).

# Usage

1. Clone this repo.
2. Open a Julia REPL and `cd` to the project's root directory.
3. Enter Pkg REPL mode and execute:
   ```julia
   activate .
   instantiate
   ```
4. Exit Pkg REPL mode and execute:
   ```julia
   using IJulia
   notebook(dir=pwd())
   ```
 This open Jupyter notebook in your default browser.
 
 Navigate to the [notebooks](./notebooks) folder to view the solutions presented in the blog post.
