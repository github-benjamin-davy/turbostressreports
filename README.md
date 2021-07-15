# Turbostress Reports
A collection of power consumption measurements of bare metal servers, performed using the [turbostress](https://github.com/teads/turbostress) tool

Each .csv file is named using the following convention:
Instance Name _ Date (Month/YY) _ AWS Region _ Loadstep Option _ Repeat Option

Each file first contains the CPU informations from `/proc/cpuinfo` and then a table with the CPU and DRAM power consumption as well as the CPU Package temperature reported for each stress test.
