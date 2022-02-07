=== Plugin Name ===
Contributors: s56bouya
Donate link: http://www.imamura.biz/blog/newpost-catch
Tags: widget, plugin, posts, sidebar, image, images, thumb, thumbnail
Requires at least: 5.1
Requires PHP: 7.2
Tested up to: 5.9
Stable tag: 1.3.13

Thumbnails in new articles setting widget.

== Description ==

Thumbnails in new articles setting widget.

== Frequently Asked Questions ==

### Installation

1. Unzip "Newpost Catch" archive.
2. Upload folder 'newpost-catch' to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress
4. Add the widget to your sidebar from Appearance->Widgets and configure the widget options.

Required PHP5.6+

### Apply your own css style

(Located in the plug-in directory) CSS "style.css" file the default

(Please create a directory under the "/wp-content/themes/theme directory/css/") CSS file for customization "newpost-catch.css"

**Priority**

> newpost-catch.css > style.css

Will be applied at.

With regard to CSS will either use the default CSS,

I used the CSS that you created in your own, please change to your liking.


### notice

With the version up of the plugin, so will be overwritten "style.css" file each time,

I think how to directly edit the "style.css" file and how would you or declined.

If you wish to apply a CSS style on its own,

In the "/wp-content/themes/theme directory/css/" as you please create a "newpost-catch.css".

Please the name of the file to create and "newpost-catch.css". The other is the file name, does not apply.


### Shortcode

Can use the shortcode in a textwidget and theme files.

> \[npc\]

#### parameter

* **id**(string) - Name of the id attribute "ul" element(default:npcatch)
* **post_type**(string) - Use post types. Retrieves posts by Post Types(default:post)
* **cat**(int) - Use category id(default:NULL)
* **width**(int) - Thumbnail width px(default:10)
* **height**(int) - Thumbnail height px(default:10)
* **posts_per_page**(int) - Number of post to show per page(default:5)
* **sticky**(boolean) - Sticky posts or not(on:1 off:0 default:0)
* **offset**(int) - Number of post to displace or pass over(default:0)
* **orderby**(string) - Sort retrieved posts by parameter(default:date)
* **order**(string) - Designates the ascending or descending order of the 'orderby' parameter(default:DESC)
* **date**(boolean) - Display date(on:1 off:0 default:0)
* **dynamic**(boolean) - Show only articles in the same category as the article being displayed. If you specify both "cat" parameters, "dynamic" priority(on:1 off:0 default:0)

**Example1. Want change id name of ul element.**

> \[npc id="test"\]

**Example2. Show only articles in the same category as the article being displayed.(post_type is "post" only. and is_single() == true )**

When the post other than, post_type of the current page is the value of the priority parameter cat

> \[npc dynamic="1"\]


== Screenshots ==

1. To display the eye-catching(Thumbnail) set to Latest Post.
2. Localized support is in order.
3. Is simple to add the side bar, to set the size of the thumbnail, posts, post date

== Changelog ==

See https://github.com/s56bouya/newpost-catch/commit/
