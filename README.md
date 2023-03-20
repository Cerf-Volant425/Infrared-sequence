# Infrared-sequence

### 1.1 Description
The infrared data is collected in the motion capture system in the Chinese BeiDou industrial base, with the aim ofth e test of Thermal NeRF.

### 1.2 Sensor parameter
* **Infrared Camera:** optris PI 450i,382*288

* **Rostopics of rosbag sequences:** /optris/thermal_image

* **Image format:** 16UC1




### 1.3 Dataset sequences

#### 1.3.1 2023-02-28
Sequence Name|Collection Date|Total Size|Duration|Temperature|Feature|Rosbag|GT
--|:--|:--:|--:|--:|--:|--:|--:
room_rot_01|2023-02-28|274.5MB|44.7s|-|shake|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/ERnfNCf2R3RAlXIuMdNW8eABEoUP7zsKeAvDnvaL_VcaRw?e=HwWNDU)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EaJoXdPSRZFPgTK3B2hEbQ0BOHhU8iWSRhVFSoWuXqgIkg?e=IbjAYq)
room_rot_02|2023-02-28|589.9MB|96s|-|slow|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/ETDqc-28FFRFgdvmFoEABIcBYhj0_uonFGCWWvHDiOBz8A?e=zi6esA)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EcaH-4faydFMvWmT2P_FMOoBqRv4QWyFbgSTe2NO9x8SJQ?e=gVnYO1)
room_rot_03|2023-02-28|522.5MB|85s|-|shake, dynamic|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/EXgRV72Es_9NtOfkCGpgIeABoiUMs6MIRLlf5vSIE-gsXA?e=hDAIWH)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EZ5GOAi-9QlPkqY_ALIvvjYBYBGEVXnxHVTNasP4hwXXTA?e=Ooozmr)
room_rot_04|2023-02-28|481.5 MB|78s|-|slow, static|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/EXcJdmI2o2BBgbf_m4W-QFcBDByHVZ8oXUyt18eezmYf5Q?e=lc3B8o)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EafdmR43-g5Hp1jluj3_vk8Btva9kOJCuv1YnvQTWGwFaQ?e=pgMWvr)
room_move_01|2023-02-28|725.3 MB|118s|-|by car|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/ERbolVI1Z6ZPhN1My8KaGz4BESCbGcNSiDSp8piXpEz8Iw)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EWY3buKCnnFGrSXEsfuUEuIBiTCqUSXe7qAIj74c8vv-xA?e=Jatrd9)
room_move_02|2023-02-28|521.2MB|84s|-|shake, rapid|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/EUFgMiMz5ZtNi9j_bgXlCXgBD-xJ6tlUOZIzb7ocGDzpmQ?e=aSaH66)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EeWgRcbeErlPnB0iOxT7dHUBuA9c_i6pMJfU3S64fX_lMQ?e=lHaTlr)
room_move_03|2023-02-28|406.1MB|66s|-|shake, slow, slope|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/EUFgMiMz5ZtNi9j_bgXlCXgBD-xJ6tlUOZIzb7ocGDzpmQ?e=OUGI8K)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/Ea0uxFsPo-pJikAYpVpWYMMBLMWz5rkP2RQ9FyvxeduXmw?e=xLxmbN)
room_move_04|2023-02-28|311.6MB|50.7s|-|shake, dynamic|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/EYSLlbVixdZKtLE5wKYBln8BiLKbhiBkI5wZVT_HWvmpoA?e=isTKIU)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/Ee6u8OPhGyNHmHuvxFDFMX8BYwE_4pNoxgh6onqxXBIR-A?e=4Ab6N1)
room_move_05|2023-02-28|447.9MB|72s|-|shake, dynamic|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/ERe5YqjwDnJIvdnl8YzQDRwBVTDHXYSpDZKX5TQ4JLtKFg?e=9xuguh)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/ETYwn_29AAZCjRnWsWT07SwBKNInpR2vyHgcfPJqv9ueLA?e=Q7TaPz)

#### 1.3.1 2023-03-18
This time, we collect the data at four different temperature. Due to the power limit of the air condition and the openness of the site, the importance of temperature error should be taken into consideration. Also, each trajectory at different temperature can be different.
Sequence Name|Collection Date|Total Size|Duration|Temperature|Feature|Rosbag|GT
--|:--|:--:|--:|--:|--:|--:|--:
room_rot|2023-03-18|385.4MB|62s|17°C|shake|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/EXAvRSdFCYpFio2Y8szgUmcBOinfJJbl__nn3QHgC8tXig?e=oUQJV5)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EU2Z0gHpjcdCiWmRqkCIgAgB0R8Dnxw00ukLwnpAMLw3Dg?e=wxC7nf)
room_move|2023-03-18|605.2MB|98s|17°C|shake|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/EZ074Zyq6-VBhfCARjQwP5sBBiANtwbzsjDH75E6hIAkuA?e=vna3tx)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EdVdZHjbNNpHgijtciT67YIB_nzFSBkwH-3pkQuJCLWOzA?e=Agz51p)
room_rot|2023-03-18|466.6MB|76s|20°C|shake|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/EWKQ-0T0lU5KrYO-7IutAfAB0xDevq7dZJB6gvoI_8MSDA?e=NtgTaO)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EdHGe7mT5tpOsC6JxpLtGrQB7zQFJUbUJbYlnxEMMyRe_Q?e=N6st42)
room_move|2023-03-18|788.8MB|128s|20°C|shake|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/Ed-jYungoxJMsJNmxCNGx94BCfnehl_RQ-wpJ3BYlTmNYQ?e=MqqLTK)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EUCV__RNowFEnpcu36uMIMUBJu7YEfJRsURXECOpVZvvLA?e=X6Dh0l)
room_rot|2023-03-18|662.3MB|107s|25°C|shake|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/ESC9P_icF0JIrOU1e7KlTckBmmFHzQ3JiyPrYyQYQAAiZg?e=altpZQ)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EUv7EFXrFPdKqblO7v2RAlMBTZkHWzH-mJjkQxC7PzEN_A?e=8zRLdI)
room_move|2023-03-18|698.7MB|113s|25°C|shake|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/EbTrCU4bv-BKo5eGVB1Y_5kBfKS0kQhqfmfDnh3YM_8IzA?e=nch4bZ)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/ERupQxaqBz1OqUnuBv_1RA8BWNNg_tKY6RmdEhLEIsWS2Q?e=oyT2O7)
room_rot|2023-03-18|296.9MB|48.3s|30°C|shake|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/ETWk_enIKahPvl2arxW7W04BfapxRIm9tBeXRNED0TFISQ?e=hFekFH)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EeG45rBR9CtKm7YJ9dSeioIBL0Hh7QIFXqAy-I4GK6efHQ?e=Cx1erC)
room_move|2023-03-18|494.6MB|80s|30°C|shake|[Rosbag](https://sjtueducn-my.sharepoint.com/:u:/g/personal/coulson_tx_sjtu_edu_cn/Ee9MMNdDdydAo6k7CiWN4KcB5ZoEqUNWkia5Emj8Zs3jog?e=MdrI35)|[GT](https://sjtueducn-my.sharepoint.com/:x:/g/personal/coulson_tx_sjtu_edu_cn/EVmcxoUDPntCqyLG_HF1T-QBuwyh-DRwMkX17e945yY8pw?e=HrYiaT)
