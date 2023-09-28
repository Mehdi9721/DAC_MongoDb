# DAC_MongoDb
started mongodb on 27-09-23 <br>

##client and server both exe are used for creating local server <br>
### Mongodb
mongodb is a non relational database which uses no sql for manipulating databases. <br>
### import of json file into mongodb
 mongoimport filepath -d databaseName(it will create if not exist) -c collectionName --jsonArray
 ### import of csv file into mongodb
 mongoimport filepath type=csv -d databaseName(it will create if not exist) -c collectionName 
