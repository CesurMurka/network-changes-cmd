# network-changes-cmd
Few scripts to make working with Network Windows Configuration easier.

## 1. Change IP to Dynamic & Change IP to Static


### How to get Interface Network Name: 

change_ip_to_dynamic.txt
change_ip_to_static.txt

### To dynamic
```
netsh interface ip set address name = "Wi-Fi" dhcp
```

### To static
```
netsh interface ip set address name = "Ethernet" static 10.1.51.95 255.255.255.0 10.1.51.1
```

Run cmd as administrator
```
netsh interface show interface
```

![Copy the prefered interface](https://github.com/CesurMurka/network-changes-cmd/blob/main/how_to_get_interface_network_name.png)


## How to run the sripts on Windows
Save the scripts with the .bat file extension and run them as administrator.
