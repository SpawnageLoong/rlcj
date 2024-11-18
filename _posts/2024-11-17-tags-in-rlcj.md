---
layout: post
title: 'Tags in rlcj'
date:   2024-11-17 13:49:00 +0800
tags:
  - rlcj
  - howto
hero: /uploads/2024-11-17-tags-in-rlcj/hero.jpg
overlay: orange
---

Tags are built using the auto-pages features of [jekyll-paginate-v2](https://github.com/sverrirs/jekyll-paginate-v2/tree/master). This is a plugin that automatically generates pages for each tag and extends the default Jekyll pagination with additional features such as filtering posts by tags, categories and collections.
{: .lead}

<!–-break-–>

## How to add a new tag

Tags are automatically indexed when you add them to a post. To add a new tag, simply add it to the `tags` field in the post's front matter. For example, to add the tag `dactl` to a post, you would add the following to the post's front matter:

{% highlight yaml %}
---
layout: post
title: 'My Post Title'
date: 2024-11-17 13:49:00 +0800
tags:
  - dactl
---
{% endhighlight %}

That's it! The tag `dactl` will now be indexed and will appear at the address `/tag/dactl`.

## Tag pages

All tag pages use the layout `autopage_tags.html`. This layout is responsible for displaying the tag's name, description, and a list of posts that have that tag. The layout is located in the `_layouts` directory. At this point in time, it's basically the same as the default blog page layout.
