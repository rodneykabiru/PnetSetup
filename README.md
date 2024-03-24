## PNET LAB IMAGES INSTALLATION STEP BY STEP
### PNET Lab Setup and Integration of Devices

1. Download the pnet image from the official pnet website [pnet image](https://pnetlab.com/pages/download)
2. Download virtualbox from the official site.[Virtualbox](https://www.virtualbox.org/)
3. import the pnet image to virtualbox
4. Download Putty from official site [Putty](https://www.putty.org/)

![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/30863651-82e5-4735-89b3-26c99bcb89c1)

<!-- 5. update pnet to the latest version 5.3.11 use winscp sftp to trnsfer the file to the machine from your local machine -->

![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/91c413f0-34f0-42c4-953a-790c506df41b)
### Download link of ishare2 from github [ishare2-cli](https://github.com/ishare2-org/ishare2-cli)
![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/40259989-5cfe-4dbd-ad7f-9c38f085e7a8)

Open PuTTY and enter the IP address or hostname of your Pnet link in the "Host Name (or IP address)" field.
Make sure the connection type is set to SSH.
Click on "Open" to initiate the connection.
When prompted, enter your username and password to log in to the Pnet link.
![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/f7f238a7-0815-48d1-9bb9-6acd596b31d4)

Once logged in, you can execute commands to install iShare2
Download link to using wget
```html
wget -O /usr/sbin/ishare2 https://raw.githubusercontent.com/ishare2-org/ishare2-cli/main/ishare2
```
![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/d3933fd4-ccad-45a3-93c9-4ad03719175f)
![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/4a73745e-fb6e-4828-a9a6-b627e3f0bce8)


### ishare 2 commands usage and download images
## ishare2 commands

ishare2 uses the following syntax to execute different actions, each action is explained in detail below:

```bash
    ishare2 [action] [param1] [param2]

    action:
      search      : Search for images by type
      pull        : Download an image by type and number
      installed   : Show installed images on server
      labs        : Show labs on server and download images for those labs
      mylabs      : Same as labs command but using a customized path to labs
      relicense   : Generate a new iourc license for bin images
      upgrade     : Retrieves a menu that allows users to upgrade ishare2 and PNETLab VM
      changelog   : Show the latest changes made to ishare2
      gui         : Web app to use ishare2 in browser
      help        : Show useful information
      test        : Test if ishare2 dependencies are reachable (GitHub, Google Spreadsheets)

    param1:
      type = all, bin, qemu, dynamips, docker or name

    param2:
      number = This number can be obtained using ishare2 search <type>
```
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
ishare2 pull  bin all
ishare2 pull qemu 'number' number include [511,512 879-898]
```
An example would be the ``` iShare2 search dynamips```. An installation instructions command is located at the bottom of the page. You would therefore use ``` iShare2 pull dynamips all``` to pull all images. For iol, ```ishare2 search iol```, then for the install command, it will be ```ishare2 pull bin all```. For Vios, the installation of images is done one by one. 

![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/170dbd8f-88f5-4b77-b3f1-c76b2d1c7266)
![image](https://github.com/rodneykabiru/PnetSetup/assets/25923110/5718dfa3-5826-4029-87fc-f0dfdffb9f66)

 ALL NODES SHOULD BE UP AND RUNNING







