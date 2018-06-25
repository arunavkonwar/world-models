# Overview


A Keras implementation of the ideas from the paper 'World Models' by David Ha and Jurgen Schmidhuber https://arxiv.org/pdf/1803.10122.pdf. 

Code base adapted from [Hardmaru ESTool](https://github.com/hardmaru/estool). 

# SETUP

```
git clone 
https://github.com/arunavkonwar/world-models.git
```

2. Set up a virtual environment

Create a Python 3 virtual environment 


```
sudo apt-get install python-pip
sudo pip install virtualenv
sudo pip install virtualenvwrapper
export WORKON_HOME=~/.virtualenvs
source /usr/local/bin/virtualenvwrapper.sh
mkvirtualenv --python=/usr/bin/python3 worldmodels
```
3. Install packages
```
sudo apt-get install cmake swig python3-dev zlib1g-dev python-opengl mpich xvfb xserver-xephyr vnc4server
```

4. Install requirements.txt
```
cd world-models
pip install -r requirements.txt
```
