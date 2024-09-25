# GitHub Actions Matrix Build for Multiple Python Versions
[![CI/CD run](https://github.com/nogibjj/Diego_Rodriguez_Miniproject4/actions/workflows/hello.yml/badge.svg)](https://github.com/nogibjj/Diego_Rodriguez_Miniproject4/actions/workflows/hello.yml)
## File Structure 
```
Diego_Rodriguez_Individual_Project#4/
├── .devcontainer/
│   ├── devcontainer.json
│   └── Dockerfile
├── .github/
|   └── workflows/hello.yml
├── .gitignore
├── main.py
├── Makefile
├── README.md
├── requirements.txt
└── test_main.py
```
## Purpose of project
The purpose of this project is to test multiple python versions and environments in Github Actions. I use `setup-python` action in conjuction with `matrix strategy` to run multiple jobs with different configurations. I use a script `main.py` to check the operating system and python version. Most of the changes go through the YML file: 

<img width="414" alt="yml_jobs" src="https://github.com/user-attachments/assets/31b37969-5a30-42d2-98a8-4f07c57a2703">

## Preparation
1. Open Github codespaces 
2. Wait for container to be built and virtual environment to be activated with requirements.txt installed 
3. Make changes to any parts of the code `main.py` or `test_main.py`
4. Push to see code testing in different operating systems and different python environments 

## Github actions with matrix strategy 

<img width="237" alt="matrix_jobs" src="https://github.com/user-attachments/assets/c106205f-c740-409b-b7d6-3236ffd615f8">

