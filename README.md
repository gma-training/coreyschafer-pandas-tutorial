# README

This repository contains the files I created while following Corey Schaffer's [video series on pandas].

## Getting started

To install the libraries you'll need to install the packages listed in `requirements.in`. If you're working in a venv, you can install them all with `pip-tools`, like this:

    python -m venv venv
    source venv/bin/activate
    pip install pip-tools
    pip-sync

You should then be able to run JupyterLab:

    jupyter lab

To work with this code you'll want to download the 2019 StackOverflow [developer survey].

Once downloaded, put the files into a directory called `data`:

    unzip ~/Downloads/stack-overflow-developer-survey-2019.zip -d data

[video series on pandas]: https://www.youtube.com/watch?v=ZyhVh-qRZPA&list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS
[developer survey]: https://insights.stackoverflow.com/survey
