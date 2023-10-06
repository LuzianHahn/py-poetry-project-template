# How to contribute?


### Git Hooks
Before contributing anything, please ensure to set up the git hooks in your local setup.
You can do so by running 
```shell
poetry install 
pre-commit install --hook-type pre-commit --hook-type prepare-commit-msg --hook-type commit-msg
```
in the root of this project. 
> Ensure that you have a poetry setup in place.
> Refer to [this introduction](https://python-poetry.org/docs/#installation) for details on setting up `poetry`.


### Conventional Commits
Please follow the approach of [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/#specification).
A respective git hook is installed and enforces this. 

