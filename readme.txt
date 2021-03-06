=== Paid Memberships Pro - Recurring Emails Add On ===
Contributors: strangerstudios
Tags: pmpro, paid memberships pro, files, uploads, downloads, secure, protect, lock
Requires at least: 3.5
Tested up to: 4.6
Stable tag: .5

Sends out an email 7 days before a recurring payment is made to remind members.

== Description ==

Sends out an email 7 days before a recurring payment is made to remind members.

== Installation ==

1. Upload the `pmpro-recurring-emails` directory to the `/wp-content/plugins/` directory of your site.
1. Activate the plugin through the 'Plugins' menu in WordPress.

== Frequently Asked Questions ==

= I found a bug in the plugin. =

Please post it in the issues section of GitHub and we'll fix it as soon as we can. Thanks for helping. https://github.com/strangerstudios/pmpro-recurring-emails/issues

= I need help installing, configuring, or customizing the plugin. =

Please visit our premium support site at http://www.paidmembershipspro.com for more documentation and our support forums.

== Changelog ==
=======
= .5 =
FIX: Too restrictive when looking for recurring memberships to warn of upcoming payments for
FIX: Make sure the test mode doesn't actually send any emails (record to error_log())

= .4 =
FIX: Didn't always include the membership_recurring.html template
ENH: Documentation for filters

= .3 =
FIX: Would sometimes send reminder to all users, regardless of time until next payment.
FIX: Didn't always select all the expected users for notification
FIX: Set the start times for the time intervals correctly (midnight to midnight)
ENH: Load the content of the plugin specific template file
ENH: Add support for inclusion in the Email Templates add-on
ENH: Added error logging & error checking
ENH: WP Style
ENH: Add filter for recurring payment settings
ENH: Adding pmprorm_send_reminder_to_user filter
REF: Renamed template directory for pmpro_getTemplate() function to load template(s)

= .2.1 =
* Uncommented line that actually sends the email.

= .2 =
* Fixed user meta keeping track to prevent duplicate emails.

= .1 =
* Initial release.
