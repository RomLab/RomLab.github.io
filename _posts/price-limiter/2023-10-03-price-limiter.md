---
layout: post
title:  "Price limiter"
date:   2023-10-03 09:29:20 +0700
categories: price limiter ote photovoltaics
usemathjax: true
---

# Price limiter

The pricelimiter is device for control of a converter (a domestic photovoltaic power plant) according to current daily market prices. The target of control is saving of money. The disabling of supplying electricity to the system in case of low electricity prices (according to a price limit). The device downloads current daily market prices from [OTE (prices of electricity for Czech Republic)](https://www.ote-cr.cz/cs/kratkodobe-trhy/elektrina/denni-trh). The current hour is compare with current price hour from daily market, according to price limit is output relay (with connect the converter) turn on or turn off. The current version of device controls only sale electricity to the system. The settings is in the picture 1.

<p align="center">
<img src="/assets/img/posts/price-limiter/screenshot-price-limiter.png" width="500px" alt="The settings for the price limiter.">
</p>
<p align="center">
Picture 1: The settings for the price limiter.
</p>

The device is based on [Olimex ESP32-EVB-EA-IND](https://www.olimex.com/Products/IoT/ESP32/ESP32-EVB/open-source-hardware). The device is in the picture 2.

<p align="center">
<img src="/assets/img/posts/price-limiter/olimex-esp32-evb-ea.png" width="500px" alt="Olimex ESP32-EVB-EA-IND.">
</p>
<p align="center">
Picture 2: Olimex ESP32-EVB-EA-IND.
</p>

## Future development

The extended version of this device contains linear solver for optimization of all devices in a house (heating water tank, boiler, battery, …) according to the lowest price. User can set necessary settings for example time for domestic heat water, priority of using electricity in the house, …


