# find-close-meteorites 
demo learning python from acloud

## Running

This project requires python3 and requests packages.
    python3 find_meteors.py

## install pip3 for linux
    sudo apt-get install python3-pip
    pip3 install pipenv

## Package Requirement in pipenv
    Install pipenv to have exact match package to run this script.
    pip3 install pipenv

## Set the current pipenv to python3.7
    pipenv --three


## run the script to see if any error generate and install the required package in pipenv

    $ pipenv run python find_meteors.py
    Traceback (most recent call last):
      File "find_meteors.py", line 4, in <module>
        import requests
    ModuleNotFoundError: No module named 'requests'
    $ pipenv install requests


