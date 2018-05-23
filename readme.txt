=== AOC Multiple Post Images ===
Contributors: ankittiwaari
Donate link: 
Tags: post thumbnails, multiple featured images
Requires at least: 4.6
Tested up to: 4.7
Stable tag: trunk
Requires PHP: 5.2.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

AOC Multiple Post Images allows a user to upload multiple featured images to a post.

== Description ==

This plugin aims at providing users the capability to upload multiple thumbnails/featured images to a post. It uses wp.media js object to open a image uplaoder frame and choose/upload images. Once the images are seleted, it will save the id of uploaded media object in a custom field.

== Installation ==

1. Upload the plugin folder to the `/wp-content/plugins/` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress


== Frequently Asked Questions ==

= Does this plugin support video upload =
No, not at present though this feature is being worked on.

= Can I use this plugin to uplaod other file formats =
No, this plugin is intended to support only image uploads.

== Getting uploaded images ==
You can use the function aoc_get_images($post_id) to retrieve an array of urls of all the images that have been uploaded to a post. This function accepts the id of post (for which the images are to be fetched) as a parameter.

== Screenshots ==

== Changelog ==

= 0.1 =
* First stable version

== Upgrade Notice ==

= 0.1 =
This is the first version, subsequent improvemnts will be pushed later