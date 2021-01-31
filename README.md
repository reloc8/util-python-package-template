# Python Package Template

A template for Python packages with Continuous Integration capabilities.

When a pull request is merged into master a new version is released based on the name of the merged branch. 
For example, feature branches trigger new minor releases while bugfix branches trigger new patch releases ([more info here](https://github.com/reloc8/action-choose-release-version)).

## Development

1. Create a virtual environment:

    `$ python3 -m venv .venv`

2. Activate the created environment:

    `$ source .venv/bin/activate`

3. Upgrade `pip`:

    `$ python3 -m pip install --upgrade pip`

4. Install the requirements:

    `$ pip install --upgrade -r requirements.txt`
