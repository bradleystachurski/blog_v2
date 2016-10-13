---
layout: "post"
title: "Book Review: Data Visualization with Python and JavaScript"
date: "2016-10-12 14:45"
---

![](/assets/Data-Viz-KyranD.jpg)

_Disclaimer: I received a free copy of the book in exchange for an honest review. I am not affiliated with the publisher nor do I receive any financial incentives other than the privilege of reading a book on data visualization for free._

On to the book.

This is my first review of any product on the internet so I feel it's appropriate to offer a short version and a long version.

## Short Version

Whether you're new to the field of data visualization and looking for a book to get up to speed, a seasoned veteran looking to see the industry standard of your peers, or anywhere in-between, there isn't a better source than Data Visualization with Python and JavaScript. You'll be able to go from a small working knowledge of either Python or JavaScript, to being able to use data from the wild to create professional visualizations with an intimate understanding of every step of the process.

## Long Version

After reading Data Visualization with Python and JavaScript, it feels like I had a mentor sit down with me over the course of several days to show how a professional data visualizer goes about business.

I'm a self-taught developer and relatively green in the world of data visualization. My background is in finance and mathematics with limited experience in web development and even less experience working with Python to manipulate data. I figured the best way to learn the field of data visualization is to throw myself into a project, so I volunteered to help a startup with their data visualization needs. Volunteering for this task while backpacking solo across Europe and having no coworkers in the field to learn from left me in an awkward spot. How do I learn to create professional data visualizations? The data gods graced me with this text.

The budding data visualizer is entering the field at an exciting time, and Kyran immediately pulls you in and lets you know the excitement is warranted. By the end of the introduction I couldn't contain myself and was fist pumping the air, eager to consume the wisdom in the chapters that lay ahead.

The title of the book gets straight to the point. The modern way to create data visualizations is to use both Python and JavaScript. Python is used for the processing of data, where JavaScript is used to create the interactive visualization in the browser. Kyran has many years of experience working with the data visualization workflow, and his wisdom shines through in his discussion of why these two technologies provide the strongest foundation for modern visualizations.

To accommodate readers like myself that have limited experience with either Python or JavaScript, the first part of the book includes three preliminary chapters that bring you up to speed on both languages and how to get them to play in the same sandbox. To anyone new to either Python or JavaScript, this alone could be worth the value of the book. For the more experienced developer, these chapters can be skipped or used as a reference without any disruption to the flow of the book.

Kyran approaches the difficult task of driving home the lessons of the book by way of example from the wild. He chooses to use the list of all Nobel Prize winners scraped from Wikipedia. At first glance, this might seem like a dull choice when considering the current domain of datasets in the wild, however as the pages unfold you realize the beauty in this choice. The more insights and stories that are teased out of this "dull" dataset make you question what types of insights you'll be able to pull from datasets you'll work with on your future data visualization adventures.

The meat of the book takes this example dataset and unfolds how to create a professional data visualization from scratch to finished product. You'll be gently guided through every step of the process and the author includes a healthy dose of useful anecdotes throughout that provide color to the process. This is truly a gem for anyone looking to put the pieces together in creating an efficient and modern work flow.

Without spoiling the heart of the book, I'll give an overview of the main sections of the work flow. The five sections that make up the rest of the book include scraping the data from Wikipedia's website using both Beautiful Soup and Scrapy, storing this data in both SQL and NoSQL databases, cleaning the data using Pandas, exploring the data using Pandas and Matplotlib, creating a RESTful API to serve the data from both SQL and NoSQL databases, and finally taking the data served from the API and creating an interactive visualization on the browser using JavaScript and D3. If that sounds like a lot of content, it's because it is.

In order to get the most out of this text requires active participation from the reader. Type in every line of code and follow all the links -- and there are several links, Kyran isn't shy about sending you to different resources on the web. It requires a material amount of time to work through all the examples, but you'll be rewarded with having gone from a small working knowledge of Python and JavaScript, to being able to create professional quality, interactive data visualizations.

I'd like to address some of the other reviews that complain about typos in the code in this book. As you work through the text, you will find typos if you are taking the time to type in all the code. None of these typos are major and if you've been following along and have the patience to do a little problem solving (if you don't have the patience to problem solve, it might be worth considering a different field), you'll be able to see the errors and quickly fix them. There is a GitHub repository with all the code necessary to work through the text, which you'll be able to reference if you get hung up on a typo.

It's also worth addressing the nature of creating a book that involves web scraping. To include an example that comes from the wild -- in this case Wikipedia -- you offer an example that is closer to a real-world scenario at the risk of having the website change and breaking part of the code that scrapes. Unfortunately, Wikipedia changed the structure of their website between the time the book was published and when I got to the section on scraping. This is no fault of the author, nor does it take away from the quality of the book. As the reader, you have the ability to update the code to play nicely with the changes in Wikipedia. For those looking to take a shortcut, you have the choice to download the scraped "dirty" data from the GitHub repository and continue working through the text.

These two issues were very minor in the overall context of the book and don't detract from the value. If anything, the hiccup with the web scraper serves as a valuable lesson in web scraping. Web sites change, so you'll need to either adapt quickly or find a different source of data.

Bottom Line:

If you're interested in learning the process of a professional data visualizer and are willing to put in the time, then you've found the perfect book. You'll learn everything from the basics of Python and JavaScript, all the way through using D3 to create interactive visualizations from data served using a RESTful API that was scraped and cleaned by your efforts. It's a transformative process that can convert you from amateur to professional in a relatively short period of time.
