# airline-reservation-system
Airline reservation system provides you the best experience in which you want to book flights for tourists and so on 
## Table of Contents

- [Installation](#Installation)
  - [Client](#Client)
  - [Server](#Server)

## Installation

### Client

1. Navigate to the `client` directory.

```bash
cd client
```

2. Install the required react dependencies through.

```bash
npm install
```

3. Run the frontend server.

```bash
npm start
```


### Server

1. Navigate to the `server` directory.

```bash
cd server
```

2. Install the required react dependencies through.

```bash
npm install
```

3. All the commands to create all the functionalites for the sql database are in `Database.sql` file. You have to run them one by one to create all the required tables, triggers and other procedures.

4. Change this code snippet in the `index.js` file accordingly. The comments represent the values I have set for my local machine.

```bash
   const db= mysql.createPool({
    host:"localhost",
    user:"your_sql_db_name",
    password:"your_sql_db_password",  
    database:"your_database_name"   //airport_management
});
```

5. Run the backend server.

```bash
nodemon index.js
```
