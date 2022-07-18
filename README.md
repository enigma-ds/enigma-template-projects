# Cookiecutter for Data Science Projects

`This is a template for data science projects created by Enigma group.`

## Requirements

* [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/download.html)
* [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html): This can be installed with pip by or conda depending on how you manage your Python packages:

```
pip install cookiecutter
```
or

```
conda install -c conda-forge cookiecutter
```

## Create a new project

```
cookiecutter https://github.com/enigma-ds/enigma-template-projects
```

## Resulting directory structure

```
├── 00-first-exploration                 <- Where first exploration of data will be located.
│....
└──  environment.yml    <- The requirements file for reproducing the analysis environment.
```
