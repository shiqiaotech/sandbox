## 1. Create an account on https://github.com if you do not have one;
## 2. Connect to GitHub through visual studio 2019: https://visualstudio.github.com/
## 3. Git installation: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
## 4. Install the Heroku Command Line Interface (CLI): https://devcenter.heroku.com/articles/getting-started-with-python
## 5. Use the heroku login command to log in to the Heroku CLI:

    heroku login

## 5. Acccess the app on Heroku

    heroku git:remote -a ci-2020
    
## 6. Deploy your code

    git push heroku master
    
## 7. Provision Database    

    heroku run python manage.py migrate


## Reference:

https://www.enterprisedb.com/postgres-tutorials/how-use-postgresql-django

https://devcenter.heroku.com/articles/getting-started-with-python

https://www.postgresqltutorial.com/connect-to-postgresql-database/

https://devcenter.heroku.com/articles/django-app-configuration


## Link: 

https://ci-2020.herokuapp.com
