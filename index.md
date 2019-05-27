---
layout: default
title: Topic names and synonyms
---

# Topic names and synonyms
<byline>Eric Walker, May 26, 2019</byline>

As I've used [Digraph](https://digraph.app/) over the past six months, I've noticed several categories
into which the topics I'm making often fall:

* There are very abstract topics, such as
[Devices, machines, vehicles and robots](https://digraph.app/wiki/topics/ce40a0c0-ef9c-11e8-9826-dbc543f3126a),
which are a bucket into which a whole set of things can be grouped together.
* There are very specific topics,
such as [Use of phages to treat Isabelle Holdaway](https://digraph.app/wiki/topics/536f3a61-e9e6-4d85-8285-f680b4a6a7b4),
which collect together a number of articles on a long-running story.
* There are topics that capture an event in time, such as
[2019-02 Atlas Air Flight 3591](https://digraph.app/wiki/topics/667dfdff-451c-4c8f-be99-baa0264ea3f8),
about the Atlas Air aviation accident.
* There are topics that cover a specific person, such as
[Nicholas Kristof](https://digraph.app/wiki/topics/acdf684f-d4e0-4f08-8af2-196e016e591d), an op/ed contributor
at the *New York Times* that I follow.
* And there are topics that cover something specific, such as
[Colistin](https://digraph.app/wiki/topics/4c343394-bd54-411f-84fa-cdbb09b0e429), an antibiotic.

The case of colistin is an interesting one because there's more than one way to refer to it.  It's also
been called Polymyxin E. There are many similar cases, where a topic that I want to keep tabs on can be called more
than one thing or described in different terms, and it would be nice to be able to search for any one of those
sets of terms and bring up a single topic that can be used to tag an article.

To handle this situation, I've added synonyms to topics:

![Screenshot of a topic with a synonym](https://user-images.githubusercontent.com/760949/58384410-9ac9fd80-7f9e-11e9-8fd5-a33180aa0815.png "Screenshot of a topic with a synonym")

When you search for "Polymyxin E", colistin now comes up.  There's also a locale field, which allows you to
select a language (e.g., Spanish or French).  At some point Digraph will be localized, and if you're
using a non-English locale, any topics with a synonym in the locale you're using will be displayed as the name
of the topic.

At some point I'll show the synonyms that match a search, so you'll know why you're seeing a topic
that matched on a synonym.
