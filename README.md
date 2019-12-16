# Template

This is a template repository for building Python packages. It allows you to quickstart
your Python package.

## Using it

- Click on [Use this template](https://github.com/soerface/template-flask-bootstrap/generate)
- Customize
- Create an account on [readthedocs](https://readthedocs.org/) and connect this repository
- Create an account on [PyPI](https://pypi.org) and an API-Key for your project

Go to your repository Settings -> Secrets and add the `PYPI_API_KEY` secret with the key you received from PyPI.

Below is a README.md template for your project.

---

# Hello GitHub Actions!

TODO: CHANGE BADGE URLS AFTER FORKING

[![Documentation Status](https://readthedocs.org/projects/hello-gh-actions/badge/?version=latest)](https://hello-gh-actions.readthedocs.io/en/latest/?badge=latest)
[![Tests Status](https://github.com/soerface/template-python-package/workflows/CI/badge.svg)](https://github.com/soerface/template-python-package/actions?query=workflow%3ACI)

- Documentation: https://hello-gh-actions.readthedocs.io/en/latest/
- PyPI: https://pypi.org/project/hello_gh_actions

## Getting started

Installation via pip:

    pip install hello_gh_actions
    
Using the fizzbuzz:

    >>> from hello_gh_actions.fizzbuzz import fizzbuzz
    >>> fizzbuzz(35)
    'fizzbuzz'
