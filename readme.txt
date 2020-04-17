=== Members Only Membership - Simple membership plugin for WordPress ===
Contributors: icelayer, sirwil
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6D6W2KXB88NKE
Tags: membership, memberships, restrict content, members, restrict, restrict access, profile, role, roles, members shortcode, user, access, authentication, block, community, content, login, password, permissions, register, registration, restriction, security, members only,
Requires at least: 3.4
Tested up to: 5.4
Stable tag: 6.2
Requires PHP: 5.4
License: GNU Version 2 or Any Later Version
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Protect content in posts and pages with shortcodes.

== Description ==

[My Members Only](https://switchwebdev.com/wordpress-plugins/) WordPress Plugin makes it easy for anyone to protect content on a WordPress site in any post or page using shortcodes.

`[membersonly]
Protected Content Here
[/membersonly] `

The shortcode can be used along with other shortcodes, this plugin is very simple and light weight making it a very useful tool for any WordPress website.

`[membersonly]
[myshortcode title="Post title here"]
Protected Content
[/membersonly] `

= Restrict access to =
* Downloads
* Articles in Whole or Part
* Videos
* Private Forums
* Premium Support
* And so much more.

★★★★★
> Superb “Plugin is Superb! exactly what I wanted thanks - [zala5958](https://wordpress.org/support/users/zala5958/)

= New in 4.5 =
* Present Users who are not logged in with a link to "Register or Login Here",
* Redirect Users to current page after login.

1. Create a Post or Page or protect existing content.
2. Place the shortcodes around the content you wish to protect.


New Shortcode Options Use With Options

* display="Custom text" change the message for none logged in user (default: You Must be Logged in to view this content)
* linkto="/wp-admin/" Link to a specific page, recommended usage would be to use /wp-admin/ without http://www this is very good practice in case if you are using SSL or custom subdomain, Note that this will also disable Auto redirect (default: WordPress Login Page)
* linktext="Click Here" change the text for the link (default: Register or Login Here)


= Example Shortcodes =

`[membersonly]
Premium Content Here
[/membersonly] `


= With Options =
`[membersonly display="Login To Download" linkto="/wp-admin/" linktext="Login Here"] protected content here [/membersonly] `


the user will then have to be logged in to view.

== Installation ==

1. Upload iCEYi Members Only to the /wp-content/plugins/ directory.
2. Activate the plugin through the \'Plugins\' menu in WordPress.
3. Use the shortcode [membersonly] protected content here [/membersonly] the user must be logged in to view.

== Frequently Asked Questions ==

= What about custom Post Types =

You can use the shortcode on any post types and also pages.

= Where can I find the Admin Settings =

Admin Settings for this plugin is a sub-menu under Settings in the WordPress Admin Dashboard.

= How Do I lock Down the Entire Website =

This Plugin does not support full website lock-down at this time.

= Will this work with my current theme =

Yes, this plugin will work with any WordPress theme.


== Screenshots ==

1. Protect Content With [membersonly] Shortcode
2. Visitors Will Be Presented with a login form

== Changelog ==


== Upgrade Notice ==
