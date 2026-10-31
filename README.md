# oldsnooz

Home Assistant custom integration for Snooz Bluetooth devices. This fork uses
the `oldsnooz` integration domain so it can be installed alongside the original
Snooz integration.

## Installation with HACS

1. In HACS, open the menu and choose **Custom repositories**.
2. Add this GitHub repository URL and select **Integration** as the category.
3. Install **oldsnooz**, then restart Home Assistant.
4. Open **Settings > Devices & services > Add integration** and search for
   `oldsnooz`.

## Manual installation

Copy `custom_components/oldsnooz` into the `custom_components` directory in
your Home Assistant configuration, then restart Home Assistant and add the
`oldsnooz` integration from **Settings > Devices & services**.

The integration discovers supported Snooz devices over Bluetooth. Keep the
original Snooz Bluetooth identifiers unchanged when modifying this fork.


This is based on an older version of the snooz home-assistant core component
https://github.com/home-assistant/core/tree/2026.9.4/homeassistant/components/snooz
