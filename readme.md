## Systemd serivce by SYHGroup  

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](./LICENSE)  

 * [vncserver@.service](https://github.com/SYHGroup/easy_systemd/blob/master/vncserver%40.service)
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/vncserver%40.service -O /etc/systemd/system/vncserver@.service
   systemctl enable vncserver@1.service
   systemctl start vncserver@1.service
   ```
   TIPS: `1` represents for port number.

 * [x0vncserver@.service](https://github.com/SYHGroup/easy_systemd/blob/master/x0vncserver%40.service)
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/x0vncserver%40.service -O /etc/systemd/system/x0vncserver@.service
   systemctl enable vncserver@5901.service
   systemctl start vncserver@5901.service
   ```
   TIPS: `5901` represents for port number. For lightdm only.

 * [chinadns.service](https://github.com/SYHGroup/easy_systemd/blob/master/chinadns.service)
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/chinadns.service -O /etc/systemd/system/chinadns.service
   systemctl enable chinadns.service
   systemctl start chinadns.service
   ```
   TIPS: For chinadns-c only.

 * [ssserver.service](https://github.com/SYHGroup/easy_systemd/blob/master/ssserver.service)
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/ssserver.service -O /etc/systemd/system/ssserver.service
   systemctl enable ssserver.service
   systemctl start ssserver.service
   ```
   TIPS: For shadowsocks python version only.


 * [shadowsocks-server.service](https://github.com/SYHGroup/easy_systemd/blob/master/shadowsocks-server.service)
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/shadowsocks-server.service -O /etc/systemd/system/shadowsocks-server.service
   systemctl enable shadowsocks-server.service
   systemctl start shadowsocks-server.service
   ```
   TIPS: For shadowsocks golang version only.

* [go-shadowsocks2.service](https://github.com/SYHGroup/easy_systemd/blob/master/go-shadowsocks2.service)
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/go-shadowsocks2.service -O /etc/systemd/system/go-shadowsocks2.service
   systemctl enable go-shadowsocks2.service
   systemctl start go-shadowsocks2.service
   ```
   TIPS: For shadowsocks golang version 2 only. You may need to manually edit configs in this systemd file.

* [aria2.service](https://github.com/SYHGroup/easy_systemd/blob/master/aria2.service)
   ```
   wget https://github.com/SYHGroup/easy_systemd/raw/master/aria2.service -O /etc/systemd/user/aria2.service
   systemctl --user enable aria2.service
   systemctl --user start aria2.service
   ```
   TIPS: For Aria2 rpc server only.
