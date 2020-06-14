---
layout: default
title: Classifying ideas
permalink: 2020-next-classifying-ideas.html
---

# Classifying ideas
<byline>Eric Walker, TBD</byline>

- Wikipedia is doing something kind of amazing with the categories at the bottom of the page and in the articles that group together other articles on a general topic. They've gone beyond [Linnaeas](https://en.wikipedia.org/wiki/Linnaean_taxonomy), who focused on plants, animals and minerals.  In the case of Wikipedia, they're classifying every *idea* that people use and rely on in modern life.

- This is trickier than it might seem.  Suppose you want to create a topic like "South China Sea".  You can place this under a topic like "Oceans and seas," which works.  But we can't place "Oceans and seas" as it is currently named under a topic for "Earth," because Jupiter's moon Europa also has seas.  So to make the association we initially wanted to make, we should rename the topic "Earth's oceans and seas."  In this way, things can become very general.

- The Director of National Intelligence heads the United States Intelligence Community (IC).  Does the directorship belong beneath this topic, or above it?
  → Above: any time you search within DNI, you want to know what's going on in the agency it's overseeing
  → Below: the activities of the DNI are a small part of what's going on in the larger IC, and we also want to see DNI-related topics and links whenever we search within IC
  → Let's go with "below".

- A [formal ontology](https://en.wikipedia.org/wiki/Ontology_(information_science)) will be too slow-moving and inflexible for what we need here.  We need to be able to create new topics on demand and gradually iterate on their names and structures as we learn more about a domain.

- We want to organically infer the superset-subset relationships from thinking about what would be useful in search results.

- Often the superset-subset relationship is straightforward and intuitive.  In corner cases it seems forced.  How do you deal with "Mel Gibson" → "Movies directed by Mel Gibson" → "Apocalypto" → "Rudy Youngblood"?  We don't want everything about Rudy Youngblood to show up under Mel Gibson, especially if Youngblood were ever to direct a film that Gibson played a role in (as an example).  The solution here is to name the topic something like "Rudy Youngblood and Apocalypto".  But it's not always as easy to sort out as this.

- Why not use something like RDF, which in general does not assume that every entity is a subset or superset of another entity?  (1) We want to keep things simple and easy to use and evolve, and RDF allows too many possibilities for what we need.  (2) We want to be able to take two topics, obtain their intersection, and have the number of documents in the result be smaller than the number in either of the two initial topics.  Enforcing a superset-subset replationship as the main organizing principle helps us to accomplish both of these goals.

- One possible exception to the above idea is that there are entities that we find recurring over and over: people, organizations, events in history, acts of congress, court cases, publications.  For each kind of entity, we've been making collection topics (e.g., United States Supreme Court cases).  Could we avoid the boilerplate topics if we provided a range of possible types when creating a new topic and then automatically grouped them in suitable collections under the parent topic?


