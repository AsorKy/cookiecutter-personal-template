# {{ cookiecutter.project_title }}

By: {{cookiecutter.project_author_name}}

{{ cookiecutter.project_description }}

## License

Version: 0.1.0

This is a project template for the usage of cookiecutter for data science template creation.

## Prerequisites

- [Anaconda](https://www.anaconda.com/download/) >=4.x
- Optional [Mamba](https://mamba.readthedocs.io/en/latest/)

## Create environment

```bash
conda env create -f environment.yml
activate cookiecutter_testing
```

or 

```bash
mamba env create -f environment.yml
activate cookiecutter_testing
```

## Project organization

    cookiecutter_testing
        ├── data
        │   ├── processed      <- The final, canonical data sets for modeling.
        │   └── raw            <- The original, immutable data dump.
        │
        ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
        │                         the creator's initials, and a short `-` delimited description, e.g.
        │                         `notebook-test-template.ipynb`.
        ├── envs               <- Virtual environment location.
        ├── models             <- Trained model location.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        └── README.md          <- The top-level README for developers using this project.


