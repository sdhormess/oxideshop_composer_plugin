OXID eShop composer plugin
==========================

This plugin is used to install OXID eShop and OXID eShop third party integrations (modules, themes).

More information how to install OXID eShop using this plugin can be found `here <http://oxid-eshop-developer-documentation.readthedocs.io/en/latest/getting_started/eshop_installation.html#eshop-installation-via-composer>`__.

Supported types
---------------

Packages are recognised by their type, specified in composer.json file.
Available types are:

- oxideshop - Main shop package is installed into source directory.
- oxideshop-module - Modules, which are installed into source directory. Modules depends on main shop package.
- oxideshop-theme - Themes, which are installed into source directory. Themes depends on main shop package.
- oxideshop-demodata - Demodata package contains demodata.sql and pictures directories.

More information how to create module installable via composer: http://oxid-eshop-developer-documentation.readthedocs.io/en/latest/modules/module_via_composer.html

More information how to create themes installable via composer: http://oxid-eshop-developer-documentation.readthedocs.io/en/latest/themes/theme_via_composer.html
