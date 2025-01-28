# Zen Changelog

## [Fix Profile Detection] - {PR_MERGE_DATE}

- Fixed "Zen Browser not installed" error by improving profile detection
- Added support for ".Default (release)" profile pattern
- Added fallback to use any available profile if no default profile is found
- Maintained backward compatibility with custom and alpha profiles

## [Fix Error: Zen Browser browser is not installed] - {PR_MERGE_DATE}

- Fix new tab command, by removing unnecessary app check.

## [Fix New Tab] - 2025-01-11

- Fix new tab command, by removing unnecessary app check.

## [Update Logo] - 2024-12-11

- Updated to latest logo since rebrand.

## [Fix Bookmark Duplicates Issue] - 2024-11-21

- Fix duplicate entries in bookmark search results. Previously, bookmarks would show up multiple times if they had tags. Now each bookmark appears only once regardless of how many tags it has.

## [Fix Bookmark Search] - 2024-11-18

- Fix Bookmark search by using the SQlite DB instead of bookmarkbackups directory.

## [Initial Version] - 2024-10-02

- Copied Firefox extension and rename all necessary parts.
