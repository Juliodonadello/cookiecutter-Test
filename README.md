# {{ cookiecutter.project_title }}

By: {{ cookiecutter.project_author_name }}

{{ cookiecutter.project_description }}

##  License reserved to Analítica Avanzada & Machine Learning ®

**Esta es una platilla para la creación de repositorios únicos para cada modelo de VertexAI**

Para clonar este repositorio usando y hacer uso de los archivos de creación del entorno (**environment.yml**), de configuracion del repo(**cookiecutter.json**) y acciones personalizadas (**hooks**):

> cookiecutter "url_del_repo" 

  
## Installation guide

Please read [install.md](install.md) for details on how to set up this project.

## Project Organization

*los directorios con # no estan creados*

    ├── tasks.py#          <- Invoke with commands like `notebook`.
    ├── README.md          <- The top-level README for developers using this project.
    ├── install.md#        <- Detailed instructions to set up this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── processed        <- Intermediate data that has been transformed.
    │   ├── final      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references#        <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports#            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures         <- Generated graphics and figures to be used in reporting.
    │
    ├── environment.yml    <- The requirements file for reproducing the analysis environment.
    │
    ├── .here#              <- File that will stop the search if none of the other criteria
    │                         apply when searching head of project.
    │
    ├── setup.py#           <- Makes project pip installable (pip install -e .)
    │                         so final_project can be imported.
    │
    └── final_project               <- Source code for use in this project.
        ├── __init__.py    <- Makes final_project a Python module.
        │
        ├── data           <- Scripts to download or generate data.
        │   └── make_dataset.py
        │
        ├── features       <- Scripts to turn raw data into features for modeling.
        │   └── build_features.py
        │
        ├── models         <- Scripts to train models and then use trained models to make
        │   │                 predictions.
        │   ├── predict_model.py
        │   └── train_model.py
        │
        ├── utils#         <- Scripts to help with common tasks.
        │    └── paths.py   <- Helper functions to relative file referencing across project.
        │
        └── visualization  <- Scripts to create exploratory and results oriented visualizations.
            └── visualize.py

---
Project based on the [cookiecutter conda data science project template](https://github.com/jvelezmagic/cookiecutter-conda-data-science).