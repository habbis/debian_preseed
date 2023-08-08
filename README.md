# debian_preseed
debian preseed auto installer files


preseed file for VM or other server/desktop using /dev/sda [preseed-bookworm-min-vm](preseed-bookworm-min-vm.txt)

tested with pxe booting on proxmox



 Mdadm raid setup [raid1 preseed](raid1_preseed)
 and root and boot have two disks in raid1

boot "/dev/sda /dev/sdb" and root "/dev/sdc /dev/sdd" 




<br />


 [full preseed](full_preseed) config with comments i got this from user  [ Andrey Klimentyev ](https://github.com/zuzzas?tab=repositories)
here is his  [github gist](https://gist.github.com/zuzzas/a1695344162ac7fa124e15855ce0768f)



<br />

Much of this should also work with ubuntu server legacy server installer. 

<br />
links:

http://cdimage.ubuntu.com/ubuntu-legacy-server/releases/20.04/release/

https://help.ubuntu.com/lts/installation-guide/s390x/apb.html

