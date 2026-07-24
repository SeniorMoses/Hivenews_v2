# Hivenews_v2 is a fastapi web service that user can read news, and add comments

it has multiple features as far as secured restapi is concerned,

key features include

#signup 
#login
#authentication with oauth2 
#authorization
#role based access control 
#post news
#read news
#find news by title
#comment

#technology used


#oauth2 of authentication 
#bcrypt for hashing password 
#dependency injection 
#sqlalchemy 


#next improvement 

#like news
#rate limiting 
#alembic migration 
#docker
#logs
#testing


#how to run
Note: this web service is live on this url
https//:hivenews-v2.onrender.com
automatic docs for testing at 
https//:hivenews-v2.onrender.com/docs

to run this service:
#clone the repo : SeniorMoses/Hivenews_v2
install depency : [pip install -r requirements.txt]
create .env file the following variables 
SECRET = secret_key_here
DBURL = your_database_url

run uvicorn main:app 
or 
gunicorn main:app -k uvicorn workers.UvicornWorker
test the server at your localhost:port_number/docs

