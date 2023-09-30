# DAC_MongoDb
started mongodb on 27-09-23 <br>

##client and server both exe are used for creating local server <br>
### Mongodb
mongodb is a non relational database which uses no sql for manipulating databases. <br>
### import of json file into mongodb
 mongoimport filepath -d databaseName(it will create if not exist) -c collectionName --jsonArray <br>
#### this working in all
 mongoimport --db dbName --collection collectionName <fileName.json
 ### import of csv file into mongodb
 mongoimport filepath type=csv -d databaseName(it will create if not exist) -c collectionName <br>
 
 ## Aggregate Function
 aggregate is different from find, we create stages using {},{} for fetching date in mongodb collection. <br>
 stages run from 1st to last and same data with using id is transferd from one stage to another
