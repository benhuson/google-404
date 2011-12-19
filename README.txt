=== Google 404  ===
Contributors: husobj
Donate link: http://www.benhuson.co.uk/wordpress-plugins/google-404/
Tags: google, 404, error
Requires at least: 2.5
Tested up to: 3.1.2
Stable tag: 1.0.2
License: GPLv2 or later

Allows you to add a Google 404 widget to your missing 'page not found' pages which allows you to do a Google search of the site.

== Description ==

A 404 page is what a user sees when they try to reach a non-existent page on your site (because they've clicked on a broken link, the page has been deleted or they've mistyped a URL).

While the standard 404 page can vary depending on your web host, it doesn't usually provide the user with much useful information and users may just surf away from your site. Therefore, Google recommend creating a custom 404 page that provides the user with more information about your site and its content.

The Google 404 widget is a quick and easy way to embed a search box on your custom 404 page and provide users with useful information designed to help them find the information they need. Where it can, the Google widget will also suggest other ways for the user to find the information they need, thus increasing the likelihood that they'll continue to explore your site.

You should set up a [Google webmaster account](http://www.google.com/webmasters/ "Google") and submit an XML sitemap of your blog to ensure the Google 404 widget works effectively.

Find out more [here...](http://www.google.com/support/webmasters/bin/answer.py?answer=93644&cbid=-he7hb1tg6az&src=cb&lev=answer "Google")

= Please note =

The Google 404 widget plugin is NOT a WordPress widget.
It is simply the term Google use to describe their enhanced 404 page script.

== Features ==

Currently the plugin only outputs the Google 404 widget in English (UK).
Will hopefully add support for other languages in future versions.

Also looking to add the possiblity to [change the appearance](http://www.google.com/support/webmasters/bin/answer.py?answer=100044&cbid=-1p0j7f68xlmqq&src=cb&lev=answer "Google") of the widget.

== Installation ==

You should first set up a [Google webmaster account](http://www.google.com/webmasters/ "Google") and submit an XML sitemap of your blog to ensure the Google 404 widget works effectively.

1. Download the archive file and uncompress it.
2. Put the "google404" folder in "wp-content/plugins"
3. Enable in WordPress by visiting the "Plugins" menu and activating it.
4. Add the following code to your 404.php template.

`<?php if ( function_exists( 'google404' ) ) google404(); ?>`

You could also add this code to your theme's index.php, single.php, image.php, archive.php and search.php below the HTML that is displayed if no posts are present (where you insert this may vary from theme to theme).

== Screenshots ==

No Screenshots yet.

== Changelog ==

= 1.0.2 =
* Added GPL License info.
* Try to use current WordPress language before defaulting to English.
* Moved all functionality into class.
* Update styles.

= 1.0.1 =
* Added documentation to read me file.

= 1.0 =
* First release.

== License ==

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.
