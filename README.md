# About

ansible Scripts

# How to

```bash
■基本形
$ ansible-playbook -i production [servername].yml --extra-vars '{ "hosts":"[servername]" }'

・タグ指定実行 (-t [タグ名])
$ ansible-playbook -i test-servers site.yml -t nc

・fact変数一覧
$ ansible -m setup localhost
```
