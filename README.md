# tp_smapi ThinkPad battery management in Linux 

## Category

Laptop power management

## Description

tp_smapi enables ThinkPad Linux Laptop to start/stop charging at specified level

This suppose to extend battery life time.

Example

Stop charging at 79%

Start charging at 20&

Try to reload tp_smapi when systemctl cannot start service after kernel update.

`sudo modprobe tp_smapi`

confirm by

`sudo echo 75 > /sys/devices/platform/smapi/BAT0/stop_charge_thresh `

## Demo in Animation

## Overview

## Requirements

tp-smapi-dkms

## Install

`sudo apt -y install tp-smapi-dkms`

## Usage

## Contribution

## Updates

## Licence
[MIT]

## Author

[linuxkay](https://github.com/linuxkay)
