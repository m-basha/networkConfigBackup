# networkConfigBackup
This Repo is used to backup network configuration files using ansible
Supported platforms:
Cisco IOSXR
Cisco IOS


Command:
ansible-playbook -i inventoryFile.ini confBKP.yml -e "workspace=."
