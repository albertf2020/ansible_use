Usage:

ansible-playbook -i ./inventory/{test,stage,prode}/hosts -l {host or group hosts} site.yml
```
Note: if you want only check what is execute use -C -D keys

ansible-playbook -i ./inventory/test/hosts -C -D -l host site.yml
```
