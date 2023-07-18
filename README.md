# NoSQL-Social-Network-API

## About The Application

This application is a demonstration of what you would be able to do with NOSql in terms of setting up a database for a social media platform! The demonstration video below will take you through the steps of;

* Adding new users

* Viewing all users

* Viewing a single user

* Updating a single user

* Deleting a single user (which at the same time will delete any associated thoughts and reactions)

* Adding a friend

* Deleting a friend

* Adding a thought

* Viewing all thoughts created by all users

* Viewing a single thought

* Updating a single thought

* Deleting a single thought and its associated reactions

* Adding a reaction

* And finally, deleting a reaction!

Watch the video below to see it in action!

## Issues

I ran into a few issues when building this, some were solved, some unfortunately remain!

* One issue I ran into when testing in Insomnia, was I was consistently getting errors on the Insomnia side of things (even though, the data would still pass through and show up in my NOSql database) I eventually found the errors and fixed them (it was just how certain things were named in a couple places).

* An issue that persists (and is seen in the video) is that after posting a thought, it seems to crash the server, so you have to do a quick restart to continue on. (It still works properly after the restart, its just a hiccup in the code I'm sure!)

* One other issue that persists and I could not seem to solve, is that the DELETE reaction route doesn't actually seem to work! I tried bug fixing this one quite a bit, but couldn't seem to get it figured out. However, if you delete the thought it is associated with (or the user), then the reactions associated will also be deleted!

* In the beginning, I was having a bit of trouble figuring out how to implement the Reactions, but once it clicked, it became pretty easy to do so! (aside from them not deleting from the proper route of course)

## Screenshots

Below I will include a video of the application working as well as some screenshots!



![NoSQL-Social-Network-API](./)


## Conclusion

In conclusion, this project wasn't a bad one! It was a bit confusing at first trying to figure out how everything should tie together, as well as setting up insomnia in a way that I could make the demonstration as short as possible. Other than the time spent on bug fixing, I enjoyed putting this together!

## The Link

Below is the link that will take you to the repository of this application!

https://github.com/Bidoofs-Dad/NoSQL-Social-Network-API