# Python MQTT example

Example application using MQTT in Python.  

## Requirements
 - Python3 > 3.9.*

## Getting started
 - Clone the repository
```bash
git clone https://github.com/alptbz/mqttdemo
```
 - Change into repository
```bash
cd mqttdemo
```
 - Create venv
```bash
python -m venv env
```
 - Activate enviroment
```bash
# Linux:
source env/bin/activate

# Windows (PowerShell):
.\env\Scripts\activate

# Windows (bash):
source env/Scripts/activate
```
 - Install requirements
```bash
python -m pip install -r requirements.txt
```
 - Create own config.py and insert credentials and connection information
```bash
cp config.template.py config.py
vim config.py
```
 - Run
```bash
python main.py
```

## Notes
 - Use `python3` instead of `python` if you're using Linux
   
## Links
 - https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment
 - https://pypi.org/project/paho-mqtt/