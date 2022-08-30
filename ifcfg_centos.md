# 配置Linux网卡

1. `cd /etc/sysconfig/network-scripts/`

2. `ls`查看文件夹下的文件

3. `vi ifcfg-ens33`查看文件内容  

   :hammer: 配置**IPADDR**.**DNS**.**NETMASK**.**GATEWAY** 

   打开**ONBOOT**服务

   记得**restart network service**

   测试：ping www.baidu.com

4. 完成网络配置

   

   

   
