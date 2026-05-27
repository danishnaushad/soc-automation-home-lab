# Wazuh Installation Steps

## Lab Setup
- Ubuntu Server installed in VirtualBox
- Bridged Networking enabled
- Windows Host connected as Wazuh Agent

## Wazuh Manager Installation

```bash
curl -sO https://packages.wazuh.com/4.12/wazuh-install.sh && sudo bash ./wazuh-install.sh -a -i
