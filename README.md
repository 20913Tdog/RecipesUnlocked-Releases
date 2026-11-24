# Recipes Unlocked — Cooking releases

WoW Forever Cooking catalog with native item tooltips and on-demand data loading.

## Install with WowUp CF

Select WoW Forever, choose **Install from URL**, and paste:

https://github.com/20913Tdog/RecipesUnlocked-Releases

Download `RecipesUnlocked-…-forever.zip` for a manual installation.

Development remains in a separate repository. This repository contains the release updater workflow and finished addon/source packages in Releases. No personal token is stored in the workflow.

The updater checks LibProfessionDB and foreverfraddons/forever-db daily, validates Cooking data, runs the bundled tests and publishes only changed packages. Missing/unconfirmed sources stay labelled.

Lua code is included in the addon ZIP; the corresponding `-sources.zip` includes editable Cooking JSON, its offline builder and source/license notices. Addon/tool code: MIT. Imported merged data: GPL-3.0 and upstream notices (included in the downloads).

During active development, disable automatic updates for this addon after the one-time WowUp test and keep using direct local deployment.
