=== ra_qrcode ===
Contributors: RobertoAlicata
Tags: qr code, qrcode, qr code generator, qrcode generator, qr code shortcode
Donate link: http://www.robertoalicata.it
Requires at least: 3.5
Tested up to: 4.2.3
Stable tag: 2.1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

a simple WordPress plugin to generate a QR code with a configurable shortcode and Widget

== Description ==
Usage:

write [qrcode] to generate a QRcode for the actual url with size of 100x100 pixels

you can specify these attributes:

size 	(it indicates the size in pixels for width and height, default: 100)

alt  	(it indicates the alternative text for the image: default "scan QR code")

content (leave it blank to pass the actual url or write the content to encode)

click 	(write "yes" to make the image clickable)

fgcolor (foreground color in hexadecimal format)

bgcolor (background color in hexadecimal format)

**example**: [qrcode size=200 content="www.robertoalicata.it" alt="scan me NOW" click="yes"]


== Installation ==
1. Upload the plugin directory to the /wp-content/plugins/ directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==
.

== Screenshots ==
1. The simplest shortcode
2. The qr code generated

== Changelog ==

= 2.1.0 =
* NEW feature: Now you can change foreground and background color (require GD library installed on the server)

= 2.0.0 =
* NEW feature: the Widget

= 1.1.1 =
* Fixed some bugs on the clickkable qrcode

= 1.1.0 =
* NEW feature: a tinyMCE button for configure the qrcode shortcut

= 1.0.0 =
* Fisrt stable version

= 0.1.0 =
* First version of the plugin

== Upgrade Notice ==
.