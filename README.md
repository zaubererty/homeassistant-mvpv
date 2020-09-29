# homeassistant-kostalplenticore

Home Assistant Component for AC-Thor of MyPV

<a href="https://www.buymeacoffee.com/ittv" target="_blank"><img height="41px" width="167px" src="https://cdn.buymeacoffee.com/buttons/default-blue.png" alt="Buy Me A Coffee"></a>

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

### Installation

Copy this folder to `<config_dir>/custom_components/mypv/`.

### HACS
Search for MyPV

### Configuration

Add the following to your `configuration.yaml` file:

```yaml
# Example configuration.yaml entry
sensor:
    - platform: mypv
      host: <IP>
```