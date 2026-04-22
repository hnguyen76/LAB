# Creating a virtual ENV (venv)
1. create your project folder and make sure you terminal is at the root of the project
2. To create virtual env, run in the terminal `python3 -m venv venvname`

# Using a virtual env
-If you don't activate your v.e., when you install packages they won't be env specific
- To activate mac: `source venvname/bin/activate`
- for Windows: `source venvname/Scipts/activate`
-To deactivate 'deactivate

# Github with venv
- NOT ALL FILES SHOULD BE PUSHED TO GITHUB
- Create a `.gitignore' 
-list all folder to be ignore by github (venvname)

# To save the list of installed packages
Run command: `pip freeze > requirements.txt`
