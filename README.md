A console app to compute time for boiling eggs (based on "An Egg-Boiling Fuzzy Logic Robot" video, available on: https://www.youtube.com/watch?v=J_Q5X0nTmrA)

# How to use 

## Requirements
for execute this program you'll need Python 3.x (you can get from http://python.org)

## Installation
1. clone the repo `git clone https://github.com/jmaquin0/Tipping-problem.git`
2. go to the project directory: `cd Tipping-problem`
3. (optional) create and activate a virtual environment
    - create the virtual environment: `python3 -m venv venv`
    - activate the virtual environment: `source venv/bin/activate`
4. install required packages: `pip install -r requirements.txt`
    - if there is an error during installation install packages individually:
    ```
    pip install numpy
    pip install matplotlib
    pip install scikit-fuzzy
    ```
5. run the program: `python3 tipping.py`