0.11.0 (Apr 10 2014)
====================

* Code has been refactored and tested
* Added hotkey-activation back in (defaults to Ctrl+Shift+Space)
* Added warning when both auto-activation and the autosave package are active
* Fixed styling
* Fixed positioning of the overlay (using CSS3 transforms)
* Added a delay option (integer) that defines when the autocompletion should happen after pressing a key
* Scope autocompletion words are now added to the wordlist every time autocompletion happens
* Using the ES6 Set feature for unique arrays
* Confirm button is now customizable (defaults to Tab)
* Using atom's keymap feature instead of handling the keyboard input manually
* Got rid of Atom's SelectListView, moved over to our own view class

0.10.0 (Apr 3 2014)
===================

* Fixing a little issue where the autocompletion would appear even though the word was already confirmed (#23, #25 - thanks to @rpg600)

0.9.0 (Mar 19 2014)
===================
* Correctly clean up registered events on the editor etc. Fixes an issue where closed tabs would result in uncaught exceptions.

0.8.0 (Mar 18 2014)
===================

* Pasting content will no longer toggle autocompletion
* Saving will cancel autocompletion

0.7.0 (Mar 9 2014)
==================

* Fixes an issue where moving the cursor is slowed down

0.6.0 (Mar 9 2014)
==================

* Fixes a bug that caused an uncaught exception when closing a tab with autosave enabled

0.5.0 (Mar 4 2014)
==================

* Added file blacklisting option (glob supported, separated by commas)
* Added TAB as a completion key
* Adds words to the wordlist as they are typed

0.4.0 (Mar 4 2014)
==================

* Only display up to 10 items
* Removed sorting from the word list generator
* Only run autocompletion when the buffer really changed
* More cancellation cases (on line switch, on tab switch)

0.1.0 - 0.3.0 (Mar 4 2014)
==========================

* Initial release