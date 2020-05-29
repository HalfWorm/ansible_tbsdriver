# ansible_tbsdriver
# install TBS_drivers TVHeadEnd OSCAMD
#
$ sudo dnf install ansible git
$sudo visudo
$ansible-playbook -i inventory ansible_tbsdriver.yaml or ansible-playbook -i inventory ansible_tbsdriver.yaml -vvv
