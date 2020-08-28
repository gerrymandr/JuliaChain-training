# JuliaChain-training

### Get Julia working on Jupyter 

To get Julia working on Jupyter, do the follwing:

1. On your command line, type `julia` to start the Julia REPL.
2. Type `using Pkg; Pkg.add("IJulia")`

Now when you open up a Jupyter Notebook, you should have the option to open up a Julia notebook.

Reference link with pretty pictures: https://datatofish.com/add-julia-to-jupyter/

### Get GerryChain working for this training

1. Clone the GerryChainJulia repo.
2. Clone this training repo.
3. Set up an environment:

```
using Pkg
Pkg.activate("JuliaChainTraining"; shared=true)
Pkg.add(Pkg.PackageSpec(; path="/path/to/local/package"))
```

The "/path/to/local/package" right above should point to the path of GerryChain repo you just cloned. You can find this path by going to that GerryChainJulia directory, and typing `pwd` on the commandline.


