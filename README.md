gpio_config_tool

This tool will allow for easier setup and tear down of gpio pins.

armbian_gpio_up is used to read the conf file in /etc/armbian_gpio.conf and configure gpio pins as assigned.

armbian_gpio_down reads the same conf file /etc/armbian_gpio.conf and tears down the configured pins.

you need to assign the gpio_user and gpio_group to a user and group like wheel or a special user.

