---
layout: post
title:      "Dog Toy Lister Sinatra App"
date:       2018-08-20 18:45:49 +0000
permalink:  dog_toy_lister_sinatra_app
---


For my Sinatra Section project, I decided that I wanted to create a web app that helps you track all the favorite toys you buy for you and your dog. 

The project had 8 main requirements that you must meet in order to submit.

1. Build an MVC Sinatra Application.
2. Use ActiveRecord with Sinatra.
3. Use Multiple Models.
4. Use at least one has_many relationship on a User model and one belongs_to relationship on another model
5. Must have user accounts. The user that created a given piece of content should be the only person who can modify that content
6. Must have the abilty to create, read, update and destroy any instance of the resource that belongs to a user.
7. Ensure that any instance of the resource that belongs to a user can be edited or deleted only by that user.
8. You should also have validations for user input to ensure that bad data isn't added to the database. The fields in your signup form should be required and the user attribute that is used to login a user should be a unique value in the DB before creating the user.

It took me a long time to decide on how to begin and I thought of doing 2 other domains before deciding on this one. 

Starting out I created my basic file tree structure and tracked my files with Git. I added my gems after to get moving along and set up my environment and database migrations. Once those were up and running, I began to create the controllers I would need based on the info in my database.

Once I had the controllers in place, it was now time to add all of the necessary routes and making sure my logic met the requirements of the project. I didn't run into many issues regarding how to set up the models and user accounts or authentication. Those were straightforward and easily referenced in the curriculum if I did have a hiccup. 

Adding input validations errors took me some time to implement, as I was writing code to show errors using the Rack Flash gem, and none was being displayed. I realized I didn't read enough into the documentation to wholly understand what was going on for errors to be displayed. So I sat down to go through it and figured it out. What I was missing was adding logic to my view files to show the error. 

After making sure input validations were working and in place, I was done with the main requirements. I now wanted to add Bootstrap to my project in order to clean up my web app and add a navbar. 

I chose to add the 'sinatra-twitter-bootstrap' gem to my project which allows me to access the css and js files from bootstrap without having to add the files to my project's directory manually. Bootstrap allowed me to easily change my table for my data into a responsive one. 


Finishing up, I created a CRUD Sinatra web app that tracks all the toys my dogs go crazy about using Ruby + Bootstrap for the front end and Sqlite3 for my back end. 



