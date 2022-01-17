# ansible_vcenter

### Usage
I use my roles **vars/main.yml** with ansible-vault, please change this variable for you enviroment

Change hosts file for yourself

<dl>
<dt>In this roles i use 2 section ansible_nodes, ansible_vmware.</dt>
<dd>* ansible_nodes - Use this for CIS Benchmark your OS hardening.</dd>
<dd>* ansible_vmware - Use this section to create your virtual machine from your vmware template.</dd>
</dl> 

```sh
ansible-playbook VMfromTemplare.yml # for create vmware machine
```


```sh
ansible-playbook CISforCentOS8.yml # for deploy CIS to virtual machine
```
