# ansible_tbsdriver
# install TBS_drivers TVHeadEnd OSCAMD
#
$ sudo visudo

$ sudo dnf -y install ansible git

$ git clone https://github.com/HalfWorm/ansible_tbsdriver.git

$ cd ansible_tbsdriver

$ ansible-playbook -i inventory ansible_tbsdriver.yaml 

or 

$ ansible-playbook -i inventory ansible_tbsdriver.yaml -vvv

or

$ ansible-playbook -i inventory ansible_tbsdriver_only_driver.yaml

version media_build https://www.tbsdtv.com/forum/search.php?keywords=http%3A%2F%2Fwww.tbsdtv.com%2Fdownload%2Fdocument%2Flinux%2Fmedia_build-
