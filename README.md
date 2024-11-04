# Setting up the environment

## 1. Install Python
- Download and install Python from [here](https://www.python.org/downloads/).
- Make sure to check the box that says "Add Python to PATH" during installation.
- Open a command prompt and type `python --version` to verify that Python is installed correctly.

## 2. Make a virtual environment using venv
- Open a command prompt and type `python -m venv .venv` to create a virtual environment named `.venv`.
- To activate the virtual environment, type `.venv\Scripts\activate` on Windows or `source .venv/bin/activate` on MacOS/Linux.
- To deactivate the virtual environment, type `deactivate`.

## 3. Install the required packages
- Make sure the virtual environment is activated.
- Type `pip install -r requirements.txt` to install the required packages.


# Running the code

1. Open a command prompt and navigate to the directory containing the code.
2. Make sure the virtual environment is activated.
3. Type `flask run` to start the Flask server. (You can also use --debug to enable debug mode.)