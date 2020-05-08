# ansiblerole-iptables

---

Ansible Role for iptables based Linux firewall. It can be used in
different distributives. Main targets - Ubuntu and Debian Linux Operating
Systems.

*Main functions of the Role:*

- Disable ufw firewall (if enabled);
- Installing Iptables, if it's not installed;
- Setting iptables rules;
- Installing init.d sript and enable firewall service;

Some Variables, then used in this Role for Rules configuration:
```
iptables_TCP_in - TCP ports, that should be opened on this server;
iptables_TCP_out - Outside TCP services, that should work on this server;
iptables_UDP_in - UDP ports, that should be opened on this server;
iptables_UDP_out - Outside UDP services, that should work on this server;
```

----

**Author of the Role** - Andrey Useinov aka andreyus.
