# MongoDB_NodeJS
MongoDBNodeJS  examples 

API Request Details
1)Finding all Cards

curl -i -X GET http://localhost:3000/FindAllCard 

2)Finding Card by ID

curl -i -X GET http://localhost:3000/findbyid/<ID>

3)Creating a new List

curl -i -X POST -H 'Content-Type: application/json' -d "list_name='test'" -d "list_detais=''test list" http://localhost:3000/createList

4)Deleting the card by ID

curl -i -X DELETE http://localhost:3000/delete/<ID>


5)Modify the card using id

curl -i -X PUT -H 'Content-Type: application/json' -d 'name=bobba' http://localhost:3000/update/<id>
