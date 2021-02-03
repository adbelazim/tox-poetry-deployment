# tox-poetry-deployment
Combination of poetry with tox to manage multiple environments

This project generates 3 virtual environments depending on the operative system. 3 commands are executed for each virtual environment:

* poetry install -v
* python regression_model/train_pipeline.py
* poetry run pytest

In order to generate execute the project it's necessary to have tox and poetry installed. Then just execute the follow commands

* cd regression_model
* tox

