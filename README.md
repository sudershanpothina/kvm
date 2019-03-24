# kvm
1. Install ubuntu on dell poweredge r610. 
  - Go to the raid settings by pressing ctrl+r
  - make a volume with raid 1,5 or 10
  - https://www.orangecomputers.com/node/?command=kb&docid=25
2. Turn on virtualization
  - Press F2 and goto bios 
  - Go to processes and enable virtualization
3. Install Ubuntu by creating a boot usb and going to the boot manager and selecting the usb, follow regular instructions
4. Install xrdp
  - http://c-nergy.be/blog/?p=8952
  - check status by running 
  ```
  /etc/init.d/xrdp status
  ```
5. Install kvm
  - https://www.itworld.com/article/2827037/crash-course--virtualization-with-kvm-on-ubuntu-server.html?page=2
6. Creating guests 
  - make sure to create a bridge. This will help in accessing the guest machine outside the host
  - https://www.techotopia.com/index.php/Creating_a_CentOS_6_KVM_Networked_Bridge_Interface
  - reboot the machine 
  - create guest vms on the node.
  - Make sure you select the VCN is selected in the display options instead of spice before installing the gues
  
