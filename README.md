# WISE-1570-HelloMQTTSN

## Introduction
This sample is on going for experiment and test on WISE-1570. It aims to work on mbed OS 5.5 port with Quectel BC95(NB-IoT).

## Patch MQTTSN library

Please follow the below steps to setup for development:

1. `git clone https://github.com/ADVANTECH-Corp/WISE-1570-HelloMQTTSN.git`

1. `cd WISE-1570-HelloMQTTSN`

1. `mbed config root .`

1. `mbed deploy`

1. `patch -p0 < patch/0001-mqttsn-for-wise1570-mbed5.patch`

## Compilation
No supported right now if you have no source code obtained from ARM.

`mbed compile -m ADV_WISE_1570 -t GCC_ARM -c`
