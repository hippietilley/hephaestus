# Hephaestus

## Dependency Management

Dependencies managed via [pip-tools](https://github.com/jazzband/pip-tools).

Install: `pip install -r requirements.txt`
Install Dev: `pip install -r requirements_dev.txt`

Upgrade Packages: `pip-compile --upgrade requirements.in`
Upgrade Dev Packages: `pip-compile --upgrade requirements_dev.in`

## Local Development via Docker

    $ docker-compose up

