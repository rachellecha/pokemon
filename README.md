# pokemon

## Inspiration 
I wanted to do a R project after completeing the codecademy.com's R tutorials to reinforce what I learned. Growing up, I've always played Pokemon and something that has always puzzled me is "how long it takes to hatch specific eggs?" Maybe it was because I was young but I never looked into if different pokemon needed more in-game steps or not. I have quickly realized this was the case and I wanted to take these in-game metrics and provide a way for people to be able to use a real life measure of time to see how long egg hatching actually takes

## What it does
This R program's main function is to tell the user how long it takes in seconds to hatch a specific Pokemon egg based on user inputed Pokemon Name, Which Generation of the Game They Are Playing, and Mode of Transportation (Running Vs. Biking). There are some extra basic analysis at the end where I do a 5 number summary of each generation, graph the number of Pokemon in each generation, and a bar graph showing Generation 7's step counts. 

## How I built it
I used R to create this. Some packages I used were tidyverse, ggplot2, stringr, rvest, jsonlite, etc. As I will explain further in "Challenges," there was no available dataset of the information I wanted so I had to web scrape to get it.

## Challenges I ran into
I scraped bulbapedia.net for egg hatching data since there was no available data. This was my first time webscraping and the data was messy! The website didn't have many html divisions/containers so I basically scraped the whole website into a one column table with over 8000 entries. I then worked on putting each type of data into different columns and renamed them. I turned 8000+ entries into 800 entries!

After this, it was smooth sailing!

## Accomplishments that I'm proud of
This was my first project in R and my first introduction to webscraping in general. It would've been easier to just find a different dataset that was cleaner for my first project but I'm proud of how I was able to think on my feet and learn how to do all this with relative ease. 

I really was thrown into the fire with this one! hahaha

## What I learned
I learned how to web scrape in R using rvest, clean data with the tidyverse packages, and some extra functionalities of ggplot2!

## What's next?
Hopefully, I'll be able to make it so the program will understand misspelled Pokemon names and maybe even bring this to a website so people can try it out. I made some graphs but didn't really analyze them so I will probably go back and comment in my analysis of different trends I see. I also plan on maybe analyzing if there's any correlation between how early you encounter a pokemon (low level pokemon) and how quickly it can hatch. 

# check out the dataset on kaggle https://www.kaggle.com/rachellecha/egg-hatching-step-counts-in-pokemon
