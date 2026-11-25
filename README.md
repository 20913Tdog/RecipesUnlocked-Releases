# Recipes Unlocked releases

Install the addon with WowUp CF using **Install from URL**:
https://github.com/20913Tdog/RecipesUnlocked-Releases

The current development version uses only ForeverDB and has independent
load-on-demand modules for all twelve professions. Data from ForeverDB.net:
https://foreverdb.net and https://github.com/foreverfraddons/forever-db.
Wowhead is only a copyable link in the UI, never a data source.

The private development pipeline checks ForeverDB daily, validates and tests
the complete generation, and produces addon/source ZIPs. During active
development installation continues directly into the local WoW AddOns folder.
Public automatic releases remain paused; disable WowUp automatic updates for
this addon while testing local development builds.

Future releases contain an addon ZIP and its corresponding source/license
ZIP. Original addon and build-tool code: MIT. Imported data retains its
upstream licences and notices. Existing test releases may predate this migration.
