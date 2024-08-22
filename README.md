# Cookiecutter Templates

Just a personal repo where I plan to keep a collection of Cookiecutter templates for various programming languages and frameworks. They're for my convenience but absolutely feel free to fork the repo and use anything you find helpful. 

## Available Templates

### Coming soon: Python Project Template

This template is tailored for Python projects using the following stack:

-   **Poetry**: Dependency management and packaging.
-   **MySQL**: Database integration.
-   **Alembic**: Database migrations.
-   **Kubernetes**: Container orchestration.
-   **Flask (optional)**: Web framework for building APIs and web applications.

You can customize your project setup by choosing whether or not to include Flask.

## How to Use a Template

To generate a project from a template:

1.  Ensure you have [Cookiecutter](https://cookiecutter.readthedocs.io/en/latest/installation.html) installed:
    
    bash
    
    Copy code
    
    `pip install cookiecutter` 
    
2.  Use the following command to create a new project:
    
    bash
    
    Copy code
    
    `cookiecutter gh:your-github-username/cookiecutter-templates` 
    
3.  Follow the prompts to customize your project.
    

### Example:

bash

Copy code

`cookiecutter gh:your-github-username/cookiecutter-templates --checkout python` 

This will generate a Python project based on the specified template.


