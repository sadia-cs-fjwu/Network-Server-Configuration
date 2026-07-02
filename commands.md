# Network Server Configuration Commands

## Update System

```bash
sudo apt update
sudo apt upgrade
```

## Install DHCP Server

```bash
sudo apt install isc-dhcp-server
```

## Install DNS Server

```bash
sudo apt install bind9 bind9utils bind9-doc
```

## Install FTP Server

```bash
sudo apt install vsftpd
```

## Install Apache Web Server

```bash
sudo apt install apache2
```

## Check Services

```bash
sudo systemctl status isc-dhcp-server
sudo systemctl status bind9
sudo systemctl status vsftpd
sudo systemctl status apache2
```
