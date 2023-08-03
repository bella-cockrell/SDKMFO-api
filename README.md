# SDKMFO-api

This repo houses the API for the Super Duper Knitting Machine Figure Outer.

## Requirements
1. Python v 3.10.11
2. FastAPI v 0.100.1
3. pytest v 7.4.0
4. Ruff 0.0.282

## Installation
1. Set up pyenv with 3.10.11 and activate it with `$ pyenv activate <name>`
2. Install dependencies: `$ pip install -r requirements.txt`
3. Run the local server: `$ uvicorn main:app --reload`

## Testing
Run `pytest` and see those tests go.

## Linting
This codebase uses Ruff for linting. More info can be found [here](https://github.com/astral-sh/ruff#getting-started).

## Updating dependencies
Inside the environment, run `pip freeze > requirements.txt`