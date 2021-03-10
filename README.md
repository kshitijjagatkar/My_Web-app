# My_Web-app
## Personal profile web dashboard
## Using HTML, JS, Python and Flask

1. Installation
2. Project Motivation
3. Functionalities
4. File Descriptions
5. Summary

## Project Motivation

Wanted to create a simple dashboard to show my projects & my personal profile. This is very very simple and basic web-development project. So this repo consist Data analysis report, interactive graphs in my one the project, right now I have only one project to showcase haha. So my main goal is to create a platform that I can put and show my projects 
the I way I want. So in this project I use plotly for interactive graphs(you can play with those graphs) with javascript, Created webpages using bootstrap library and for the backend I use Flask which is microframe and pretty easy to start with.


## Installation

You need IDE to play with all files, So just integrate with your IDE using git or download this code as zip and add project folder to you IDE explorer.
First of all you need to create virtual environment and install flask. [Here](https://flask.palletsprojects.com/en/1.1.x/installation/) is good explanatory.
So uptill all good? That's all you need to setup now in the activated environment run app.py(python "app.py") the server will genrate a link click on that link or paste in you browser you will see webpage is running


## Functionalities

Well, you can use this code to buid your own portfolio just add or remove some things and you are good to go. (Just keep in mind if sometimes the update/changes you made in javascript file doesn't reflect in your browser then try to har refresh or clear the cache within that period. I even added code for this issue under the main method but just telling other way round. This happens because your browser stores cache data.)

## File Structure

File structure is very important for this cause flask searches for your static files and templates. So make new folder/dir and add these files and folders as it. your app.py or flask application should be outside of all those folders your static files such as css/js/images should be go in static folder and html files should go in templetes folder. [this documentation](https://flask.palletsprojects.com/en/1.1.x/tutorial/layout/) will help you understand your project layout.

Additionally there are two more files which is essential for deployement purpose if you are deploying to heroku platform. 1. Procfile: which basically tells heroku from where it should start running. and 2. requirements.txt: which tells heroku these fils are necessary to run this application so download it.

## Summary 

This is very basic web project that helps me understand the process of web-development. from doing the data wrangling, creating visualizations, making the web pages to deploying the the application locally/globally. This project gives me confidence to start next big thing with this.

