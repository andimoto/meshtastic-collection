# Meshtastic Info Collection

This Repo stores my Meshtastic related Builds, Measurements, etc.
As I'm searching for Power Consumption of Meshtastic Devices, I also want
to share the measurements of the devices I have and which I used for my builds.


# Power Consumption

```
All Measurements have been done over USB Connection @5V with "Qway USB Measurement Device"
```

| Device | flashing |  not initialized | BT | Wifi |
|----|----|----|----|----|
| LilyGo Lora32 T3_V1.6.1 | @5.125V 40mA 0.2W | @5.125V 60mA 0.3W | @5.125V 60mA 0.3W | @5.125V 135mA 0.68W |
| Heltec V3 | @5.125V 40mA 0.2W | @5.115V 125mA 0.6W |  |
| Heltec Wireless Stick Lite v3.1 | @5.125V 45mA 0.25W | @5.115V 110mA 0.56W | @5.115V 110mA 0.56W  | |

# Builds

## rak19007 WisBlock Node

- WisBlock rak19007
- BMP280
- Waveshare MPPT A
- 3500mAh Li Ion Battery
- 3D Printed case and holder

Will be used to read out a Victron MPPT 100/20 and forward to my other nodes which will (hopefully) work with Home Assistant to intergrate telemetry of the Victron into HA.

|![](builds/rak-node-001/001.jpg)|![](builds/rak-node-001/002.jpg)|![](builds/rak-node-001/003.jpg)|
|----|----|----|
|![](builds/rak-node-001/004.jpg)|![](builds/rak-node-001/005.jpg)|![](builds/rak-node-001/006.jpg)|
|![](builds/rak-node-001/007.jpg)|![](builds/rak-node-001/009.jpg)|![](builds/rak-node-001/0011.jpg)|

# LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Dieses Werk ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz</a>.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
