---
layout      : post
title       : "Example Post"
author      : Jane Doe
date        : 2015-08-13
featureimg  : /img/pic01.jpg
tags        :
- dummy text
- random
- type
description : Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates, possimus.
categories  :
- typography
--- 

An h1 header
============

**Pellentesque habitant morbi tristique** senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. _Aenean ultricies mi vitae est_. Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, `commodo vitae`, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum  rutrum orci, sagittis tempus lacus enim ac dui. [Donec non enim](#) in turpis pulvinar facilisis. Ut felis.

  * this bullet
  * that bullet
  * the other bullet

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.

An h2 header
------------

Here's a numbered list:

 1. first item
 2. second item
 3. third item


<!-- OR -->

{% highlight python %}
import time
# Quick, count to ten!
def tick:
  for i in range(10):
      # (but not *too* quick)
      time.sleep(0.5)
      print i
{% endhighlight %}

### An h3 header ###

Now a nested list:

 1. First, get these ingredients:

    * carrots
    * celery
    * lentils

 2. Boil some water.

 3. Dump everything in the pot and follow
    this algorithm:

        find wooden spoon
        uncover pot
        stir
        cover pot
        balance wooden spoon precariously on pot handle
        wait 10 minutes
        goto first step (or shut off burner when done)

    Do not bump wooden spoon or it will fall.

Notice again how text always lines up on 4-space indents (including
that last line which continues item 3 above).

Here's a link to [a website](http://foo.bar), to a [local
doc](/feed.xml), and to a [section heading in the current
doc](#an-h2-header). Here's a footnote [^1].

[^1]: Footnote text goes here.

Tables can look like this:

size | material     | color
---- | ------------ |------------
9    | leather      | brown
10   | hemp canvas  | natural
11   | glass        | transparent

Table: Shoes, their sizes, and what they're made of

(The above is the caption for the table.)
A horizontal rule follows.

***

Here's a definition list:

apples
  : Good for making applesauce.


oranges
  : Citrus!


tomatoes
  : There's no "e" in tomatoe.

Again, text is indented 4 spaces. (Put a blank line between each
term/definition pair to spread things out more.)

Here's a "line block":

| Line one
|   Line too
| Line tree

and images can be specified like so:

![Beautiful Picture]({{ site.baseurl }}/img/pic01.jpg)
{: .image .fit}

And note that you can backslash-escape any punctuation characters
which you wish to be displayed literally, ex.: \`foo\`, \*bar\*, etc.

