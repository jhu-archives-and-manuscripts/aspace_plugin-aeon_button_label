## Summary

This plugin modifies the behavior of the [ArchivesSpace-Aeon-Fulfillment-Plugin](https://github.com/AtlasSystems/ArchivesSpace-Aeon-Fulfillment-Plugin)
plugin. It is not designed for standalone use.

---

## Customizations

### Button label text

  - Button label text is changed from the default (currently "Aeon Request") to simply "Request".

---

## Activate the plugin
- Install the plugin:
  - Clone this repository into the plugins/aeon_button_label directory; or
  - Unzip the release zip into the plugins/aeon_button_label directory.

- Enable the plugin and the associated theme:
  - In config/config.rb, add the plugin name to the "AppConfig[:plugins]" list, e.g.:

    AppConfig[:plugins] = ['aeon_button_label']

- Restart ArchivesSpace

