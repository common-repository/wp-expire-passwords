=== WP Expire Passwords ===
Contributors: rob.divincenzo
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=RNNDZEXE7HZYJ&lc=US�cy_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted
Tags: password, expire, user, security, administration, automatic, expiration
Requires at least: 3.3
Tested up to: 3.6
Stable tag: 1.1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

This plugin allows you to set passwords to expire every X amount of days (default is 90) and to expire all non-admin user passwords (requiring new unique passwords).

== Installation ==

1. Upload `wp-expired-passwords` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Change your settings in Settings-> Expired Password Settings

== Frequently asked questions ==
* Where can I configure the plugin?
Open the settings Menu and select "Expired Passwords Settings"

== Changelog ==
= 1.0.0 =
First Initial Release

= 1.0.1 =
Reworded settings page
Set a default of 90 days to expire

= 1.1.0 =
Lock will not lift unless a user enters a new password that is different than the old one

= 1.1.1 =
Added case to lift password expiration lock to include password resetting as well as updating user.