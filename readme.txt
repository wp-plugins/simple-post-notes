=== Simple Post Notes ===
Contributors: Kubitomakita
Tags: post, page, custom post type, cpt, note, notes, informations, info
Requires at least: 3.6
Tested up to: 4.3
Stable tag: 1.2.2

Adds simple notes to post, page and custom post type edit screen.

== Description ==

= Features =

* Simple note section on the post edit screen
* Note column in posts table

= Available languages =

*   English (author)
*   Polish (Kuba Mikita - [Sztuka WordPress](http://www.wpart.pl/ "Sztuka WordPress"))
*   Spanish (Alfonso Frachelle - [idearius](http://www.idearius.com/es/ "idearius"))

Want to use this plugin in your language? Send me your translation and get your website link here!

Cover photo [designed by Freepik](http://www.freepik.com)

== Installation ==

Don't download .zip file - is silly when you can search for this plugin in your WordPress!
(unless you need .zip)

1. Go to Plugin -> Add New
1. Search for Popslide
1. Install and enjoy!

== Frequently Asked Questions ==

= Custom post type are supported? =

Yes! Enable them on the plugin settings screen.

= Can I disable display of admin column? =

Yes, by a simple filter.

Use:
`add_filter( 'spn/columns-display', '__return_false' );`
To disable SPN column for all post types

Or use
`add_filter( 'spn/columns-display/POST_TYPE_SLUG', '__return_false' );`
To disable SPN column only for specific post type

== Screenshots ==

1. Post Note area
2. Post Note in Posts table
3. Settings

== Changelog ==

= 1.2.2 =
* Added Spanish translation thanks to Alfonso Frachelle 

= 1.2.1 =
* Added filter to prevent displaying post note column

= 1.1.0 =
* Added Note to admin column

= 1.0.0 =
* Release

== Upgrade Notice ==

= 1.0.0 =
Release