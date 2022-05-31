# Bluetooth Fan

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![License][license-shield]](LICENSE)
[![hacs][hacsbadge]][hacs]
[![Community Forum][forum-shield]][forum]

![Project Maintenance][maintenance-shield]
[![BuyMeCoffee][buymecoffeebadge]][buymecoffee]


_Component to integrate with [Chungear, Harbor Breeze, or Hunter bluetooth fans][bluetooth_fan]._


## Notes:
- **This integration ONLY works with Chungear Industrial / Satellite Electronic fan controllers that support bluetooth. It does not support RF only fans (433mhz, etc) or Wifi Fans.**
- **Your server must have bluetooth capability to use this integration.**


**This component will set up the following platforms.**

Platform | Description
-- | --
`fan` | Set the speed of a 3 speed fan.
`light` | Toggle and set the brightness of a light connected to the fan.

## Installation

1. Using the tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
2. If you do not have a `custom_components` directory (folder) there, you need to create it.
3. In the `custom_components` directory (folder) create a new folder called `bluetooth_fan`.
4. Download _all_ the files from the `custom_components/bluetooth_fan/` directory (folder) in this repository.
5. Place the files you downloaded in the new directory (folder) you created.
6. Restart Home Assistant
7. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Bluetooth Fan"

Using your HA configuration directory (folder) as a starting point you should now also have this:

```text
custom_components/bluetooth_fan/translations/en.json
custom_components/bluetooth_fan/translations/nb.json
custom_components/bluetooth_fan/translations/sensor.nb.json
custom_components/bluetooth_fan/__init__.py
custom_components/bluetooth_fan/config_flow.py
custom_components/bluetooth_fan/const.py
custom_components/bluetooth_fan/fan.py
custom_components/bluetooth_fan/light.py
custom_components/bluetooth_fan/manifest.json
```

## Configuration is done in the UI

<!---->

## Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

***

[bluetooth_fan]: https://github.com/JohnnyNoodlez/bluetooth-fan
[buymecoffee]: https://www.buymeacoffee.com/JohnnyNoodlez
[buymecoffeebadge]: https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg?style=for-the-badge
[commits-shield]: https://img.shields.io/github/commit-activity/y/JohnnyNoodlez/bluetooth-fan.svg?style=for-the-badge
[commits]: https://github.com/JohnnyNoodlez/bluetooth_fan/commits/master
[hacs]: https://github.com/hacs/integration
[hacsbadge]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge
[exampleimg]: example.png
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge
[forum]: https://community.home-assistant.io/
[license-shield]: https://img.shields.io/github/license/JohnnyNoodlez/bluetooth-fan.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-John%20Rice%20@JohnnyNoodlez-blue.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/JohnnyNoodlez/bluetooth-fan.svg?style=for-the-badge
[releases]: https://github.com/JohnnyNoodlez/bluetooth_fan/releases
