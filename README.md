# Hello-World Flask Application

This repo hosts a simple Flask application deployed with continuous integration and delivery via Google Cloud Platform using Google Cloud Build and App Engine. Build triggers have been set up to enable continuous delivery and quick application deployment.

The app can be accessed [**HERE**](!https://flask-gcp-304218.uc.r.appspot.com/) and it has two routes:

1. /name/**input** where **input** can be replace with any word of the user's choice. The input is returned as a json string of the form:

        {"value":"input"}

2. /job which always returns the following json string:

        {"value":"Data Scientist"}