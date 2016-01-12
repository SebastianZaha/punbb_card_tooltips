Plugin for Card Tooltips
========================

Enables card images to show on mouseover for Magic the Gathering, World of Warcraft
and Warhammer: Invasion cards.

__Branch for PunBB 1.3.x__

Description
-----------

[deckbox.org](http://deckbox.org) provides a javascript utility that enables links to its 
Magic the Gathering card pages to automatically show card image tooltips on hover. 
For more information see [the tooltips integration page](http://deckbox.org/help/tooltips).

This **PunBB** plugin provides the bbcode tags `[mtg]`, `[wow]`, `[whi]` that turn a 
simple card list into links to card pages. It automatically includes the tooltip.js
file that provides the mouseover functionality.

As a complement of this plugin there is also a modified version of the 
[official PunBB BBCode plugin](http://punbb.informer.com/svn/additions/punbb-1.3/extensions/pun_bbcode/),
which provides buttons in the detailed editor for MtG, WoW and WHI respectively. 
You can see more information about this plugin on is github project page: 
[PunBB BBCode](https://github.com/SebastianZaha/punbb_bbcode).


Usage
-----

To install [download the latest 0.3 release](https://github.com/SebastianZaha/punbb_card_tooltips/releases) 
and extract the zip into in your forums' extension folder. Then enable the plugin through the forums' 
administration / extensions interface.

After installing, use the bbcode tags `[mtg]`, `[wow]`, `[whi]` to surround card names or deck
lists in your posts.


Examples
--------

The official Deckbox forum uses the plugins. As examples, check out the 
[EDH Format Staples](http://deckbox.org/forum/viewtopic.php?id=1871) thread for MtG cards,
or the [Warhammer Rules Summary](http://deckbox.org/forum/viewtopic.php?id=232) thread for
Warhammer: Invasion.


Support and development
-----------------------

If you run into problems installing or using the plugin, please contact 
[support@deckbox.org](mailto:support@deckbox.org).

If you would like to contribute, I will gladly accept pull requests.
