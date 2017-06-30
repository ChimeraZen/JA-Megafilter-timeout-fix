# JA-Megafilter-timeout-fix
CMS: Joomla 3.7.2

Initial Program: Joomlart Mega Filter
Website: https://www.joomlart.com/documentation/joomla-component/ja-megafilter

Timeout Fix: Chimera.Zen
Email: chimera.zen@gmail.com

A basic fix for the timeout caused by indexing all filters with many relationships.
NOTE: May require echo str_repeat(' ', 1024*64) prior to flush() in order to fill buffer.

Files modified:
  - administrator/components/com_jamegafilter/controllers/defaults.php

Tested on:
  - Chrome Version 59.0.3071.115 (Official Build) (64-bit)
  - Ubuntu 17.04
