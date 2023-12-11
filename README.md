<h2 align="center"><u>CamHacker</u></h2>

![Hack anyone's camera and get images](https://github.com/karthik-reddy4444/cam-hack/raw/main/files/banner.png)
<h4 align="center"> Hack anyone's camera and get images!</h4>

<p align="center">
    <img src="https://img.shields.io/badge/Version-1.5-blue?style=for-the-badge&color=blue">
    <img src="https://img.shields.io/github/stars/karthik-reddy4444/cam-hack?style=for-the-badge&color=magenta">
    <img src="https://img.shields.io/github/forks/karthik-reddy4444/cam-hack?color=cyan&style=for-the-badge&color=purple">
    <img src="https://img.shields.io/github/issues/karthik-reddy4444/cam-hack?color=red&style=for-the-badge">
    <img src="https://img.shields.io/github/license/karthik-reddy4444/cam-hack?style=for-the-badge&color=blue">
<br>
    <img src="https://img.shields.io/badge/Author-Karthik-green?style=flat-square">
    <img src="https://img.shields.io/badge/Open%20Source-Yes-orange?style=flat-square">
    <img src="https://img.shields.io/badge/Maintained-Yes-cyan?style=flat-square">
    <img src="https://img.shields.io/badge/Written%20In-Shell-blue?style=flat-square">
</p>

### [+] Installation

 - `git clone https://github.com/karthik-reddy4444/cam-hack`
 - `cd cam-hack`

For termux, use additional command `termux-setup-storage`
 - `bash ch.sh`

##### Or Run Directly
```
wget https://raw.githubusercontent.com/karthik-reddy4444/cam-hack/main/ch.sh && bash ch.sh
```


##### Usage
```
Usage: bash ch.sh [-h] [-o OPTION] [-p PORT] [-t TUNNELER] [-u] [-nu]

Options:
  -h, --help                           Show this help message and exit
  -o OPTION, --option OPTION           Index of the template
  -p PORT, --port PORT                 Port of CamHacker's Server (Default: 8080)
  -t TUNNELER, --tunneler TUNNELER     Name of the tunneler for url shortening (Default: cloudflared)
  -d DIRECTORY, --directory DIRECTORY  Directory where images will be saved
  --update(-u), --no-update (-nu)      Check for update (Default: true)
```


### [+] Features
 - Three Templates
 - Get IP, Location, Device type and Browser
 - Concurrent double tunneling (Cloudflared and Loclx)
 - Choose where to save images(custom directory) 
 - Error Diagnoser
 - Argument support for templates, tunnelers and directory



