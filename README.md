# LuppiLandia-MacOS-RDP

### MacOS 10.15

VM features:
- 3-core vCPU
- 14 GB RAM
- 14 GB SSD Disk **(Excluded System used)**

---

Secrets Name | Uses | Notes
----- | ----- | -----
**MAC_REALNAME** | For MacOS User Display Name | Type any name you want
**MAC_USER_PASSWORD** | For MacOS System Admin Password | Type any password you want
**VNC_PASSWORD** | For the login password of VNC remote authentication | Type any password you want

---

## Deploy and Run
<details>
    <summary>MacOS Install and Run</summary>
<br>
    
* Go to **Actions** Tab and select one of system workflow.

* Click **Run Workflow** button on the left of **This workflow has a workflow_dispatch event trigger** line.

* Wait until a few minutes.

* Copy the link(**without tcp://**) and go to VNC Viewer(Download and install it [here](https://www.realvnc.com/download/file/viewer.files/VNC-Viewer-6.21.406-Windows.exe)), input the link to connect that u copied from the website.

* Fill in those login info, within username **TCV** and password from **VNC_PASSWORD** in Secret that you typed.

* Enjoy!

</details>

<details>
    <summary>MacOS System Features</summary>
<br>

- Desktop Screenshot
<img src="https://raw.githubusercontent.com/prateekg34/testing/main/screenshots/1.png" >

- Settings
<img src="https://raw.githubusercontent.com/prateekg34/testing/main/screenshots/2.png" >

- RAM
<img src="https://raw.githubusercontent.com/prateekg34/testing/main/screenshots/3.png" >

- Storage
<img src="https://raw.githubusercontent.com/prateekg34/testing/main/screenshots/4.png" >

- Pre-Installed Apps
<img src="https://raw.githubusercontent.com/prateekg34/testing/main/screenshots/5.png" >

</details>

:warning: Dont install "Big Sur" updates on your MACOS virtual machine, it will break your remote process!

<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.35.57%20AM.png">
</details>
