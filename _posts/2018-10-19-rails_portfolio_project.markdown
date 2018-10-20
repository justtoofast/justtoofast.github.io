---
layout: post
title:      "Rails Portfolio Project "
date:       2018-10-20 01:42:19 +0000
permalink:  rails_portfolio_project
---


**Off To A Bad Start**

When I first began my project, I decided to create an Instagram clone. I went as far as to be able to CRUD a post with my app, but as I was working on it, I couldn't find the motivation to keep working as the project didn't feel so personable to me. So I scratched that app and decided to create a tutorial website. I was so excited to begin working, that I didn't stop to think about my model associations to each other. I got as far as being able to CRUD a post again, but when it came time to associate that post with another model, I made the wrong association and my database migrations started to get pretty messy, really quick. 

I remedied the issue by scrapping that project and taking time to fully write out and understand what models I wanted to have in my application and how they would associate to each other while meeting the project requirements. From there, I was able to work to past the point of only being able to CRUD a post and my app really started to come together. 

**Running Into Trouble**

For the authentication requirement, I decided to implement Devise into my app. It took me some time to understand each part of adding in Devise, from adding migrations for creating a user and associating that user to my models. However after some time, learning how to implement Devise turned out to be pretty straight forward and makes authentication a piece of cake. 

Adding OmniAuth via Devise was another issue I ran into. I decided to add the Google strategy to my app. After I fixed one error on loading my app through the sign in via Google, I would run into another. There were various fixes to each error and finding the right ones that all worked to get me through and successfully login via OmniAuth was a struggle. 

**Trying To Make Things Nice**

Once OmniAuth was working and I was able to log into my website through Google, my app was pretty much complete but I needed to add designs to my front end. I added the bootstrap gem and set up necessary files, but as soon as I started up my server again, I was given a error:

ExecJS:ProgramError 

Turns out there are many "fixes" to this error, but trying each of those fixes turned to no avail. I ended up having to install Node.js and adding "ENV['EXECJS_RUNTIME'] = 'Node'" to my config/boot.rb file. Then my server started just fine and the basic bootstrap theme was applied to my application.

After bootstrap was finally working with my application, I used various bootstrap specific code from websites that I googled to add styling to my views. 


**Finishing Up**

After completing my project, one of the key things I took away from the learning process was to make sure to think out my models and their associations first and foremost as that gets you to be able to finish out creating your app without having to have a roadblock in the middle of your project trying to create migrations that don't really make sense with one another. 
