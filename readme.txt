=== WP Post Likes ===
Contributors: thanhlt, designwall
Donate link: http://thanhlt.com/
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.html
Tags: likes, posts, post, page, shortcodes
Requires at least: 3.0
Tested up to: 4.7
Stable tag: 1.0

A simple and efficient post like system for WordPress.

== Description ==
Want to add a simple and efficient post likes button?

This plugin provides the `wp_post_likes()` template tag which generates simple and efficient likes button. See the [installation instructions](http://wordpress.org/plugins/wp-post-likes/installation/) for using it in your theme.

= Development =
* [https://github.com/thanhluu/wp-post-likes](https://github.com/thanhluu/wp-post-likes "https://github.com/thanhluu/wp-post-likes")

= Translations =
[http://dev.wp-plugins.org/browser/wp-post-likes/i18n/](http://dev.wp-plugins.org/browser/wp-post-likes/i18n/ "http://dev.wp-plugins.org/browser/wp-post-likes/i18n/")

== Installation ==

1. Open `wp-content/plugins` Folder
2. Put: `Folder: wp-post-likes`
3. Activate `WP Post Likes` Plugin

= Usage =
1. Open `wp-content/themes/<YOUR THEME NAME>/index.php`
2. You may place it in archive.php, single.php, post.php or page.php also.
3. Find: `<?php while (have_posts()) : the_post(); ?>`
4. Add anywhere below it (the place you want the likes button to show): `<?php if ( function_exists( 'wp_post_likes' ) ) { wp_post_likes(); } ?>`
* If you DO NOT want the likes to appear in every post/page, DO NOT use the code above. Just type in `[wp-post-likes]` into the selected post/page content and it will embed likes into that post/page only.

== Changelog ==

= 1.0 =
* Initial Release