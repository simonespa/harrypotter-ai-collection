# Harry Potter AI collection

## Automatic Setup

Install the `hp` environment and all its dependencies from the `environment.yaml` config file

```
conda env create -f environment.yaml
```

Activate the `hp` environment

```
conda activate hp
```

## Manual Setup

Create an empty environment specifying the name and the Python version

```
conda create --name hp python=3.12 -y
```

Activate the `hp` environment

```
conda activate hp
```

Install the dependencies

```
conda install notebook jupyterlab matplotlib seaborn plotly pandas -y
```

## Cleanup

Deactivate the environment

```
conda deactivate
```

Remove the `hp` environment and all its dependencies (if needed)

```
conda remove --name hp --all -y
```

## Sources
- Screenplay: https://bulletproofscreenwriting.tv/happy-potter-screenplay-download/
