# Beaglebone
This folder contain different device tree files for beaglebone.
For SC16IS750, SC16IS762 there is one configuration need to disable CONFIG_SERIAL_DEV_CTRL_TTYPORT, as it breaks
CONFIG_SERIAL_SC16IS7XX

https://github.com/RobertCNelson/ti-linux-kernel-dev/commit/c8bf98fd9324e3973d5021eefcfa7a549869a578
