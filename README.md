# Generic-Cisco-Zabbix-template
Generic cisco zabbix template

# Intro
I was looking for a template that gave me as much information as possible on a Cisco device, working on Zabbix 4.0.x + and quick implementation of multiple Zabbix servers. Template is based on the stock Cisco SNMPv2 template but with some additional content

# Features
- Device Model Name
- FAN Discovery
- Power Supply
- Temperature
- CPU Discovery
- Serial Numbers Discovery
- Memory Discovery
- Network interfaces Discovery


Based on your device it will create around:
150-250 items
100-150 triggers
20-50 graphs


# Tested and worked on
- Cisco 800
- Cisco 878 k9
- Cisco 881
- Cisco 803

As it is based on the default Cisco SNMPv2 template it will work on every generic Cisco Router/Switch.
