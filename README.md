# Recipes Unlocked — WoW Forever

Independent profession catalogs with native WoW item/recipe tooltips, reagents, acquisition sources and navigation. No What's Training dependency.

All twelve professions have separate LoadOnDemand data modules: Alchemy, Blacksmithing, Cooking, Enchanting, Engineering, First Aid, Fishing, Herbalism, Leatherworking, Mining, Skinning and Tailoring. Only an opened profession loads its data. Opposite-faction-only recipes are hidden.

## Install with WowUp CF

Choose WoW Forever → **Install from URL** → paste:

https://github.com/20913Tdog/RecipesUnlocked-Releases

After installing new profession modules, restart WoW completely before opening them.

For manual installation download the latest `RecipesUnlocked-…-forever.zip`. During active development keep auto-updates disabled after the successful one-time WowUp test; development installs continue directly to D:.

## Releases and sources

Development stays in a separate private repository. This repository contains only release documentation, the updater workflow and finished downloads attached to Releases. Lua source is included in the addon ZIP. The corresponding `-sources.zip` contains editable per-profession catalog JSON, the offline builder, tests, provenance and licences.

The GitHub updater runs daily at 06:23 UTC and can be started manually. It checks LibProfessionDB and foreverfraddons/forever-db versions, updates changed catalogs, runs tests and publishes validated changes. It uses this repository's own GITHUB_TOKEN, with no stored personal token.

Original addon/tool code: MIT. Imported merged data: GPL-3.0 and included upstream notices. Missing data stays unknown; borrowed Classic source records remain labelled. Coverage is not guaranteed complete.
