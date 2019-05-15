---
id: 10744
title: 'EMWCon 2016 &#8211; some notes (day 2)'
date: 2016-05-26T09:00:29+00:00
author: gBRETTmiller
layout: post
guid: http://gbrettmiller.com/?p=10744
permalink: /2016/05/26/emwcon-2016-some-notes-day-2/
publicize_twitter_user:
  - gbrettmiller
  - gbrettmiller
  - gbrettmiller
publicize_google_plus_url:
  - https://plus.google.com/+GBrettMiller/posts/cV7hb2nU4uX
  - https://plus.google.com/+GBrettMiller/posts/cV7hb2nU4uX
  - https://plus.google.com/+GBrettMiller/posts/cV7hb2nU4uX
publicize_linkedin_url:
  - 'https://www.linkedin.com/updates?discuss=&scope=13627326&stype=M&topic=6141598728970133506&type=U&a=5Emk'
  - 'https://www.linkedin.com/updates?discuss=&scope=13627326&stype=M&topic=6141598728970133506&type=U&a=5Emk'
  - 'https://www.linkedin.com/updates?discuss=&scope=13627326&stype=M&topic=6141598728970133506&type=U&a=5Emk'
original_post_id:
  - "10691"
image: /wp-content/uploads/2016/05/emwcon_banner.jpg
categories:
  - Pound of Obscure
tags:
  - emwcon
  - emwcon 2016
  - enterprise mediawiki
  - enterprise mediawiki conference
  - liveblog
  - mediawiki
  - open source
  - open source software
