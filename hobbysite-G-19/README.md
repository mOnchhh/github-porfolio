# Hobbysite Website

This folder contains the files and directories for a django-based website made in fulfillment of requirements for the subject CSCI 40 - Software Tools and Frameworks. The project "hobbysite" contains two apps: "wiki" and "forum" which both take in user input and and display the logged-in user's articles, posts, and comments. 

# How to use

To access the website, you must first clone the repository or download the zip file on your local device and extract the folder "hobbysite-G-19," then open the Command Terminal. Ensure that python (any version) and django 5.0.3 is installed, and that your virtual environment is setup!

To setup your virtual environment, run the following code in the command terminal:
```
python -m venv env

.\env\Scripts\activate
```

Once your virtual environment is running, access the directory wherein "hobbysite-G-19" is located. To do this, type "cd [folder containing hobbysite-G-19]". It should look something like this:
```
(env) C:\m0nchie\github-portfolio\hobbysite-G-19
```

Run this last code to start the website
```
cd hobbysite
# (env) C:\m0nchie\github-portfolio\hobbysite-G-19\hobbysite for reference

python manage.py runservevr

Then, in your browser, enter the URL "localhost:8000" to finally access the website.