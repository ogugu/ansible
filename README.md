# About

ansible Scripts

# How to

```bash
�E��{�`
$ ansible-playbook -i production [servername].yml --extra-vars '{ "hosts":"[servername]" }'

�E�^�O�w����s (-t [�^�O��])
$ ansible-playbook -i test-servers site.yml -t nc

�Efact�ϐ��ꗗ
$ ansible -m setup localhost
```
