# VMware安装CentOS7

**准备工作**

- VMware，我用的是VMware Workstation Pro 15

* CentOS7镜像文件下载地址 http://isoredirect.centos.org/centos/7/isos/x86_64
  选择阿里的镜像，点击下载即可。



参考

https://blog.csdn.net/babyxue/article/details/80970526

https://m.yisu.com/zixun/63953.html

VMware虚拟机网络配置-NAT篇：https://zhuanlan.zhihu.com/p/130984945



```bash
# 修改网关配置
vi   /etc/sysconfig/network-scripts/ifcfg-ens33
# 重启网络服务
service network restart
```

