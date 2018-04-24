Gerrit webhooks
===============

[![Join the chat at https://gitter.im/GetBadges/gerrit-webhooks](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/GetBadges/gerrit-webhooks?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![GetBadges Game](https://getbadges-gerrit-webhooks.getbadges.io/shield/company/getbadges-gerrit-webhooks)](https://getbadges-gerrit-webhooks.getbadges.io/?ref=shield-game)

Overview
--------
Set of gerrit hooks that will fire webhooks to your URLs. Inspired by jerrit.

More info on hooks at:
https://gerrit.googlesource.com/plugins/hooks/+/HEAD/src/main/resources/Documentation/config.md

Requirements
------------
 - `requests` library

Installation Steps
-------------------
 - Install `requests`
 - Drop hook files into `$site_path/hooks`
 - Setup config file in the home folder for the user that runs gerrit: ~/.gerrit-webhook

Config file
------------
This plugin looks for a config file at ~/.gerrit-webhook
See `gerrit-webhook.example`
