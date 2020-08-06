# setup
##1. install pipenv
pip3 install pipenv

##2. if has error "keyring.itul.escape"
pip3 insatll --upgrade keyring.alt

#33. clone this repo, change dir to dowloaded folder

##4.initialize pipenv
pipenv shell

##5. install dependencies of project
pipenv install

##6. addtional for vscode:
add setting for visual code
add .vscode/setting.json:
{
    "python.pythonPath": "<Path to venv>",
    "files.exclude": {
        "**/.git": true,
        "**/.svn": true,
        "**/.hg": true,
        "**/CVS": true,
        "**/.DS_Store": true,
        "**/.pyc": true,
        "**/__pycache": true
    }
}
