## PNET LAB IMAGES INSTALLATION STEP BY STEP
PNET SETUP
```html
PNET LAB SETUP AND Integration of devices
```

1. Download the pnet image from the official pnet website [pnet image](https://pnetlab.com/pages/download)
2. Download virtualbox from the official site.
3. import the pnet image to virtualbox

<!-- 5. update pnet to the latest version 5.3.11 use winscp sftp to trnsfer the file to the machine from your local machine -->

![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/91c413f0-34f0-42c4-953a-790c506df41b)
![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/40259989-5cfe-4dbd-ad7f-9c38f085e7a8)


Download link of ishare2 from github [ishare2-cli](https://github.com/ishare2-org/ishare2-cli)


![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/f7f238a7-0815-48d1-9bb9-6acd596b31d4)
![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/d3933fd4-ccad-45a3-93c9-4ad03719175f)
![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/4a73745e-fb6e-4828-a9a6-b627e3f0bce8)


Download link to using wget [ishare2-cli](wget -O /usr/sbin/ishare2 https://raw.githubusercontent.com/ishare2-org/ishare2-cli/main/ishare2)

### ishare 2 commands usage and download images
#### Commands for Search
```html
ishare2 search all
ishare2 search dynamips
ishare2 search iol
ishare2 search vios
```



![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/8df2c039-c087-4009-9344-fc177edd3ca7)
![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/08cba9d5-83bf-40d3-81c4-dfc6f821c3e4)
![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/954d65a2-aac0-4eb0-9480-81215b0983c9)

## Commands for installation
### N/B remember to utilize search before pulling
```html
ishare2 pull dynamips all
ishare2 pull pull bin all
ishare2 pull qemu 'number' number include [511,512 879-898]
```

![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/170dbd8f-88f5-4b77-b3f1-c76b2d1c7266)
![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/5718dfa3-5826-4029-87fc-f0dfdffb9f66)

 ALL NODES SHOULD BE UP AND RUNNING








