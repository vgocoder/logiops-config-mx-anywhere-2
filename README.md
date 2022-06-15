# logiops-config-mx-anywhere-2
Logiops configuration file (logid.cfg) for Logitech Wireless Mobile Mouse MX Anywhere 2 mouse

## Usage
### Install logiops
```shell
# Ubuntu Or Debian
sudo apt-get install logiops
# Arch Linux
sudo pacman -S logiops
```
### Configure logiops
```shell
git clone https://github.com/vgocoder/logiops-config-mx-anywhere-2.git
cd logiops-config-mx-anywhere-2
cp logid.cfg /etc/logid.cfg
```
### Start logiops
```shell
sudo systemctl start logid
```
### Stop logiops
```shell
sudo systemctl stop logid
```
### Check logiops status
```shell
sudo systemctl status logid
```
### Restart logiops
```shell
sudo systemctl restart logid
```
### Debug logiops
```shell
sudo logid -v
```
### Uninstall logiops
```shell
# Ubuntu Or Debian
sudo apt-get remove logiops
# Arch Linux
sudo pacman -R logiops
```

### Start at boot
```shell
sudo systemctl enable --now logid
```

## CIDs for Wireless Mouse MX Anywhere 2

    0x0050 (Left Mouse Button)
    0x0051 (Right Mouse Button)
    0x0052 (Middle Mouse Button)
    0x0053 (Back Button)
    0x0056 (Forward Button)
    0x005b (Left Scroll)
    0x005d (Right Scroll)
    0x00d7 (Switch Receivers)


## Thanks
[PixlOne/logiops](https://github.com/PixlOne/logiops)
