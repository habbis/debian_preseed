# debian_preseed

<br />
debian preseed auto installer files

preseed file for vmware VM  [preseed-bookworm-min-vm-vmware](preseed-bookworm-min-vm-vmware.txt)

package for vmware is open-vm-tools

<br />

preseed file for proxmox VM  using /dev/sda [preseed-bookworm-min-vm-proxmox](preseed-bookworm-min-vm-proxmox.txt)

tested with pxe booting on proxmox

package for promox is cloud-init qemu-guest-agent

<br />
preseed file for libvirt VM using /dev/vda [preseed-bookworm-min-vm-libvirt](preseed-bookworm-min-vm-libvirt.txt)

tested with pxe booting on proxmox

package for libvirt is cloud-init qemu-guest-agent
<br />


 Mdadm raid setup [raid1 preseed](raid1_preseed)
 and root and boot have two disks in raid1

boot "/dev/sda /dev/sdb" and root "/dev/sdc /dev/sdd"




<br />


 [full preseed](full_preseed) config with comments i got this from user  [ Andrey Klimentyev ](https://github.com/zuzzas?tab=repositories)
here is his  [github gist](https://gist.github.com/zuzzas/a1695344162ac7fa124e15855ce0768f)



<br />

Much of this should also work with ubuntu server legacy server installer. 

<br />

<br />

To generate password hash 

```
mkpasswd --method=yescrypt
```

<br />


links:

http://cdimage.ubuntu.com/ubuntu-legacy-server/releases/20.04/release/

https://help.ubuntu.com/lts/installation-guide/s390x/apb.html



