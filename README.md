# Howto install Home Assistant in Proxmox
Howto Install Proxmox with HA

## Install Proxmox

## Install Home Assistant
- Use the script at the TTECK github https://tteck.github.io/Proxmox/
- Install HA as VM
## Passthrough USB device to HA
- Plug USB device in proxmox server
- Login in the Proxmox server
- Go to the VM or LXC you want to add the usb device
- Go to 'Hardware' and click 'Add' and click 'USB Device'
![image](https://user-images.githubusercontent.com/100353268/212086652-64cf0e36-5509-40b4-85d4-eaafd5a1ae69.png)
- Click to add the full USB port
![image](https://user-images.githubusercontent.com/100353268/212086900-355e5395-882c-4145-ba90-e4a68dc86b9e.png)
- Click 'Add'
- Device can now be found in your HA install
