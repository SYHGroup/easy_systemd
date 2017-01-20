### Systemd File by simonsmh  

 * [vncserver@.service](https://github.com/SYHGroup/easysystemd/blob/master/vncserver%40.service)  
   ```
   wget https://github.com/SYHGroup/easysystemd/raw/master/vncserver%40.service -O /etc/systemd/system/vncserver@.service  
   systemctl enable vncserver@1.service  
   vncserver :1  
   vncserver -kill :1  
   systemctl start vncserver@1.service  
   ```
   TIPS:`1` represents for port number.  
 
 * [shadowsocks-server.service](https://github.com/SYHGroup/easysystemd/blob/master/shadowsocks-server.service)  
   ```
   wget https://github.com/SYHGroup/easysystemd/raw/master/shadowsocks-server.service -O /etc/systemd/system/shadowsocks-server.service  
   systemctl enable shadowsocks-server.service  
   systemctl start shadowsocks-server.service  
   ```
   TIPS:For shadowsocksR python only.  