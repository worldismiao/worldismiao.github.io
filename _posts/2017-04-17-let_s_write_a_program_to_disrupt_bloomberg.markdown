---
layout: post
title:  "Let’s write a program to disrupt Bloomberg!"
date:   2017-04-17 02:50:53 +0000
---



When I started my first job as a financial analyst I was amazed by how expensive Bloomberg terminal is -- they essentially paid more for this machine than they paid for me. How pathetic! Now I have a chance to take my revenge. Let’s write a ruby gem to replace Bloomberg!

I started by following this wonderful video Avi made() and created a bundle gem. Then, I designed the basis structure of my cli interface – what questions I want to ask the users (wall street traders in this case ), and what information I want to feed them back. Here I decided I want to ask the traders for the ticker of the stock, and return them the company name and stock price. 

Then I started building a CLI class to realize the functions of the cli interface. After that, I built a Stock class to get the information I need to return in the program. I wrote two web scrapers, one on Google Finance and the other on Yahoo Finance, to get the company name and stock price.

And then – ta-da! My little Bloomberg is born! I know this is a very, very, very simplified version of Bloomberg, but this is how every disruption starts! At least I can offer it for free, watch out for my low-end disruption Bloomberg!

