=======
# node-rest
node/backbone rest application based on Chris Coenraets wine cellar app.

# how to start the MongoDB

cd /usr/local/mongodb

start mongoDB
./bin/mongod

start mongo shell
./bin/mongo

query database through shell
db.wines.find().pretty()

switch database
use winedb

return all collection/db records
db.getCollection("wines").find()

db.wines.find({year: "2009”})

Start App
~/Sites/labs/nodecellar
$ node server.js

http://localhost:3000/index.html

API
http://localhost:3000/wines/
http://localhost:3000/wines/554e8e704ad503c74a6fc7f0
