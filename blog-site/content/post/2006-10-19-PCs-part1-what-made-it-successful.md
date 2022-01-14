---
layout:     post
title:      "PCs and web2.0 : Part 1 What made PCs so successful"
subtitle:   ""
description: ""
excerpt: ""
date:       2006-10-19 11:00:00
author:     " Jobi George"
image:     "static/img/grey-transparent.jpg"
published: true
showtoc: false 
tags:
    - Strategy
    - Ecosystem
    - Business
URL: "/2006/10/19/personal-computers-part1"
categories: [ Business ]
---

There is enough written about the PCs' success and the overall impact it has had over decades. PCs are attributed to increased productivity, economic gains, and the creation of the Information Technology business. I don't have to delve into it very much. I am looking at PCs and their role in the changing landscape of services-based applications, call it [web2.0](http://www.oreillynet.com/pub/a/oreilly/tim/news/2005/09/30/what-is-web-20.html), SOA, or some flavor of SaaS. I am using the term PCs very loosely to refer PC

PCs became successful because they were the ultimate **“Multiple-Application”** player. Before PCs, compute capability was something that people with halos around their heads worked on in the safety of cold-closed enclosures. PCs changed all that; suddenly, everybody had a platform on top of which they could write real-world applications that solved real needs. It resulted in overall [productivity](http://web.gsm.uci.edu/%7Egurbaxan/Productivity%20and%20the%20PC%20Revolution.pdf#search=%22How%20PC%20changed%20Productivity%20Economy%22%29%20but%20also%20gave%20us%20the%20massive%20Y2K%20spending) and also gave us multiple booms, including the massive Y2K spending.

But since the real PC innovation of the early 80s, things have not changed much. If you look at various citing on the history of PC, almost all of them stop around  [1985s](http://inventors.about.com/library/blcoindex.htm). WWe had the Linux revolution, but the fundamental physical form factor and H/W Spec never changed.

PC brought computing to the common masses and hence replicated (in small form) the compute characteristics of standalone mainframes. It provided a steady platform for innovation at the application level tied to the operating systems. The client-server world of applications design was always tuned towards replicating portions of computation and then doing some form of update between clients and server to get applications to work together. But for all practical purpose, they were individual units of compute. These PCs were not inherently designed to be working in the connected world. Windows for Workgroup (3.11) was almost an afterthought.

The PCs of the 90s performed three critical tasks. Its principal role used to be that of **executing application**. The process by which a computer grinds through the bits of logical commands interprets and produces intelligent stuff. Things that made Word run and PhotoShop do their magic.

Client PC needed to support an **"interaction interface,"** its second significant role by its very nature. The I/O interface made the computer understand humans and understand what the computer did.

The third important role it provides is that of an **information repository** (mainly file store today). The repository to stores your life at home and vital files/data that makes businesses work

These are the three roles -  **Application Execute, Interaction and Storage**.

Even the advent of networking did not change this much. Before networking, client-server compute meant you carried around physical copies of data, and now in the networked world, you could start each client node as an extension of the file system from the server and vice versa. (Even that was not seamless, though…topic for some other day)

The advent of the web browser and the pervasiveness of the internet (now called web 1.0) did not change that much either. All it did was allow distributed client nodes to uniquely point and click stuff on the other end. Now you could uniquely access files published anywhere on the world wide web and bring them to your machine for viewing or manipulating. The user experience was still very limited and was constrained by the requirements that the files had to work in a uniform way across multiple platforms and operating systems. So browser took the easy route-target the least common denominator. [AJAX](http://adaptivepath.com/publications/essays/archives/000385.php) changes that a bit and is finally trying to bring client-server compute to the browser.

One of the most important things Internet's popularity of HTML/Script showed was the real potential of separating User Interface (HTML) from code (JavaScript). The critics would argue HTML was not the first, but HTML brought it to the masses. Technology that is not for the masses is useless. I have seen enough of that in my days at IBM Watson labs. Style sheets and DOM finally drove the point home that separating U/I from the inherent logic has enormous potential to address transformation and scale and support personalization. This is the groundwork that started us towards loosely binded U/Is. Finally, mashups are ready to take over where the promises of Composite Application left.

What web2.0 drove home very clearly, but the other industry trends like XUL, Laszlo, JSF, ASP+ were already doing was this notion of separating U/I from code. Coding U/I in a declarative form that could be processed independent of the application logic has become the cornerstone for U/I rendering, including FLEX & [XAML](http://en.wikipedia.org/wiki/XAML). And with the pervasive connectivity and increasing broadband adoption, consumers now have a thicker/faster pipe coming the last mile. We now have the perfect ingredient to **start separating the Application, Storage** and **Interaction** finally.

Suddenly you are in a situation where Application Execute could be separated from Interaction and Storage could be distributed. Now PCs don't have to do the role of data repository & application execution engine. Browsers have taken it upon themselves to fulfill the part of platform and OS agnostic interaction engine. And there are anecdotal pieces of evidence that we are slowly moving toward that. For example, this[Business Week](http://www.businessweek.com/technology/tech_stats/software060316.htm) article says that in the last year the two niches in which PC Software have done very well (except OS) include "Security" (things you buy to make sure you have a working PC next time you want to do something useful) and PC Games. (One exception is the Turbo Tax which shows people still worry about where their sensitive data resides. But it could be a very US/Western phenomenon)

With pervasive connectivity and programming models that are easy to separate application, data storage, and interaction, it makes a lot of sense to pull some of the computation back into the cloud. You have a better view of the application, and one can make faster adaptive applications".

The trend towards accessing *"Applications Anywhere Anytime" *will continue. That means applications need to scale/adjust to all device forms and interactions. It also means that applications cannot assume their interaction type. This example of[Google Earth](http://earth.google.com/), where users have come up with a new way to interact with [Google Earth], is an excellent showcase of this capability. Indeed, we will have richer interactions happening as more and more content is created and the edge nodes start getting sucked into the cloud.

Also, separating data that can sit in the cloud allows all forms of ways in which data can be used (Maybe that is what Tim means when he says, **“[Data is the next Intel Inside”](http://www.oreillynet.com/pub/a/oreilly/tim/news/2005/09/30/what-is-web-20.html?page=3)**). Interaction is the glue that connects the user to the machine and will always be at the edge, and there sits the most significant opportunity for an edge compute device or the **"new PC"**

***All is not lost for the old PC more on that next week……***


_______________
Originally posted at 
[ Blogspot ](http://jobig.blogspot.com/2006/10/pcs-and-web20-part-1-what-made-pcs-so.html) 
on **{{< param date >}}** 