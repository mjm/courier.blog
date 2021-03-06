---
title: Frequently Asked Questions
permalink: /faq/
---

* [Why did you make Courier?](#why-did-you-make-courier)
* [My tweets aren't showing up in Courier as quickly as I'd expect](#my-tweets-arent-showing-up-in-courier-as-quickly-as-id-expect)

## Why did you make Courier?

I really like microblogging: in particular, I like posting my content to my own site that I can control and own forever. I also enjoy engaging with the Twitter community, so I value being able to continue posting my thoughts and writing there.

When I first started microblogging, I tried a number of tools and plugins to crosspost from my blog to Twitter. Every single one of them produced tweets that felt unnatural and artificial: they didn't really fit in with the way people write for Twitter.

I wanted a tool that would let me keep posting to my own site while posting tweets that felt like they were actually written for Twitter. Courier is that tool.

## My tweets aren't showing up in Courier as quickly as I'd expect

Courier will periodically check the feeds that it knows about for new posts, but the quickest way to get posts from your blog to Courier is to set up your blog to ping Courier when you make changes.

Many blogging CMSes have a setting where you can add URLs to ping when you've updated you blog. If you use WordPress, you can find this in the admin section of your site under **Settings** → **Writing** → **Update Services**.

If your blog supports this feature, add the URL `https://app.courier.blog/ping` to the list.

When your blog pings Courier, it will immediately check the feed for new posts and create tweets for them.
