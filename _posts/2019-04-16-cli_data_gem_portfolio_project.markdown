---
layout: post
title:      "CLI Data Gem Portfolio Project"
date:       2019-04-17 01:38:25 +0000
permalink:  cli_data_gem_portfolio_project
---


Over the past two weeks, I was working on building my first Ruby gem that provides a Command Line Interface (CLI) to an external data source. This project was definitely challenging because it was based on everything that I learned about including object-oriented Ruby and writing code to scrape data from a public website. 

**CLI Data Project Reqs**: 
1. Provide a CLI
2. CLI application must provide access to data from a web page.
3. The data provided must go at least one level deep. A "level" is where a user can make a choice and then get detailed information about their decision.
4. Your CLI application should not be too similar to the Ruby final projects. Also, please refrain from using Kickstarter as that was used for the scraping 'code along.'
5. Use good OO design patterns. You should be creating a collection of objects, not hashes, to store your data.

### Choosing a topic
The hardest part was starting off because I was used to forking and cloning existing projects and using prompts to guide me to the solution. The blank screen is really intimidating, but I would recommend finding a functional website first. I chose to scrape a BuzzFeed article "10 Best Places to Travel in 2019." This seemed to be the best structural website where it would be easy to scrape and iterate over. Besides, this would be a topic that I wouldn't get bored with. 

### Planning out the Layout
Now that I had a website to base my project on, I was able to create a flow chart of how I wanted my project to flow. I wish I had a whiteboard or artistic qualities for drawing, but different colored pens and paper worked fine.  

Ideally, I wanted the user to be presented with a listing of travel locations and let the user choose which travel location they wanted to learn more about. After the user, read the travel location details he/she can decide to view another destination or quit. 

Avi's video provided guidance on how to use bundler and create my framework. In total, I have three files: Cli.rb, Place.rb and Scrape.rb. Cli.rb will welcome the user, present the list, gather the user's input and present the deals. Scrape.rb will point to the Buzzfeed article, pull the location and details from the div sections and store them into an object of the class Place. The file Place.rb will host my class, initiate my values and store them into a global array. 

### Real Life Roadblocks
After creating a general layout for my project, two significant things happened: a massive project at work and I was diagnosed with a nasty cold. Did I mention that I lost my voice (for several days)?! Despite everything, I made an effort to join the group sessions. 
Fast forward to five days before the project due date, I made little to no progress in my project. On the verge of frustration and giving up, my educational coach came to the rescue. My educational couch allowed me to vent and helped me create a realistic plan for myself. I also have to give credit to my instructor for always being available and my classmates for the guidance. 

After the major setbacks, I was able to complete my project. The last time, I felt so accomplished and tired was after submitting my thesis in grad school. 


### Tips and biggest takeaways:
1. Avi's video is a BIG help for getting started. 
2. Googling 'Ruby Nokogiri CLI' is a good source for help
3. Attend as many group sessions as possible- even if you don't think that you need help.
4. Don't give up! 

