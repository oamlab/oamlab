- OAMlab
- https://github.com/oamlab

# 在本地linux使用ssh免秘钥登录方法登录远程linux

- ----------------------------

注意：以下为提供参考的安装或编译过程，具体过程可根据自有情况进行调整。

## 本地终端：

#### 1、在本地终端上生成公钥
- linux的shell命令行：

``` bash
ssh-keygen -t rsa
ls /用户名/.ssh/id_rsa.pub
cat /用户名/.ssh/id_rsa.pub
```

#### 2、传送本地公钥到远程主机

``` bash
ssh-copy-id -p 端口 用户名@远程主机ip
```
- 回车后会询问远程主机的密码。

#### 3、登录测试：

``` bash
ssh 用户名@远程主机ip
```

## 远程主机：

#### 1、在远程主机上检查公钥

``` bash
cat /用户名/.ssh/authorized_keys
```