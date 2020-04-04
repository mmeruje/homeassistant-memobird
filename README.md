# memobird-homeassistant
A Home-Assistant component for Memobird

## Installation

Copy `custom_components` to your Home Assistant setup (usualy `/home/homeassistant/.homeassistant/`)

## Configuration

Add the following line to your `configuration.yaml` file

```
notify:
  - name: MyMemobirdPrinterName
    platform: memobird
    api_key: MyAccessKey
    device_id: MyDeviceID
```
