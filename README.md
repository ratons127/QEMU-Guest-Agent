# QEMU-Guest-Agent
QEMU Guest Agent install in ubuntu
## Update Package Lists
```
sudo apt update
```
## Install QEMU Guest Agent
```
sudo apt install qemu-guest-agent
```
## Start and Enable the Service
```
sudo systemctl status qemu-guest-agent
```
```
sudo systemctl start qemu-guest-agent
sudo systemctl enable qemu-guest-agent
```
## Verify the Installation
```
systemctl status qemu-guest-agent
```
You should see an output indicating that the service is "active (running)."
