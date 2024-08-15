# QEMU

https://www.qemu.org/download/#linux

````
安装转换工具
yum install qemu-utils

查看虚拟机文件信息
qemu-img info source-name.vmdk

qcow2转vmdk
qemu-img convert -f qcow2 -O vmdk source-name.qcow2  target-name.vmdk

vmdk转qcow2
qemu-img convert -f vmdk -O qcow2 source-name.vmdk target-name.qcow2

vmdk的多文件合并
vmware-vdiskmanager.exe -r sourceDisk.vmdk -t 0 destinationDisk.vmdk
````