<p align="center">
    <img src="docs/image/logo.avif" height="128">
    <h1 align="center">Aruba Mobility Controller SNMP Zabbix Template</h1>
</p>

This template is meant for monitoring Aruba Mobility Controller appliances using SNMP MIB [WLSX-WLAN-MIB](https://mibbrowser.online/mibdb_search.php?mib=WLSX-WLAN-MIB)

- [Features](#features)
- [How to use](#how-to-use)
- [Contribute](#contribute)
- [License](#license)

## Features

- APs status.
- APs Radio statistics.
- Number of APs and Clients connected.

## How to use

1) Import the template file ***zbx_template_aruba_mobility_controller.yaml*** in Zabbix.
2) Create SNMP credentials on Aruba Mobility Controller.
3) Create the Zabbix host with an SNMP interface and assign the ***Aruba Mobility Controller SNMP*** template.

> [!TIP] You can personalize the Zabbix template behaviours using MACROS.

## Contribute

This template is on early stage and can bee improved supporting other Unity parameters. Feel free to fork and submit pull request. 🙏🏻

## License

Licensed under the [MIT license](https://github.com/MassimilianoPasquini97/zbx_aruba_cppm/blob/main/LICENSE.md).
