---
layout:     post
title:      " WebSphere Browser Framework and Faces Client"
subtitle:   ""
description: ""
excerpt: ""
date:       2005-06-05 11:00:01
author:     " Jobi George"
image:     "static/img/grey-transparent.jpg"
published: true
showtoc: false 
tags:
    - Html
    - Web
    - Serverless
URL: "/2005/06/02/websphere-browser-framework/"
categories: [ Tech ]
---


WebSphere Browser Framework (now called Faces Client) for WebSphere Studio provides a set of JSF based U/I Controls and Data Emitters for doing Rich browser applications without server round trips. It provided client-side processing coupled with a client-side data model to reduce server and network loads and user wait times. The result: richly interactive Web applications utilizing JavaScript for client-side processing and data structuring without browser or client upgrades.

A key Browser Framework component is its structured data model that supports dynamic data manipulation -- meaning that data could be lately bounded and can be manipulated on the client, either by the user or through a Web service or other Web-based update mechanisms, without a page-refresh. We had a [ Eclipse Modelling Framework EMF Core classes ](http://www.eclipse.org/emf) based implementation. The [BF framework](https://web.archive.org/web/20061105102147/http://www-128.ibm.com/developerworks/web/library/wa-facescomp1/) also provides rich user interface controls that were tied to JSF based emitters -Twisty, TreeView, DataGrid, ListView, TabbedPanel, DatePicker, GraphDraw, and Dialog.

Some of the design aspects we talked about in our 2004 paper in IBM Systems Journal

Browser Framework used some of the design patterns that WebSites such as Flickr and Laslo are using today. I developed a javascript based generic interface for WebServices WSDL parsing and requester using Flash Player. Another cool component was the generic Chart component which used the Movie concept to Flash Player to paint Pie, Line and Bar Charts without server round trips

Here is an image of some of the controls and a portal app - ![Portlet in works]( https://web.archive.org/web/20070320035308im_/http://www-128.ibm.com/developerworks/web/library/wa-facescomp1/banking_page.gif )



##### Original Post

* Originally posted at [ Blogspot ](http://jobig.blogspot.com/2005/06/websphere-browser-framework-and-faces.html) on {{< param date >}}

