---
comments: true
date: 2011-04-13 19:35:55
layout: post
slug: useful-bookmarklets-for-your-ipad-and-iphone
title: Useful Bookmarklets for your iPad and iPhone
wordpress_id: 20187
categories:
- informatica
tags:
- iphone
- ipad
type: draft 

---

>
Here’s a comprehensive list of useful bookmarklets that you can easily add to the mobile Safari browser of your iPhone, iPad and iPod Touch. With bookmarklets, you can translate web pages, make them more readable, find word meanings and more.


![bookmarklets for iphone and ipad][1]

Unlike most desktop browsers, the Safari browser of your iOS device doesn’t support extensions but you can still add extra functionality to the browser with the help of bookmarklets. These are single-line codes that look like regular bookmarks but slightly more intelligent as they can help you translate sites, find word meanings, make pages more readable and so on – all with a single click.

I’ve covered [bookmarklets][2] before and they should also work with your iPhone, iPad or iPod Touch but there’s one problem – how do you install bookmarklets? In the case of Chrome or Firefox, you could have simply dragged and dropped them onto the bookmarks toolbar but unfortunately, the mobile Safari browser doesn’t support drag and drop.

**How to Install Bookmarklets in Safari?**

Here’s an alternate method that will help you install bookmarklets in mobile Safari with a few easy clicks. Just click a [bookmarklet name][3], add that page to your Safari Bookmarks and then remove everything from the bookmarklet URL that’s before the # symbol. Simple! Watch this [video screencast][4] to learn more.

<iframe width="640" height="360" src="http://www.youtube.com/embed/Jm1j9-lfw98?feature=player_embedded" frameborder="0" allowfullscreen></iframe>

### Readability

This provides a distraction – free reading environment on the web. The bookmarklet will remove all the clutter from web pages and what you get is a clean and comfortable reading view.

	#javascript:(%28function%28%29%7Bwindow.baseUrl%3D%27https%3A//www.readability.com%27%3Bwindow.readabilityToken%3D%27%27%3Bvar%20s%3Ddocument.createElement%28%27script%27%29%3Bs.setAttribute%28%27type%27%2C%27text/javascript%27%29%3Bs.setAttribute%28%27charset%27%2C%27UTF-8%27%29%3Bs.setAttribute%28%27src%27%2CbaseUrl%2B%27/bookmarklet/read.js%27%29%3Bdocument.documentElement.appendChild%28s%29%3B%7D%29%28%29)


### Translate to English

Reading a page that’s not written in your native language? Click this bookmarklet and it will translate it to your language using [Google Translate][7].

	javascript:location='http://translate.google.com/translate?langpair=auto|en&u='%2BencodeURIComponent(location);


[Shorten with Goo.gl][8]

This bookmarklet will create a short URL of the current page using [goo.gl][9].



[Download as PDF][10]

Lets you download the current web page as a PDF file that you may attach as an email or read it offline.

[Read the NYT][11]

If the [NYT paywall][12] is preventing you from reading a Times’ story, this bookmarklet may help you bypass the restriction ([see alternative][13]).

[Share on Tumblr][14]

Post the content of the current page, be it an image, video, text or something else, to your Tumblr blog.

[Share on Facebook][15]

Share any web page with your Facebook friends.

[Share on Twitter][16]

Lets you post the URL and title of the current page on to Twitter.

[Send to Instapaper][17]

Save web pages directly to your Instapaper account with a click.

[Google Cache][18]

If a web page is offline, you can retrieve a copy from Google Cache.

[Coral Cache][19]

If you are unable to access a web page due to ISP filtering or because of any geo-restrictions, Coral Cache can fetch a copy for you.

[QR Code][20]

When you want to quickly send the URL of a page from your iPad to your iPhone or Android phone, simply use [QR Codes][21] ([see alternatives][22])

[Google Bookmarks][23]

Save the current page to your Google Bookmarks.

[Google Dictionary][24]

Select a word on the page, copy it to the clipboard and then click the bookmarklet to find its meaning, pronunciation, synonyms, etc. using [Google dictionary][25].

[Flip to Bing][26]

Google is your default search engine in Safari but if it can’t find the information you are looking for, click the Flip to Bing bookmarklet and it will execute the [same search on Bing][27]. There’s no need for you to re-type the search query.

[Add to Wish List][28]

Lets you add an item to your Amazon’s Wish List. You may even add items to the wish-list that are [not listed on Amazon.com][29].

[Subscribe in Google Reader][30]

Subscribe to a blog with Google Reader. The bookmarklet will automatically figure out the RSS feed of that blog.

[Share It!][31]

