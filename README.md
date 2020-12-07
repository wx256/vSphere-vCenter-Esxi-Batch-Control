# vSphere-vCenter-Esxi-Batch-Control
vSphere-vCenter-Esxi虚拟机管理工具，可以连接到任何vCenter机器进行批量创建主机，批量关机，批量开机，批量重启，批量删除释放等操作。后端接口Django开发，用户界面易语言开发。 

部署方式
1,django.rar解压到电脑中,运行起来即可
2,打开vSphere.e修改里面的所有网页访问地址(网页_访问S (“http://192.168.1.100:8000/vsphere/testconnect”, 1, data)),把里面的IP:端口修改为运行中的Django机器地址
3,编译即可连接使用

![screen1](https://github.com/wx256/vSphere-vCenter-Esxi-Batch-Control/blob/main/screen1.png)
![screen2](https://github.com/wx256/vSphere-vCenter-Esxi-Batch-Control/blob/main/screen2.png)
