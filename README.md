# Harry Potter AI collection

## Manual Setup

Create an empty environment specifying the Python version

```
conda create --name hp python=3.12
```

Activate the environment

```
conda activate hp
```

Add a new channel

```
conda config --env --add channels conda-forge
```

Install the dependencies

```
conda install anaconda::notebook conda-forge::jupyterlab
```
