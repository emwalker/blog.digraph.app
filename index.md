---
layout: default
title: Ten thousand links and counting
---

# Ten thousand links and counting
<byline>Eric Walker, July 6, 2019</byline>

If you could keep track of everything slightly interesting that you read at one point on the Internet, about how many links would we talking about?

I can now attempt a ballpark estimate.  As you can see in this screenshot, since the time that Digraph emerged as an application that was actually useful, at the end of November 2018 (before it was hosted online), around 10,000 links and 4,000 topics have been added, almost all by one person (myself):

<img class="centered" width="550" alt="10,000 links" src="https://user-images.githubusercontent.com/760949/60759900-ab33b600-9fe9-11e9-9fd1-5e3e7b316601.png">

So over eight months that's 10,228 links — about 1,250 links per month, or about 15,000 links per year. Suppose I were to use Digraph over five years at the same level of activity.  I will have added about 75,000 links during that period.  I think I'm an outlier in wanting to be able to get back to everything I've read in the past, so discount that number by some fraction to get what might be the average per person.

How many links would I actually be able to track down again in the future if there was something that I vaguely recalled that I wanted to look at again?  An unscientific guess based on my experience over the last eight months is that I can find about 50 percent of such links with little effort and another 25 percent with more digging around.  The remaining 25 percent would require me to search Google.  Also anecdata: once I've searched for a link, and, seeing it miscategorized or inadequately categorized, and after I've added the topics that came to mind when I started looking for it, the link will be much easier to find during later attempts.

Having 4,219 topics means that topics now dominate Digraph search results, since they appear before links.  Having topics dominate search results is not necessarily a bad thing, because the desired link is often a click or two away when you follow a relevant topic.  But it does mean that if the topics were to increase by an order of magnitude or more, some decent ordering of topics in search results would be needed, in the manner of Google, in order not to be overwhelmed by a sea of slightly relevant topics.

If everyone in the world were to sign up for Digraph and start adding topics of their own, what would the upper bound on the number of topics be?  I think it would be in the neighborhood of some multiple of the number of Wikipedia articles, or the number of people in the world, or the number of proteins of scientific interest — so perhaps billions of topics in all.  There would be many technical challenges that would need to be addressed to keep Digraph useful as an app well before it reached that scale.

As one small example, there are now enough topics and links in the system that the topic graph that appears on the home page is no longer useful:

<img class="centered" width="550" alt="Topic graph" src="https://user-images.githubusercontent.com/760949/60760267-d7523580-9fef-11e9-8d38-3a3e0f347412.png">

This graph hints at why the app is called "Digraph" by showing how the topics are organized in a [directed acyclic graph](https://en.wikipedia.org/wiki/Directed_acyclic_graph).  It was originally intended to grab people's attention and give them a sense of how Digraph is keeping track of something subtly interesting and is more than just a directory for links.  But now the topic graph is mostly a blob that is difficult to navigate, and it will only become more of a blob as topics continue to be added. (And it causes the CPU fan to spin up.) So I plan to replace it with an understated landing page before too long.  The landing page will convey in simple terms one way that Digraph might be useful to the reader.  There are several use cases that I'm keeping in mind, which you can read about [here](https://github.com/emwalker/digraph/wiki).
