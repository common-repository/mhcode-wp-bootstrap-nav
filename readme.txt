=== Plugin Name ===
Contributors: mhshohel
Tags: responsive wp menu html, bootstrap, wordpress navmenu, insert html5 tag
Requires at least: 3.0.1
Tested up to: 3.8
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html



Make bootstrap tags navigation menu in wordpress easyly, here included all tag related navigation menu

== Description ==

Twitter bootstrap menu esily insert in wordpress meny, no hassle
with child menu  and top menu style. More Frendly update comming soon

== Installation ==

1. Upload `mhcode-wp-bootstrap-nav` to the `/wp-content/plugins/wp-bootstrap-navmenu/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Create a menu from wordpress admin panel and insert `<?php echo mhcode_wp_bootstrap_nav( MENU NAME ); ?>` in your templates to get menu list.

Example:
<code>
		<?php if (function_exists('mhcode_wp_bootstrap_nav')): ?>
			<?php echo mhcode_wp_bootstrap_nav('mainmenu'); ?>
		<?php endif; ?>
</code>

