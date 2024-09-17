# datafun-04-jupyter

Professional analytics project using Git, Python, venv, pip, VS Code, and Jupyter Notebooks.
Commands were used on a Windows machine running PowerShell.  

## Create and Activate Project Virtual Environment

```shell
py -m venv .venv
.venv\Scripts\Activate
py -m pip install -r "requirements.txt"
```

## Freeze Requirements

```shell
py -m pip freeze > requirements.txt
```

## Git Add / Commit / Push 

```shell
git add .
git commit -m "create Project 4 repo, .gitignore, .venv, and README"
git push -u origin main
```
## Install dependencies

```shell
py -m pip install -r requirements.txt
```

## How to Install and Run the Project

```shell
py -m pip install numpy
py -m pip install scipy
```

## Specification

This project was built to the following specification:

- [datafun-04-spec](https://github.com/denisecase/datafun-04-spec)