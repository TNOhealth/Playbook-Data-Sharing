# The Playbook for Health Data Sharing Ecosystems

<img src="https://user-images.githubusercontent.com/9567830/199050409-8e9dc3a5-de2d-416a-9d33-dc7be25a72f0.png" align="right" width="128px"/>
A complete knowledge base for health data sharing ecosystems using FAIR data and services, made possible by TNO for the National eHealth Living Lab (NeLL).

<br clear="right"/>

[![playbookbutton](https://user-images.githubusercontent.com/9567830/199052304-ecfedcae-e88e-4c37-838e-fcd9c1b03c87.png)](https://tnohealth.github.io/Playbook-Data-Sharing/)

This web application is automatically built from this repository using a [Github workflow](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions).

## Development Instructions

### Building the book

If you'd like to develop and/or build the the playbook, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the books source files located in the `Playbook/` directory (markdown, jupyter notebooks and tex supported)
4. Run `jupyter-book build Playbook/` to compile

A fully-rendered HTML version of the book will be built in `Playbook/_build/html/`.

### Hosting the book

Please see the [Jupyter Book documentation](https://jupyterbook.org/publish/web.html) to discover options for deploying a book online using services such as GitHub, GitLab, or Netlify. This project already includes a Github workflow that automatically compiles the book to the `gh-pages` branch of this repository.

For GitHub and GitLab deployment specifically, the [cookiecutter-jupyter-book](https://github.com/executablebooks/cookiecutter-jupyter-book) includes templates for, and information about, optional continuous integration (CI) workflow files to help easily and automatically deploy books online with GitHub or GitLab. For example, if you chose `github` for the `include_ci` cookiecutter option, your book template was created with a GitHub actions workflow file that, once pushed to GitHub, automatically renders and pushes your book to the `gh-pages` branch of your repo and hosts it on GitHub Pages when a push or pull request is made to the main branch.


## Acknowledgement

This project is created using the excellent open source [Jupyter Book Project](https://jupyterbook.org/) and the [Jupyter Book Template](https://github.com/executablebooks/cookiecutter-jupyter-book).

## Core Contributors

The core contributors of this project include:
- [Andre Boorsma](https://github.com/aboorsma)
- [Robin van Stokkum](https://github.com/stokkumrmv)
- [Elena Lazovik](https://github.com/elenalazovik)
- [Ruduan Plug](https://github.com/dualslash)

### Would you like to contribute? 

An accessible option is to [open an issue](https://github.com/TNOhealth/Playbook-Data-Sharing/issues) with any question, suggestion or addition that you may have. More advanced users can [create a branch](https://github.com/TNOhealth/Playbook-Data-Sharing/branches) and then make a [pull request](https://github.com/TNOhealth/Playbook-Data-Sharing/pulls) to merge their contribution with the knowledge base.
