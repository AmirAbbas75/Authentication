# Authentication
Authenticating users when login to system
_SERVICE master:
go to master folder 
run:
docker-compose up // up service to port 8083
for test open url in browesr localhost with port or docker container ip
localhost:8083

you can access api from masterapache

for query to database use api address below
masterapache/cloud/public/api/master/query

params : token
		 query
		 
for vote use api address below
masterapache/cloud/public/api/master/vote

params : token
		 fbid
		 voterId
		 candidateId
		 
you must send valid token to master with name token


finish
