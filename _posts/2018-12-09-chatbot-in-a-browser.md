---
layout: post
title:  "Chatbot in a Browser"
date:   2018-12-09 15:12:00 -0600
categories: [python, nltk, eliza, docker, aws, twitter] 
---

# Chatbot in a Browser

Until now, all of my Impractical Bots were Impractical *Twitterbots*, tied to the Twitter platform. As I re-discovered recently, that means they are all at the mercy of the capricious Twitter API. Alas, poor [@wumpus_bot](https://twitter.com/wumpus_bot/)! A casualty of API changes.

## A Bot in a Web Page

As a test, I decided to create a somewhat crude interface for interacting with a chatbot in a web page. I decided to start simple, using the pre-built ELIZA chatbot included in the Python Natural Language ToolKit, or [NLTK](https://www.nltk.org/).

After stumbling through a variety of pieces of technology, I present:
[Chat with ELIZA](http://impractical.bot/chat/)

## The Details

The backend code is running uWSGI to call a Flask app, all of which is in a Docker container running in an Amazon EC2 instance. When I said stumbling, those are the technologies I stumbled through.

If you want to build your own, the code is available on GitHub at:
[https://github.com/cherdt/docker-nltk-chatbot](https://github.com/cherdt/docker-nltk-chatbot)
