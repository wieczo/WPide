=== WPide ===
Contributors: WPsites
Tags: code, theme editor, plugin editor, code editor
Requires at least: 3.0
Tested up to: 3.3
Stable tag: 1.0.2

Replace the default WordPress code editor for plugins and themes. Adding syntax highlighting, autocomplete of WordPress functions + PHP, line numbers, auto backup of files before editing.

== Description ==

Out of frustration of unsatisfactory experiences with desktop based IDE's and code editors we (WPsites) decided to make use of the Ajax.org Cloud9 Editor (http://ace.ajax.org/) and embed it in place of the default WordPress file editor.

= This plugin does not currently work on Internet Explorer! =

= Current Features: =

*   Syntax highlighting
*   Line numbers
*   Autocomplete of WordPress functions and PHP
*   Automatic backup of every file you edit. (one daily backup and one hourly backup of each file stored in plugins/WPide/backups)
*   Highlight matching parentheses
*   Auto indentation

= Planned Features: =

*   Tabbed document interface for editing multiple files
*   Ajax Save
*   Create and edit directories and files
*   ctrl + s saving
*   Improve the code auto complete so that it shows command arguments rather than just commands, possibly with links through to the WordPress codex for further info
*   Create an admin panel to choose between syntax highlighting themes and turn on/off other Ajax.org Cloud9 functionality
*   Better automated file backup process 
*   Integration with git for version control


As with most plugins this one is open source. For issue tracking, further information and anyone wishing to get involved and help contribute to this project can do so over on github https://github.com/WPsites/WPide



== Installation ==

1. Upload the WPide folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Does this plugin work on Internet Explorer =

No support for Internet Explorer right now

== Screenshots ==

1. Editor view, showing line numbers and syntax highlighting.

== Changelog ==

= 1.0.2 =
* Tidy and comment code
* Added message when backup file is generated
* Adjust code complete dropdown position
* Improved editor responsiveness when using delete or enter keys

= 1.0.1 =
* Fixed "Folder name case" issue.

= 1.0 =
* Initial release.