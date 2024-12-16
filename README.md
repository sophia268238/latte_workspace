# Set Up LATTE
## [LATTE Git Repo](https://github.com/noraeisner/LATTE)
## Prepare System
- [Install python 3.7](https://www.python.org/downloads/release/python-370/)
- `python3.7 -m pip install pdm`
- `/Library/Frameworks/Python.framework/Versions/3.7/bin/pdm sync`
## Prepare LATTE
- `mkdir ./LATTE_output`
- `python -m LATTE --new-data`
## Run LATTE
- `source .venv/bin/activate`
- `python -m LATTE`
  - One time setup:
    - When running for the first time, it will do "Downloading https://hpiers.obspm.fr/iers/bul/bulc/Leap_Second.dat" 
    - When running for the first time, it will also ask " Please enter a path to save the files (e.g. ./LATTE_output or /Users/yourname/Desktop/LATTE_output) : ./LATTE_output"
  - Example:
    - Then enter the TIC such as 122695048
    - Then enter the sectors: 59,73
