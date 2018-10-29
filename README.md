**** Fail2ban Service *****

fail2ban.yaml

For the configuration part of the playbook input your IP/CIDR block on lines 48 and 60
THis playbook installs and configures Fail2ban Service on Amazon-Linux and CentOS7


The requirement to install Fail2ban service is epel-release repository

It installs epel-release on CentOS7
It installs epel-release on Amazon-Linux
Installs Fail2ban service on Amazon-Linux and CentOS7
Enables Fail2ban Service
Creates configuration file on CentOS7
Configures Fail2ban service on CentOS7
Configures Fail2ban service on Amazon-Linux
Restarts Fail2ban service on Amazon-Linux
Restarts Fail2ban service on CentOS7
** Fail2ban Configuration"



The configuration:

Allows 3 retry

Allows 2 minutes to login

If failed to login, bans for 1 hour

Ignores company's CIDR block
