# CreamApp - NodeExpress Backend
React-Native App that links Drivers and Passengers. 

Main Repo: [https://github.com/muhammadalizkhan/CreamApp]

Main Repo: SoketIO [https://github.com/muhammadalizkhan/CreamAppSokectIO]

Backend server for managing the database (Mongodb) and auth of the app.

Create a MongoDB Atlas database on https://www.mongodb.com/ 

Connect to your application and copy de connection string:
```
mongodb+srv://<username>:<password>@your-db.d9con.mongodb.net/<dbname>?retryWrites=true&w=majority
```
Create a file named mongodb.js inside the config folder.

Add the Mongodb string with your personal db's information.
```
const mongodb = "mongodb+srv://<username>:<password>@your-db.d9con.mongodb.net/<dbname>?retryWrites=true&w=majority";

module.exports = mongodb;
```

## Running

```
$ node index.js
```
## Contributing

Email-me: ali7847khan@gmail.com

Connect with me at [LinkedIn] https://www.linkedin.com/in/malizamankhan/

Thank you!
