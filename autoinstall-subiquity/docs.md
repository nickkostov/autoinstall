
Create a VM in Virtual Box with 4GB of RAM and make sure the following options are enabled for this test:

- Networking should look like this:

![Network](https://github.com/nickkostov/autoinstall/blob/main/autoinstall-subiquity/files/networking.png)

- System settings should look like this:

![System](https://github.com/nickkostov/autoinstall/blob/main/autoinstall-subiquity/files/vmnetworkboot.png)

- The reason for this amout of RAM is due to the fact that netbootxyz & also other TFTP booting ways will have to load the .iso of Ubuntu into RAM in order to start the installation proccess.

When you boot the VM you should see:

![Boot](https://github.com/nickkostov/autoinstall/blob/main/autoinstall-subiquity/files/boot.png)

Choose the following options:

![Option](https://github.com/nickkostov/autoinstall/blob/main/autoinstall-subiquity/files/option.png)

In order to push the autoconfiguration for the autoinstall you should choose the folloing settings into the netbootxyz:

First try is to map only the folder.

Did not work out.

-----------------------------------------------------------------------------------------------------------------------------

I tried just pointing the file and it did not work out nothing was automatically configured.

![Optaution](https://github.com/nickkostov/autoinstall/blob/main/autoinstall-subiquity/files/autoin.png)
-----------------------------------------------------------------------------------------------------------------------------
I tried with adding extension to the files .yaml 

And it did not work out.
