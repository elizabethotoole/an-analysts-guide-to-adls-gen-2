# An Analyst's Guide to Azure Data Lake Storage Gen 2
## Description
This repository contains a beginner-friendly guide for connecting to Azure Data Lake Storage (ADLS) Gen 2 using Python 🐍.

Join me as I walk you through the essentials, so you can focus on analysing data, not battling with storage setups. 🚀

## Key Features
- :muscle: **Hands-on notebook**: Dive right in with an interactive Jupyter notebook that you can run and modify to see the results yourself.
- :sparkles: **Simple and clear explanations**: Written for analysts by an analyst, helping to cut through the technical jargon.

## Contents:

1. An Overview of Fundamental Concepts
2. Connecting to Your Storage Account
3. Viewing Files Within Your Storage Account
4. Downloading Files for Analysis
5. Uploading Files to Your Storage Account

## Prerequisites
To follow along with this guide, you'll need to:
- **Have a Python installation**
- **Jupyterlab, VS Code or similar**  (If VS code, the python and jupyter extensions should be installed).
- **Create a virtual environment and install dependencies**

### Instructions for Windows Users:
**Open the command prompt and navigate to your project directory**. <br>
> `cd "path/to/your_project"` <br>

**Create a virtual environment**.  
To create a virtual environment, use the following command:
> `py -<python-version> -m venv <venv-directory>` <br>
- Replace `python-version` with your desired version (optional, it will default to your system's Python version if not specified). <br>
- Replace `venv-directory` with the name you want for your virtual environment. Common names include venv, but you can choose any name (e.g. project_env). Just make sure you add this custom name to your .gitignore file to avoid pushing it to GitHub. <br>

**Activate the virtual environment**. 
> `<venv-directory>/Scripts/activate` <br>
- Make sure to replace <venv-directory> with the name you gave your virtual environment, like venv or project_env.

**Install the dependencies specified in the requirements.txt file**. <br>
> `pip install -r requirements.txt`

**You're good to go!** <br>
After installation, you can start working within your virtual environment. Simply activate it whenever you start a new session and deactivate it when you're done.
> `deactivate`

## Contributing
If you'd like to contribute to this project, feel free to fork the repository, create a new branch, and submit a pull request with your changes. Contributions, bug reports, and feature requests are always welcome!

## License
This project is licensed under the MIT License – see the LICENSE file for details.
