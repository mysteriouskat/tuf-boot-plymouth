TUF plymouth boot theme 
-------------------------------------------------------------------

This is a plymouth boot theme with TUF logo like MacOS boot animation

<img src="tuf-boot.png" alt="Image" align="left">

![TUF logo](tuf-logo.png)


Installation
-------------------------------------------------------------------

Open a terminal in the folder wherever the downloaded 'tuf-boot' folder is located in your device.
Copy the theme to /usr/share/plymouth/themes:

`sudo cp -r ./tuf-boot /usr/share/plymouth/themes`

After copying, get a list of the installed themes with the following command:

`plymouth-set-default-theme --list`

Set it to tuf-boot theme:

`sudo plymouth-set-default-theme tuf-boot -R`
