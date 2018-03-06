# Flying Car Udacity Nanodegree

## Environment Setup
1. Download and install [miniconda3](https://conda.io/miniconda.html).
2. Clone the repository and then navigate to `FCND-Term1-Starter-Kit` submodule:
```bash
git clone --recursive https://github.com/pyadmell/flying-car-udacity.git

cd ext/udacity/FCND-Term1-Starter-Kit
```
3. Create the miniconda environment:
```bash
conda env create -f environment.yml
```
4. Verify the fcnd environment:
```bahs
conda info --envs
```
5. Clean up downloaded packages:
```bash
conda clean -tp
```
6. Activate `fcnd` conda environment:
```bash
source activate fcnd
```

