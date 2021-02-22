# AndroidTools

### Developer Assistant
仅通过辅助开关，就能查看任何app的布局及Activity信息。部分手机上须配合Button Mapper来启动语音助手。

### Droni
通过VPN的方式，对APP的流量进行聚合，再转发到电脑代理端口，实现流量监听。  
一、打开Drony，并右滑至SETTING标签页，选择Networks，点击当前在用的wifi名，进入Network details设置页  
二、网络详情设置
1、点击Proxy type，选择manual（手动）  
2、点击Hostname，输入当前电脑的局域网IP，比如192.168.1.123  
3、点击Port，输入抓包软件的端口号，比如8888  
4、点击Filter default value，选择Direct all  
5、点击Rules，进入Rules详情页，点击右上角的加号，进入Add filter rule，action选择Local proxy chain，Application选择需要抓包的应用，然后保存，返回主页  
三、左滑到LOG标签页，点击底部到OFF按钮，启用Drony，同时确保Drony进程在后台不会被杀掉

### HttpCanary
抓包

### VMOS
虚拟系统，可以干很多事。这个系统是5.1的，而且是支持明文传输的，也就是说安装在里面的APP，再通过Droni实现流量聚合转发，即使是HTTPS，也能抓包。
