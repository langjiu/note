### GitHub创建公钥
```
操作步骤
1.生成公钥\
    ssh-keygen -t rsa -C "GitHub账号的注册邮箱"
2.进入路径
    vim ~/.ssh/id_rsa.pub
    或输入
    cat ~/.ssh/id_rsa.pub 命令后复制key
    
3.复制公钥到GitHub设置中 SSH and GPG keys中的SSH keys

4、最后就可以使用SSH上传代码了
```