# Suricata Lab Commands

## Update Ubuntu
sudo apt update

## Install Suricata
sudo apt install suricata

## Check Suricata Version
suricata -V

## Check Build Information
suricata --build-info

## Check Suricata Service
sudo systemctl status suricata

## Restart Suricata
sudo systemctl restart suricata

## Check Network Interfaces
ip addr

## Install Network Tools
sudo apt install net-tools

## Display Network Interfaces
ifconfig

## Check Suricata Configuration
sudo nano /etc/suricata/suricata.yaml

## View Suricata Logs
sudo ls -lah /var/log/suricata/
