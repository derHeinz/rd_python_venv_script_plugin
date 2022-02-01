Plugin for Rundeck (see https://www.rundeck.com/) to run python3 code locally.

# Requirements
- linux host to run Rundeck
- python3 installed on that host
- pip3 installed on that host

# What it does
1. create venv in /tmp/ directory
2. activate venv
2. installs your requirements using pip3 
4. runs your python script
5. finally removes the venv temp directory

# How to build
1. use linux
2. goto directory 
3. call build_plugin.sh
4. receive python_venv_script-plugin.zip
5. use python_venv_script-plugin.zip just like https://docs.rundeck.com/docs/administration/configuration/plugins/installing.html says.
