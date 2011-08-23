
Installation
------------

This plugin cannot be installed as a symlink as there are issues with the admin
menus not appearing. As a work around, copy the plugin files to the relevant
wp-content directory, allow www-data write permission, then activate the plugin 
to set up all the necessary db records and extra files. After this, you will need
to copy the generated abspath.php file to the musicglue.wordpress.sites copy of the
plugin, then you shall be able to remove the copied version and re-symlink from
the repo.