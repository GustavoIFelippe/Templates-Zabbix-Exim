# Templates-Zabbix-Exim

Functionalities:

- Monitor Exim Mail Queue via Zabbix Agent active checks.

How To:

- Create the following UserParam on the "zabbix_agentd.conf" of your agent: UserParameter=exim.mail.queue, sudo exim -bpc
- Put the following text to your sudoers file using vi /etc/sudoers, or visudo: zabbix ALL = NOPASSWD: /sbin/exim

    Any template upgrades, missing files or doubts, get in touch by gustavoifelippe@hotmail.com.

Zabbix Version 4.0.17
