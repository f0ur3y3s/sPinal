# sPinal

sPinal turns a Raspberry Pi Zero W or any other wifi-capable Raspberry Pi board into a simultaneous Wifi Client and Access Point.

The end goal of sPinal is to create a standalone device capable of creating a secure VPN connection to a server of your choice. Any other internet capable device can then connect to the Pi, preventing any information leakage.

---

## Usage

```
curl https://github.com/43y3s/sPinal/blob/master/configure -a MyAP myappass -c EnterWiFiSSID EnterWifiPass
```

## Credit

Many thanks to the author of the configuration script,[Darko Lukic](lukicdarkoo@gmail.com), and albeec13 on github for his wifi AP + client [guide](https://albeec13.github.io/2017/09/26/raspberry-pi-zero-w-simultaneous-ap-and-managed-mode-wifi/)