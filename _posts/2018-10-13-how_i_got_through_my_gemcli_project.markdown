---
layout: post
title:      "How I got through my GemCLI project"
date:       2018-10-13 16:45:04 +0000
permalink:  how_i_got_through_my_gemcli_project
---



Well, the first thing I did was watch multiple videos provided by Learn.  I watched the one done by Avi, and the Amazon group scraping video.  These provided 2 different ways of how to think about the project and forced me to think about how I like to code.  "Do I start with the CLI component, working with how the user would interface with my gem?"  Or "Do I jump right in and scrape the data and then decide how to use it?"

For me, I felt most comfortable working on the scraping methods first.  I was thinking that would be the trickiest part for me so why not get it out of the way.  Then the rest should be gravy.  Well, sort of.  So, after watching a video put on by Jonathan Foster, I decided to go with New Egg.  It's a nice site, well organized and with very little js.  That was the easiest part.  After that, I had to decide what information I wanted to scrape and how was I going to present it to the user.  That was harder than I thought it would be.

At first, I was going to scrape all the data I wanted and then ask the user in what size "chunks" they wanted to see it.  But that felt arbitrary, so I decided to ask the user how many products they wanted to see at one time.  And then display those products and then, to go one level deeper, I asked the user to choose a product they would like more info on.  This seemed clean, straightforward and applicable to the real world.  Scraping the data was easy, until I realized some products did not list the "price" until you put it in your basket for checkout.  So I discovered what the data looked like when there was no "price", turns out it was "nil".  And I replaced the nil with "PRICE UNAVAILABLE".  Not a great solution, but it worked.

The rest of the project was pretty straight-forward.  I created objects with the data scraped and printed out the information that was requested.  The hardest part was making the data look clean and presentable using CSS.  It took a lot of time and patience, (with some Googling) but it was not as daunting of a task as I usually think it is going to be.  And in fact, that is a theme that runs through most of the labs and this project.  It's really not as hard as you think it's going to be.  You are better prepared then you think you are.  

I ended up having 2 meeting with Leads, the first one was to go over big picture questions, "Do I need to use a Module?", " Where is the best place to require files?", etc.  The second meeting actually wasn't necessary.  I was some difficulty using my second scraper method, so I signed up for help, but as it turned out, I fixed the problem before the meeting.  Speaking of "fixing' problems, multiple times, Avi refers to "fixing broken code."  Meaning, it starts out broken and all we are trying to do is fix it.  That is a powerful way to look at the process.  It really does make the creation process much less stressful.  I try to remind myself as often as I can when working.  

I did try  to use the project as a opportunity to experiment and play around a bit with certain things.  I changed the color of the font in the terminal, I was even inspired to try to output a picture of the product to the terminal, but that seemed too daunting of a task, and was reminded to keep the project simple.  I can always improve it later.  





