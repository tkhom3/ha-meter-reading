# ha-meter-reading

## Guides

- https://youtu.be/8uB-vFmEuD0?si=Epo6eAhgZ4IpgfQh
- https://youtu.be/xOgEjd_2hnA?si=IHAdpOhic442TAJm

## Interesting Repos
- https://github.com/bemasher/rtlamr-collect
- https://github.com/bemasher/rtlamr

# Meters

## Electric

Meter: sk9ami7

https://github.com/bemasher/rtlamr

Device: Nooelec NESDR Mini USB RTL-SDR & ADS-B Receiver Set

## Water

Meter: iPerl

- https://github.com/zibous/ha-watermeter?tab=readme-ov-file
- https://community.home-assistant.io/t/looking-for-help-using-iperl-watermeter-with-esphome-esp32-cc1101/868031

## Gas 

Guide: https://www.rickmakes.com/collecting-power-and-gas-meter-data-for-home-assistant-using-raspberry-pi-and-sdr/

`sudo rtl_433 -f 912M`
12 93652251 100G DLS
Reading: 7106

id: 93652251

```
time      : 2025-08-11 17:24:55
model     : SCMplus      id        : 93652251
Protocol_ID: 0x1E        Endpoint_Type: 0x9C       Endpoint_ID: 93652251     Consumption: 710600       Tamper    : 0x0F08        crc       : 0xBF64        Meter_Type: Gas           Integrity : CRC
```
