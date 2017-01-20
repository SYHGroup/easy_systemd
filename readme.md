### Systemd File by simonsmh  

 * [vncserver@.service](https://gist.github.com/simonsmh/36217aad5adf3514c87a087ee5017843#file-vncserver-service)  
   ```
   wget https://gist.githubusercontent.com/simonsmh/36217aad5adf3514c87a087ee5017843/raw/vncserver@.service -O /etc/systemd/system/vncserver@.service  
   systemctl enable vncserver@1.service  
   vncserver :1  
   vncserver -kill :1  
   systemctl start vncserver@1.service  
   ```
   TIPS:`1` represents for port number.  
 
 * [shadowsocks-server.service](https://gist.github.com/simonsmh/36217aad5adf3514c87a087ee5017843#file-shadowsocks-server-service)  
   ```
   wget 'https://gist.githubusercontent.com/simonsmh/36217aad5adf3514c87a087ee5017843/raw/shadowsocks-server.service' -O /etc/systemd/system/shadowsocks-server.service  
   systemctl enable shadowsocks-server.service  
   systemctl start shadowsocks-server.service  
   ```
   TIPS:For shadowsocksR python only.  
   
 * [shadowsocks-go](https://gist.github.com/simonsmh/36217aad5adf3514c87a087ee5017843#file-shadowsocks-go)
   ```
   wget https://gist.githubusercontent.com/simonsmh/36217aad5adf3514c87a087ee5017843/raw/shadowsocks-go -O /etc/init.d/shadowsocks-go
   chmod a+x /etc/init.d/shadowsocks-go
   chmod a+x /usr/bin/shadowsocks-server
   systemctl enable shadowsocks-go
   ```
   TIPS:Works with update-rc.d only.
   