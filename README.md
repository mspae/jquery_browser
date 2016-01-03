# Drupal module polyfill for $.browser

$.browser was removed in jQuery 1.9, so if you want to use newer version of Jquery but have a module utilising the jQuery.browser you will have an '$.browser is undefined' error. When activated this module stops that error from occuring by providing a functional $.browser object for the legacy module.