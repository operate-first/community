# Contributing to GitOps Docs

## Pre-requisites

- Fork and clone the [operate-first/community][community] repo
- Install [JupyterBook cli][jbook-install]

## Adding markdown docs

All `markdown` files are found within this repository. Add your markdown as needed.

Update `_toc.yml` by adding the location of your new markdown document to the appropriate chapter/section.
Read more about how to structure a `_toc.yml` [here][tocstructure]

Follow [Build the Docs section][builddocs] below to ensure your markdown appears in the rendered JupyterBook.

Once confirmed, commit your changes, and submit a PR to the  [`community` repo][community].

## Build the docs

In the repository you can create a virtual environment with [pipenv](https://pipenv.pypa.io/en/latest/)
```
pipenv install --dev
```
After that you can enter the virtual environment
```
pipenv shell
```
Now build the Jupyter book
```
cd docs
jupyter-book build .
```
The compiled book can be found in the `_build` folder.

[builddocs]: #Build-the-docs
[community]: https://github.com/operate-first/community
[jbook-install]: https://jupyterbook.org/start/overview.html#install-jupyter-book
[tocstructure]: https://jupyterbook.org/customize/toc.html
