---
id: 225
title: Benefits of WinFS explained
date: 2003-11-22T10:11:00+00:00
author: gBRETTmiller
layout: post
guid: http://nsl.gbrettmiller.com/2003/benefits-of-winfs-explained
permalink: /2003/11/22/benefits-of-winfs-explained/
tags:
  - Mastery
blogger_blog:
  - nsl.blogspot.com
  - nsl.blogspot.com
  - nsl.blogspot.com
blogger_author:
  - Brett
  - Brett
  - Brett
blogger_permalink:
  - /2003/11/benefits-of-winfs-explained.html
  - /2003/11/benefits-of-winfs-explained.html
  - /2003/11/benefits-of-winfs-explained.html
original_post_id:
  - "225"
  - "225"
  - "225"
  - "225"
  - "10086"
categories:
  - Pound of Obscure
---
Another good article from [Ray Ozzie](http://www.ozzie.net), this one called [640K Ought to be Enough for Anyone](http://www.ozzie.net/blog/stories/2003/11/14/640kbOughtToBeEnoughForAnyone.html) discussing the potential of [WinFS](http://msdn.microsoft.com/Longhorn/understanding/pillars/WinFS/default.aspx), the storage scheme for the next Windows OS, code-named [Longhorn](http://msdn.microsoft.com/longhorn). Well worth reading the whole thing, here is a key clip:  


> In a pre-WinFS world, each application has managed its own &#8220;documents&#8221; and &#8220;records&#8221; and &#8220;collections&#8221; as an island unto itself &#8211; each with its own indexing and interaction mechanisms, each with its own solution-building mechanisms. Good &#8216;nuf. But in a WinFS world &#8211; just like in a Web Services world &#8211; we have the opportunity to explore what would happen if we dared to &#8220;deconstruct and refactor&#8221; our concepts of traditional client-side applications into a mesh of separately-built application components that &#8220;meet&#8221; at the level of common persistent objects and relationships.

From the [WinFS](http://msdn.microsoft.com/Longhorn/understanding/pillars/WinFS/default.aspx) site is this description:

> &#8220;WinFS&#8221; is the code name for the next generation storage platform in Windows &#8220;Longhorn.&#8221; Taking advantage of database technologies, Microsoft is advancing the file system into an integrated store for file data, relational data, and XML data. Windows users will have intuitive new ways to find, relate, and act on their information, regardless of what application creates the data. Also, &#8220;WinFS&#8221; will have built-in support for multi-master data synchronization across other Longhorn machines and other data sources.

For more details on WinFS, check out the site.

Ray also goes off on a bit of a tangent exploring the debate between &#8220;rich&#8221; and &#8220;thin&#8221; clients. In my experience, many people have a tendency to want one or the other almost exclusively. Of course, what they really want is just a single interface to everything.