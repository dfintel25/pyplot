# Matplotlib and pyplot
#### Developer: Derek Fintel
#### Contact: s542635@youremail; 555-abc-1234

## Project Intro
This project utilizes matplotlib packages to construct code that satifies the prompted questions (Steps 1 thru 4). We perform a number of functions through the steps and plot the results with bar, line, and scatter plots. The results are rich visualizations that help the user understand the processing of the data through our coded functions. 

## Preliminary Project Setup Steps
### 1. Initialize
```
1. Click "New Repository"
    a. Generate name with no spaces
    b. Add a "README.md"
2. Clone Repository to machine via VS Code
    a. Create folder in "C:\Projects"
3. Install requirements.txt
4. Setup gitignore
5. Test example scripts in .venv
```
### 2. Create Project Virtual Environment
```
py -m venv .venv
.venv\Scripts\Activate
py -m pip install --upgrade pip 
py -m pip install -r requirements.txt (if using)
```
### 3. Git add, clone, and commit
```
git add .
git clone "urlexample.git"
git commit -m "add .gitignore, cmds to readme"
git push -u origin main
```
### 4. If copying a repository:
```
1. Click "Use this template" on this example repository (if it's not a template, click "Fork" instead).
2. Clone the repository to your machine:
   git clone example-repo-url
3. Open your new cloned repository in VS Code.
```
## HTML Export
import os
os.system('jupyter nbconvert --to html python-ds.ipynb')

## matplotlib install
pip install matplotlib