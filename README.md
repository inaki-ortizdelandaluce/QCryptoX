# QCryptoX

## Julia set-up
1. Install Julia from https://julialang.org/downloads/
2. Install IJulia
```
using Pkg
Pkg.add("IJulia")
Pkg.add("Conda")
using Conda
Conda.pip_interop(true)
Conda.pip("install", "webio_jupyter_extension")
```
3. Install other packages
```
Pkg.add("PyPlot")
Pkg.add("Interact")
Pkg.add("Convex")
Pkg.add("SCS")
```
4. Open IJulia notebook
```
using IJulia
notebook(detach=true)
```
