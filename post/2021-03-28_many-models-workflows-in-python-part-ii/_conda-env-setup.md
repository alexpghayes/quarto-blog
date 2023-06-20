# Setting up the sklearn0.24 conda env

1. Install conda

2. Name to this folder as the working directory

3. Create the conda env

```sh
conda create --name sklearn0.24 --file requirements.txt
```

4. Construct a Jupyter kernel from the conda env

```sh
python -m ipykernel install --user --name sklearn0.24
```

5. Confirm existence of Jupyter kernel with

```sh
jupyter kernelspec list
```