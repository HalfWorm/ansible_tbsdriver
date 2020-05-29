# ansible_tbsdriver
# install TBS_drivers TVHeadEnd OSCAMD
#
$ git clone https://github.com/HalfWorm/ansible_tbsdriver.git

$ sudo dnf install ansible git

$ cd ansible_tbsdriver

$ sudo visudo

$ ansible-playbook -i inventory ansible_tbsdriver.yaml or ansible-playbook -i inventory ansible_tbsdriver.yaml -vvv
