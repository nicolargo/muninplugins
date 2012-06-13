muninplugins
============

# ddos_ 

A Simple Munin plugin to monitor DDOS Attack.

Installation on a Munin node:

   cd /tmp
   wget https://raw.github.com/nicolargo/muninplugins/master/ddos_
   sudo munin-node-configure --shell
   sudo cp ddos_ /usr/share/munin/plugins/
   sudo chmod a+x /usr/share/munin/plugins/ddos_
   sudo munin-node-configure --shell
   sudo ln -s /usr/share/munin/plugins/ddos_ /etc/munin/plugins/ddos_
   sudo service munin-node restart

Enjoy !
