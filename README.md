<!--

---
lang: american
---
-->

[![Build Status](https://travis-ci.org/cw-ansible/cw.wireless.svg?branch=master)](https://travis-ci.org/cw-ansible/cw.wireless)
[![Tweet this](http://img.shields.io/badge/Tweet-it00aced.svg)](https://twitter.com/intent/tweet?tw_p=tweetbutton&via=renard_0&url=https%3A%2F%2Fgithub.com%2Fcw-ansible%2Fcw.wireless&text=Configure%20%23Linux%20wireless%20network%20with%20%40ansible%20and%20allow%20remote%20encrypted%20root%20FS%20unlock%20over%20%23WIFI.)
[![Follow me on twitter](http://img.shields.io/badge/Twitter-Follow-00aced.svg)](https://twitter.com/intent/follow?region=follow_link&screen_name=renard_0&tw_p=followbutton)


# Wireless

Configure wireless.


## Usage

Include `cw.wireless` role to your playbook.

## Description

This module will install `wpasupplicant` package and configure wireless
interfaces in `/etc/network/interfaces.d/wlan`.

if `wireless_bootime` is defined and `true`, required hooks and scripts will
be deployed to allow wireless network to be run at boot time. This might be
useful if you need to remotely unlock your root file system (you have to
install `dropbear` for that).

## Configuration

See specific documentation in `defaults/main.yml`

## Copyright

Author: Sébastien Gross `<seb•ɑƬ•chezwam•ɖɵʈ•org>` [@renard_0](https://twitter.com/renard_0)

License: WTFPL, grab your copy here: http://www.wtfpl.net
