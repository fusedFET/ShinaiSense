# Shinai Sense (竹刀のセンサー)

Shinai Sense is a sensor device aiming at gathering data
about how users use their Shinai during kendo practice.
The device is attached to the sword and connected via bluetooth to a computer.

## Status

First version under heavy development.

## Operations

Shinai Sense is a device composed of two boards. The mainboard is put between the tsuba and tsuba dome. The second is located
inside the kensen. The mainboard holds a rechargable battery, the main microcontroller, one 9 axis IMU sensor and the RF parts.
The second board in the kensen only holds a second 9 axis IMU. that is connected over a cable routed inside the shinai's channel.
Data is gathered from both sensors and sent to a computer using Bluetooth 5 Low Energy.
