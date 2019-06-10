# Python-TroubleShooting
 Solutions targeting the python environment
 
 ### 1.1 Install the python package to a specific python environment.
```bash
sudo python2.7 -m pip install pycoin
```
### 3.2 When using 'pip' to install some python libraries, it may throw some errors (e.g., missing dependencies).
```bash 
sudo apt-get install python3.6-dev
```
can fix this kind of errors.

### 3.3 Set up a clean environment with 'virtualenv'
```bash
# Install pip if it is not available:
which pip || curl https://bootstrap.pypa.io/get-pip.py | python

# Install virtualenv if it is not available:
which virtualenv || pip install --upgrade virtualenv

# *If* the above command displays an error, you can try installing as root:
sudo pip install virtualenv

# Create a virtual environment:
virtualenv -p python3 ~/.venv-py3

# Activate your new virtual environment:
source ~/.venv-py3/bin/activate

Remember that each new terminal session requires you to reactivate your virtualenv through the above command.
```

