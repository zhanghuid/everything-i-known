## 介绍

## 最优雅的 ssh 连接管理方式
### 配置字段
```ruby
Host 11
HostName 127.1.1.1
Port 22022
User work
PreferredAuthentications publickey
IdentityFile ~/.ssh/id_rsa
```

### 使用
```
ssh 11
```

### 查看
```
cat /etc/ssh/ssh_config | grep '^Host'
```

### 引用
>[使用 SSH config 文件](https://daemon369.github.io/ssh/2015/03/21/using-ssh-config-file)
>[Alfred SSH connection shortcuts that open in iTerm 2](https://github.com/projectweekend/alfred-iterm-ssh-workflow)


## 预设
### 更改提示符
```bash
export PS1="\[\e[37m\]\[\e[32m\]\u\[\e[37m\]@\h:\[\e[36m\]\w\[\e[0m\n\$ "
```

### 命令行输入的 vi 风格
```bash
set -o vi
```