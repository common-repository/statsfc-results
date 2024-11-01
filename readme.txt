=== StatsFC Results ===
Contributors: willjw
Donate link:
Tags: widget, football, soccer, results, premier league, fa cup, league cup
Requires at least: 3.3
Tested up to: 6.2.2
Stable tag: 3.1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This widget will place list of football results in your website.

== Description ==

Add a list of football results to your WordPress website. To request a key sign up for your free trial at [statsfc.com](https://statsfc.com).

For a demo, check out [wp.statsfc.com/results](https://wp.statsfc.com/results/).

= Translations =
* Bahasa Indonesia
* Dansk
* Deutsch
* Eesti
* Español
* Français
* Hrvatski Jezik
* Italiano
* Magyar
* Norsk bokmål
* Slovenčina
* Slovenski Jezik
* Suomi
* Svenska
* Türkçe

If you're interested in translating for us, please get in touch at [hello@statsfc.com](mailto:hello@statsfc.com) or on Twitter [@StatsFC](https://twitter.com/StatsFC).

== Installation ==

1. Upload the `statsfc-results` folder and all files to the `/wp-content/plugins/` directory
2. Activate the widget through the 'Plugins' menu in WordPress
3. Drag the widget to the relevant sidebar on the 'Widgets' page in WordPress
4. Set the StatsFC key and any other options. If you don't have a key, sign up for free at [statsfc.com](https://statsfc.com)

You can also use the `[statsfc-results]` shortcode, with the following options:

* `key` (required): Your StatsFC key
* `competition` (required*): Competition key, e.g., `EPL`
* `team` (required*): Team name, e.g., `Liverpool`
* `group` (optional): Group name, e.g., `Group A`
* `season` (optional): Season to show results for, e.g., `2016/2017`
* `highlight` (optional): The name of the team you want to highlight, e.g., `Liverpool`
* `from` (optional): Date to show results from, e.g., `2014-01-01`
* `to` (optional): Date to show results to, e.g., `2014-01-07`
* `limit` (optional): Maximum number of results to show, e.g., `4`, `10`
* `goals` (optional): Show goal scorers, `true` or `false`
* `assists` (optional): Show assists, `true` or `false`
* `show_badges` (optional): Display team badges, `true` or `false`
* `show_dates` (optional): Display match dates, `true` or `false`
* `order` (optional): Whether to order ascending or descending, `asc` or `desc` *(default)*
* `timezone` (optional): The timezone to convert match times to, e.g., `Europe/London` ([complete list](https://php.net/manual/en/timezones.php))
* `default_css` (optional): Use the default widget styles, `true` or `false`
* `omit_errors` (optional): Omit error messages, `true` or `false`

*Only one of `competition` or `team` is required.

== Frequently asked questions ==



== Screenshots ==



== Changelog ==

= 3.1.0 =
* Feature: Allow results to be shown for a specific group via the new `group` parameter

= 3.0.0 =
* Refactor: Update plugin for new API

= 2.1.2 =
* Hotfix: Prevent match scores from wrapping

= 2.1.1 =
* Hotfix: Possible issue loading language/CSS files

= 2.1.0 =
* Feature: Added `assists` parameter

= 2.0.0 =
* **BREAKING CHANGE**: Feature: Added `season` parameter to replace the `year` parameter

= 1.23.1 =
* Hotfix: Check options exist before using them

= 1.23.0 =
* Feature: Allow results to be shows for a specific season via the new `year` parameter

= 1.22.2 =
* Hotfix: Check highlight value against short and full team names

= 1.22.1 =
* Hotfix: Check the before/after widget/title bits exist before using them

= 1.22.0 =
* Feature: Translate dates if using non-English.

= 1.21.2 =
* Hotfix: Load relevant language file based on the default language for the site

= 1.21.1 =
* Hotfix: Match event times should be single quoted, e.g., 10' instead of 10''

= 1.21.0 =
* Feature: Show when a match has been won on penalties

= 1.20.1 =
* Hotfix: Fixed missing team badges

= 1.20.0 =
* Feature: Added multi-language support. If you're interested in translating for us, please get in touch at [hello@statsfc.com](mailto:hello@statsfc.com)

= 1.19.2 =
* Hotfix: Added a responsive horizontal scroll if the widget is too wide for mobile

= 1.19.1 =
* Hotfix: Fixed possible `Undefined index: omit_errors` error

= 1.19.0 =
* Feature: Put CSS/JS files back into the local repo
* Feature: Enqueue style/script directly instead of registering first

= 1.18.0 =
* Feature: Added `omit_errors` parameter
* Feature: Load CSS/JS remotely

= 1.17.3 =
* Hotfix: Fixed "Invalid domain" bug caused by referal domain

= 1.17.2 =
* Hotfix: Minor bug fix with `to` example value

= 1.17.1 =
* Hotfix: Fixed bug saving 'Highlight team', 'Show goals', 'Show badges' and 'Show dates' options

= 1.17.0 =
* Feature: Added `highlight`, `goals`, `show_badges` and `show_dates` parameters

= 1.16.0 =
* Feature: Allow more discrete ads for ad-supported accounts

= 1.15.0 =
* Feature: Enabled ad-support

= 1.14.0 =
* Feature: Added `order` parameter

= 1.13.0 =
* Feature: Use built-in WordPress HTTP API functions

= 1.12.0 =
* Feature: Added badge class for each team

= 1.11.0 =
* Feature: Default `default_css` parameter to `true`

= 1.10.0 =
* Feature: Updated team badges.

= 1.9.0 =
* Feature: Added `[statsfc-results]` shortcode.

= 1.8.0 =
* Feature: Tweaked CSS.

= 1.7.0 =
* Feature: Allow an actual timezone to be selected, and use the new API.

= 1.6.0 =
* Feature: Tweaked error message.

= 1.5.0 =
* Feature: Added fopen fallback if cURL request fails.

= 1.4.1 =
* Hotfix: Fixed possible cURL bug.

= 1.4.0 =
* Feature: Use cURL to fetch API data if possible.

= 1.3.0 =
* Feature: Added Community Shield results.

= 1.2.1 =
* Hotfix: Fixed a bug when selecting a specific team.

= 1.2.0 =
* Feature: Added a setting for number of results. Applies to single team only. Choose '0' to display all results.

= 1.1.0 =
* Hotfix: Fixed various bugs
* Feature: More relevant scores/status for matches that were decided after extra-time or penalties.

== Upgrade notice ==

