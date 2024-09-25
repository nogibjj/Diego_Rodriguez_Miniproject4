# GitHub Actions Matrix Build for Multiple Python Versions
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
The purpose of this project is to test multiple python versions and environments in Github Actions. I use `setup-python` action in conjuction with `matrix strategy` to run multiple jobs with different configurations. I use a script `main.py` to check the operating system and python version. 

## Preparation
1. Open Github codespaces 
2. Wait for container to be built and virtual environment to be activated with requirements.txt installed 
3. Make changes to any parts of the code `main.py` or `test_main.py`
4. Push to see code testing in different operating systems and different python environments 

## Check format and test errors 
1. Format code `make format`
2. Lint code `make lint`


3. Test code `make test`


## Github actions with matrix strategy 

