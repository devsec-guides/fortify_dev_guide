
# Fortify Developer Guide

This guide is used to help unify the Fortify production documentation.
It includes information that help developers to quickly get started with our products and tools.

The site was built with [MkDocs](https://www.mkdocs.org/) and the styling was applied using [MkDocs  material](https://squidfunk.github.io/mkdocs-material/)

## Requirements
- python 3.11+
- pip 22.3.1+

## Download the repository

```
git clone git@github.com:techtimefly/fortify-dev-guide.git
```

## (Optional) Python Virtual Enviroment
It's recommended to create a python virtual environment in order to avoid conflicting with global python packages on the system

```
python -m pip -U install virtualenv

# navigate into the project folder and create the virtual environment

python -m virtualenv .env

# activate the virtual env on Windows

.env\scripts\activate

# activate the virtual env on linux/mac
.env\bin\Activate

```
## Installing
python -m pip install -r requirements.txt

## Running the application

```
python -m mkdocs serve
```

By defaul the application will be served on port 8080 and will be accessible at http://localhost:8080


## Running in production

The following syntax specifies the IP address, port, and disables live reloading

```
python -m mkdocs server -a ip:port --live-reload=false
```