---
Live-blogging (kind of) again, day 2. Also, [livestream](http://livestream.com/internetsociety/emwcon/).

**Notifications in MediaWiki**

<img class="alignnone size-full wp-image-10789" src="https://i0.wp.com/167.99.231.190/wp-content/uploads/2016/05/emwcon_yaron.jpg?resize=640%2C360" alt="EMWCon_yaron" width="640" height="360" srcset="https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_yaron.jpg?w=1267 1267w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_yaron.jpg?resize=300%2C169 300w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_yaron.jpg?resize=768%2C432 768w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_yaron.jpg?resize=1024%2C576 1024w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_yaron.jpg?resize=640%2C360 640w" sizes="(max-width: 640px) 100vw, 640px" data-recalc-dims="1" /> 

Yaron discussing the current status of notification (poor), and what would make an ideal notification system for MediaWiki. Page creation, edit, etc in different sets of pages, such as all pages, pages in namespace, etc, and certain people notified, e.g. users in a user group, specified list, users signed up to be notified, maybe external users via email.

Notification done by maybe email, [Extension:Echo](https://www.mediawiki.org/wiki/Extension:Echo), or custom webhook of some kind. Echo (you can see on mediawiki.org) is planned to be added into MW Core. Several other extensions rely on Echo.

Many potential pitfalls. Too few options not helpful, too many confusing. Regular users vs. admins vs. &#8220;superadmins&#8221;.

&#8220;Looked at SharePoint for bad notification design, and SharePoint didn&#8217;t disappoint.&#8221;

Google Summer of Code, Yaron is co-mentoring a project to create a &#8220;page notifications extension&#8221;, started this past Monday. Goal is to create a framework that covers all the possible options, to make notifications in MediaWiki useful.

Jason mentioned [Extension:Notificator](https://www.mediawiki.org/wiki/Extension:Notificator), which allows users to set up notifications of others. NASA&#8217;s [Enterprise Media Wiki](http://www.enterprisemediawiki.org) team released [Extension:WatchAnalytics](https://www.mediawiki.org/wiki/Extension:WatchAnalytics) and others that provide some insight into watching.

**Inside Wiki Sales**

<img class="alignnone size-full wp-image-10783" src="https://i0.wp.com/167.99.231.190/wp-content/uploads/2016/05/emwcon_am.jpg?resize=640%2C352" alt="EMWCON_am" width="640" height="352" srcset="https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_am.jpg?w=1117 1117w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_am.jpg?resize=300%2C165 300w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_am.jpg?resize=768%2C423 768w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_am.jpg?resize=1024%2C564 1024w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_am.jpg?resize=640%2C352 640w" sizes="(max-width: 640px) 100vw, 640px" data-recalc-dims="1" /> 

Angelika Müller from [Hallo Welt!](http://hallowelt.com/) talking about selling wiki services, especially [Blue Spice](http://bluespice.com/), their enterprise wiki distro. Covered the basic lifecycle of sales, from contact to requirements to estimates to doing the work and shipping the final product. Challenges include technical and organizational.

All development, as much as possible, should be customer driven. After all, they are the ones who know what they want.

Discussed some of their big use cases.

  * Wiki farms
  * Document management &#8211; they first ask, why not use a document management tool, why a wiki? Things to address &#8211; setting rights for files, managing and editing
  * Quality management

In many ways, the same challenges any design / development shop has, but some uniqueness based on the product (MediaWiki based).

A big topic of interest is how they are using WebDAV with MS Office to allow their users to edit / save MS Office documents in-place inside the wiki, instead of having to download &#8211; edit &#8211; save &#8211; upload the file.  This was developed as custom work for a group of customers who came together to fund it, with a restriction that the code for doing it could not be shared for one year (which is almost up).

Anja offered that their WebDAV developer will have a webinar next week to discuss with those who are interested.

**Lightning Talks**

**CWIX Wiki for Interoperability Testing**

An overview of the [CWIX 2016](http://www.act.nato.int/cwix) wiki.

**Making Cool Directories with MediaWiki**

Yaron showed some examples of &#8220;cool&#8221; directory sites. Can you do this with MediaWiki? Functionally, yes. Visually / UI, no.

Question: how can we make our display as cool as theirs? Important for external facing wikis, but can be useful and important internally as well.

Check out [migadv](http://migadv.com/). And MITRE&#8217;s [Gestalt](https://collaborate.mitre.org/gestalt/index.php/Main_Page).

Another option is to leverage the MediaWiki API to use MediaWiki as back end and build a custom front end using Javascript, etc.

**Social Semantic**

<img class="alignnone size-full wp-image-10784" src="https://i2.wp.com/167.99.231.190/wp-content/uploads/2016/05/emwcon_jb2.jpg?resize=640%2C387" alt="EMWCon_jb2" width="640" height="387" srcset="https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_jb2.jpg?w=1156 1156w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_jb2.jpg?resize=300%2C181 300w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_jb2.jpg?resize=768%2C464 768w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_jb2.jpg?resize=1024%2C619 1024w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_jb2.jpg?resize=640%2C387 640w" sizes="(max-width: 640px) 100vw, 640px" data-recalc-dims="1" /> 

Jason Bock sharing some of the things we&#8217;ve been working on using SMW for bringing some social features to MediaWiki. Started with a brief overview and history of milWiki (see [milSuite article](https://en.wikipedia.org/wiki/MilSuite) on Wikipedia) and installing SMW.

If you are going to use SMW, you should definitely use Semantic Forms. &#8220;Has default form&#8221; and &#8220;has alternate form&#8221; are crucial to make sure people are using forms to enter semantic data.

Create Templates based on Queries, makes it so the user doesn&#8217;t need to understand how to create queries, they can just use them. Browse pages are the most popular click from homepage, a fact of life in a hierarchical-minded organization. Query forms, with filters, provides an &#8220;Amazon&#8221; like search / filter experience.

A 12 step training guide for general users to learn how to use SMW to create their own projects, covers basic overview through the more complex concepts. Crucial if you want your users to be able to create their own solutions.

Three examples of user created semantic projects: IT ticketing system, app store, unit training.

**Lunch**

**Anatomy of a Cyber Taxonomy Development Wiki**

<img class="alignnone size-full wp-image-10781" src="https://i1.wp.com/167.99.231.190/wp-content/uploads/2016/05/emwcon_cc.jpg?resize=640%2C375" alt="EMWCon_cc" width="640" height="375" srcset="https://i0.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_cc.jpg?w=1309 1309w, https://i0.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_cc.jpg?resize=300%2C176 300w, https://i0.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_cc.jpg?resize=768%2C450 768w, https://i0.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_cc.jpg?resize=1024%2C600 1024w, https://i0.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_cc.jpg?resize=640%2C375 640w" sizes="(max-width: 640px) 100vw, 640px" data-recalc-dims="1" /> 

[Cindy Cicalese](https://www.mediawiki.org/wiki/User:Cindy.cicalese) from MITRE ([Extensions by MITRE](https://www.mediawiki.org/wiki/Category:Extensions_by_MITRE)). Demonstrated live at the [Malware ATtribute Enumeration and Characterization](https://collaborate.mitre.org/maec/index.php/Malware_Attribute_Enumeration_and_Characterization) wiki.

Purpose of the wiki is to help generate an ontology for describing malware. Includes consistant iconography to provide better navigation and visual indicators of what you&#8217;re looking at. Built around hiearchies to work ([hierarchy builder](https://www.mediawiki.org/wiki/Extension:HierarchyBuilder)?). Uses a combination of Cargo and SMW, but the only SMW still in use will ultimately be converted to Cargo. It is an example of how the two can coexist, use each where best suited. (nts: Cargo vs. SMW?)

The &#8220;Graph this page&#8221; option uses MITRE&#8217;s [VIKI](https://www.mediawiki.org/wiki/Extension:VIKI) extension. Very nice, reminds me of [The Brain](http://thebrain.com/).

Cindy walked through some key aspects of the site, how it&#8217;s structured and configured. Went down the rabbit hole of walking through some of the code. (I stood at the top of the hole and watched her walk around, a bit beyond my own current knowledge 🙂

**Contracting with the GPL**

<img class=" size-full wp-image-10774 aligncenter" src="https://i0.wp.com/167.99.231.190/wp-content/uploads/2016/05/emwcon_gr.jpg?resize=640%2C347" alt="EMWCon_gr" width="640" height="347" srcset="https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_gr.jpg?w=1206 1206w, https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_gr.jpg?resize=300%2C162 300w, https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_gr.jpg?resize=768%2C416 768w, https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_gr.jpg?resize=1024%2C554 1024w, https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_gr.jpg?resize=640%2C347 640w" sizes="(max-width: 640px) 100vw, 640px" data-recalc-dims="1" /> 

[Greg Rundlett](https://www.mediawiki.org/wiki/User:GregRundlett) talking about the challenges &#8211; and joys? &#8211; of doing MediaWiki work for large enterprise clients.

Challenge 1 &#8211; Lead time: Make sure lead time and discovery are in your pricing model

Challenge 2 &#8211; Payment: Large enterprises have set processes that may not be in your best interest. Negotiate for the best terms you can get (net 14 would be good).

Challenge 3 &#8211; Insurance: E&O (errors and omissions) and general liability

Challenge 4-6 &#8211; &#8220;All Your Base Are Belong to Us&#8221;. The challenge is how to convince the client to allow you to publish the custom work as GPL.

The &#8220;Master Services Agreement&#8221; is a standard contract, typically a take-it-or-leave-it thing. But, you should try to write details into the agreement where details are allowed. This is especially needed for the code, how much can you &#8220;keep&#8221; for reuse or publishing to open repos.

Collaboration and cooperation, more is needed among consultants in EMW space. _We aren&#8217;t competing against each other, we are competing against the Microsofts. _

Comment from Mark &#8211; we need more consultants like freephile as members of the MediaWiki stakeholders.

A bit of discussion &#8211; and disagreement &#8211; around GPL and how it applies to custom/proprietary code development.

**Lightning Talk**

Me &#8211; MediaWiki as part of larger Enterprise Social Network

**Technical Collaboration &#8211; WMF** 

<img class="alignnone size-full wp-image-10766 aligncenter" src="https://i2.wp.com/167.99.231.190/wp-content/uploads/2016/05/emwcon_ckoerner.jpg?resize=640%2C322" alt="EMWCon_ckoerner" width="640" height="322" srcset="https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_ckoerner.jpg?w=1366 1366w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_ckoerner.jpg?resize=300%2C151 300w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_ckoerner.jpg?resize=768%2C387 768w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_ckoerner.jpg?resize=1024%2C516 1024w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_ckoerner.jpg?resize=640%2C322 640w, https://i2.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_ckoerner.jpg?w=1280 1280w" sizes="(max-width: 640px) 100vw, 640px" data-recalc-dims="1" /> 

Chris Koerner providing some insight into the [technical collaboration team](https://meta.wikimedia.org/wiki/Technical_Collaboration) at WikiMedia Foundation.

The team primarily focuses on supporting the WMF and its official efforts, but they do take input from 3d party users and work on things that provide value to them as well.

[Phabricator](https://phabricator.wikimedia.org/) &#8211; bug tracking. Look at in more detail later.

The team hosts several events &#8211; [developer summit](https://www.mediawiki.org/wiki/Wikimedia_Developer_Summit_2016), [hackathons](https://www.mediawiki.org/wiki/Wikimedia_Hackathon_2016), [Wikimania](https://wikimania2016.wikimedia.org/wiki/Main_Page), and others. If you are doing good things with MediaWiki, let them know so they can get the word out.

**WMF &#8211; the ongoing saga**

General discussion of topics related to the WikiMedia Foundation. Didn&#8217;t catch it all, so no real notes here.