
   DL LAB SETUP - Ubuntu
===================

STEP 1: Check Python
---------------------
python3 --version

sudo apt install python3 python3-venv -y

STEP 2: Folder
---------------------
cd ~/prac


STEP 3: Create & Activate Virtual Environment
----------------------------------------------
python3 -m venv venv --system-site-packages
source venv/bin/activate

STEP 4: Install All Required Libraries
----------------------------------------
pip install jupyter notebook numpy pandas matplotlib scikit-learn tensorflow ipykernel

STEP 5: Launch Jupyter Notebook
---------------------------------
jupyter notebook

Then copy the localhost:8888/... URL and paste it in the browser.


   DL LAB SETUP - WINDOWS
============================================

STEP 1: Check Python
---------------------
python --version

- Download Python from https://www.python.org/downloads/

STEP 2: Folder
--------------------------------------
cd \prac

STEP 3: Create & Activate Virtual Environment
----------------------------------------------
python -m venv venv
venv\Scripts\activate

NOTE: If activation gives error in PowerShell, run this first:
Set-ExecutionPolicy Unrestricted -Scope CurrentUser

STEP 4: Install All Required Libraries
----------------------------------------
pip install jupyter notebook numpy pandas matplotlib scikit-learn tensorflow ipykernel

STEP 5: Launch Jupyter Notebook
---------------------------------
jupyter notebook

Then copy the localhost:8888/... URL and paste it in the browser.



