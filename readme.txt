=== Picturefill fix for WooCommerce ===
Contributors: jeremymoseley
Donate Link: https://www.paypal.me/jeremymoseley
Tags: woocommerce, wp-retina-2x, picturefill, variable product, retina, hidpi
Requires at least: 4.1
Tested up to: 4.3.1
Stable tag: 1.0.1
License: GPLv2 or later

Adds WP Retina 2x picturefill compatibility for WooCommerce variable product images.

== Description ==

If you love WooCommerce and WP Retina 2x you have likely ran into an issue on variable product pages if you are using the recommended retina method of picturefill. When selecting a variation with an attached image it should replace the product image shown. Unfortunately, the way that WooCommerce replaces the image it is not compatible with the picturefill method... until now!

== Installation ==

Upload the Picturefill fix for WooCommerce plugin to your blog, and Activate it.

== Frequently Asked Questions ==

= Why do I need this plugin? =

Variable product images do not update when selecting a variation if picturefill is used. This plugin fixes that issue.

= Where is the settings for the plugin? =

There are no settings. If you have WooCommerce and WP Retina 2x installed it will just work.

= Why don't I just use the Retina.js method? =

Retina.js results in the loading of both the standard and retina image. Picturefill only loads the image best suited for the display.

= Will this work with my theme? =

Most likely yes. As long as your theme keeps the WooCommerce product image convention of a wrapper div with the '.images' class it will work.

== Changelog ==

= 1.0.1 =
*Release Date - 29 October 2015*

* Added Frequently Asked Questions

= 1.0.0 =
*Release Date - 29 October 2015*

* Initial release
