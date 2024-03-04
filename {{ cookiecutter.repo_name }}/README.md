{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── commons        <- Scripts used in multiples modules in the same project
    │   │
    │   ├── connectors     <- Scripts to connect to databases, APIs, Clouds
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── features.py
    │   │   └── fetch.py
    │   │   └── preprocessing.py
    │   │
    │   ├── utils          <- Scripts to use in diferents projects 
    │   │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


