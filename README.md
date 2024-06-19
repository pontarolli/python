# Python

## Install
```bash
# python
sudo apt install python3
# package manager
sudo apt install python3-pip
# virtual environment creator to install packages
sudo apt install python3-venv
```

## Project
```bash
# Create a project folder
mkdir requests
# Create the main code
nano example_requests.py
# Create a virtual environment
python3 -m venv myenv
# Activate the virtual environment 
source myenv/bin/activate
# Install the package
pip install requests
# Run the code
python example_requests.py
# Generate the requirements.txt
pip freeze > requirements.txt
# Install dependencies from requirements.txt
pip install -r requirements.txt
# Disable the virtual environment
deactivate
```
