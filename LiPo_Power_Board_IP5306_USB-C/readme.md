# IP5306 LiPo Power Board USB-C

LiPo battery charger, protector and 5V booster based on the [IP5306](https://datasheet.lcsc.com/szlcsc/INJOINIC-IP5306_C181692.pdf) with USB-C input featuring:
- synchronous switch-mode charging with up to 2.1A / 91% efficiency,
- discharging with up to 2.4A,
- 5V boost converter with up to 92% efficiency,
- integrated power-path management (charging battery and 5V output at the same time),
- voltage based fuel gauge indication with 4 LEDs,
- on/off key,
- smart load detector (switching to standby mode automatically),
- less than 100uA standby current,
- charging/boosting with a single inductor,
- output over-current, over-voltage, short-circuit protection,
- input over-voltage, over-current protection,
- battery over-charge, over-drain, over-current protection,
- thermal shutdown.

Key functions:
- If button is pushed longer than 30ms but shorter than 2s, IP5306 will identify the action as short push. Short push will activate state of charge (SOC) indicator LEDs and step-up converter.
- If two short pushes are detected within 1s, IP5306 will deactivate step-up converter, SOC indicator LEDs and PWR LED (flashlight).
- If button is pushed longer than 2s, IP5306 will identify the action as long push. Long push will enable or disable PWR LED (flashlight).
- If button is pushed shorter than 30ms, IP5306 will ignore the action.

![IMG_20200806_170113_x.jpg](https://image.easyeda.com/pullimage/29fr5i6Ls9qVSXgj1bzG9rKqmmX9oJmnZgL4GFrm.jpeg)
![IP5306_efficiency_x.png](https://image.easyeda.com/pullimage/wphHg653VxfUIUU01PYvrbN4pTR3UtEO0s1xtUJ8.png)
