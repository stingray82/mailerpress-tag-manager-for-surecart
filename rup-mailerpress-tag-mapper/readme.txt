=== MailerPress Tag Manager for SureCart ===
Tags: SureCart, Mailerpress, tags
Requires at least: 6.5
Tested up to: 7.1.3
Stable tag: 1.1.3
Requires PHP: 8.0

Automatically add MailerPress Tags on SureCart Purchases
== Description ==

Automatically add MailerPress Tags on SureCart Purchases
== Installation ==

1. Upload the `rup-mailerpress-tag-mappe` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Configure the plugin settings it is located in the SureCart menu

== Frequently Asked Questions ==

== Changelog ==
= 1.1.3 18 October 2026 =
* [New] Add Automatic Update Support using UUPD

= 1.1.2 17 October 2026 =
* [Fixed] Removed the unwanted blank New mapping row created when opening the mapper
* [Improved] Add Mapping buttons now create an expanded row only when requested
* [Improved] Automatically scroll to a new mapping and focus its product selector
* [Fixed] Clear active search and filters when adding a mapping so it remains visible
* [Fixed] Prevent unsaved mapping row indices from colliding after deletion

= 1.1.1 16 October 2026 =
* [Fixed] Restored vertical scrolling on the CRM Tag Mapper admin screen with page-scoped overflow rules
* [Improved] Retained the compact mapping interface without restricting the page height

= 1.1.0 15 October 2026 =
* [Improved] Existing product and price mappings now start collapsed for easier navigation
* [New] Compact mapping summaries show product, price or version, selected MailerPress tags and mapping status
* [Improved] Expand individual mappings to edit their settings
* [Improved] New mapping forms open expanded while existing mappings remain collapsed

= 1.0.0 15 October 2026 =
* [New] Initial MailerPress integration for the SureCart CRM Tag Mapper
* [New] Map SureCart products or individual prices to multiple MailerPress tags
* [New] Automatically apply mapped tags following supported SureCart purchase events
* [New] WordPress admin interface for managing and enabling product and price mappings
* [New] Global and per-mapping double opt-in settings for new contacts
* [Improved] Preserve existing MailerPress subscription statuses and previously assigned tags
* [Info] New contacts created through purchase tagging are not automatically treated as subscribed without confirmation