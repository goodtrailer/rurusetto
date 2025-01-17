---
layout: page
title: install and update rulesets
permalink: /install/
img: None
summary: "Instruction to install and update rulesets to osu!lazer."
---

# download rulesets file

Ruleset files can be obtained at [rulesets status page](https://rulesets.info/pages/status) and then clicking on the `detail & download` button on the desired ruleset.

![status page](img/status-download.png)

A dialog will appear with a changelog. Click the `Download` button at the bottom-right corner to initiate the download.

![sentakki release download](img/sentakki-release-download.png)

The changelog and download link will automatically update when a ruleset is updated.

# import rulesets to osu!lazer

### step 1: navigate to osu! data directory

In osu!lazer's setting panel, there is a button to `Open osu! folder` within the "General" section. On windows you could navigate to the data folder directly via Windows Explorer, by default this location is `%AppData%/osu!/rulesets`. On MacOS default this location is in application itself.

![open-osu-folder.png](img/open-osu-folder.png)

### step 2: installing the ruleset

Copy the ruleset file (.dll file that you just downloaded) into the rulesets directory, do make sure that duplicate copies of the ruleset are overwritten.

Other rulesets also could share the same folder.

### stpe 3: have fun!

After completing the above steps, you may need to restart osu!lazer if it is already open. Once restarted, you should see the ruleset alongside the standard rulesets.

![complete installation](img/rulesets-complete.png)

# update rulesets

To update rulesets, just do the same step and overwrite the old rulesets file.