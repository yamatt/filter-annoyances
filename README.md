# Annoyances

[![CC0 Logo](https://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](https://creativecommons.org/publicdomain/zero/1.0/)

This is an opinionated set of filters for [uBlock Origin](https://github.com/gorhill/uBlock/) that removes some of the visual annoyances around the web. Annoyances such as:

- Cookie and GDPR notices
- E-mail sign-up notifications
- Lightboxes
- Basically anything that is modal, takes up more than 20% of your screen or needs you to hit a button to make it go away

uBlock Origin does a good job of these by default, but I wanted to get in to more detail.

## Annoyances Filters

This repo provides 2 main filter options. Specific and Aggressive.

### [Specific](https://yamatt.github.io/filter-annoyances/specific.filter)

This filter list is specific to particular websites. This will be a much larger task and slower to update.

### [Aggressive](https://yamatt.github.io/filter-annoyances/aggressive.filter)

This filter list is designed to work on as many sites as possible, but is likely to be less accurate and as a result may have some unintended consequences.

> [!NOTE]
> You may need to deactivate uBlock Origin occasionally (and refresh the page) if the page loads black or won't scroll, you can then accept the cookie barrier, and reenable uBlock Origin.

## [Personal Distractions](https://yamatt.github.io/filter-annoyances/distractions.filter)

This is a filter designed to remove distractions and dark patterns from websites that keep me coming back. Because of this, this is purely a personal filter and not intended for general use.

## How to install

1. Open uBlock Origin in your browser
1. Click on the Cluster of Cogs icon
1. Go to the second tab _Filter list_
1. At the bottom of the tab there is an _Import_ drop down, expand that
1. Enter the URLs from above, one on each line
1. At the top of the tab click _Apply Changes_

You will then see the list under _Custom_ at the bottom of the page.

## Contribute

[Please help](https://github.com/yamatt/filter-annoyances) by reporting when filters cause issues, or sites that you want to see added.

## License

CC0: To the extent possible under law, Matt Copperwaite has waived all copyright and related or neighboring rights to yaMatt Annoyances Filter. This work is published from: United Kingdom.
