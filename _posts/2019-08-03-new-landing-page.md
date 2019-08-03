---
layout: default
title: New landing page
permalink: 2019-08-03-new-landing-page.html
---

# New landing page
<byline>Eric Walker, August 3, 2019</byline>

The landing page of [Digraph](https://digraph.app/) has been updated to contain a brief description of the main use case together with some recent activity:

<img class="centered py-3" width="550" alt="New landing page" src="https://user-images.githubusercontent.com/760949/62417519-ef2cd180-b60e-11e9-84ef-9121d7b6acbd.png">


Previously the page had a 3D chart that allowed you to see all of the topics and how they related to one another.  But the topics have grown to over 4,000, and the chart had become unwieldy.  The usual landing page for a SaaS app serves as a kind of billboard and has marketing copy and graphics.  But for the moment I want to keep Digraph's landing page understated.  The app is a side project at this point, built out little by little during my free time, and I want to avoid telegraphing larger ambitions.

Landing pages for decent apps invariably load very quickly, and in order to keep things snappy while incorporating data from the API, I decided to refactor the app to make use of server-side rendering.  A nice side effect is that all of the pages now feel like static pages.

In addition to the main use case, saving personal bookmarks, other use cases are described [here](https://github.com/emwalker/digraph/wiki).
