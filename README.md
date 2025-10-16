# Cspell configuration file

This repo contains the config file for Cspell that is specific to our docs and terminology.

A few ways to execute in our repo are:

* Check one file `npx cspell --config <path to .cspell.json> <path of MD files>`
* Recursively check files in the current folder `npx cspell --config <path to .cspell.json> .`
* Recursively check MD files in the current folder `npx cspell --config <path to .cspell.json> "**/*.md"`
* Recursively check MD files in the current folder and save the output in a local file `npx cspell --config <path to .cspell.json> "**/*.md" > <path of a local file>`
  * Example, run this command in the Agent Platform docs folder `npx cspell --config C:\Users\Ashish.Gupta\Documents\GitHub\koreaidocs-cspell-config\.cspell.json "**/*.md" > spellcheck-agent-platform.txt`

Credits to, 

* [Cspell project](https://cspell.org/about)
