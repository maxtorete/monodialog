This module provides a tiny API to make SIMPLE and EASY the usage of jQuery
Dialogs with Drupal pages and forms.

This module hasn't as many features as ctools or DialogAPI, it only provides
two functions: one per page dialogs and other one for form dialogs as
drupal_get_form replacement. These functions are intended to be used as
'page callback' argument on hook_menu item arrays without additional
coding or configutarion.

With these functions on your page callback, you only need to call the path with
ajaxed links (with nojs path argument and use-ajax class on it). As simple as
that, jQuery Dialog for lazy developers!

The module has a third function to use as form callback with some advanced
features but with the same SIMPLE and EASY usage basis.

You can find an example module in monodialog_example folder.
