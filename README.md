# Recipes Unlocked — WoW Forever

Native profession book with unlearned recipes, item and reagent tooltips,
acquisition sources, faction filtering, navigation and drop-chance sorting.
All twelve professions have separate load-on-demand data modules.

## Install and update with WowUp CF

Select **WoW Forever → Install from URL** and paste:

https://github.com/20913Tdog/RecipesUnlocked-Releases

Enable automatic updates for **Recipes Unlocked**. WowUp downloads the latest
complete addon package during its update checks. If WoW is running, use
`/reload` after an update; restart WoW if new addon folders were installed.
No Python installation or local updater helper is required.

For manual installation, download the `RecipesUnlocked-…-forever.zip` asset
from the latest release and extract its addon folders into `Interface/AddOns`.
The separate `-sources.zip` is for editable sources and license information,
not for installation. `release.json` identifies the Forever installation ZIP
for WowUp.

## Data and releases

Primary data: [ForeverDB.net](https://foreverdb.net) and the
[official ForeverDB database](https://github.com/foreverfraddons/forever-db).
Wowhead Forever supplements genuinely missing fields before packaging;
known ForeverDB facts are retained. Missing facts remain marked as `???`.
The game makes no external HTTP requests.

The private build pipeline checks data twice daily at **08:17 and 20:17 UTC**,
one hour after ForeverDB's scheduled builds. GitHub may delay scheduled jobs.
Changed packages are released after source validation and the Python/Lua test
suite pass. Uploads are staged privately and SHA-256 checked before publication.
Unchanged packages do not create another release. Failed checks or uploads
leave the last public release available.

This repository hosts release documentation and finished packages. Development
remains separate. Each release includes the addon, corresponding editable
sources, WowUp metadata and SHA-256 checksums. Original addon/build-tool code:
MIT. Imported data retains the upstream licenses and attribution notices
included in both downloads.
