# Setting up the VM for mac os Catelina

Step 1 : Download and setup VMware workstation as instructed on its official website

Step 2: To activate the VMware workstation, use keys from [this github repository](https://gist.github.com/gopalindians/94c2c8617028cfe7a5788f760e036fd2).

Step 3: Download the archive containing vmdk file for the macOS catalina from [here](https://www.geekrar.com/download-macos-catalina-vmdk-virtual-machine-disk-file/). And extract the content to get the vmdk file.

![](.gitbook/assets/image%20%282%29.png)

![](.gitbook/assets/image%20%2820%29.png)

Step 4: After successful activation of VMware, we need to use unlocker so that macOS can be installed on the VMware. Clone [this github repository ](https://github.com/paolo-projects/unlocker)to get unlocker.

![Unlocker repository](.gitbook/assets/image%20%289%29.png)

On the linux system run lnx-install.sh with sudo and on windows run unlocker.exe as administrator.

![unlocker](.gitbook/assets/image%20%2815%29.png)

Wait till the unlocker runs, it will download and apply some patches on the VMware system, to allow the installation of macOS. After successful, check the VMware installation whether it has been unlocked or not.

Go to "Create new VM -&gt; Typical -&gt; I will install operating system later". If you are able to view the option for apple macos means that your unlocking is successful. Now proceed to masOS catalina installation.

![](.gitbook/assets/image%20%2814%29.png)

Step 5: Click on "Create new Virtual Machine". Under the type of configuration select "Typical"

![Type of configuration](.gitbook/assets/image%20%283%29.png)

then select "I will install the operating system later" under new vm wizard.

![I will install the os later](.gitbook/assets/image%20%285%29.png)

Select the type of guest operating system. Select "Apple Mac OS X".

![apple mac os x](.gitbook/assets/image%20%2814%29.png)

Create the name of the Virtual machine, and enter the location for the VM files to be saved.

![Name and Location](.gitbook/assets/image%20%2819%29.png)

![](.gitbook/assets/image%20%288%29.png)

Click Finish to create the virtual machine.

![](.gitbook/assets/image%20%281%29.png)

After successful creating of virtual machine, allocate it half of your host systems memory and processor resource.

![](.gitbook/assets/image%20%2811%29.png)

Click on "Add", select "Hard Disk" and click next.

![](.gitbook/assets/image%20%284%29.png)

Select the type of virtual disk type as SATA, click "use an exiting virtual disk". and select the vmdk file downloaded and click "ok" to finish the editing VM settings. 

![](.gitbook/assets/image%20%2812%29.png)

![](.gitbook/assets/image%20%2813%29.png)

![](.gitbook/assets/image%20%2816%29.png)

![](.gitbook/assets/image%20%2810%29.png)

Step 6: Click on power on virtual machine, the machine starts to boot up, wait and follow the instuctions for the os installation steps.

![](.gitbook/assets/image%20%286%29.png)

![](.gitbook/assets/image%20%2817%29.png)











