---
layout: default
permalink: 2019-05-25-the-problem-of-antimicrobial-resistance.html
---

# The problem of antimicrobial resistance
<byline>Eric Walker, May 25, 2019</byline>

Each day I open an email in my inbox with the title "Google Alerts" and follow dozens of links.
The links are to articles that Google has discovered that match keyword searches like
"Carbapenem resistant," "MRSA" and "superbug." Each link brings up an article from *Vox*, the
*New York Times* or *The Guardian*, or, more often, lesser-known sites such as *Bovine Veterinarian* and
*KRTV Great Falls News*.

The articles discuss the growing problem of antimicrobial resistance. The
antibiotics we've relied on and taken for granted since the 1940s to make surgery and
recovery from cuts and grazes straightforward are gradually losing their effectiveness. Instead
of recovering quickly, a young man
who fractures his foot might
[die of a drug-resistant infection](https://digraph.app/wiki/topics/5f99db26-bc1e-4a87-ba16-6a5d2eb87999)
a few days later, because doctors are unable to find an antibiotic that can deal with the infection in time.
I read or skim through the articles in the email, and, if they look like they might
be of interest to others, I enter the URL into a form on Reddit and submit the link to the
[r/DrugResistanceBugs](https://www.reddit.com/r/drugresistantbugs), a forum I started a few
weeks ago.

Here I'm going to set out some of the things I've learned in the course of this project as well as
how it relates to [Digraph](https://digraph.app), the tool I'm using to keep track of everything.

## Antimicrobial resistance

There are at least three broad categories of microscopic creatures that are trying to kill us: bacteria,
viruses and fungi.  We use antibiotics to keep bacteria under control, vaccines to protect
against viruses and fungicides to kill fungi.  When we talk about "antimicrobial resistance," or AMR
for short, we're generally talking about bacteria and fungi.

We've had reason to worry about about the threat of
[antibiotic resistance](https://digraph.app/wiki/topics/08896547-9923-4667-946c-c62a42baf939)
since the dawn of antibiotics.  Our bodies are teeming with bacteria, good and bad, and antibiotics
kill not only the undesirable bacteria, but also the desirable kind as well.
Use of an antibiotic has two important side effects.  First, it accelerates evolution, selecting for any small fraction
of the target bacteria that we might be trying to get rid of that has some kind of trick that will
thwart the antibiotic. Second, by killing off the good bacteria, a space is created for any
remaining bacteria to take over.

The threat of antifungal resistance is only gradually gaining attention, most recently with an outbreak of
[pan-resistant Candida auris](https://digraph.app/wiki/topics/ad502ce4-022e-4e18-be00-c6ffa9e2c5a5), a lethal strain of
Candida. It was an [article in the New York Times](https://www.nytimes.com/2019/04/06/health/drug-resistant-candida-auris.html)
on this topic that motivated me to start this project.  In 2018, *The Atlantic*
[ran a story](https://www.theatlantic.com/science/archive/2018/11/when-tulips-kill/574489/) about
another fungus, *Aspergillus fumigatus*, which has been killing not only tulips in the Netherlands
but also immunocompromised hospital residents as well.

The U.N. Interagency Coordination Group on Antimicrobial Resistance
[estimates](https://digraph.app/wiki/topics/44632072-dc30-45c7-84a2-a0620dda3682) that by 2050 as many as 10
million people could die each year from complications arising from antimicrobial resistance if the
world does not step up to the challenge.  Strains with names like
[E. faecalis](https://digraph.app/wiki/topics/83ed17bf-ea22-485f-9821-274a832b2ac0),
[C. difficile](https://digraph.app/wiki/topics/c99c06ba-3f30-4e00-8490-ef4c460d3466),
[Shigella](https://digraph.app/wiki/topics/603d0ab7-90cd-448c-85ba-aa15ac596599),
[A. baumannii](https://digraph.app/wiki/topics/c9ccd0b2-02ab-428b-96ef-8ccb7934d4b2),
[Enterobacteriaceae](https://digraph.app/wiki/topics/7c68815b-0d50-4f7f-9b39-d586bc02d2bb),
[Klebsiella](https://digraph.app/wiki/topics/e607870d-40df-4907-adfb-e5df2f3b8d27),
[P. aeruginosa](https://digraph.app/wiki/topics/6cddcc4c-a09f-40f3-b944-0c1cdd19d4cb) and
[MRSA](https://digraph.app/wiki/topics/67534341-7352-437f-89ef-c019d3de5f5e) are already a big challenge
to deal with, especially in developing countries, where the rates of infection by drug-resistant bugs
are relatively high.

Antibiotic and antifungal resistance both arise in similar conditions, with resistant bacterial infections
a much bigger problem at the moment. Resistance is created through the
[misuse of antibiotics](https://digraph.app/wiki/topics/83e5fcce-97bc-4c26-b32b-9494376ea623) and
[antifungals](https://digraph.app/wiki/topics/2f3c6351-74b7-4d40-b3f7-8a0b9d2f281d) in humans, when, for example,
antibiotics are over-prescribed or not taken through a full course. In addition, when someone arrives at a hospital
and is deathly ill, an antibiotic will often be prescribed on the basis of symptoms alone,
before the infection has been accurately identified, in the hope that it will deal with the infection.
Bacteria are transmitted to humans via
[privacy curtains](https://digraph.app/wiki/topics/a2bb20c1-3e9a-4f00-823b-c5a74de0cbea),
[dirty hands](https://digraph.app/wiki/topics/3f6e143c-6660-487b-901d-7de58abcb05b),
[stethoscopes](https://digraph.app/wiki/topics/3ebe5045-0e39-4895-8765-c07879a0bf59) and
[endoscopes](https://digraph.app/wiki/topics/5ec157a0-7726-4acc-9946-b4b7e68e9f90), among other things.

Resistance is also thought to arise in the context of
[industrial agriculture](https://digraph.app/wiki/topics/9bba852b-3451-42ba-9dc6-3d1a9c3fa5ae).
Farm animals are routinely given medically important antibiotics in their feed and drinking water.
This is done partly to protect against the
kinds of infections that occur under cramped and unsanitary conditions.  But farm animals are also given
antibiotics to fatten them up and to accelerate their growth; why this works is not yet understood.  But the
routine use of antibiotics turns large scale farms into Petri dishes for the development of new drug-resistant
strains of bacteria.

The situation with antifungals is perhaps more worrying. In the case of antibiotics, there are numerous varieties
that can be used and others under active development.  As resistance arises in one antibiotic, there is a
possibility that an infection will respond to another, possibly somewhat toxic, antibiotic.  In the case of
fungicides, there are only three man classes that are currently available, so there are effectively no backups.

Which has more impact on the development of antibiotic and antifungal resistance — the misuse of antimicrobials
in humans in a medical context, or the routine use of antimicrobials in an agricultural context?  This is
a question that is still being investigated, and the answer will probably depend on the specific medically
important antibiotic or fungicide in question.

There's an even more vexing problem. It seems that existing market mechanisms [do not provide adequate
incentives](https://digraph.app/wiki/topics/83bf2e85-05b6-44db-b04a-11b433026cc6) for pharmaceutical makers
to research and invest in new antimicrobials. As one example, the startup
[Achaogen](https://digraph.app/wiki/topics/d1c0a5ca-2170-4436-a8ad-b0074e0a6695), which had a promising new
antibiotic, could not cover its expenses and filed for bankruptcy.  Over the last few decades, more and more
pharmaceutical companies have ceased researching new antibiotics, and now only a handful continue.

There are a number of strategies that can be used to address the problem of antibiotic resistance. These
include simple things such as educating hospital workers about the need for washing their hands with soap,
as well as more challenging approaches, such as attempting to adjust market incentives for the development of
new antimicrobials.  Technological strategies include
robots that go from room to room in a hospital, disinfecting the room with
[ultraviolet light](https://digraph.app/wiki/topics/2b8e2aab-fad3-47e1-80c8-249f9a188a85)
while no one is around.  An important strategy is that of
[antimicrobial stewardship](https://digraph.app/wiki/topics/388e6187-2052-4e62-9147-ade2ef002a4f), a
careful set of controls around the use antibiotics so that they continue to be effective.

## Antimicrobial resistance, Digraph and Reddit

This description only scratches the surface. We won't get into some
[Civil War–era medicinal plants](https://digraph.app/wiki/topics/1cc739a8-577f-4ec9-b4a4-27e8a1efecb0) that
show promise, the [use of phages](https://digraph.app/wiki/topics/8c443fc2-c1d0-4c3e-8b46-9a8765495b92)
to selectively attack specific strains of bacteria, or some of the
[mechanisms](https://digraph.app/wiki/topics/eb03df6d-6a6f-4d05-b28a-ee46c25163ee) that are thought to
underlie the development of antimicrobial resistance.  No matter how deep you go into a question, there always
seems to be a [more specific topic](https://digraph.app/wiki/topics/68b5f8e4-f4eb-4982-89f8-404163e38c9c)
that looks at some aspect in even greater detail.

This research confirms for me what you might call the fractal nature of knowledge. However far
you zoom in to a topic, you can often zoom in even further, subject only to the limitations of what
science has discovered so far.  The topics discussed above were arrived at empirically, through a process of
anthropological observation of the language used by medical professionals and journalists, of asking what
buckets an article might be placed in, and whether there were any recurring themes that had not yet been noted.

How do you capture all of that information in a form that can be revisited later on without too much difficulty,
and is there a way to make the process collaborative?  These are some of the questions that motivated me
to write Digraph.

Another thing that I wanted to be able to do was to have a place to put every link I came across,
so that I didn't have to be selective.  If there's a link that's vaguely relevant or interesting, I wanted
there to be a place for it, without having to make a judgment at that time about whether to keep it around or
not.  From the outset I had a sense, and I now better appreciate, just how many articles there are out there
in the world. On a given topic, some articles describe studies, some summarize the studies, some of
them summarize the summaries, some of them reprint the summaries verbatim, and yet others give broad overviews
many weeks later.  How do you both keep all those links around, and also make things easy to navigate and
find later on?  Part of the answer must involve filters of different kinds.  This article was in a quality
publication, so sort it to the top.  This other article was a reprint of an earlier one, so filter it out
by default.  None of these or other filters have been added yet, so things are still a little bit messy.

Going through the daily emails from Google, sifting through the articles and putting them up on
r/DrugResistanceBugs on Reddit has been a useful exercise.  It has helped me to better understand what
features to prioritize and build out in Digraph, and I think I'll continue to do it for a little while
longer.
