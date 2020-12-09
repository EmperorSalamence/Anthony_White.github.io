---
layout: post
title: Hospital Lab Recap
subtitle: Going Through the Hospital Lab
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

Through accessing a database, converting the gathered information into a csv file and interperting the data, I figured out that New York County has the most amount of hospital beds per person. This lab required the use of reading a csv file, requesting data from a database, using commandline to send to output into a readable file and manipulating dictionaries to get the desired information. I believe that the hardest part of the lab for me was getting the data to a point of workability, as I forgot that you could read files as things other than jsons and i didn't understand how to pipe the information into a csv file until working with it for a while. For some reason the csv file didn't want to read as a csv file until I uploaded and redownloaded it as a csv file.

My code accesses a database with data about how many hospital beds are available in New York State, seperated by county and further seperated by bed count. My first step was to standarized the data, as all of the bed counts were in different terms, so I just made them all over 1 by multiplying population by the bed count, and then dividing by the measure (ex.(2.172856 beds * 308580 population)/500 measure) 

I probably could've handled this lab more cleanly by ~~handing it in on time~~ using less lists, as i could've combined all the lists I used to handle the number of beds into one and just manipulated it