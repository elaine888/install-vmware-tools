# ./vmware-install.pl
The installer has detected an existing installation of open-vm-tools packages 
on this system and will not attempt to remove and replace these user-space 
applications. It is recommended to use the open-vm-tools packages provided by 
the operating system. If you do not want to use the existing installation of 
open-vm-tools packages and use VMware Tools, you must uninstall the 
open-vm-tools packages and re-run this installer.
The packages that need to be removed are:
open-vm-tools
The installer will next check if there are any missing kernel drivers. Type yes
if you want to do this, otherwise type no [yes] yes

A previous installation of VMware Tools has been detected.

The previous installation was made by the tar installer (version 4).

Keeping the tar4 installer database format.

You have a version of VMware Tools installed.  Continuing this install will 
first uninstall the currently installed version.  Do you wish to continue? 
(yes/no) [yes] yes

Uninstalling the tar installation of VMware Tools.

The removal of VMware Tools 10.1.6 build-5214329 for Linux completed 
successfully.

Installing VMware Tools.

In which directory do you want to install the binary files? 
[/bin] /usr/bin

What is the directory that contains the init scripts? [/etc] /etc/init.d

In which directory do you want to install the daemon files? 
[/usr/sbin] /usr/sbin

In which directory do you want to install the library files? 
[/usr/lib/vmware-tools] /usr/lib/vmware-tools

The path "/usr/lib/vmware-tools" does not exist currently. This program is 
going to create it, including needed parent directories. Is this what you want?
[yes] yes

In which directory do you want to install the documentation files? 
[/usr/share/doc/vmware-tools] /usr/share/doc/vmware-tools

The path "/usr/share/doc/vmware-tools" does not exist currently. This program 
is going to create it, including needed parent directories. Is this what you 
want? [yes] yes

The installation of VMware Tools 10.1.6 build-5214329 for Linux completed 
successfully. You can decide to remove this software from your system at any 
time by invoking the following command: "/usr/bin/vmware-uninstall-tools.pl".

Before running VMware Tools for the first time, you need to configure it by 
invoking the following command: "/usr/bin/vmware-config-tools.pl". Do you want 
this program to invoke the command for you now? [yes] yes


You have chosen to install VMware Tools on top of an open-vm-tools package.  
You will now be given the option to replace some commands provided by 
open-vm-tools.  Please note that if you replace any commands at this time and 
later remove VMware Tools, it may be necessary to re-install the open-vm-tools.

The file /usr/bin/vmware-hgfsclient that this program was about to install 
already exists.  Overwrite? [no] yes

The file /sbin/mount.vmhgfs that this program was about to install already 
exists.  Overwrite? [no] yes

The file /usr/bin/vmhgfs-fuse that this program was about to install already 
exists.  Overwrite? [no] yes

Initializing...


Making sure services for VMware Tools are stopped.



The module vmci has already been installed on this system by another installer 
or package and will not be modified by this installer.

The module vsock has already been installed on this system by another installer
or package and will not be modified by this installer.

The module vmxnet3 has already been installed on this system by another 
installer or package and will not be modified by this installer.

The module pvscsi has already been installed on this system by another 
installer or package and will not be modified by this installer.

The module vmmemctl has already been installed on this system by another 
installer or package and will not be modified by this installer.

The VMware Host-Guest Filesystem allows for shared folders between the host OS 
and the guest OS in a Fusion or Workstation virtual environment.  Do you wish 
to enable this feature? [yes] yes

The vmxnet driver is no longer supported on kernels 3.3 and greater. Please 
upgrade to a newer virtual NIC. (e.g., vmxnet3 or e1000e)

VMware automatic kernel modules enables automatic building and installation of
VMware kernel modules at boot that are not already present. This feature can
be enabled/disabled by re-running vmware-config-tools.pl.

Would you like to enable VMware automatic kernel modules?
[yes] yes

Thinprint provides driver-free printing. Do you wish to enable this feature? 
[yes] yes

Creating a new initrd boot image for the kernel.
update-initramfs: Generating /boot/initrd.img-4.8.0-54-generic
The configuration of VMware Tools 10.1.6 build-5214329 for Linux for this 
running kernel completed successfully.

Enjoy,

--the VMware team
