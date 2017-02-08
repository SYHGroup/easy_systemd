## Systemd serivce by SYHGroup  

 * [vncserver@.service](https://github.com/SYHGroup/easysystemd/blob/master/vncserver%40.service)  
   ```
   wget https://github.com/SYHGroup/easysystemd/raw/master/vncserver%40.service -O /etc/systemd/system/vncserver@.service  
   systemctl enable vncserver@1.service  
   vncserver :1  
   vncserver -kill :1  
   systemctl start vncserver@1.service  
   ```
   TIPS: `1` represents for port number.  

 * [x0vncserver@.service](https://github.com/SYHGroup/easysystemd/blob/master/x0vncserver%40.service)  
   ```
   wget https://github.com/SYHGroup/easysystemd/raw/master/x0vncserver%40.service -O /etc/systemd/system/x0vncserver@.service  
   systemctl enable vncserver@5901.service  
   systemctl start vncserver@5901.service  
   ```
   TIPS: `5901` represents for port number. For lightdm only.  

 * [shadowsocks-server.service](https://github.com/SYHGroup/easysystemd/blob/master/shadowsocks-server.service)  
   ```
   wget https://github.com/SYHGroup/easysystemd/raw/master/shadowsocks-server.service -O /etc/systemd/system/shadowsocks-server.service  
   systemctl enable shadowsocks-server.service  
   systemctl start shadowsocks-server.service  
   ```
   TIPS: For shadowsocks golang version only.  

 * [chinadns.service](https://github.com/SYHGroup/easysystemd/blob/master/chinadns.service)  
   ```
   wget https://github.com/SYHGroup/easysystemd/raw/master/chinadns.service -O /etc/systemd/system/chinadns.service  
   systemctl enable chinadns.service  
   systemctl chinadns.service  
   ```
   TIPS: For chinadns-c only.  

 * [shadowss.service]((https://github.com/SYHGroup/easysystemd/blob/master/shadowss.service)
   ```
   wget https://github.com/SYHGroup/easysystemd/raw/master/shadowss.service -O /etc/systemd/system/shadowss.service  
   systemctl enable shadowss.service  
   systemctl start shadowss.service  
   ```
   TIPS: For shadowsocks python version only.  

* [go-shadowsocks2.service](https://github.com/SYHGroup/easysystemd/blob/master
/go-shadowsocks2.service)
   ```                                                                                wget https://github.com/SYHGroup/easysystemd/raw/master/go-shadowsocks2.service -O /etc/systemd/system/go-shadowsocks2.service  
   systemctl enable go-shadowsocks2.service  
   systemctl start go-shadowsocks2.service  
   ```
   TIPS: For shadowsocks golang version 2 only.  
