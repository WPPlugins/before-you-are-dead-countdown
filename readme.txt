=== Before You Are Dead Countdown ===
Contributors: anou
Donate link: http://www.smol.org/studio-de-creation-sympathique/habitants/anou
Tags: countdown, timer, counter, javascript, widget, shortcode, filter, action
Requires at least: 3.5
Tested up to: 4.0
Stable tag: 1.5.4
License: GPL2
License URI: http://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html


== Description ==
The Before You Are Dead (BYAD) Countdown provides a simple widget witch displays a countdown timer with Days, Hours, Minutes, Seconds and optionally, Years. You can configure some settings: Final date, Final time in the day, Final date format, Your final words and Years display.

= Plugin Features =
* You can display the BYAD Countdown via:
 * a Widget
 * a Shortcode
* BYAD Countdown implements some **filters** to use with *add_filter()* function:
 * *byad_date_data* > array( byadRegional, byadIcon) for jquery datepicker in admin. Useful for localization. Default in french. (see - *byad-settings.php* - around line 131). Check code example in [**help-code.txt**](http://plugins.svn.wordpress.org/before-you-are-dead-countdown/trunk/help-code.txt) file.
 * *byad_title* > filter for the widget title output. (see - *byad-countdown_widget.php* - around line 25)
 * *byad_timezone* > to set timezone for date php functions. Default: 'Europe/Paris'. (see - *byad-countdown_widget.php* - around line 42)
 * *byad_jsdata* > to configure data passed to the main - *byad-countdown.js* - file displaying and activating your "last time of life". (see - *byad-countdown_widget.php* - around line 53)

* You can also:
 * use your own css using this simple action hook: *byad_stylesheet*.
 * use your own datepicker JS language file using this other action hook: *byad_datepicker_lang*.
 * Check examples in [**help-code.txt**](http://plugins.svn.wordpress.org/before-you-are-dead-countdown/trunk/help-code.txt) file.


== Installation ==
This section describes how to install the plugin and stay alive.

1. Upload *before-you-are-dead-countdown/* folder to the */wp-content/plugins/* directory.
2. Activate the plugin through the - Plugins - menu in WordPress.
3. In the Plugins main page, click - Settings - under the plugin's name or go to the options panel under the - Settings > BYAD Countdown - and select the day of your death, your death date format, fill your last words, and choose to enable/disable Years display.
4. Have fun before it's to late!


== Frequently Asked Questions ==
None. Everybody RIP.


== Screenshots ==
1. Default countdown look
2. Settings for the countdown
3. Look it twice and in french


== Localizations ==
BYAD Countdown distributes with translations for the following languages:
* English
* Français
* Italiano

Don't see your language on the list?
There is a - byad-countdown-default.po - in the languages/ directory. 
Use it with [Poedit](http://www.poedit.net/) as a base .PO file for your language. 
Save it as: byad-countdown-LANGCODE.po where LANGCODE is your language code (e.g. fr_FR). 
If you create any, I'll be glad to include it in the plugin.

* [Link to Languages Codes](http://fr.termwiki.com/TWSpecial:ISO_Language_Code_Comparison)
* Link to the excellent [Poedit software](http://www.poedit.net)
* See also my [**help-code.txt**](http://plugins.svn.wordpress.org/before-you-are-dead-countdown/trunk/help-code.txt) file for more info.


== Changelog ==

= 1.5.4 =
* Added option to specify the time (HH:MM:SS) of the day you want to die (you can even specify the seconds for the really precise ones)
* Tested in WP 4.0

= 1.5.3 =
* Changed the donate link

= 1.5.2 =
* Bug with the readme file...

= 1.5.1 =
* Compatibility with WP 3.9
* Improved date format settings
* Updated translations (EN,FR & IT)

= 1.5 =
* Added Italian language
* Included - jquery.ui.i18n.all.js - file. This way every languages are possible for the datepicker.
* Removed js/datepicker-fr.js

= 1.4 =
* Added shortcode funtionnality [byad_countdown title="Your-custom-title"] (title optional)
* Renamed classes from ..._CountDown_... to ..._Countdown_... for best practices
* Changed and insure existence of a default widget title
* Added action: "byad_datepicker_lang" to facilitate the enqueueing of other datepicker languages
* Updated .PO files

= 1.3 =
* Changed version number.
* Reordered options settings fields

= 1.2 =
* Changed version number.

= 1.1 =
* Fixed date format bug.
* Added new option

= 1.0 =
* Beginning of the rest of my life.


== Upgrade Notice ==

= 1.5.4 =
* If you want to control the time of your death, you must upgrade to this version.

= 1.5.3 =
* Go ahead, no souci.

= 1.5.2 =
* Nothing change, just a svn bug...

= 1.5.1 =
* Tested Compatibility with WordPress 3.9

= 1.0 =
Upgrade before it's to late!