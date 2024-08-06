# ☕ Coffee Machine Automation Blueprint

## Overview

This Home Assistant blueprint automates your coffee machine using a schedule helper and optional wattage-based heat-up detection. It provides a smart and flexible way to manage your daily coffee routine.

## Features

- 🗓️ Schedule-based triggering
- ⚡ Optional wattage-based warmup detection
- 🏡 Person presence check
- 📱 Mobile notifications with action buttons
- ⏱️ Configurable delays and messages

## Requirements

- Home Assistant
- A smart switch to control your coffee machine
- (Optional) A power monitoring plug for wattage-based detection

## Installation

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flasharor%2Fespresso-blueprint%2Fblob%2Fmain%2Fespresso.yaml)


## Configuration

When creating an automation using this blueprint, you'll need to configure the following:

- Coffee machine switch
- Person entity for presence detection
- Notification device
- Schedule entity
- Warmup mode (time-based or wattage-based)
- For wattage based detection additional helpers are required. These can be configured from the blueprint. 
- Various timing and message settings

Refer to the blueprint description for detailed information on each configuration option.

## Usage

Once configured, the automation will:

1. Turn on the coffee machine based on the schedule
2. Send a notification asking if you want coffee
3. Warm up the machine (using time or wattage detection)
4. Send notifications when coffee is ready and before turning off
5. Automatically turn off the machine after a set time

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Home Assistant community for inspiration and support
- Coffee lovers everywhere 🌍☕
