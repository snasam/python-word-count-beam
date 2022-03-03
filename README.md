# python-word-count-beam

## Set up the Environment

Check the version by using the command:python --version

## Install pip
pip --version

PS> python -m pip install --upgrade pip

## Create and activate a virtual environment
PS> python -m venv C:\path\to\directory

PS> C:\path\to\directory\Scripts\activate.ps1

## Download and install
PS> python -m pip install apache-beam

## Execure the pipeline
python -m apache_beam.examples.wordcount --input /path/to/inputfile --output /path/to/write/counts
