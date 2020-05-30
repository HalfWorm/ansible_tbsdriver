# ansible_tbsdriver
# install TBS_drivers TVHeadEnd OSCAMD
#
$ sudo visudo

$ sudo dnf -y install ansible git

$ git clone https://github.com/HalfWorm/ansible_tbsdriver.git

$ cd ansible_tbsdriver

$ ansible-playbook -i inventory ansible_tbsdriver.yaml or ansible-playbook -i inventory ansible_tbsdriver.yaml -vvv
