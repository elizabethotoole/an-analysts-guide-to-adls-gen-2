# Creating a virtual environment

A virtual environment allows anyone cloning this repository to install the dependencies in the requirements.txt file meaning they can replicate the same environment on their own system. 

## Instructions for Windows Users:
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
