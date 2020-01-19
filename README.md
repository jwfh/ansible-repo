Run on master:

```shell
git clone https://github.com/jwfh/ansible-repo /usr/local/etc/ansible
```

Run on each host:

```
fetch -o- https://raw.githubusercontent.com/jwfh/ansible-repo/master/trusted-keys.pub | tee -a ~/.ssh/authorized_keys
```

