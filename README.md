# Scroll-to-anchor

## Add anchors and use a smooth scrolling animation for a better user experience.

![Scroll-to-anchor](/assets/banner-1544x500.png)

## Description ##

Do you write longer text in posts or pages and want to provide links to skip parts?

Usually this is done by adding HTML anchors in the text editor as link targets. But not everyone feels happy writing HTML code, which also may be error-prone. After installing this plugin you can use the new anchor icon in your visual editor toolbar to place anchors.

Click in your text where you want to place the anchor, then click on the anchor icon. A dialog box appears where you can provide a short name for your anchor (e.g. "summary"). Optionally you may also provide CSS class name to individually style the anchor. As a result, a shortcode will be placed into your text. This shortcode will render according to your settings and get replaced in the front end with the correct HTML.

Next you can create a link to this anchor. Write some Text (e.g. "Skip to summary"), mark the text and use the default link icon in the editor toolbar. Instead of the complete URL it is sufficient to provide the previously created anchor name, preceded by a hash sign (e.g. "#summary"). That’s about it. If a visitors of your website now clicks on that link in the front end, they will see the web page scrolling smoothly to the defined anchor.

### Individual Settings ###

This plugin provides some enhancement only, so it doesn't come with yet another settings page but instead adds a settings section to the menu **Settings > Reading**.

Here you can select the speed of the scrolling animation or even disable the animation entirely.

You can also set an **offset** for anchors, which comes handy if you e.g. use a fixed header.

Some users just want the smooth scrolling effect, but don't want any text to show up in their posts or pages. Therefore the plugin won't display anything in the front end unless you choose differently in the settings. Those who want to show the anchors as text, may choose their own label for anchors, e.g. "footnote" or "section" (followed by the name you chose for that particular anchor).

I appreciate all feedback.

### Installation ###

You can install **Scroll to Anchor** automatically from the plugin directory, or by uploading the files manually to your server. After activating **Scroll to Anchor** you'll be forwarded to the settings section at the bottom of the menu **Settings > Reading**.

To uninstall, just deactivate and delete the plugin. Remember to remove the shortcodes you may have added using the plugin.

### Frequently Asked Questions ###

Q: Why don't I see any settings page?
There is no need to add yet another settings page. You'll find the plugin settings at **Settings > Reading**.

Q: Are there any restrictions for anchor names?
The plugin skips anchor links starting with `#respond` (usually comments) and on pages with a body-class `.woocommerce` anchors starting with `#tab` to avoid conflicts with WooCommerce's product tabs.

### Screenshots ###
![Settings > Reading](https://github.com/pixolin/scroll-to-anchor/blob/master/assets/screenshot-1.png)
1. Settings > Reading
![Adding a new anchor](https://github.com/pixolin/scroll-to-anchor/blob/master/assets/screenshot-2.png)
2. Adding a new anchor
![Creating link to anchor](https://github.com/pixolin/scroll-to-anchor/blob/master/assets/screenshot-3.png)
3. Creating a link to anchor

### Changelog ###

### 0.3.5 ##
Release date: April 8, 2016
Bug-Fix: added exception for Woocommerce Tabs
(thank you for feedback by francismacomber)

### 0.3.4 ###
Release date: March 26, 2016
Bug-Fix: Settings weren't deleted from the database due to a wrong variable name.
Enhancement: Changes initial setting after installation to hide the anchor in the front end by default. Settings menu rearranged and with easier to understand descriptions.

### 0.3.3 ###
Release date: March 14, 2016
Bug-Fix: Replaces hook used to show settings link

### 0.3.2 ###
Release date: March 12, 2016
Enhancement: Menu plugins now shows link to settings section

### 0.3.1 ###
Release date: February 13, 2016
Enhancement: .pot-File for translation and German formal translation added.
Bug-Fixes:   Some minor changes like removing unnecessary variables.

### 0.3 ###
Release date: February 12, 2016
Initial release.

-----
The banner for the WordPress Plugin Repository is based on the image ["Coast and Geodetic Survey Ship FATHOMER. In service 1905-1941."](http://www.photolib.noaa.gov/htmls/theb0139.htm) published in **Public Domain** by National Oceanic and Atmospheric Administration/Department of Commerce, USA. Photograph by C&GS Season's Report Miller, 1911.

Text in the background is from the novel *Moby Dick* by Herman Melville, **Public Domain**.

And just in case you wonder about the maritime elements – this plugin is about *anchors*. :)
