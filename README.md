# World Values Survey Analysis

Analysis and visualization of the different cultures of the world using the World Values Survey dataset.

## Project Organization
------------

    │
    ├── README.md           
    ├── CHANGELOG.md        <- See keepachangelog.com
    ├── pyproject.toml      <- See PEP 518
    ├── poetry.lock         <- See Poetry documentation
    ├── tests               <- Scripts for testing
    ├── notebooks           <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │   └── fix_notebook_imports.py
    ├── references          <- Data dictionaries, manuals, and all other explanatory materials.
    ├── reports             <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures         <- Generated graphics and figures to be used in reporting
    └── world_values_survey_analysis
        ├── util.py         <- Shared functions and helpful file paths
        ├── make_dataset.py <- Dataset download and generation
        ├── pipeline.py     <- Data processing pipeline to be used in train.py and predict.py
        ├── train.py        <- Train model
        ├── predict.py      <- Make predictions using a trained model
        ├── visualize.py    <- Create exploratory and results-oriented visualizations
        ├── data
        │   ├── external    <- Data from third party sources.
        │   ├── interim     <- Intermediate data that has been transformed.
        │   ├── processed   <- The final, canonical data sets for modeling.
        │   └── raw         <- The original, immutable data dump.
        └── models          <- Trained and serialized models and model predictions
     



--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
