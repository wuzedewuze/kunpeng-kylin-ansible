# kunpeng-kylin-ansible
个人测试 鲲鹏ARM 麒麟v10 高级服务器版本 ansible批量部署脚本代码

### ansible设置

```
[defaults]
# 新增配置
interpreter_python = /usr/bin/python3
host_key_checking = False
```

### exec 
```
ansible-playbook init.yaml  -i /etc/ansible/hosts
```



