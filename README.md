# Introduction

This repository contains a set of scripts and dotfiles for setting up a new Macbook.

### Automated setup

1. Sign in in App Store

2. Run `./setup.sh`

> Running the script repeatedly will install missing packages and upgrade the existing ones.

3. Run `./setup_ssh.sh` (if you need a new SSH key)

### Manual setup

Not everything is on Appstore. Some good tools should be installed manually:

- [Ludwig](https://ludwig.guru)
- [iA Writer](https://ia.net/writer)

I use Safari to browse the internet. All Safari extensions I need have been installed programmatically via `Brewfile`.

I use Chrome for web app development. Unlike Safari, Chrome plugins must be installed manually:

- [Vue DevTools](https://addons.mozilla.org/en-US/firefox/addon/vue-js-devtools/)
