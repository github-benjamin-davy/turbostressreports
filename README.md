# Turbostress Reports
A collection of power consumption measurements of AWS bare metal servers, performed using the [turbostress](https://github.com/teads/turbostress) tool.

See the [Estimating AWS EC2 Instances Power Consumption](https://medium.com/teads-engineering/estimating-aws-ec2-instances-power-consumption-c9745e347959) article for more details.

Each .csv file is named using the following convention:
`Instance Name _ Date (MonthYY) _ AWS Region _ Loadstep Option _ Repeat Option`

Each file first contains the CPU informations from `/proc/cpuinfo` and then a table with the CPU and DRAM power consumption as well as the CPU Package temperature reported for each stress test.
