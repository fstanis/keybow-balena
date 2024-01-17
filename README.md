# Keybow and Keybow MINI for balena cloud

[![balena deploy button](https://www.balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https%3A%2F%2Fgithub.com%2Ffstanis%2Fkeybow-balena)

This repo is a docker image wrapper around the
[`keybow-firmware`](https://github.com/pimoroni/keybow-firmware) project,
mainly meant to be used with [balena](https://www.balena.io/).

## Configuring

The main entry point, `/boot/keys.lua`, is read from the `keybowKeys` variable.
This allows you to change the behavior without having to modify the image.
