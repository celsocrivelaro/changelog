## Boot

**systemd-analize**: boot time

**systemd-analize blame**: boot time of each process

## Services

**systemclt**: show service status

**systemclt status ssh.service**: show servie status

**systemctl is-enabled ssh.service**: service is enabled on boot

**systemctl enable/disable ssh.service:** enable/disable on boot

**systemctl cat ssh.service:** show service details, service file

##Logging

**journalctl -b**: boot log

**journalctl -f**: syslog

**journalctl -f --since=today**: today log

**journalctl /user/sbin/cron**: log from a service

##System events

**systemctl poweroff/halt/reboot/suspend**

**hostnameclt**: system information

Source: [Linux Descomplicado](http://sysadmin.linuxdescomplicado.com.br/2016/05/comandos-systemctl-para-administrar-os-servi%C3%A7os-do-systemd-no-debian)
