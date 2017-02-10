## Systemd serivce by SYHGroup  

 * [vncserver@.service](https://github.com/SYHGroup/easy_systemd/blob/master/vncserver%40.service)  
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/vncserver%40.service -O /etc/systemd/system/vncserver@.service  
   systemctl enable vncserver@1.service  
   vncserver :1  
   vncserver -kill :1  
   systemctl start vncserver@1.service  
   ```
   TIPS: `1` represents for port number.  

 * [x0vncserver@.service](https://github.com/SYHGroup/easy_systemd/blob/master/x0vncserver%40.service)  
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/x0vncserver%40.service -O /etc/systemd/user/x0vncserver@.service  
   systemctl enable vncserver@5901.service  
   systemctl start vncserver@5901.service  
   ```
   TIPS: `5901` represents for port number. For lightdm only.  

----------

 * [shadowsocks-server.service](https://github.com/SYHGroup/easy_systemd/blob/master/shadowsocks-server.service)  
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/shadowsocks-server.service -O /etc/systemd/user/shadowsocks-server.service  
   systemctl --user enable shadowsocks-server.service  
   systemctl start shadowsocks-server.service  
   ```
   TIPS: For shadowsocks golang version only.  

 * [chinadns.service](https://github.com/SYHGroup/easy_systemd/blob/master/chinadns.service)  
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/chinadns.service -O /etc/systemd/user/chinadns.service  
   systemctl --user enable chinadns.service  
   systemctl chinadns.service  
   ```
   TIPS: For chinadns-c only.  

 * [ssserver.service](https://github.com/SYHGroup/easy_systemd/blob/master/ssserver.service)
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/ssserver.service -O /etc/systemd/user/ssserver.service  
   systemctl --user enable ssserver.service  
   systemctl start ssserver.service  
   ```
   TIPS: For shadowsocks python version only.  

* [go-shadowsocks2.service](https://github.com/SYHGroup/easy_systemd/blob/master/go-shadowsocks2.service)
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/go-shadowsocks2.service -O /etc/systemd/user/go-shadowsocks2.service
   systemctl --user enable go-shadowsocks2.service
   systemctl start go-shadowsocks2.service
   ```
   TIPS: For shadowsocks golang version 2 only. You may need to manually edit config in systemd file.
