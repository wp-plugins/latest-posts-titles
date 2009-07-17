=== Plugin Name ===
Contributors: Sachethan G Reddy
Tags: latest posts, list latest posts, list posts titles, list latest post titles
Requires at least: 2.6
Tested up to: 2.8

List Latest Posts with Title plugin allows to fetch all latest posts in a given category without any further work.

== Description ==

There are number of solutions to list latest posts of your blog, but this plugin uses less number of MySQL queries to fetch latest posts titles from given category.
This plugin is successfully used at http://searchandhra.com
== Installation ==

The plugin is simple to install:

1. Download the zip file
2. Unpack the zip. You should have a directory called `latestpostitles`, containing several files and folders
3. Upload the `latestpostitles` directory to the `wp-content/plugins` directory on your WordPress installation. 
4. Activate plugin
5. Edit latestpostitles.php if you need to tweak the settings

It will work immediately!

== Frequently Asked Questions ==

= Is not working for me. Why? =

First, the question is too generic. But the main cause may be that category name you have given is present in your blog or not.

== Screenshots ==


== Documentation ==
	Use function get_latest_posts($category, $limit=5, $start_tag='<li>', $end_tag = '</li>'), to list latest post titles.

	Ex:	i) get_latest_posts("News");
		above function call will list all latest posts titles from category 'News'.
		ii) get_latest_posts("News", 10);
		above function call will list ten latest posts titles.
	
	You can place fetched titles at any place of your web page, depending on your design.


== Settings ==


== Changelog ==

1.0 [July 07, 2009]
- first release