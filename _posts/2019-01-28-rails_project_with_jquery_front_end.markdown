---
layout: post
title:      "Rails Project with Jquery Front End"
date:       2019-01-28 23:13:11 +0000
permalink:  rails_project_with_jquery_front_end
---


**Starting A New Project **

Going into the 4th project, I figured this project would be one of the easier projects since we got to start off with the Rails application we had build during the 3rd project. All we *had* to do was to add Javascript to our Rails app. Not so bad, sounds easy, right? The Rails app I had built was a website that allows dog trainers to create their own training tutorials and post comments on other tutorials including their own. I thought I had a few great ideas that I wanted to implement and the project would be over in a breeze. 

**How Much Javascript Do I Actually Know?**

Looking over the project requirements, I figured the steps seemed simple enough: 

1. Must render at least one index page (index resource - 'list of things') via JavaScript and an Active Model Serialization JSON Backend
2. Must render at least one show page (show resource - 'one specific thing') via JavaScript and an Active Model Serialization JSON Backend.
3. Your Rails application must dynamically render on the page at least one 'has-many' relationship through JSON using JavaScript.
4. Must use your Rails application and JavaScript to render a form for creating a resource that submits dynamically.
5. Must translate the JSON responses into JavaScript Model Objects using either ES6 class or constructor syntax. The Model Objects must have at least one method on the prototype. Formatters work really well for this.

At first for rendering an index page, I wanted to display the index of a User's comments on their show page. But I realized that that information wouldn't really be beneficial from the User's perspective. I ended up deciding to render the index of a tutorial's comments on the index page of tutorials so that the User can see the comments of the tutorials without having to view the content of the tutorial themselves. When it came to implementing the feature on the backend, I came into issues trying to get the comments to load into the right place of the DOM. However I found a way to fix it by adding a class within a div that contained the tutorial id so that it incremented for each time each tutorial is loaded into the DOM. Then when it came to actually loading the comments with jquery, I interpolated the tutorial id given to me through the AJAX get request to fill the correct divs with the corresponding comments. 

**Power Of Javascript**

When I was adding each of the requirements, I realized that turning responses into JSON made everything I wanted to do much easier. JSON is formatted in a way that is easy to understand and stays consistent for any object. Creating classes and methods on the prototype made adding info into the DOM simple and filled my application with all the necessary information. I realized that on the return value of a of a method on a Javascript Model Object prototype could return even styling I had added with Bootstrap. 

**End In Sight**

Once I completed one requirement, it made thinking about how to implement the next requirement that much easier and seeing a path to completion gave me the thought that, "Hey, maybe I actually know how to code. That wasn't so hard". Finishing up the project I realized that I didn't know how to write much Javascript and Jquery at all, but I knew enough that I could reference the correct material to find the answer to the questions I had. I felt accomplished on all that I had learned and am excited to learn more and find out new things that can be done via Javascript. 


