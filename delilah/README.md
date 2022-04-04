###### "Delilah Restó"######



### 1 - Clone Project

Clone the repository from the [link](o).

You can also clone it from your terminal:

`git clone  .`

###  Install the required dependencies

```
npm install
```

###  Creating the database

- Open XAMPP and make sure the port being used is number `3306`
- Start the Apache and MySQL services
- Open the Admin panel for the MySQL Service
- Create a new database called `delilah_resto` from the panel
- Open the file located in `/database/queries.sql` and from the `control panel` input via the SQL input section the content to create the tables and populate them with mock values

### Starting the server

From your node terminal open the file located in `/server/server.js`

`node server`