You’ve previously seen sharing bookmarklets for Twitter, Facebook and Twitter but if you would like to share stuff on a different social sites – like Reddit, Google Buzz, StumbleUpon, etc. – use this universal sharing bookmarklet ([see alternatives][32]).

[Search Site][33]

If a website is missing a search box, you can use Google’s Site Search function to search for internal pages of that site.

[Send to Evernote][34]

Save pages to Evernote, an awesome note taking software.

[Google %2B1][35]

With the [Google %2B1 bookmarklet][36], you can %2B1 any web page from your mobile browser.

Note: You may have noticed that a couple of really good bookmarklets – like the one that [turns webpages into a whiteboard][37] or the one that lets you [edit web pages][38] – are missing here and that’s because they do not work with the mobile Safari browser.


Fuente: [http://www.labnol.org](http://www.labnol.org/software/iphone-ipad-bookmarklets/18969/ "Permalink to Useful Bookmarklets for your iPad, iPhone and iPod Touch Browser")


 [1]: http://img.labnol.org/di/bookmarklets-iphone-ipad.jpg
 [2]: http://www.labnol.org/internet/guide-to-useful-bookmarklets/7931/ "Most Useful Bookmarklets"
 [3]: http://www.labnol.org/software/iphone-ipad-bookmarklets/18969/#bookmarklets
 [4]: http://www.youtube.com/watch?v=Jm1j9-lfw98&hd=1
 [6]: http://img.labnol.org/b/translate.html#javascript:location='http://translate.google.com/translate?langpair=auto|en&u='%2BencodeURIComponent(location);
 [7]: http://www.labnol.org/internet/google-translation-widgets/10135/
 [8]: http://img.labnol.org/b/bitly.html#javascript:void(location.href='http://digitalinspiration.com/tools/googl/?u='%2BencodeURIComponent(location.href))
 [9]: http://www.labnol.org/internet/googl-bookmarklet/11871/
 [10]: http://img.labnol.org/b/pdf.html#javascript:void(window.open('http://www.web2pdfconvert.com/convert.aspx?cURL='%2Bescape(location.href)))
 
 [11]: http://img.labnol.org/b/nyt.html#javascript:(function(){var s=document.createElement('script');s.setAttribute('src','http://toys.euri.ca/nyt.js');document.getElementsByTagName('head')[0].appendChild(s);})();
 
 [12]: http://www.labnol.org/internet/nyt-paywall/18992/
 [13]: http://www.labnol.org/internet/free-access-to-online-newspaper-articles/12336/ "Get Free Access to Online Newspaper Articles with a Google Hack"
 [14]: http://img.labnol.org/b/tumblr.html#javascript:location.href='http://www.tumblr.com/share?v=3&u='%2BencodeURIComponent(window.location.href)%2B'&t='%2BencodeURIComponent(document.title);
 [15]: http://img.labnol.org/b/facebook.html#javascript:location.href='http://www.facebook.com/sharer.php?src=bm&v=4&i=1301235609&u='%2BencodeURIComponent(window.location.href)%2B'&t='%2BencodeURIComponent(document.title);
 [16]: http://img.labnol.org/b/twitter.html#javascript:location.href='http://twitter.com/share?url='%2BencodeURIComponent(window.location.href)%2B'&text='%2BencodeURIComponent(document.title);
 [17]: http://img.labnol.org/b/instapaper.html#javascript:function iprl5(){var d=document,z=d.createElement('scr'%2B'ipt'),b=d.body,l=d.location;try{if(!b)throw(0);d.title='(Saving...) '%2Bd.title;z.setAttribute('src',l.protocol%2B'//www.instapaper.com/j/uQMxxPQBfUxi?u='%2BencodeURIComponent(l.href)%2B'&t='%2B(new Date().getTime()));b.appendChild(z);}catch(e){alert('Please wait until the page has loaded.');}}iprl5();void(0)
 [18]: http://img.labnol.org/b/cache.html#javascript:location.href='http://webcache.googleusercontent.com/search?q=cache:'%2Bwindow.location.href;
 [19]: http://img.labnol.org/b/coral.html#javascript:void((function(){location.href=location.href.replace(/^http://([^/@]%2B)/(?:)/,"http://"%2B"$1".replace(":",".")%2B".nyud.net/");})())
 [20]: http://img.labnol.org/b/qr.html#javascript:location.href='http://chart.apis.google.com/chart?cht=qr&chs=300x250&chl='%2BencodeURIComponent(location.href);
 [21]: http://www.labnol.org/internet/tools/qr-codes-share-text-inside-images/3867/
 [22]: http://www.labnol.org/internet/from-desktop-to-mobile/18212/ "Sharing Links Between your Desktop and Mobile"
 [23]: http://img.labnol.org/b/bookmark.html#javascript:location.href='http://www.google.com/bookmarks/mark?op=edit&output=popup&bkmk='%2BencodeURIComponent(window.location.href)%2B'&title='%2BencodeURIComponent(document.title);
 [24]: http://img.labnol.org/b/dictionary.html#javascript:(function(){void(q=prompt('Enter a word:',''));if(q)location.href='http://www.google.com/dictionary?langpair=en|en&q='%2Bescape(q)})()
 [25]: http://www.labnol.org/internet/online-google-dictionary/5942/
 [26]: http://img.labnol.org/b/bing.html#javascript:location.href=location.href.replace('google','bing');
 [27]: http://www.labnol.org/internet/switch-between-google-and-bing/13275/
 [28]: http://img.labnol.org/b/amazon.html#javascript:(function(){var%20w=window,l=w.location,d=w.document,s=d.createElement('script'),e=encodeURIComponent,o='object',n='AUWLBook',u='http://www.amazon.com/wishlist/add',r='readyState',T=setTimeout,a='setAttribute',g=function(){d[r]&&d[r]!='complete'?T(g,200):!w[n]?(s[a]('charset','UTF-8'),s[a]('src',u%2B'.js?loc='%2Be(l)),d.body.appendChild(s),f()):f()},f=function(){!w[n]?T(f,200):w[n].showPopover()};typeof%20s!=o?l.href=u%2B'?u='%2Be(l)%2B'&t='%2Be(d.title):g()}())
 [29]: http://www.labnol.org/internet/amazon-wish-list-universal-clipper/4196/
 [30]: http://img.labnol.org/b/reader.html#javascript:var%20f=false;var%20ls=document.getElementsByTagName('link');for(var%20i=0,l;l=ls[i];i%2B%2B){var%20t=l.getAttribute('type');var%20r=l.getAttribute('rel');if(t&&(t=='application/rss%2Bxml'||t=='application/atom%2Bxml')&&r&&r=='alternate'){var%20h=%20l.getAttribute('href');if(h.indexOf('http')!=0){var%20p=(h.indexOf('/')!=0)?'/':location.pathname;h='http://'%2Blocation.hostname%2Bp%2Bh;}location='%20http://google.com/reader/preview/*/feed/'%2Bh;f=true;break;}}if(!f)alert('Oops.%20Can't%20find%20a%20feed.');
 [31]: http://img.labnol.org/b/share.html#javascript:void((function(svc)%20{var%20d=document,w=window,p=0,b=function(){if(!p){p=1;if(_atc.xol)_adr.onReady();if(w.addthis_sendto)addthis_sendto(svc||'bkmore',{product:'bmt-'%2B_atc.ver})}else{p=0;if(_atw)_atw.clb()}};if(!w._atc){var%20ol=w.addthis_onload||[],o=d.createElement('script');w.addthis_product%20=%20'bmt-250';o.src='//s7.addthis.com/js/250/addthis_widget.js#domready=1&username=bookmarklet';ol.push(b);w.addthis_onload=ol;d.getElementsByTagName('body')[0].appendChild(o)}else%20b()})())
 [32]: http://www.labnol.org/internet/sharing-widgets-for-websites/9249/ "Social Bookmarking Widgets"
 [33]: http://img.labnol.org/b/search.html#javascript:(function(){void(q=prompt('What are you looking for?',''));if(q)location.href='http://www.google.com/search?q=site%3A'%2Bdocument.domain.replace('www.','')%2B'%20'%2Bescape(q)})()
 [34]: http://img.labnol.org/b/evernote.html#javascript:(function(){EN_CLIP_HOST='http://www.evernote.com';try{var x=document.createElement('SCRIPT');x.type='text/javascript';x.src=EN_CLIP_HOST%2B'/public/bookmarkClipper.js?'%2B(new Date().getTime()/100000);document.getElementsByTagName('head')[0].appendChild(x);}catch(e){location.href=EN_CLIP_HOST%2B'/clip.action?url='%2BencodeURIComponent(location.href)%2B'&title='%2BencodeURIComponent(document.title);}})();
 [35]: http://img.labnol.org/b/plusone.html#javascript:(function(){var c;c=document.createElement('script');c.type='text/javascript';c.src='http://www.ctrlq.org/plusone/index.js?r='%2BMath.random();document.body.appendChild(c);})();
 [36]: http://www.labnol.org/internet/google-plus-one-bookmarklet/19474/
 [37]: http://www.labnol.org/internet/webpage-into-whiteboard/17923/
 [38]: http://www.labnol.org/internet/design/edit-web-pages-like-wiki/3832/  