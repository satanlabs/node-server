# node-server
MySQL , Express-JS , NodeJS merged together to create a RESFful server.


## SETUP

- Restore database using `customer.sql` file to DB `test`.

- ( Optional ) change the credentials of MySQL-DB ( in index.js ) .

- $ `npm install`

- $ `node index.js`

- Hit `http://localhost:33000/customer`  ( you should see a JSON array of customers' data )



## Extra features

 -  Run server in background using command $ `nohup node index.js &`
