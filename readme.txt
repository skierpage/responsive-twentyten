=== Responsive TwentyTen ===
Contributors: toddhalfpenny, skierpage
Tags: css, twentyten, responsive
Requires at least: 2.8
Tested up to: 6.6.1
Stable tag: 0.0.5

Makes your TwentyTen themed site have a responsive and fluid layout


== Description ==

Makes your TwentyTen themed site have a responsive and fluid layout. Making it ideal for for viewing across a whole range of devices and screen sizes (i.e iPhones, Android, iPads).
Uses CSS and media queries to enable the fluidity and responsiveness.



== Installation ==

1. Install the plugin from within the Dashboard or upload the directory `responsive-twentyten` and all its contents to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Voila!


== Frequently Asked Questions ==

= Why is this not a child theme = 

The WordPress.org theme repository doesn't support the submission of child themes yet. This is meant to be on it's way some time soon... but in the meantime a similar result can be gotten with this plugin.


== Screenshots ==

1. Normal browser

2. Narrow Browser

3. iPhone Browser


== Changelog ==

= 0.0.5 =

 * Correct @import of the original twentyten/style.css.
 * Update README: other forks, remove 404 donation link.

= 0.0.4 = 

Tweaks from https://www.mikematera.com/make-your-wordpress-twenty-ten-theme-responsive/ :

 * Adjust header image to screen size

 * Don't add shadows and borders to images

= 0.0.3 = 

 * Fix for image scaling to keep ratio instead of squashing.
 
 
= 0.0.2 = 

 * Images centered now when screen size gets small
 
 * Images with captions also now re-sized
 
 

= 0.0.1 = 

First Release.


== TODO ==

* (these should be filed as GitHub issues)

* twentyten is increasingly broken with problems in both Gutenberg editor and when viewing pages. Bullets look wrong in the former, group layouts don't work in the latter, etc.

* the Gutenberg editor does not load the responsive-twentyten CSS

= Other forks =
https://github.com/EatingRichly/responsive-twentyten/commits/master has a 2014 commit from "wormeyman" "Remove all image stylings"
that comments out all of the CSS for.entry-content img.size-full.

It also has a cleanup commit "Add my fork's settings." that gets rid of trailing whitespace and adjusts CSS whitespace.

= http:// removal =
header.php has <link rel="profile" href="http://gmpg.org/xfn/11" />

the site is down, let alone an https version. It's for defining FOAF relationships in a Links Manager (for a "blogroll") that I no longer use.

https://orbitingweb.com/blog/remove-unnecessary-tags-wp-head/ explains how to remove it with a plug-in.
