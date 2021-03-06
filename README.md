# Missing Persons Archive Backend [![Build Status](https://travis-ci.com/dcmpa/backend.svg?branch=master)](https://travis-ci.com/dcmpa/backend)

# Project Setup 

## Set up a virtual environment with a python3.6 interpreter(Ubuntu):
```
virtualenv --python={PATH_TO_PYTHON3.6} dcmpa
source dcmpa/bin/activate
```

## Install requirements:
```
pip install -r requirements/local.txt
```

## Set up environment variables:
Provide values for the following environment variables:
- DCMPA_ENVIRONMENT=local
- POSTGRES_DB_NAME
- POSTGRES_DB_USER
- POSTGRES_USER_PASSWORD

## Start django server :
```
python manage.py runserver
```

## Deployment
- master branch:- staging branch
- production branch:- production branch; the branch is tagged on each merge to show backend versioning.