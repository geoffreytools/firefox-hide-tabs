# firefox-hide-tabs

A CSS override that pairs well with the [Tree Style Tab](https://github.com/piroor/treestyletab) extension (which enables managing tabs in a side panel). It is basically an enhanced title bar for Firefox.

![Firefox window with the Tree Style Tab panel closed](./README/tabs-closed.png)

It removes tabs from the toolbar but keeps the current tab's title and favicon, as well as the "List all tabs" button, which can be used to manage tabs until you feel the need to open the side panel.

![Firefox window with the Tree Style Tab panel open](./README/tabs-open.png)

It has been tested with Firefox 105 / Ubuntu 22. It is very likely that this hack will break at some point. I *may* maintain it.

## How to use

1) Navigate to `about:config` and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`;

1) Navigate to `about:support` and locate your `Profile Directory`;

3) Create a `chrome` directory there if does not already exist, and place `hide-tabs.css` and `userChrome.css` in that directory;

4) Restart Firefox.