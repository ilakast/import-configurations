# Firefly III CSV importer configuration files

This repository contains standardized import configurations for the [Firefly III CSV importer](https://github.com/firefly-iii/csv-importer).

Various banks and financial institutions have already been added by contributing users. Thank you!

## Finding an import configuration for your bank.

Browse the files above, which are grouped by country and then by bank.

In the folder `other-software` you will find import configurations for other financial tools. In `firefly-iii`, you will find import configurations for Firefly III itself.

## All contributors

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-13-orange.svg?style=flat-square)](#contributors)
<!-- ALL-CONTRIBUTORS-BADGE:END --> 

## Adding an import configuration

First of all, thanks for adding your configuration! 🎉

These instructions will help you add a configuration file to the project which others can use. You can do this on GitHub itself, without having to use command line tools or weird commands.

1. Find the correct country code for the bank your configuration file relates to. Check out [this list of country codes](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements).
2. Log into GitHub and fork the project using the icon at the top right of the screen.  More info can be found in [the GitHub help pages](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo).
3. From the forked repo select **Create New File**.
4. To create folders type `<country code>/<bank name>/default.json` e.g `gb/monzo/default.json`.
5. Paste your `.json` file contents into the file window.

⚠️ Before you continue, make sure that the JSON file contains no private data, like account names.

Then, finish the commit:

1. Type a commit title and message so the owner knows what benefits the change gives.
2. Select your account from the dropdown.
3. Select __Create a new branch for this commit and start a pull request__.
