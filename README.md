# update.pmmp.io

This repository contains stuff used by https://update.pmmp.io/api.

## api.php
This script serves the newest version of https://update.pmmp.io/api.

## channels/*.json
These files contain information about build channels served by update.pmmp.io, such as information on the versions of PHP required, compatible Minecraft versions, download URLs and more.

These files are generated by `build/generate-build-info-json.php` in the pmmp/PocketMine-MP repository and automatically committed here by GitHub Actions whenever a new GitHub Release is published.
