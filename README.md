# Julia-Programming-Language
Learning Julia Programming Language


### Important Commands 

1. To start a Julia terminal simply type 'julia'
2. To enter into a package mode use ']'
3. To check where conda has installed jupyter notebook type below command in the julia terminal
```julia
import Conda; Conda.SCRIPTDIR
```
output
```bash
/Users/nkkaushal/.julia/conda/3/bin/jupyter-notebook
```
4. To start jupyter notebook use
```julia
using IJulia
notebook(detached=true, dir="/some/path)
```
5. To start jupyter lab use
```julia
using IJulia
jupyterlab(detached=true, dir="/some/path)
```
6. To stop jupter notebook use
```bash
path/to/your/jupyter-notebook stop port-number
```
7. To start jupyter notebbok from different port use
```bash
path/to/your/jupyter-notebook --port=8080
```