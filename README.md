# MongoDB-Data-Transfer

1. Install [MongoDB Community Server](https://www.mongodb.com/try/download/community)
2. Install [MongoDB Database Tools](https://www.mongodb.com/docs/database-tools/installation/installation/)
3. Command to data transfer:
   ```py
     mongodump --uri="<connection_string_of_first_mongod>/<dbname>"
     mongorestore --uri="<connection_string_of_second_mongod>" ./dump/
   
     #to restore from a dump directory to a local mongod instance running on port 27017
     mongorestore  dump/
   ```
4. [The MongoDB Database Tools Documentation](https://www.mongodb.com/docs/database-tools/)
