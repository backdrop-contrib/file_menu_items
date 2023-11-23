File Menu Items
====================

This module supports creating menu items that are a link to a local file, like a PDF.

Installation
------------

- Install this module using [the official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

Usage
------------

This module creates a menu router item that contains the directory of the local public file system, e.g., `files`. This, in turn, allows you to use a file path as the destination of a menu item.

Note that if the file does not exist, the menu item will still be present, but attempting to access it will result in a server 404 error, rather than the Backdrop 404 page.

Documentation
-------------

[Discussion and approach are described here.](https://www.drupal.org/forum/support/post-installation/2008-06-03/menu-linking-direclty-to-a-pdf-file#comment-7817259)


Related Modules
---------------

The [Special Menu Items](https://backdropcms.org/project/special_menu_items) module lets you create menu items that are placeholders (text that is not a link) and/or separators between menu items.

Issues
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/file_menu_item/issues).

Current Maintainers
-------------------

- [Robert J. Lang](https://github.com/bugfolder)

Credits
-------

- Written for Backdrop CMS by [Robert J. Lang](https://github.com/bugfolder).

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
