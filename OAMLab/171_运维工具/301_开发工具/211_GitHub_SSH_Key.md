- OAMlab
- https://github.com/oamlab

# 关于在windows上使用ssh的方式连接GitHub代码仓的方法

- ----------------------------

注意：以下为提供参考的安装或编译过程，具体过程可根据自有情况进行调整。

## windows 10：

#### 1、查看当前的git配置
- windows的cmd命令行：

``` bash
git config --global --list
```

- 回显内容

``` bash
user.name=xxx
user.email=xxx@example.localhost
```

#### 2、生成rsa证书

``` bash
cd C:\Users\你的当前用户名
ssh-keygen -t rsa -C "你在github使用的邮箱，譬如：xxx@example.localhost"
```
- 回车后会询问ssh key生成的路径，以及是否需要密码，可以直接留空回车即可。

- 查看生成的文件：
``` bash
dir .ssh
```

#### 3、将id_rsa.pub内的内容复制到Github，在GitHub建立ssh key
- 打开：https://github.com/settings/keys
- 点击按钮 《New SSH key》
- 填写 Title
- 复制 id_rsa.pub 内的内容到 Key
- 点击按钮 《Add SSH key》

#### 4、切换本地项目连接GitHub的方式，譬如：

``` bash
cd 你的项目代码目录
git remote set-url origin git@github.com:你的项目仓库.git
```
- 回顾和检查开发工具的设置