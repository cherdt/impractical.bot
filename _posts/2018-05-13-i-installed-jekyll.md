---
layout: post
title:  "I installed Jekyll"
date:   2018-05-13 18:50:58 -0500
categories: demo jekyll
---


# I installed jekyll

After I installed it, I edited a few files:

* `_config.yml`
* `about.md`

I added a new file:
* `_posts/2018-05-13-i-installed-jekyll.md`

Then I ran:

    bundle exec jekyll serve

Why does Jekyll keep putting `/jekyll` in my post's path? That's due to the categories I apply in the post metadata. For example, I changed this post to used the categories `demo jekyll` and it changed the path to `/demo/jekyll`. This is undoubtedly configurably using the [https://jekyllrb.com/docs/permalinks/](Jekyll permalinks settings), which I will look into later.

Then I ran:

    JEKYLL_ENV=production bundle exec jekyll build

I copied `./_site` to my document root. Voila!

Eventually I will add content to this site.
