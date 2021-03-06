# Seren For Kodi - plugin.video.seren
Repository for Seren Development

This version of Seren may be unstable and may result in some undesired behavior. Use is at own risk

Change Log:

### Version 0.1.13 Changelog:
* Source Select items now clickable
* Esc Key now closes Source Select dialog

### Version 0.1.12 Changelog:
* Added premiumize transfer database cleanup to maintenance script
* Changed scrobble ID back to Trakt as IMDB ID was unreliable causing trakt progress for some random show called pride
* if the IMDB ID wasn't available for an episode (sorry for my testers watching origin)
* Fixed issue with keepalive not dying causing scrobble issues and issues with Upnext
* Added 265 priority sort
* Some spelling mistakes
* Changed Upnext episode IDs to Trakt ID
* Added setUniqueIDs to tools.addDirectoryItem function
* Hide Item in trakt manager now actually sends the trakt request (Bad nix)

### Version 0.1.11 Changelog:
* Added workaround for Kodi 18 Widgets
* Increased support for Kodi 18 player
* Fixed issue with Kodi 18 where pre-emptive scraping wouldn't occur
* Adjusted menu content types so they now respect their content correctly

### Version 0.1.10 Changelog:
* Adjusted Migration Script so it no longer broke Super Faviorates
* Adjusted TMDB movie artwork to fix issue where it would display the wrong media (removed thumbnail)

### Version 0.1.09 Changelog:
* Increased torrent file identification
* Extended timeout for failed cache assit attempts to 3 hours
* Changed Trkat Scrobble Object to current playing item IMDB Number
* Fixed Trakt Scrobbling with Up Next Addon Intergration
* Fixed Trakt Scrobbling when seeking
* Added increased fallbacks for TV show metadata

### Version 0.1.08:
* Restructed Settings page to use subsetting attribute
* Added Support for Context Menu Addon

### Version 0.1.07:
* Added automatic migration from incorrect addon ID release
* Added Notification if no sources are found during pre-scrape
* Removed manual cache dialog prompt during pre-emptive scraping
* Cache inserts now threaded
* Added Semaphore to relieve thread pressure on database
* Fixed KeyError exception in TVDB episode function
* Custom Windows are now removed from scope with del
* Removed Please Check Internet Connection Dialog
* Added Logging for RD refresh Errors

### Version 0.1.06:
* Added 3D filter Setting
* Added File Size Limit
* Added View types for Seasons, Episodes and Default for Menus
* Added Debrid Priorities
* Added Install UpNext Addon Setting
* Fixed capitalised Addon ID
* Fixed issue where TVDB token was not initially created
* Added ability to hide items from trakt manager
* Adjusted Source Select to multiline string
* Increased listitem size in custom source select window

### Version 0.1.05:
* Added better Hoster support
* Changed hoster domains to (domain, name) tuple
* Fixed issue where color change would set color even if cancelled
* Cleaned up logging
* Fixed Manual Caching
* Adjusted Manual Caching display string
* Fixed View Types not being set

