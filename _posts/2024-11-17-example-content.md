---
layout: post
title: Example content
date:   2024-11-17 10:29:58 +0800
tags:
  - jekyll
  - rlcj
description: >
  Howdy! This is an example blog post that shows several types of HTML content
  supported in this theme.
hero: /assets/images/test_hero.jpeg
overlay: green
published: true
---

Howdy! This is an example blog post that shows several types of HTML content supported in this theme. This is a leading paragraph and should be used as a short introduction to your content.
{: .lead}

The content after the `{: .lead}` will not appear in the post preview on the home page or in the post list. You can exclude the `{: .lead}` tag and the preview will show as much as can fit.

This text is in **bold** font by using `**bold**`. This text is in _italic_ font by using `_italic_`. This text is in ~~strikethrough~~ by using `~~strikethrough~~`. This text is in <sup>superscript</sup> by using `<sup>`. This text is in <sub>subscript</sub> by using `<sub>`. This text is in <mark>highlighted</mark> font by using `<mark>`.

> This is a block quote. You can create a block quote by using `>` at the beginning of the line.

This is a notice block. You can create a notice block by using `{: .notice}`. There are other styles available like `{: .notice-alert}` and `{: .notice-success}`. As you can see, inline code tends to blend in with notice blocks.
{: .notice}

## Inline HTML elements

HTML defines a long list of available inline tags, a complete list of which can be found on the [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML/Element){:target="_blank"}.

- **To bold text**, use `**To bold text**`.
- *To italicize text*, use `*To italicize text*`.
- Abbreviations, like HTML should be defined like this `*[HTML]: HyperText Markup Language`.
- Citations, like <cite>&mdash; Mark otto</cite>, should use `<cite>`.
- ~~Deleted~~ text should use `~~deleted~~` and <ins>inserted</ins> text should use `<ins>`.
- Superscript <sup>text</sup> uses `<sup>` and subscript <sub>text</sub> uses `<sub>`[^1].

Most of these elements are styled by browsers with few modifications on our part.

## Heading

Vivamus sagittis lacus vel augue rutrum faucibus dolor auctor. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.

## Code

Cum sociis natoque penatibus et magnis dis `code element` montes, nascetur ridiculus mus.

{% highlight js %}
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those
// arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
{% endhighlight %}

## Lists

Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.

* Praesent commodo cursus magna, vel scelerisque nisl consectetur et.
* Donec id elit non mi porta gravida at eget metus.
* Nulla vitae elit libero, a pharetra augue.

Donec ullamcorper nulla non metus auctor fringilla. Nulla vitae elit libero, a pharetra augue.

1. Vestibulum id ligula porta felis euismod semper.
2. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
3. Maecenas sed diam eget risus varius blandit sit amet non magna.

Cras mattis consectetur purus sit amet fermentum. Sed posuere consectetur est at lobortis.

HyperText Markup Language (HTML)
: The language used to describe and define the content of a Web page

Cascading Style Sheets (CSS)
: Used to describe the appearance of Web content

JavaScript (JS)
: The programming language used to build advanced Web sites and applications

Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo.

Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo. Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo.
{: .notice-alert}

## Images

Quisque consequat sapien eget quam rhoncus, sit amet laoreet diam tempus. Aliquam aliquam metus erat, a pulvinar turpis suscipit at.

![1200x700](http://placehold.it/1200x700 "Large example image"){:.oversize}
![800x400](http://placehold.it/800x400 "Large example image"){:.lead}
![400x200](http://placehold.it/400x200 "Medium example image")
![200x200](http://placehold.it/200x200 "Small example image")

## Tables

Aenean lacinia bibendum nulla sed consectetur. Lorem ipsum dolor sit amet, consectetur adipiscing elit.

| Name     | Upvotes   | Downvotes |
|----------|-----------|-----------|
| Alice    |        10 |        11 |
| Bob      |         4 |         3 |
| Charlie  |         7 |         9 |
| Totals   |        21 |        23 |

Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.

## Math

Block math:

$$ \frac{1}{1 + \frac{1}{a}} $$

Inline math: $$ \frac{1}{1 + \frac{1}{a}} $$

Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.
Nullam id [^2] dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.

Photo by [Viktor Hanacek](https://picjumbo.com/author/viktorhanacek/) from picjumbo.com 

[^1]: You can insert footnote marks using `[^1]`, `[^2]`, etc and write the footnote text at the bottom of your file like this: `[^1]: You can also insert footnote marks...`

[^2]: Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.

*[HTML]: HyperText Markup Language
*[CSS]: Cascading Style Sheets
*[JS]: JavaScript