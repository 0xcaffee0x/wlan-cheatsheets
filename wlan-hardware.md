# USB Adapters

## 2.4 GHz only (single radio - single band)

### Atheros

| Driver |  ID | Chipset | Radio | Vendor |  Modelname | HW Rev | API | Monitor Mode | Packet-Injection | SoftAP | Confirmed |
| ------ | --- | ------- | ------ | ---------- | -------| ------  | ----- | ----- | ---- | ----- | ---- |
| ath9k_htc | 0cf3:9271 | AR9271 | 1T1R | TP-Link | TL-WN722N | | nl80211 | 2.4GHz | 2.4 GHz| Not working |5.7.0-kali3-amd64 VirtualBox6.1 |

### Realtek
| Driver |  ID | Chipset | Radio | Vendor |  Modelname | HW Rev | API | Monitor Mode | Packet-Injection | SoftAP | Confirmed |
| ------ | --- | ------- | ------ | ---------- | -------| ------  | ----- | ----- | ---- | ----- | ---- |
| rtl8192cu | 7392:7811  | RTL8188CUS | 1T1R | Edimax | EW-7811Un |  | nl80211 | 2.4GHz | 2.4GHz | Not working |5.7.0-kali3-amd64 VirtualBox6.1 |

## 2.4 + 5 GHz (single radio - dual band)

### Mediatek/Ralink

| Driver |  ID | Chipset | Radio | Vendor |  Modelname | HW Rev | API | Monitor Mode | Packet-Injection | SoftAP | Confirmed |
| ------ | --- | ------- | ------ | ---------- | -------| ------  | ----- | ----- | ---- | ----- | ---- |
| mt76x0u | 148f:761a  | Mediatek MT7610U | 1T1R | TP-Link | Archer T2U | v1.0 | nl80211 | 2.4+5GHz | 2.4 GHz only | 2.4+5GHz |5.7.0-kali3-amd64 VirtualBox6.1 |
| mt76x0u | 148f:761a  | Mediatek MT7610U | 1T1R | TP-Link | Archer T2U | v2.0 | nl80211 | 2.4+5GHz | 2.4 GHz only | 2.4+5GHz |5.7.0-kali3-amd64 VirtualBox6.1 |
| mt76x2u | 057c:8503  |  | 1T1R | AVM GmbH | FRITZ!WLAN AC 860 |  | nl80211 | 2.4+5GHz | 2.4+5GHz | 2.4GHz only |5.7.0-kali3-amd64 VirtualBox6.1 |

### Realtek
| Driver |  ID | Chipset | Radio | Vendor |  Modelname | HW Rev | API | Monitor Mode | Packet-Injection | SoftAP | Confirmed |
| ------ | --- | ------- | ------ | ---------- | -------| ------  | ----- | ----- | ---- | ----- | ---- |
| 88XXau | 0bda:8812  | RTL8812AU | 2T2R | AlfaNetworks | AWUS036AC |  | nl80211 | 2.4+5GHz | 2.4+5GHz | None |5.7.0-kali3-amd64 VirtualBox6.1 |
