=== Audio Comments Plugin ===
Tags: audio, comments, mp3, flash, moderated, audio comments
Requires at least: 3.0.0
Tested up to: 4.7.0
Stable tag: 1.0.4
Version : 1.0.4
Contributors: radu.patron, naicuoctavian
License: GPLv2 or later

The Audio Comments Plugin for WordPress adds audio comments to your WordPress content by integrating Audior - a powerful mp3 web recording solution.

== Description ==
<a href='http://audior.ec#wp' onclick="window.open(this.href,"_blank");return false;" target="_blank" title='Record mp3 in browser'>Audior is a simple mp3 recording tool for the web</a> that can record your microphone, encode the sound to MP3, and save it to your computer or upload it to a web server. Audior is developed in Flash and works from any browser. For a complete list of features check out the <a href='http://audior.ec/features#wp' target="_blank" title='Audior Features'>Audior features page</a>. For pricing check out the <a href='http://audior.ec/order#wp' title='Audior Pricing Page' onclick="window.open(this.href,"_blank");return false;" target="_blank">Audior pricing page</a>.

With this plugin you will be able to leverage Audior to:

* Record, post and playback audio comments directly on your WordPress blog post pages
* Reply to existing audio comments with another audio comment
* Review and moderate audio comments from your WordPress backend just like any other comment.
* Control the max record limit/comment for each user role (you can change it from your WordPress admin area)
* Change the looks, language file, sound wave and more with the 11+ Audior options exposed in the WordPress backend
* Display Audior in your Posts and Pages using the shortcode [audior]

Other features include:

* Simple install: it installs as any other WP plugin
* compatible with SEO friendly URL's in WordPress
* the Audior recorder colors can be changed to fit with your existing WordPress theme
* the AUDIO HTML5 element is used for playback
* audio comments are always optional
* the MP3 format of the audio comments is supported by most browsers including those on mobile devices


== Installation ==
For the Audio Comments plugin to work, **you need to purchase the web based Audior mp3 recording software** from <a href='http://audior.ec/order#wp' title='Purchase Audior'>here</a>. The free Audio Comments plugin only takes care of the integration between WordPress and the Audior web software, it does not contain the actual Audior software.

Once you purchase Audior from audior.ec website, follow these steps:

1. Download the plugin archive from this page.
2. Extract the archive and upload the **audio-comments** folder to your **/wp-content/plugins** folder.
3. Download the Audior archive from your Audior client area (you will receive the link by e-mail after purchasing Audior).
4. Extract the Audior archive (Audior.zip) and upload the contents of **Audior** folder to **/wp-content/plugins/audio-comments/audior/**
5. Go to the WordPress admin area -> Plugins page and activate the **Audio Comments for WordPress** plugin
6. Go to the WordPress admin area -> Settings -> Audio Comments and fill in the **License key** field with your Audior license key, it's in your Audior client area.
7. Done, you can now go to a blog post and add an audio comment or add the [audior] shortcode to any page to capture audio recordings

== Frequently Asked Questions ==

= Where are the MP3 files stored? =

wp-contents/uploads/audio-comments

= What are the requirements ? =

A WordPress web site and Audior from http://audior.ec .

= Do I need a media server like Red5 or Wowza ? =

No, Audior records by storing the raw audio data in the computer RAM until it is converted to MP3 and uploaded to the web server.

= How about HTML5? Can't it handle audio recording instead of Audior? =

No, at the moment, recording audio in the browser using native HTML is in it's infancy and implementations differ between browsers or are missing entirely.


= What if I need help ? =

1. Post a question in the Support area of this page: http://wordpress.org/support/plugin/audio-comments
2. Post a question in our official Audior support forum: http://nusofthq.com/forum/index.php?/forum/29-general-discussions/ (free account needed).
3. Email support@nusofthq.com 

== Screenshots ==

1. Audio comments in a blog post

2. Recording an audio comment reply

3. Playing an audio comment reply

4. Moderating audio comments

5. Moderating an audio comment

6. Audio Comments Plugin Settings

== Changelog ==
= 1.0 (18.02.2014) =
* 1st release in WordPress plugin directory.
= 1.0.1 (25.10.2014) =
* added shortcode function. shortcode: [audior].
= 1.0.2 (14.12.2016) =
* wmode=transparent for transparent corners
* correct Flash Player requirement: 11.1.0 instead of 12.x
= 1.0.3 (17.01.2017) =
* the plugin does not rely anymore on SWFObject to embed Audior in the page or comments
* compatibility with Audior 1.4 which does not ship with SWFObject.js
= 1.0.4 (11.03.2017) =
* The plugin now works on PHP7 hosts, it relies entirely on $wpdb