# Simple update/upgrade/autoremove/restart server using ansible
## Update all varariables in group_vars/all.yml

    ansible_user: <USERNAME>
    ansible_email: <MAIL@DOMAIN.TLD>
    systemd_dir: /etc/systemd/system

## Then use the command to start the setup
    ansible-playbook update.yml 

### Have fun !