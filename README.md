# Littleton Bemis Public Library — The Studio Docs Project

[![Azure Static Web Apps CI/CD](https://github.com/chworthey/bemis-public-library-studio-docs/actions/workflows/azure-static-web-apps-gray-stone-085c4c510.yml/badge.svg)](https://github.com/chworthey/bemis-public-library-studio-docs/actions/workflows/azure-static-web-apps-gray-stone-085c4c510.yml)

The Studio is a makerspace located at Littleton Bemis Public Library.

![Picture of The Studio](docs/assets/images/studio.webp)

This repository contains documentation sources for The Studio @ Littleton Bemis Public Library.

**This is volunteer work done by Charlotte Worthey and does not represent Littleton Bemis Public Library or the docs in its final form.**

## Live Demo Website
[Demo Website](https://gray-stone-085c4c510.5.azurestaticapps.net/)

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

VSCode is an extensible text editor that can be opened in a directory and includes a terminal panel which is convenient. It also has a dedicated user interface for manipulating git without the command line.

## Fetch Sources

We need to start by grabbing the source code.
```sh
git clone https://github.com/chworthey/bemis-public-library-studio-docs.git studio-docs
cd studio-docs
```

Note: You may instead download the sources as a zip from GitHub if you prefer to not use git.

Optional: Open VSCode editor
```sh
code .
```

## Install Python Dependencies

For a first time run, you will need to run this command from a command line:
```sh
poetry install
```

Note: The working directory ie. `cd <SOME PATH>` should be the project directory, the same directory that contains this README.

## Reading Documents Locally

This command will start a local development server. The server will watch for file changes and refresh any browser tabs pointed to the server URL upon file changes.

Run:
```sh
poetry run mkdocs serve
```

After running the command, open up a browser to the printed localhost URL, ie. [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
