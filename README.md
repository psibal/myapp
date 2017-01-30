# add to bitbucket
### create a repo in bitbucket first
### then in your local
* git init
* git add -A
* git commit -m "first commit"
* git remote add origin git@bitbucket.org:psibal/hello_app.git
* git push -u origin master
### updating file on bitbucket
* git commit -a -m "Update Gemfile for Heroku"
* git push

###deploy to heroku
* git init
* git add .
* git commit -m "first commit"heroku login
* heroku create <appname>
* git push heroku master

* heroku run rake db:migrate

###deploy to github
* git init
* git add .
* git commit -m "first commit"
##create github repo
* git remote add origin https://github.com/psibal/myapp.git
* git push -u origin master

### for changes 
* git add .
* git commit -m "first commit"
* git push 

