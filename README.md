# KamiPCB
Custom PCB for the Kamigami Robot

![Base PCB](/images/board.png "Base PCB")

![PCB with Motor Driver and IMU](/images/board+breakouts.png "PCB with Motor Driver and IMU")

![PCB with RaspberryPi plugged in](/images/board+Pi.png "PCB with RaspberryPi plugged in")


## Features:

- GPIO pinout for a 40 pin RaspberryPi Zero 2W

- Footprint for a [slide switch](https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/450405020524/11631973?utm_adgroup=Slide%20Switches&utm_source=google&utm_medium=cpc&utm_campaign=Shopping_Product_Switches_NEW&utm_term=&utm_content=Slide%20Switches&gclid=Cj0KCQiA4OybBhCzARIsAIcfn9kZlnFyzppiJHsiPTWcjy89dQjPVhE4TyYMwZM6H1WzcRK5DOPNZ7AaApNZEALw_wcB).
    - On position: RaspberryPi Powers On
    - Off position: Charging port is active(can connect the charger)

- Two footprints for [JST connectors](https://www.adafruit.com/product/1769?gclid=Cj0KCQiA4OybBhCzARIsAIcfn9mior_Arr4_kmWMmG2DZCzOcw1qgwyVm_pu0oZZ_99u8Pqh-xn1VJUaAlYnEALw_wcB)
    - Bottom one for [LiPo battery](https://www.adafruit.com/product/2011?gclid=Cj0KCQiA4OybBhCzARIsAIcfn9m_BvMJyWr5UIA2iAXFcFt5TBzUcbMPFACdZFcE9SNztZ2xCmZyJWIaAiT5EALw_wcB) connection
    - Top one for [LiPo Batter Charger](https://www.adafruit.com/product/259?gclid=Cj0KCQiA4OybBhCzARIsAIcfn9mFREJotrwPtDCExjES-GZIEWACWUR3ILdbCu2zyJQ8d5L67fAggNIaAuwoEALw_wcB)

- Pinout for the [motor driver](https://www.sparkfun.com/products/14451?gclid=Cj0KCQiA4OybBhCzARIsAIcfn9nFvoWL2TaoKYcKRDQmxKHgGOQo_j1VHxN8d7iZIITaPM2o-T2BjjAaAgz_EALw_wcB)
    - simply just stacked on via header pins
    - motor leads are routed to the side for easy installation

- Pinout for [8 channel ADC](https://www.adafruit.com/product/856)
    - one channel is already connected to the battery leads for battery voltage measurements

- Footprints for voltage divider step down (all 0805 SMD footprints)
    - one 100kOhm resistor
    - one 180kOhm resistor
    - one 0.1uF capacitor

- Pinout for [9 axis IMU](https://www.adafruit.com/product/3463)
