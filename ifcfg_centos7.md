## 配置Linux网

1. `cd /etc/sysconfig/network-scripts/`

2. `ls`查看文件夹下的文件

3. `vi ifcfg-ens33`查看文件内容  

   :hammer: 配置**IPADDR**.**DNS**.**NETMASK**.**GATEWAY** 

   打开**ONBOOT**服务

   记得 `service network restart`

   测试：ping www.baidu.com

4. 完成网络配置

***
 ## 修改hostname

   * centos6: `vi cd /etc/sysconfig/network`

   * centos7:`hostnamectl set-hostname[NAME]`

   * 或者

     > 1. `vi cd /etc/hosts` 将其内出现的hostname修改成你想要的
     >
     > 2. `vi cd /etc/sysconfig/network` 将其内出现的hostname修改成你想要的
     >
     
   * ### ***重启系统***： reboot 

     

     

   

   
