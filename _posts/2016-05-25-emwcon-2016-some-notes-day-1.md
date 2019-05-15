---
id: 10711
title: 'EMWCon 2016 &#8211; some notes (day 1)'
date: 2016-05-25T08:52:11+00:00
author: gBRETTmiller
layout: post
guid: http://gbrettmiller.com/?p=10711
permalink: /2016/05/25/emwcon-2016-some-notes-day-1/
publicize_twitter_user:
  - gbrettmiller
  - gbrettmiller
  - gbrettmiller
publicize_google_plus_url:
  - https://plus.google.com/+GBrettMiller/posts/f9Xb6v36duP
  - https://plus.google.com/+GBrettMiller/posts/f9Xb6v36duP
  - https://plus.google.com/+GBrettMiller/posts/f9Xb6v36duP
publicize_linkedin_url:
  - 'https://www.linkedin.com/updates?discuss=&scope=13627326&stype=M&topic=6141234309064908800&type=U&a=b_5t'
  - 'https://www.linkedin.com/updates?discuss=&scope=13627326&stype=M&topic=6141234309064908800&type=U&a=b_5t'
  - 'https://www.linkedin.com/updates?discuss=&scope=13627326&stype=M&topic=6141234309064908800&type=U&a=b_5t'
original_post_id:
  - "10691"
image: /wp-content/uploads/2016/05/emwcon_banner.jpg
categories:
  - Pound of Obscure
tags:
  - emwcon 2016
  - enterprise mediawiki
  - liveblog
  - mediawiki
  - nyc
