># Local Setup for Running CLAPP on Windows

## Step 1: Install Python
Ensure Python is installed on your system. You can download it from the official Python website.

## Step 2: Install virtualenv using pip
`pip install virtualenv`

## Step 3: Create a New Virtual Environment
- For Python3 `python -m venv env` 
- For Python2 `virtualenv myenv`

## Step 4: Activate the created virtual environment
`.\env\Scripts\activate`

## Step 5: Install all Dependencies in requirements.txt
`pip install -r requirements.txt`

## Step 6: Run Django Server
`python manage.py runserver 8009`
