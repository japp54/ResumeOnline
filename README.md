# ResumeOnline

## This tutorial will help you deploy a Python app (a simple Flask app) in minutes.
__ Its a python based project by making use of Flask microframe work. __

#Heroku

__ Heroku is a platform as a service (PaaS) that enables developers to build, run, and operate applications entirely in the cloud.
It rents an AWS and partitions it to smaller virual severs that can each house an app.
It focuses more on addons. __

__ You will have to create a Heroku account before you can get started(its FREE).__

The link which deals with these instructions-https://signup.heroku.com/dc

## Steps- (I have written this with flask if you use any other framewok make the neccessary changes.)

(1)All the static files like .css,images etc go to your static folder.

(2)Your HTML files are to be put in the templates folder.
   Be careful with the links(external)--The syntax has to be changed as per flasks requirement.   

(3)Flask_app.py does the routing for you.It does the job of rendering your templates.

(4)requirements.txt file should contain all the dependencies that must be installed in the server(linux container(Dyno)) to host your site.

(5)A Procfile is a mechanism for declaring what commands are run by your application’s dynos on the Heroku platform.

# My resume website

__ Link->  https://ash-resume.herokuapp.com __  

(*I still have to add my projects in my resume.)  
