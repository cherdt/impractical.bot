---
layout: post
title:  "DIY Gist Chatbots"
date:   2019-02-23 20:56:00 -0600
categories: [chatbots, bots, nltk] 
---

# DIY Gist Chatbots

I created a tool that will allow anyone to experiment with NLTK (Natural Language Toolkit) chatbots without writing any Python code.

I plan to expand on this idea, but it is usable now. In order to create your own bot:

* Create a [GitHub](https://github.com) account
* Create a "gist" or fork my demo gist: [Greetings Bot Source](https://gist.github.com/cherdt/f29a847a08fdc24a42a8e427e079310c)
* Customize the name, match, and replies elements
* Note your username and the unique ID of your gist (a hash value, a 32-character string of letters and numbers)
* Visit http://impractical.bot/chat/user/hash, replacing "user" with your GitHub username and "hash" with the unique ID of your gist. For an example, see [Greetings Bot](http://impractical.bot/chat/cherdt/f29a847a08fdc24a42a8e427e079310c).

You can now interact with your custom bot, or share the link with your friends!

One more thing: if you update your gist, you'll need to let the site know to update the code. Just click the "Reload Source" link on the chat page.
