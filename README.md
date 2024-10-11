# Littleton Bemis Public Library — The Studio Docs Project

This repository contains the sources for the Littleton Bemis Public Library documentation.

## Project Architecture

The main underlying technology used for the documentation is [Markdown](https://www.markdownguide.org/basic-syntax/), [MkDocs](https://www.mkdocs.org/), and [Python](https://www.python.org/).

[Material for MKDocs](https://squidfunk.github.io/mkdocs-material/) is used for the general layout and look of the documentation.

The dependency management system used is [Poetry](https://python-poetry.org/).

[Git](https://git-scm.com/) is used for source control.

[GitHub](https://github.com/) is used for repository hosting.

## Installation Requirements

You only need to install things on a local computer if you want to develop a theme or you want to see the final output as you write. If you want, you may instead edit the markdown files right here on GitHub if you have the proper project permissions.

1. Git
    - **Windows:** [Git for Windows](https://gitforwindows.org/)
    - **Mac:** Check if already installed. If not, install: [Homebrew](https://brew.sh/); then use command: `brew install git`
    - **Linux:** Check if already installed. If not, you may use Homebrew method or your distro's package installation method ie. `sudo apt-get update` followed by `sudo apt-get install git-all`.
2. [Python 3.10.x and up](https://www.python.org/downloads/)
3. [Poetry](https://python-poetry.org/docs/#installation)

I also recommend [VSCode](https://code.visualstudio.com/download) for editing the files generally speaking, but I will not include the instructions for that here.

VSCode is an extensible text editor that can be opened in a directory and includes a terminal panel which is convenient. It also has a user interface for manipulating git if you don't want to use the command line which can be convenient.

## Install Python Dependencies

For a first time run, you will need to run:
```sh
poetry install
```

## Reading Documents Locally

Run:
```sh
poetry run mkdocs serve
```

Then, open up a browser to the printed URL, ie. [http://127.0.0.1:8000/](http://127.0.0.1:8000/)