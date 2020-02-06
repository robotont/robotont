# robotont
The metapackage for robotont

## Quick Start Guide
- Physically build your robot, connect a power supply (battery or power adapter) and turn on the robot. You may also need to turn on the onboard computer separately.
- By default, the robot creates a wireless hotspot with SSID "clearbot-#", where # is the robot's number, and password "t0ndik00bas". Connect to it from a device with SSH capability (e.g. a laptop).
    - Robot's number can be found on a sticker on the front side of the onboard computer.
- SSH into the robot at `kasutaja@clearbot-#` where # is the robot's number (same as the wireless SSID connected to) and default password `t0ndik00bas`.
    - If your device is unable to connect to the robot based on hostname, then try connecting based on IP-address: `kasutaja@192.168.200.#` where # is again your robot's number.
- Launch a demo program using the command `roslaunch robotont_teleop teleop_keyboard.launch` and control the robot using your keyboard.
    - For controls, see the terminal output when launching the command.

For a more thorough tutorial for beginners as well as tutorials on other topics see the [Robotont homepage](http://robotont.ut.ee/).

[![Build Status](https://travis-ci.org/robotont/robotont.svg?branch=master)](https://travis-ci.org/robotont/robotont)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
