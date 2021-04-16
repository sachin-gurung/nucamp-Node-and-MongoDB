1. https://learn.nucamp.co/mod/book/view.php?id=3578&chapterid=4053
(MongoDB Installation guide)

2. mongod -version
(To confirm installation of mongodb)

3. mongod --dbpath=data
(To start the MongoDB server)

4. mongo
(To start the Mongo REPL (Read Evaluate Print Loop) shell)

5. db
(Shows current database that we are accessing with the shell)

6. use nucampsite
(To change the database to nucampsite database or create a new database nucampsite)

7. db.help()
(To show list of commands that can be used with the database)

8. db.campsites.insert({ name: "React Lake Campground", description: "Test" });
(To insert this data in the campsite db)

9. db.campsites.find().pretty();
(To print out the campsites in the collection)

10. const id = new ObjectId();
(Create an object id)

11. id.getTimestamp();
(Examine object id timestamp)

12. exit
(To exit the REPL shell)

13. npm install mongodb@3.6.2
(To install the Node MongoDB driver)



