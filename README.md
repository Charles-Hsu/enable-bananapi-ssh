# enable-bananapi-ssh

https://askubuntu.com/a/1110843

@reboot mkdir -p -m0755 /var/run/sshd && systemctl restart ssh.service

but fail after reboot

### Run a Program On Your Raspberry Pi At Startup
https://www.dexterindustries.com/howto/run-a-program-on-your-raspberry-pi-at-startup/

#### Editing rc.local
vi /etc/rc.local
mkdir -p -m0755 /var/run/sshd && systemctl restart ssh.service

![image](https://github.com/Charles-Hsu/enable-bananapi-ssh/blob/master/rc.local.png)
