WP isAdmin
============

WordPress - Shortcode that can show or hide content to or from administrative users.

### Description

This plugin provides provides a simple short code to add or hide custom content to your posts and pages based on whether a user is an administrator or not.

This started as a way around having an automatic redirect if somebody belonged to a specific WishListMember membership level but not wanting to redirect _off_ of the page if I was an admin (who always has access to all membership levels.)

This plugin supports GitHub Updater.

### Supported shortcodes and default attributes:

    [isAdmin roles="administrator"][/isAdmin]
    [isNotAdmin roles="administrator"][/isNotAdmin]

[isAdmin] will only show content to users that have administrator role (by default).
[isNotAdmin] will hide content to users that have administrator role (by default).

The *roles* parameter will accept a comma separated list of roles to check against different roles or multiple roles.