---
id: 11193
title: WebDAV and MediaWiki
date: 2016-06-16T23:17:58+00:00
author: gBRETTmiller
excerpt: 'Using WebDAV integration with MediaWiki provides a much more user friendly experience for uploading and working with files on MediaWiki. '
layout: post
guid: http://gbrettmiller.com/?p=11193
permalink: /2016/06/16/webdav-and-mediawiki/
publicize_google_plus_url:
  - https://plus.google.com/+GBrettMiller/posts/EDsY6NaDY5K
  - https://plus.google.com/+GBrettMiller/posts/EDsY6NaDY5K
  - https://plus.google.com/+GBrettMiller/posts/EDsY6NaDY5K
publicize_twitter_user:
  - gbrettmiller
  - gbrettmiller
  - gbrettmiller
publicize_linkedin_url:
  - 'https://www.linkedin.com/updates?discuss=&scope=13627326&stype=M&topic=6149424661466800128&type=U&a=1n_B'
  - 'https://www.linkedin.com/updates?discuss=&scope=13627326&stype=M&topic=6149424661466800128&type=U&a=1n_B'
  - 'https://www.linkedin.com/updates?discuss=&scope=13627326&stype=M&topic=6149424661466800128&type=U&a=1n_B'
original_post_id:
  - "11117"
categories:
  - Pound of Obscure
tags:
  - blue spice
  - emwcon
  - emwcon 2016
  - enterprise mediawiki
  - hallo welt!
  - mediawiki
  - webdav
---
A few weeks back at [EMWCon 2016](https://gbrettmiller.com/2016/05/26/emwcon-2016-some-notes-day-2/), Angelika Müller from [Hallo Welt!](http://hallowelt.com/) spoke about the sales life cycle for enterprise wiki services, featuring their  [Blue Spice](http://bluespice.com/) MediaWiki Enterprise Distribution. During her talk, Angelika hinted at a project they had completed for some customers* involving [WebDAV](http://www.webdav.org/). Unfortunately, the constraints of that engagement prevented them from speaking openly about it at the conference; the one year &#8220;gag order&#8221; was set to expire a few days **after** the conference.

<img class=" size-full wp-image-11264 alignright" src="https://i0.wp.com/167.99.231.190/wp-content/uploads/2016/06/wikidav01.png?resize=320%2C240" alt="wikiDAV0.png" width="320" height="240" srcset="https://i0.wp.com/gbrettmiller.com/wp-content/uploads/2016/06/wikidav01.png?w=320 320w, https://i0.wp.com/gbrettmiller.com/wp-content/uploads/2016/06/wikidav01.png?resize=300%2C225 300w" sizes="(max-width: 320px) 100vw, 320px" data-recalc-dims="1" /> Well, that gag order is up and the Blue Spice team invited us to join a webinar today to show of what they&#8217;ve done. Very cool stuff. _(I have some screengrabs from the webinar, but they are on a different computer. I will add them in tomorrow.) _

The webinar was a demo conducted by [Markus Glaser](https://twitter.com/mrglaser) from the Blue Spice team, showing off how the WebDAV integration with [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki), through Blue Spice, works. For those not familiar, WebDAV

> stands for &#8220;Web-based Distributed Authoring and Versioning&#8221;. It is a set of extensions to the HTTP protocol which allows users to collaboratively edit and manage files on remote web servers.

Basically, it lets you interact with files on a remote web server as if they were local files. In the enterprise this typically means Microsoft Office files from a Windows computer.

To start the demo, Markus showed how you can access a wiki through Windows Explorer, with the ability to open and edit the actual wiki articles. Though this is a cool feature, as Markus noted it not an especially interesting use case. Opening a page and editing it on a text editor on your computer will be slower and more cumbersome than simply editing the page on the wiki, and you will still need to use wikitext for the content.

The really interesting, and valuable, aspect of WebDAV integration with wiki goes back to those MS Office files. With the access to the wiki through Windows Explorer, you can directly add files to the wiki through your computer file system. For example by dragging and dropping from another folder, or simply saving a new file to the Media folder (aka namespace) on the wiki.

In addition to adding files through Explorer you can open, edit, and save the file as if the file were stored locally on your computer. Which is, of course, what WebDAV does. The really great part, though, was that you can also open the file from within the wiki, edit it, and save it directly back to the wiki. No downloading, editing, and then uploading again. If you&#8217;ve ever had to do that, you know how nice this feature is. In both cases, the versioning info is maintained on the file&#8217;s wiki page.

One of the challenges with the way MediaWiki handles files, of course, is that they typically all go into a single namespace, such as &#8220;File&#8221;. Not only does this make it hard to keep things organized, all of the files have the same permissions. To address this, Markus demonstrated the [Extension:NSFileRepo](https://www.mediawiki.org/wiki/Extension:NSFileRepo) in action.

> The **NSFileRepo** extension restricts access to upload and read files and images to a given set of user groups associated with protected namespaces. Using this extension (within the security limitations noted above), you can protect not only pages and areas of your wiki, but also any uploaded images or files within those namespaces.

The WebDAV integration can be used on a &#8220;vanilla&#8221; MediaWiki install, but some of the features Markus demonstrated today are specific to Blue Spice. Installation is a bit more involved than simply installing an extension; the way that WebDAV works requires some web server configuration as well.

**tl;dr** Using WebDAV integration with MediaWiki provides a much more user friendly experience for uploading and working with files on MediaWiki.

<p class="jetpack-slideshow-noscript robots-nocontent">
  This slideshow requires JavaScript.
</p>

<div id="gallery-11193-1-slideshow" class="slideshow-window jetpack-slideshow slideshow-black" data-trans="fade" data-autostart="1" data-gallery="[{&quot;src&quot;:&quot;http:\/\/gbrettmiller.com\/wp-content\/uploads\/2016\/06\/wikidav.png&quot;,&quot;id&quot;:&quot;11258&quot;,&quot;title&quot;:&quot;wikiDAV&quot;,&quot;alt&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;itemprop&quot;:&quot;image&quot;},{&quot;src&quot;:&quot;http:\/\/gbrettmiller.com\/wp-content\/uploads\/2016\/06\/wikidav2.png&quot;,&quot;id&quot;:&quot;11260&quot;,&quot;title&quot;:&quot;wikiDAV2&quot;,&quot;alt&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;itemprop&quot;:&quot;image&quot;},{&quot;src&quot;:&quot;http:\/\/gbrettmiller.com\/wp-content\/uploads\/2016\/06\/wikidav3.png&quot;,&quot;id&quot;:&quot;11261&quot;,&quot;title&quot;:&quot;wikiDAV3&quot;,&quot;alt&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;itemprop&quot;:&quot;image&quot;},{&quot;src&quot;:&quot;http:\/\/gbrettmiller.com\/wp-content\/uploads\/2016\/06\/wikidav4.png&quot;,&quot;id&quot;:&quot;11262&quot;,&quot;title&quot;:&quot;wikiDAV4&quot;,&quot;alt&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;itemprop&quot;:&quot;image&quot;}]" itemscope itemtype="https://schema.org/ImageGallery">
</div>

_* They built the WebDAV integration as a crowdsourced project, where several customers contributed to the project to ensure it was fully funded. Those customers agreed to making the project available to general customers, but only after a certain amount of time (a year) had passed. An interesting approach to getting open source work funded, one I&#8217;ll probably come back to again later. _