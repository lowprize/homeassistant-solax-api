# homeassistant-solax-api
SolaX Power official web API

Install:
add line to configuration.yaml:

**sensor: !include sensor.yaml**

Example:
```
# Configure a default setup of Home Assistant (frontend, api, etc)
default_config:

# Text to speech
tts:
  - platform: google_translate

automation: !include automations.yaml
script: !include scripts.yaml
scene: !include scenes.yaml
sensor: !include sensor.yaml
```

Get tokenID thru web app of Solax: https://www.solaxcloud.com/#/api

Get SN from Label 

Edit sensor.yaml, add tokenID and SN

Upload sensor.yaml to config dir and restart Home Assistant

API docs: https://www.solaxcloud.com/phoebus/resource/files/userGuide/Solax_API.pdf

Note:
Tested on X3-Hybiyd/Fit
