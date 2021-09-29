# Single GPU Passthrough
* Scripts for Windows QEMU/KVM Passthrough
* Hook files to be deployed in `/etc/libvirt/hooks`
## Assumptions
Modifications to the script may need to be made if you aren't using the following:
* Nvidia 1660 Super GPU
* SDDM display manager
* Different number of vtconsoles in `/sys/class/vtconsole/`
