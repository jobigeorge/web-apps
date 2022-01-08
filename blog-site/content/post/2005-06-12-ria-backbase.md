---
layout:     post
title:      "Rich Internet Application Framework from Backbase"
subtitle:   ""
description: ""
excerpt: ""
date:       2005-06-12 11:00:00
author:     " Jobi George"
image:     "static/img/grey-transparent.jpg"
published: true
showtoc: false 
tags:
    - HTML
    - WEB
URL: "/2005/06/02/tibco-general-interface3/"
categories: [ Tech ]
---

> “Rich apps changing the internet”

Just ran across Backbase (http://www.backbase.com) a well designed thin script based U/I development framework. It uses an XML-based User Interface language and leverages XHTML, CSS and DOM. It requires no install /plugin/java/Flash and yet are very powerful. It also seem to work fine in IE and Firefox.

They use AJAX patterns heavily and leverage the browser XML namespace support.

### Demos -

* Shoping - New way to shop
* Portal - A new way to do responsive Portlets based U/I
* Google : Totally new way to experience search using Google API and using drag & drop to bookmark

Backbase has introduced BXML, a declarative GUI language. BXML consists of about 85 B-tags and over 200 attributes that can be freely mixed with HTML. They give the developer access to best practices in user interface design, while still augmenting existing web development skills. The Backbase Client transforms the B-tags into the proper HTML, CSS and JavaScript code, and it ensures compatibility with each browser. There are B-tags for many different purposes:

    * Defining the layout (panels, windows and decks)
    * Styling the interface (themes and skins)
    * Creating user interface controls (menus, tabs, trees, sliders, etc.)
    * Adding behaviors (display, hide, loading data, animations, etc.)
    * Including form functionality (conditional forms, input validation)


Extending the namespace support to clean up the page layout code seems to be in vogue. Another project [ Novell Xforms](http://ftp.novell.com/pub/forge/xforms-explorer/docs/home.html) is a cute project leveraging that for xform implementation.

Years ago I was part of the team that did the Xform 1.0 implementation that we contributed to [IBM Alphaworks site](http://www.alphaworks.ibm.com/tech/xmlforms) It formed the basis for some of the IBM products that are coming out with revised implementation. Given a second chance we would love to go back and redo it using namespaces and not IE Mime handler. 


##### Original Post

* Originally posted at [ Blogspot ](http://jobig.blogspot.com/2005/06/rich-internet-application-framework.html) on {{< param date >}}