---
A live blog (of sorts) for [Enterprise MediaWiki Conference (EMWCon) 2016](https://www.mediawiki.org/wiki/EMWCon_Spring_2016). The conference is also being [livestreamed](http://livestream.com/internetsociety/emwcon/).

## Panel &#8211; Towards a MediaWiki Foundation

<img class=" size-full wp-image-10741 aligncenter" src="https://i1.wp.com/167.99.231.190/wp-content/uploads/2016/05/emwcon_panel1.jpg?resize=640%2C322" alt="EMWCon_panel1" width="640" height="322" srcset="https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_panel1.jpg?w=1036 1036w, https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_panel1.jpg?resize=300%2C151 300w, https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_panel1.jpg?resize=768%2C386 768w, https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_panel1.jpg?resize=1024%2C515 1024w, https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_panel1.jpg?resize=640%2C322 640w" sizes="(max-width: 640px) 100vw, 640px" data-recalc-dims="1" /> 

Cindy Cicalese, Anja Ebersbach, Mark Hershberger, Chris Koerner, Yaron Koren

Panel discussion to address some of the challenges around the development, maintenance, and use of MediaWiki and related software (extensions). Not a discussion of separating Wikipedia ops from MediaWiki core (which would be something similar to how WordPress is set up).

Yaron presented a [case for a MediaWiki foundation](https://www.mediawiki.org/w/index.php?title=File:EMWCon_Spring_2016_-_EMW_Foundation.pdf) that would help fund &#8220;unfunded&#8221; software. Specifically, funnel money from the users of the software to the developers of the software. Similar to other open source &#8220;foundations&#8221;, example given was the Linux Foundation. aka pay to play.

Part of the challenge is that the Wikimedia foundation is focused almost exclusively on Wikipedia and their other projects. Desire is to make sure that the MediaWiki software remains usable by other 3d party users, and actually includes development specifically to meet the needs of those 3d party users. For example, the [MediaWiki Stakeholders Feature Wishlist](https://www.mediawiki.org/wiki/MediaWiki_Stakeholders%27_Group/Tasks/Feature_wishlist).

An interesting mess.

## Social Semantic

<img class="  wp-image-10739 aligncenter" src="https://i0.wp.com/167.99.231.190/wp-content/uploads/2016/05/emwcon_jcantroot.jpg?resize=559%2C419" alt="EMWCon_jCantRoot" width="559" height="419" srcset="https://i0.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_jcantroot.jpg?w=1040 1040w, https://i0.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_jcantroot.jpg?resize=300%2C225 300w, https://i0.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_jcantroot.jpg?resize=768%2C576 768w, https://i0.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_jcantroot.jpg?resize=1024%2C768 1024w, https://i0.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_jcantroot.jpg?resize=640%2C480 640w" sizes="(max-width: 559px) 100vw, 559px" data-recalc-dims="1" /> 

[Jason Bock](https://www.mediawiki.org/wiki/User:Jcantroot) talking about applying [SMW to achieve social objectives](https://www.mediawiki.org/wiki/File:Social_Semantic-_EMWCon_May_25_2016.pdf) on MediaWiki: standard profiles, rate/review articles, user point system, user badges. Shared some of the specific extensions used.

It is possible to create a template for userpages and have it pushed automatically, need to get user feedback on whether they like this or not. Some people prefer freeform userpage. Balance between user needs / desires and the enterprise&#8217;s needs.

All uses existing extensions, doesn&#8217;t require any development just &#8220;front end&#8221; SMW work. Walked through examples the &#8220;code&#8221; for each. This has potential to cause significant performance issues, will work to have some of this turned into extensions.

Questions about gamification: how do you handle cheating (don&#8217;t really), has it helped with adoption (with some people).

## Improving Enterprise Findability with SMW

Laurent looking at how SMW can be used to help people find answers to their questions.

&#8220;Searching doesn&#8217;t give you answers, it gives you search results.&#8221;

Use the wiki as a wiki; keep it lean and fast. Use APIs to access other systems. Such as WordPress.

## Lightning Talks

### 

### MediaWikiFarm extension

Nicolas Nallet talking about the [MediaWikiFarm extension](https://www.mediawiki.org/wiki/Extension:MediaWikiFarm). [Slides from the talk](https://www.mediawiki.org/wiki/File:MediaWikiFarm_Extension_Presentation.pdf).

### US Federal Government MediaWikis

[Peter Meyer](https://www.mediawiki.org/wiki/User:Econterms) talking about MediaWiki installations in U.S. Federal Government. [Full notes](https://www.mediawiki.org/wiki/User:Econterms/U.S._Federal_Government_MediaWikis). Something to follow up on &#8211; Federal MediaWiki Demonstration and Discussion Group, a monthly gathering to share ideas, practices, and demo ideas. A call for a more consistent coherent wiki policy across the Federal Government.

&#8220;Knowledge management is not a curse word.&#8221; &#8212; Peter Woudsma

## Lunch

## Wiki Farms (again)

Peter Woudsma. Reasons for multiple wikis: ownership, access, control, processing. Defined: MediaWiki server install that includes core and some extensions and supports multiple otherwise independent wikis. Went through an example putting three wikis on one MediaWiki server. Reasons to use common elements: data re-use, template re-use, branding, data processing (inter-wiki data data exchange, queries, transposition)

Question: how much is common to all wikis in the farm? Many possible options.

Discussion among the group about approaches they have taken.

&nbsp;

## SMW Factory

[Lex](https://www.semantic-mediawiki.org/wiki/User:Lex) Sulzer spoke about [SMW Factory](https://smw-cindykate.com/main/Component_947746). Offline, secure, encrypted, backup (and a bunch of other terms). Duplicity, Vagrant, Ansible (executable documentation). Details in the link. An easy way to &#8220;clone&#8221; a wiki soyou can work on it offline, then push changes back to production. (Meant for dev, not content.)

Ultimate goal &#8211; ability to have &#8220;offline&#8221; wikis that can be updated and merged back in with the main wiki. This would be huge. A project for Friday.

## <span style="line-height:1.7;">Single enterprise wiki</span>

[me](https://www.mediawiki.org/wiki/EMWCon_Spring_2016/Merits_and_Challenges_of_a_Single_Enterprise_Wiki)

## What&#8217;s new in Semantic Forms

Jaron giving an update.

Change 1 &#8211; Spreadsheet display. &#8220;display = spreadsheet&#8221; Each entry becomes a separate instance of  the template on the page. Less work for admins, allows for better HTML, such as <label> (important for accessibility)

Change 2 &#8211; Some input types moved from Semantic Forms Input extension to Semantic Forms, continues a process started with other input types. Few extensions, less work for admins and developers.

Semantic Forms is now its own thing, no longer requires Semantic MediaWiki.

Change 3 &#8211; removed some params, some of the long-deprecated parameters.

Thinking of changing the name, to reduce confusion with other &#8220;semantic&#8221; things.

Important takeaway &#8211; cleaning up Semantic Forms to make it better, easier for developers and admins.

Also discussed changes to Cargo (an alternative to SMW). Key feature of note (to me) &#8211; text search of articles.

## Opening Session

<img class="  wp-image-10722 aligncenter" src="https://i0.wp.com/167.99.231.190/wp-content/uploads/2016/05/emwcon_pw1.jpg?resize=582%2C320" alt="EMWCon_pw" width="582" height="320" srcset="https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_pw1.jpg?w=1040 1040w, https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_pw1.jpg?resize=300%2C165 300w, https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_pw1.jpg?resize=768%2C422 768w, https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_pw1.jpg?resize=1024%2C563 1024w, https://i1.wp.com/gbrettmiller.com/wp-content/uploads/2016/05/emwcon_pw1.jpg?resize=640%2C352 640w" sizes="(max-width: 582px) 100vw, 582px" data-recalc-dims="1" /> 

Peter Woudsma gave a quick overview of the history of MediaWiki in the enterprise and some of the challenges of taking a tool designed as an easy way to update content and making it useful and valuable at the enterprise level. A nice summary of Enterprise aspects of previous conferences, and the need for balance in discussing the non-technical aspects along with the technical.

He gave us quite a few questions, homework if you will, to consider as the conference progresses. Not just in how we use the tools, but how we influence the future development of the tools, and the support infrastructure.

Good discussion around the philosophy and implementation. Differences between what&#8217;s going on with MediaWiki software and WikiMedia. Need to show off who is using MediaWiki, and how they are using it. [WikiReport](http://www.freephile.org/wikireport).

Lex &#8211; SMW power user is critical to success. SMW is a digital co-worker.

## Introductions

Mix of corporate, government, and non-profit interests represented. People from several places in US and Europe (France, Germany, Switzerland).