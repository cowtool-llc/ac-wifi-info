# Air Canada Wifi Installation Status

This is based on wifi data that is stored when a flight is loaded on https://acflightstatus.cowtool.com/.

For the CSV to update, either:
1. A new FIN has been added
2. The FIN's wifi status or technology has changed

However, if the wifi technology is not 2Ku or ESA (or 5G, for the bus), or it doesn't have wifi, it will update regardless, at most once per day, to show the last date that FIN was checked.

The CSV is automatically updated hourly if anything has changed.
