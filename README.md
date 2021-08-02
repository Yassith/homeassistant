# homeassistant

Here are my config files of Home Assistant related to energy metering together with Huawei photovoltaics integration.
Feel free to adopt if need anything

# modbus

Modbus directory is supposed to hold config files for hardware communicating through this protocol.
For now it is only Huawei inverter ofr PV but future will bring new ones. Should you have any other equipoment you may need to update/remove this

# sensors

This directory is supposed to bring some order into sensors. Currently I have :

1. huawei_solar.yaml - this is mainly leftovers after moving Huawei sensors into modbus file
2. Supla.yaml - sensors related to my power meter. Here is where whole math is being done. Depending on your hardware use as a base for your configuration.
3. Supla_mqtt.yaml - topics for calculating daily/monthly/annual data over mqtt platform
4. Supla_sensor_template.yaml - sensors for those cumulative readings (daily/monthly/annual). They sue data from topics in previous point

# automations

scripts to take end of day/month/year summary


# disclaimer

Thise files may not be perfect, contain mistakes of lack optimisation. Most of the time I don't care as there will always be space for improvement but moreover I'm on my learning curve which may be different than yours :)

Cheers
Wojtek
