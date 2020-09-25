# omnivista_container
Run OmniVista Virtual Appliance on any Linux Machine (AWS EC2, Azure, and more)

If you need to install the OmniVista virtual appliance in cloud service and you cant. This little guide is for you :)

1. You need the appliance image installer, so, grab it (the ovf version).
2. Extract with unzip.
3. Convert the two vmdk's images to raw format using the command: qemu-img convert -f vmdk -O raw disk.vmdk disk.raw

Continue...
