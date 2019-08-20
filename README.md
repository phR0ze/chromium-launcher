# chromium-launcher [![Build Status](https://travis-ci.org/foutrelis/chromium-launcher.svg?branch=master)](https://travis-ci.org/foutrelis/chromium-launcher) [![Coverage Status](https://coveralls.io/repos/github/foutrelis/chromium-launcher/badge.svg)](https://coveralls.io/github/foutrelis/chromium-launcher)

Chromium launcher with support for Pepper Flash and custom user flags.

Forked from `foutrelis/chromium-launcher`. All credit goes to `Evangelos Foutras`. The only
change I've made is to change the config location and name.

## Usage
This launcher was originally written for the Arch Linux Chromium package.

It is meant to be installed as `/usr/bin/chromium` and act as a wrapper around
the Chromium binary. The configuration file is looked for at `/etc/chromium/launcher.conf`

Running `chromium --help` will show the config location file along with a list of the custom flags it
was able to read from it. If PepperFlash was found on the system, it will generate and display flags
for that as well.

## License

This project is licensed under ISC.
