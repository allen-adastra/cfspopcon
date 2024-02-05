cfspopcon: 0D Plasma Calculations & Plasma OPerating CONtours
--------------------------------------------------------------

[![Build Status](https://github.com/cfs-energy/cfspopcon/actions/workflows/workflow_actions.yml/badge.svg)](https://github.com/cfs-energy/cfspopcon/actions)
[![Checked with mypy](http://www.mypy-lang.org/static/mypy_badge.svg)](http://mypy-lang.org/)
[![Documentation Status](https://readthedocs.org/projects/cfspopcon/badge/?version=latest)](https://cfspopcon.readthedocs.io/en/latest/?badge=latest)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cfs-energy/cfspopcon/HEAD)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10054880.svg)](https://doi.org/10.5281/zenodo.10054880)

For more information please have a look at our [documentation](https://cfspopcon.readthedocs.io/en/latest/).

# How2Use 2263 GUI Locally as Developer
1) Use Linux
2) [Install poetry](https://python-poetry.org/)
3) Follow stupid RADS instructions given by CFSPOPCON (https://cfspopcon.readthedocs.io/en/latest/doc_sources/Usage.html)
4) Activate the poetry shell (see poetry docs) run a `poetry install` in the root of the repo
5) From the root of the repo do a `cd docs/doc_sources/`
6) To start the gui, from the root run `panel serve panel_gui.ipynb --autoreload`
7) Copy the url it spits out into your browser (probs gonna be `http://localhost:5006/panel_gui`)
