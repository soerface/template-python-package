# Template

This is a template repository for building Python packages. It allows you to quickstart
your Python package.

## Using it

- Click on [Use this template](https://github.com/soerface/template-flask-bootstrap/generate)
- Customize
- Create an account on [readthedocs](https://readthedocs.org/) and connect this repository

Set the following environment variables in your repository settings to enable publishing on PyPI:

- TWINE_USERNAME
- TWINE_PASSWORD

Below is a README.md template for your project.

---

# Hello GitHub Actions!

Documentation: [![Documentation Status](https://readthedocs.org/projects/hello-gh-actions/badge/?version=latest)](https://hello-gh-actions.readthedocs.io/en/latest/?badge=latest)
PyPI: https://pypi.org/project/hello_gh_actions

## Getting started

Installation via pip:

    pip install hello_gh_actions
    
Using the fizzbuzz:

    >>> from hello_gh_actions.fizzbuzz import fizzbuzz
    >>> fizzbuzz(35)
    'fizzbuzz'
