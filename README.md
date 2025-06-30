Python Poetry was introduced in 2020. The latest version, 2.0.1, was released on January 11, 2025. 

Some of the features of Python Poetry include: 
Dependency management: Poetry manages the installation and updates of libraries.
Virtual environment management: Poetry automatically creates and manages virtual environments for each project.
Package publishing: Poetry can publish packages.
Reproducible builds: Poetry ensures reproducible builds through intelligent dependency resolution.
Lockfile: Poetry offers a lockfile to ensure repeatable installs.

### New Python Commands (Windows/VSCODE terminal)

•	pip install poetry
•	poetry init (creates pyproject.toml file)
•	poetry config virtualenvs.in-project true (to create virtual environment in your project directory)
•	poetry install (setup dependencies inside toml file)

### Manually add packages
•	poetry add package name
•	poetry add $(cat requirements.txt) (if packages are listed in requirements.txt)
•	poetry remove package name


### List poetry environments
List poetry environments:
poetry env info --path
(usually under c:\users)
•	poetry env list
•	poetry env remove <current environment>


