---
layout: post
title:      "CLI Data Gem"
date:       2018-05-29 21:20:22 +0000
permalink:  cli_data_gem
---



The first time starting a whole project from scratch is a little overwhelming. Other than a couple of "New Project" created on my Visual Studio IDE when I was in college where you would create a new project to follow along with the lecture, there was never a whole application that I created from nothing. This project I would say tested my knowledge of the underlying programming language than any other labs I've done or college assignments. Following along
the walkthrough video on the Learn curriculum, I got a feel of how to put together a good starting point for my code and 
a way to keep writing code as I figure the rest out later. So I followed along until I had the basic CLI displaying fake data to the user. 



Once I had the barebones of my program together, it was time to build my objects or classes I was going to be using to get data for the CLI. I started with writing a class that would be responsible for initializing an instance of that class to later be used by the CLI. I had no clue how I was going to get the data to create the class, so I moved onto creating my Scraper class. This was the most difficult area of the project for my application, since all the data I needed was separated onto different websites within the main website. My proposed project was a DogCatalog that would scrape product data (product name, it's URL, and price). However, there was no "show all leashes" or "show all collars" option on the website, and so each product category was designed to be compartmentalized from the rest. For example, for leashes, there would be products in "Show dog leashes", "Long lines", "Leather leashes". But I just wanted all leashes. 



At this point, I just wanted to get any data returned from scraping so I could test my program. So I wrote code to access every website they had containing leashes, parse it's data, and store it in an array. It was an ugly experience as my code was not DRY in the least bit. I had wrote separate code for each website, while the syntax remained pretty much the same for all of them. So I took a step back and realized that I could run a loop that accesses each website containing leashes, then parse the data, and store it into an array. This saved me presumably over 200 lines of code!





In the end, I learned a lot more about OO Ruby while working on the project. It made me realize that there were some areas that I had thought I knew how to figure out, only to find out my logic and thinking process was wrong, and reading up on the documentation on each of those scenarios helped me to really understand what was going on within my code. 
