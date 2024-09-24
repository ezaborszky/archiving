- [[#1.0 Introduction|1.0 Introduction]]
	- [[#1.0 Introduction#1.1 What is this guide about|1.1 What is this guide about]]
	- [[#1.0 Introduction#1.2 Preferred archiving providers|1.2 Preferred archiving providers]]
	- [[#1.0 Introduction#1.3 What do you need to follow along|1.3 What do you need to follow along]]
		- [[#1.3 What do you need to follow along#1.3.1 Installing the extension|1.3.1 Installing the extension]]
- [[#2.0 Archiving Facebook|2.0 Archiving Facebook]]
	- [[#2.0 Archiving Facebook#2.1 What's the deal with Facebook|2.1 What's the deal with Facebook]]
	- [[#2.0 Archiving Facebook#2.2 Using the extension|2.2 Using the extension]]
		- [[#2.2 Using the extension#2.2.1 Best case scenario|2.2.1 Best case scenario]]
		- [[#2.2 Using the extension#2.2.2 The not so best case scenario|2.2.2 The not so best case scenario]]
		- [[#2.2 Using the extension#2.2.3 If all else fails (public groups)|2.2.3 If all else fails (public groups)]]
- [[#3.0 Archiving Threads and Instagram|3.0 Archiving Threads and Instagram]]
	- [[#3.0 Archiving Threads and Instagram#3.1 Instagram|3.1 Instagram]]
	- [[#3.0 Archiving Threads and Instagram#3.2 Threads|3.2 Threads]]
- [[#4.0 X (Twitter)|4.0 X (Twitter)]]
- [[#5.0 Archiving Telegram|5.0 Archiving Telegram]]
- [[#6.0 Archiving other sites|6.0 Archiving other sites]]
	- [[#6.0 Archiving other sites#6.1 Archiving LinkedIn|6.1 Archiving LinkedIn]]
	- [[#6.0 Archiving other sites#6.2 Archiving pages with 'prove you are not a robot' protection|6.2 Archiving pages with 'prove you are not a robot' protection]]
	- [[#6.0 Archiving other sites#6.3 When literally all else fails|6.3 When literally all else fails]]

## 1.0 Introduction

### 1.1 What is this guide about

This short guide is an attempt to help with some tricks for archiving. Please keep in mind that anything can change overnight, this tutorial lists method that work as of September 2024.

### 1.2 Preferred archiving providers 

This guide focuses on the preferred way of archiving using perma.cc. Whenever perma.cc is not an option Wayback Machine is used as an alternative. 

According to current guidelines archive.today is not recommended. It is a somewhat shady site that often won't load from European IP-addresses. But for some tricks we will need it. 

### 1.3 What do you need to follow along

You will need a perma.cc account, Google Chrome and a custom extension. You can download the extension [here](https://drive.google.com/drive/folders/1cu3HiJIp640ko0s_sY04ZDLvwUSIEgot).  
#### 1.3.1 Installing the extension

Simply download the folder you find under the link:

![[Pasted image 20240920155657.png]]

In Google Chrome open "Manage Extensions", you will find this in the menu on right side under the three little dots:

![[Pasted image 20240920155756.png]]

Here you must choose "Load Unpacked":

![[Pasted image 20240920155934.png]]
Then choose the **folder** you have downloaded. You **don't need to open it**! Just click on the folder itself to select it and then click "Select Folder":

![[Pasted image 20240920160215.png]]

You should see now the extension loaded under 'All extension':

![[Pasted image 20240920160313.png]]

For ease of use you can pin it under the extension tab to make it visible:

![[Pasted image 20240920161230.png]]


## 2.0 Archiving Facebook

### 2.1 What's the deal with Facebook

While we must archive public Facebook posts all the time, Facebook does everything to prevent this. Archiving programs not simply capture the website as an image, but use an automated program to capture all elements - but companies like Meta are not super happy about this.

But there is a solution: embedding. Embedding allows parts of a website to be shown inside of another website, basically creating a little island of their own. For this to work Meta must allow users to see the embedded posts even without authentication (being logged in).

Sometimes it just works, you simply paste the link to perma.cc and you are done. From now on we will assume that the 'easy way' has failed. 

### 2.2 Using the extension

#### 2.2.1 Best case scenario

Let's take this link for reference: https://www.facebook.com/NASA/posts/pfbid0qMj7VcY642ts5tRjbYQZ9zxZztZuMUZTnnH25me6UnQByjHsegmQJs9FwbmQWMNRl

Pretty impressive, right? Let's archive it! Open the link and simply click on the extension button in Chrome. (It will say 'Copied to clipboard', but that's a lie - I don't know how to code, LOL!)

Ideally you will get this funky view of the post:

![[Pasted image 20240920161417.png]]

Now simply copy the link into perma.cc and if the archiving gods are in your favour, you should have an [archived version](https://perma.cc/8YSW-7EY4). 

#### 2.2.2 The not so best case scenario

If you are reading this, the method above did not work. All hope is lost? No! You can try some of the following methods. 

First of all try [Wayback Machine](https://web.archive.org/save), sometimes it works even when perma.cc failed. It might take hours though.

You can also experiment around an [older version of the tool](https://silver-karyl-53.tiiny.site/), here all you need to do is copy and paste a Facebook URL, hit 'Generate' and then click on the alternatives (here 'copied to clipboard' is not a lie!) All else is identical, you can try the different embed URLS in perma.cc and Wayback.

![[Pasted image 20240924103958.png]]
#### 2.2.3 If all else fails (public groups)

So you have a really tricky one, for example a group post. This is a tricky one, but it's not impossible! 

The post must be from an 'open group', there is no way to archive a 'closed group' other than a screenshot. 

If you simply try to archive a group post, you will be hit by a 'Log Into Facebook' error. The method mentioned earlier is also not an option, since embedding is turned off for group posts. But often 'sharing' is allowed, and you can exploit this! If people shared the post click on the shares, it will looks something like this: '10 shares'.

Then you will get this window:
![[Pasted image 20240920163009.png]]

Now choose one of the re-shares, and you can go on with the method explained earlier. It will look really crazy, but often this is the only option to get something that resembles a real archive:

![[Pasted image 20240920163151.png]]

## 3.0 Archiving Threads and Instagram

### 3.1 Instagram

Archiving other Meta products can be definitely challenging, but it is far from impossible.

Let's take this Instagram post: https://www.instagram.com/p/DAHHOt0ppBE

If you try to archive it different things can happen, often the archive officially gets created but in reality it is stuck on the Instagram logo.

You can tweak the URL by adding the following part to it: ?utm_source=ig_embed

So the URL above will be: https://www.instagram.com/p/DAHHOt0ppBE/?utm_source=ig_embed

This can either work or not work, I had luck this time: https://perma.cc/TN7T-72SF

Another option is click 'Share to...' after clicking the three little dots at the corner of the post and choose 'Copy Link':

![[Pasted image 20240920164421.png]]

This will generate a different version of the URL: https://www.instagram.com/p/DAHHOt0ppBE/?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==

Sometime this does the trick, sometimes not. Good luck!

### 3.2 Threads

Threads can be tricky too, perma.cc most likely will outright refuse to take the URL, and respond with a 'Couldn't load URL.' error.

But there is a solution! Threads allows embeds too. Let's take this Threads post: https://www.threads.net/@ukraine/post/DAJBEYktWEI

To generate an embed URL you need to add 'embed' at the end of the URL, like this:

https://www.threads.net/@ukraine/post/DAJBEYktWEI/embed

It is possible that after the post ID there is some extra text following a question mark, for example the '?xmt' part here: https://www.threads.net/@ukraine/post/DAJBEYktWEI?xmt , you will need to remove that!

Now you will get once again a somewhat chaotic version: 

![[Pasted image 20240920165421.png]]

Since perma.cc won't even accept the link, you can try Wayback Machine as a primary alternative: https://web.archive.org/web/20240924084458/https://www.threads.net/@ukraine/post/DAJBEYktWEI/embed

If this failed for some reason, there is still a more hacky alternative, using archive.today.

"But archive.today is no longer supported", you say. And you are right, but it can serve as an intermediary. We get an archive.today version: https://archive.is/jhqkV and then add this to perma.cc: https://perma.cc/P9XR-VVZ6

Is it extremely broken and hacky? Yes. But sometimes there is no other way. You might notice that the video is broken in this version, but be not afraid, you can archive that too!

First of all you can download it using the embed view:

![[Pasted image 20240920170235.png]]
Unfortunately perma.cc won't allow you to upload videos, but there is a workaround. You will need a third party video downloader like: https://threadster.app/

 If you add the Threads post to the downloader and hit 'Download' it will generate a unique URL: https://threadster.app/download/DAJBEYktWEI

Now you can add this to perma.cc, and archive the video: https://perma.cc/W3A2-NZE5

## 4.0 X (Twitter)

For known reasons X/Twitter can change unannounced overnight, but currently these are the known methods. 

Similar to Meta products X posts can be the most reliably archived using the embed feature. 

Let's take this post: https://x.com/NASA/status/1837202334121697700

Click on the little dots at the upper right corner and choose 'Embed post':

![[Pasted image 20240924094827.png]]

Then choose 'Embedded Post':

![[Pasted image 20240924094959.png]]

Here is the tricky part, but be not afraid, it looks more complicated than it actually is! Right click somewhere in the empty region below the X sign and choose "Inspect":

![[Pasted image 20240924095145.png]]
This will show you the source code of the page. It might look intimidating but it is just HTML. Then you need to find a part that looks like this:

![[Pasted image 20240924095412.png]]

Ideally when your cursors is over the part of the code we need, the X post on the right should be highlighted. This is the part of the HTML that corresponds to the embed window. 

Now double click the URL inside the block. It should go from this...

![[Pasted image 20240924095533.png]]

...to this:

![[Pasted image 20240924095609.png]]

Be careful, only the part inside the quotation marks should be selected. Now you can paste this code to perma.cc, and it is done: https://perma.cc/FX5E-YZT8

Good job!

![[Pasted image 20240924095753.png]]

Similarly to Threads, you can archive videos from X separately. This can be useful if the video itself is important evidence.

You will need a video downloading site: https://twittervid.com/

After copying and pasting your X post to the site, and clicking 'Load Videos', you must click 'Open raw video link in new tab':

![[Pasted image 20240924105355.png]]

This will open the video in a new window. Now you can archive this URL, and you will have an archived playable version: https://perma.cc/KS2Z-3FA6
## 5.0 Archiving Telegram

I am not entirely sure what kind of privacy setting Telegram has, sometimes you can just archive a post, sometimes you can't. 

In some cases you will get this instead of an archive:

https://perma.cc/55XN-86QJ

![[Pasted image 20240924102410.png]]

What sometimes helps in this case is choosing 'Context' view:

![[Pasted image 20240924102510.png]]

This will show the post in the feed of the given Telegram channel instead of just a single post. Then you can archive this version: https://perma.cc/YR2U-HSMY

The only downside that the archive will be huge and takes a long time to load. 

## 6.0 Archiving other sites

### 6.1 Archiving LinkedIn

For this to work you will need a LinkedIn account. This is a suboptimal solution, but as far as I know there is no other way to archive LinkedIn, and sometimes experts only have this single public profile.

LinkedIn allows you to generate a PDF version of a profile:

![[Pasted image 20240924100227.png]]

Now you need to open perma.cc and type some gibberish in the URL field:

![[Pasted image 20240924100359.png]]

Now choose 'Upload your own archive' and upload the PDF under 'Choose file'. It is very important that you must manually copy paste the URL of the LinkedIn profile under 'New Perma Link URL', otherwise the live version won't be linked:

![[Pasted image 20240924100543.png]]

Click 'Create a Perma Link' and you are ready. If you have any other alternative you should avoid this method!

### 6.2 Archiving pages with 'prove you are not a robot' protection

This is one of the most annoying cases. You can easily click the field proving that a human being, but the crawler bot of archiving sites fails at this for obvious reasons. 

Perma.cc often won't even let you to archive sites protected by Cloudflare. Wayback Machine will take the link, but then gets stuck on this:

![[Pasted image 20240924101439.png]]

There is a pretty silly solution, and it should be avoided if possible, but you can archive the page with archive.today and then re-archive with perma.cc

https://perma.cc/6LAH-WXSK

I know it is pretty messy, but sometimes there is no other way. Archive.today somehow can get around Cloudflare. 

### 6.3 When literally all else fails

Sometimes it is impossible to archive a site, but you still need some proof. What you can do in this case is to copy paste the site's URL to Google and archive the Google search itself. It looks like this:

![[Pasted image 20240924101900.png]]
This is not a real archive, but if you are dealing with a problematic person at least you will have some evidence that the given post really existed. With Google Cache no longer being a thing, this is what we are left with. 

