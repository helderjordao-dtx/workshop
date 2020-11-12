# DTX-Colab

## Project Name

### Project description

Provide a description of the scope of the project and its goal

#### Staging server

Provide a staging server, if applyable

#### Production server

Provide a production server, if applyable.

### API Documentation

Provide API documentation as soon as possible. 
(ex:  swaggerhub.com)

### Installing

Provide a detailed description of what steps to follow to sucessfully install the application.

- `$ python --version` - Install python on yout local machine, check if instalation was sucessfull.
- `git clone https://github.com/dtx-colab/projetcName.git` - Clone the repository to your machine. 
- `$ python -m venv venv` - Navigate to the project folder and create a virtual enviroment.
- `$ .\venv\Scripts\activate` - Activate the enviroment.
- `$ pip install -r requirements.txt` - Install all the dependencies of the API project.
- `$ pip install -r .\packages\project_model\requirements.txt` - Install all the dependencies of the model package.
- `$ python .\packages\project_model\setup.py sdist bdist_wheel` - Package the model so you can use it as a dependency in the API.

### Running the app

Inside medicos-do-mundo folder:

- ` $ set FLASK_APP=run.py` - Set the FLASK_APP environment variable. Sintax can very depending on which command line tool you are using.
- `$ flask run` - Run the API.

### Testing

Inside inside the project folder folder:

- Run some tests - `$ pytest .\packages\project_api\tests\`

### Coding Guidelines

The coding Guidelines are available on the [`CONTRIBUTING.md`](/CONTRIBUTING.md) file for all those who want to contribute for the development of the project.

### Product owner

- Name Surname, abc.abc@dtx-colab.pt
- Name Surname, abc.abc@dtx-colab.pt

### Group elements

1. Name Surname, abc.abc@dtx-colab.pt
2. Name Surname, (TM),abc.abc@dtx-colab.pt
3. Name Surname, abc.abc@dtx-colab.pt
4. Name Surname, (PO), abc.abc@dtx-colab.pt
5. Name Surname, abc.abc@dtx-colab.pt

**Legend**: TL - Team Leader; PO - Product Owner

Provide a link containing more information of the project.
For more detailed information see the project's [wiki](https://github.com/helderjordao-dtx/workshop/wiki).
