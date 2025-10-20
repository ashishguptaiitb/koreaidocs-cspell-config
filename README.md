# Cspell configuration file

This repo contains the config file for Cspell that is specific to our docs and terminology.

Two prominent uses are:
* For writers: Use in VSCode when authoring content. Within VSCode UI. Imported config.
* For editors: Use via CLI when checking repo health. Native config via [json file](.cspell.json). The following are a few CLI examples:
  * Check one file `npx cspell --config <path to .cspell.json> <path of MD files>`
  * Recursively check files in the current folder `npx cspell --config <path to .cspell.json> .`
  * Recursively check MD files in the current folder `npx cspell --config <path to .cspell.json> "**/*.md"`
  * Recursively check MD files in the current folder and save the output in a local file `npx cspell --config <path to .cspell.json> "**/*.md" > <path of a local file>`
