---
layout: post
title: 'Layout settings and more in _config.yml'
date: 2024-11-17 14:47:00 +0800
tags:
  - jekyll
  - rlcj
  - howto
hero: /uploads/2024-11-17-config-settings/hero.jpg
overlay: blue
---

All of the rlcj's configurations has to be set in `_config.yml` file. Read on for explanation of all of the features that you can toggle, including configuring the layout.
{: .lead}

I've split rlcj's `_config.yml` into two parts. First part should be configured by you, second contains important Jekyll & build settings and you should leave it alone, unless you know what you are doing.
<!–-break-–>

Let's go through each line in the first, configurable part:

{% highlight yaml %}
# Base blog settings
blog:
  title                      : rlcj
  description                : >
                               this should contain a proper description
# Layout configuration
  logo_path                  : "assets/images/logo.svg" # path to logo file

# Author info
author:
  fullname                  : Your Name
  rss                       : true # generate RSS feed and show it's icon in header
  mail                      : your@email.com # change to your e-mail address
  twitter                   : twitter-user-name
  github                    : github-user-name
  youtube                   : youtube-user-name
  linkedin                  : linkedin-user-name
  photo                     : "uploads/me2.png"
  photo2x                   : "uploads/me.png"

baseurl                     : "/rlcj/" # the subpath of your site, e.g. /blog/, set to '' in case of hosting on GitHub pages
                                       # i.e. `http://<username>.github.io`
url                         : "" # the base hostname & protocol for your site
{% endhighlight %}

## Base blog settings
* `title` - title of your blog, both in `<title>` tag and in the header.
* `description` - descriptionof your blog, shown in the footer

## Layout settings
* `logo_path` - Path to an .svg image used as logo
* `search_path` - Path to your blog, needed for the DuckDuckGo's searchbar found in Archive page.

## Author info
* `fullname` - Your name and surname or nick, used throughout the blog.
* `rss` - true or false - Turn the RSS feeds on or off.
* `mail` - Your e-mail address.
* `twitter` - Your twitter username
* `github` - Your Github username
* `youtube` - Your YouTube username
* `stackoverflow` - Your Stackoverflow username
* `photo` - Avatar or photo of you, used on About page.
